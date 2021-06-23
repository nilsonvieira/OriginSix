# OriginSix
Projeto do Curso **Next Level Week Together**

# Prepare Enviroment
## Visual Studio Code
Configurações do Programa
### Plugins
- Bracket Pair Colorizer
- Live Server
- Material Icon Theme
- Omni Theme
- Prettier

### Preferences:: Open Settings (JSON) (CTRL + SHIFT + p)
```json
{
    "editor.fontSize": 16,
    "terminal.integrated.fontSize": 16,
    "workbench.colorTheme": "Omni",
    "workbench.iconTheme": "material-icon-theme",
    // no vídeo você viu uma config de fonte aqui, 
		// mas ela não é compatível com todos os sistemas, por isso, tirei ok?
    "editor.minimap.enabled": false,
    "editor.wordWrap": "on",
    "workbench.editor.tabSizing": "shrink",
    "explorer.compactFolders": false,
    "window.zoomLevel": 1,

    // formatter
    "prettier.tabWidth": 2,
    "prettier.semi": false, 
    "prettier.singleQuote": true,
    "prettier.trailingComma": "none", 
    "prettier.arrowParens": "avoid",
    "prettier.endOfLine": "auto",
    "editor.tabSize": 2,
    "editor.formatOnSave": true,
    "[javascript]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "[html]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "liveServer.settings.donotShowInfoMsg": true,
    "liveServer.settings.donotVerifyTags": true,
}
```