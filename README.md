# Failing Code

Thank you for visiting this repository, your efforts and help could make a huge difference to me. Currently when I trigger the vs extension debugger and run the line of `const TreeSitter =  require('tree-sitter');`, the debugger silently breaks without any error message.

## Reproduce

To reproduce the issue, run the following commands

```cmd
npm install
./node_modules/.bin/electron-rebuild -v 25.8.4
npm run compile
```

and then enter `fn + F5` for mac or `control + shift + f5` on Windows. While a window pop out with debugger selection, please select the `vscode extension development`
