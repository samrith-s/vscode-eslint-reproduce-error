# vscode-eslint-reproduce-error
Reproduce error thrown by ESLint regarding plugins.

Just open `src/index.js` and hit save. Console throws the following error:
```terminal
6/27/2019, 11:17:33 AM:
-----------------------
Failed to load plugin 'prettier' declared in 'CLIOptions'/Users/samrith/Work/vscode-eslint-reproduce-error/src/index.js:: Cannot find module 'eslint-plugin-prettier'
Require stack:
- /__placeholder__.js
```

Weirdly, it works for JSON and RC files, but not JS files.
