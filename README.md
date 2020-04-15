# vs-code-settings

### Start the configuration file

```
{
    "terminal.integrated.fontSize": 14,

    "workbench.colorTheme": "Dracula",

    // Define o tema dos icones na sidebar
    "workbench.iconTheme": "material-icon-theme",
    "workbench.startupEditor": "newUntitledFile",

    // Configura o tamanho e familia da fonte
    "editor.tabSize": 2,
    "editor.fontSize": 18,
    "editor.lineHeight": 24,
    "editor.fontFamily": "Fira Code",
    "editor.fontLigatures": true,

    "explorer.compactFolders": true,
    "editor.renderLineHighlight": "gutter",
    "workbench.editor.labelFormat": "short",
    "extensions.ignoreRecommendations": true,

    "javascript.updateImportsOnFileMove.enabled": "never",
    "typescript.updateImportsOnFileMove.enabled": "never",

    "breadcrumbs.enabled": true,
    "editor.parameterHints.enabled": false,
    "explorer.confirmDragAndDrop": false,
    "explorer.confirmDelete": false,
    
    "editor.rulers": [80,120],

    "window.zoomLevel": -1,
    
    "git.confirmSync": false,
    "git.autofetch": true,
    "git.enableSmartCommit": true,
    
    "emmet.syntaxProfiles": {"javascript": "jsx"},
    "emmet.includeLanguages": {"javascript": "javascriptreact"},

    "[javascript]": {
        "editor.codeActionsOnSave": {
            "source.fixAll.eslint": true,
        }
    },
    "[javascriptreact]": {
        "editor.codeActionsOnSave": {
            "source.fixAll.eslint": true,
        }
    },
    "[typescript]": {
        "editor.codeActionsOnSave": {
            "source.fixAll.eslint": true,
        }
    },
    "[typescriptreact]": {
        "editor.codeActionsOnSave": {
            "source.fixAll.eslint": true,
        }
    },
} 
```

### End configuration file
