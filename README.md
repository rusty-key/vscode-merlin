# VS Code Merlin Extension

Experimental build, work in progress here: https://github.com/arrowresearch/vscode-merlin

## Building the Extension

### Prerequisite
This extension requires `esy@0.6`:
```
npm install -g @esy-nightly/esy
```

### Building

- Clone this repo: `git clone git@github.com:rusty-key/vscode-merlin.git`
— Switch to this branch: `git branch rusty-build`
- Run `npm run package` to produce `*.vsix` extension package.
- Run `code --install-extension *.vsix` to install the extension with VS Code.
