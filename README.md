# nodejs-vscode-boilerplate

This is a boilerplate to develop the Node.js projects with Visual Studio Code.

## Usage

1. Run `git clone git@github.com:u4da3/nodejs-vscode-boilerplate.git`
1. Run `cd nodejs-vscode-boilerplate`
1. Run `rm -rf .git`
1. Open the `nodejs-vscode-boilerplate` directory with Visual Studio Code.
1. You are ready to develop the Node.js project with Visual Studio Code.

## Customize

Overwrite the configuration files, and you can customize your project.

### Node.js Configurations

- `.node-version`  
  Write the version of Node.js to run your project on.  
  (See https://github.com/nodenv/nodenv)
- `package.json`  
  Write the dependencies of your project manually, or automatically with the `npm` command.  
  (See https://docs.npmjs.com/files/package.json.html)

### VSCode Configurations

- `jscode.json`  
  Write the IntelliSence configurations of your project.  
  (See https://code.visualstudio.com/docs/nodejs/working-with-javascript)
- `.vscode/settings.json`  
  Write the settings of Visual Studio Code you want to share with your project mambers.  
  You can also edit this file on the workspace tab in the settings page of Visual Studio Code.  
  (See https://code.visualstudio.com/docs/getstarted/settings)
- `.vscode/extensions.json`  
  This is the list of vscode extentions that you recommend for your project members.  
  (See https:/ code.visualstudio.com/docs/editor/extension-gallery)
- `.vscode/launch.json`  
  Write the debugging configurations of your project.  
  To debug your project in Visual Studio Code, press the <kbd>F5</kbd> key.  
  (See https://code.visualstudio.com/docs/editor/debugging)
- `.vscode/tasks.json`  
  Write the build task and other custom tasks.  
  To run your build task, press <kbd>⌘</kbd>+<kbd>Shift</kbd>+<kbd>B</kbd> for macOS, or <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>B</kbd> for Windows and Linux.  
  Similarly, to run other custom tasks, press <kbd>⌘</kbd>+<kbd>Shift</kbd>+<kbd>P</kbd> or <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>P</kbd>.  
  (See https://code.visualstudio.com/docs/editor/tasks)

### Formatting Rule Configurations

- `.prettierrc.yaml` :  
  Write the Prettier formatting rules of JavaScript sources.  
  Press <kbd>Shift</kbd>+<kbd>Alt</kbd>+<kbd>F</kbd> on the editor, and the source will be formatted automatically.  
  (See https://prettier.io/docs/en/options.html)
- `.eslintrc.yaml`  
  Write the linter check rules of JavaScript sources.  
  (See https://eslint.org/docs/rules/)
