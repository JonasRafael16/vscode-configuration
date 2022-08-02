# vscode-configuration

These are my VsCode configurations.
For use them just paste in settings.json in your Vscode.

{
    "workbench.colorTheme": "Dracula",
    "workbench.iconTheme": "material-icon-theme",
    "workbench.editor.labelFormat": "short",

    "editor.fontFamily": "fira code",
    "editor.tabSize": 2,
    "editor.fontSize": 16,
    "editor.lineHeight": 24,
    "editor.rulers": [80, 120],
    "editor.renderLineHighlight": "gutter",
    "editor.fontLigatures": true,
    "editor.codeActionsOnSave": {
        "source.fixAll": true
    },
    "explorer.compactFolders": false,
    "explorer.confirmDelete": false,
    "explorer.confirmDragAndDrop": false,
    "files.trimTrailingWhitespace": true,
    "javascript.updateImportsOnFileMove.enabled": "never",
    "typescript.updateImportsOnFileMove.enabled": "never",
    "[php]": {
        "editor.defaultFormatter": "bmewburn.vscode-intelephense-client"
    },
    "php.validate.executablePath": "c:/xampp/php",
    "editor.linkedEditing": true,
    "[html]": {
        "editor.defaultFormatter": "vscode.html-language-features"
    },
    "terminal.integrated.defaultProfile.osx": "zsh",
    "terminal.external.osxExec": "iTerm.app",
    "terminal.integrated.fontFamily": "monospace"
}
