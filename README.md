
## Vscode Setup

- **Copy code 👇**
- **Open vscode and click " Ctrl + Shift + p "**
- **Find 'Open User Settings (JSON)' and open it**
- **Paste copied code and reload**
- *Enjoy*

- ❗In some cases,you need to install in your OS like font family,themes(extensions)
- Font - *[**Cascadia Font**](https://github.com/microsoft/cascadia-code)*
- Themes - **Dark Magic Tokyo**
- Icon - **Material Icon Theme**

```bash
{
  "workbench.startupEditor": "none",
  "editor.fontFamily": "'Cascadia Code','Droid Sans Mono', 'monospace', monospace",
  "editor.fontLigatures": true,
  "workbench.iconTheme": "material-icon-theme",
  "workbench.colorTheme": "Dark Magic Tokyo",
  "material-icon-theme.folders.color": "#6688cc",
  "editor.cursorBlinking": "expand",
  "editor.cursorSmoothCaretAnimation": "on",
  "containers.containerClient": "com.microsoft.visualstudio.containers.docker",
  "editor.fontSize": 16,
  "editor.lineHeight": 24,
  "liveServer.settings.donotShowInfoMsg": true,
  "workbench.editor.empty.hint": "hidden",
  "git.openRepositoryInParentFolders": "never",
  "explorer.confirmDragAndDrop": false,
  "explorer.confirmDelete": false,
  "editor.stickyScroll.enabled": false,
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "editor.formatOnSave": true,
  "liveServer.settings.donotVerifyTags": true,
  "editor.overtypeCursorStyle": "line",
  "github.copilot.enable": {
    "*": false,
    "plaintext": false,
    "markdown": false,
    "scminput": false
  },
  "git.confirmSync": false,
  "git.autofetch": true,
  "editor.wordWrap": "on",

  "better-comments.tags": [
    {
      "tag": "", //normal:...
      "color": "#616161",
      "strikethrough": false,
      "underline": false,
      "backgroundColor": "transparent",
      "bold": false,
      "italic": false
    },
    {
      "tag": "todo", //todo:....
      "color": "#ffc400",
      "strikethrough": false,
      "underline": false,
      "backgroundColor": "transparent",
      "bold": false,
      "italic": false
    },
    {
      "tag": "bug", //bug:....
      "color": "#f92672",
      "strikethrough": false,
      "underline": false,
      "backgroundColor": "transparent",
      "bold": true,
      "italic": false
    },
    {
      "tag": "info", //info:....
      "color": "#0d47a1",
      "strikethrough": false,
      "underline": false,
      "backgroundColor": "#bbdefb",
      "bold": false,
      "italic": true
    },
    {
      "tag": "done", //done:...
      "color": "#1b5e20",
      "strikethrough": false,
      "underline": false,
      "backgroundColor": "#c8e6c9",
      "bold": false,
      "italic": false
    }
  ],
  "vscode-edge-devtools.webhint": false,
  "containers.orchestratorClient": "com.microsoft.visualstudio.orchestrators.dockercompose",
  "terminal.integrated.defaultProfile.linux": "zsh",
  "workbench.secondarySideBar.defaultVisibility": "hidden"
}
```


