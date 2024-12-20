Extensions:

Theme: Monokai Pro[

Info {
Name: Monokai Pro
Id: monokai.theme-monokai-pro-vscode
Description: Professional theme and matching icons, from the author of the original Monokai color scheme.
Version: 1.3.2
Publisher: monokai
VS Marketplace Link: https://marketplace.visualstudio.com/items?itemName=monokai.theme-monokai-pro-vscode
}]

==================================

Intellij Keybinds for visualCode[
Command: "ext install k--kato.intellij-idea-keybindings"

Info { 
Name: IntelliJ IDEA Keybindings
Id: k--kato.intellij-idea-keybindings
Description: Port of IntelliJ IDEA Keybindings, including for WebStorm, PyCharm, PHP Storm, etc.
Version: 1.7.1
Publisher: Keisuke Kato
VS Marketplace Link: https://marketplace.visualstudio.com/items?itemName=k--kato.intellij-idea-keybindings
}]

==================================

Github Dark Default settings[
{
Open, use "Github Dark Default" theme and add this code in json user settings:
'
"workbench.colorCustomizations":{"editor.background": "#0c0c0c"},
'
}]

Gold Standart Dark settings[
{
    "workbench.colorTheme": "Gold Standard Dark",
    "workbench.colorCustomizations":{
        "editor.background": "#0f0f0f60",
        "editorGutter.background": "#0f0f0f60",
        "sideBar.background": "#111111",
        "sideBar.border": "#4d4d4d",
        "sideBarSectionHeader.background": "#111111",
        
        "terminal.background": "#111111",
  },
    "editor.fontSize": 27,
    "editor.fontFamily": "Fira Code",
    "terminal.integrated.fontSize": 19,
    "files.autoSave": "afterDelay",
    "python.defaultInterpreterPath": "/home/koji/Desktop/Code/flask/project3/venv",
    "workbench.iconTheme": "vscode-icons",
}
]

==================================
==================================
Tools:

sqlite3[
Info { 
Name: sqlite3
How to install: sudo apt-get install sqlite3
Settings: 
Use command in terminal: "nano ~/.sqliterc"
1. ".mode table",
2. ".headers on",
3. ".width 15 15 15 15"
4. ".timer on"
"Ctrl + S"
}]

harlequin (Terminal IDE for duckdb & sqlite)[
Info {
Name: harlequin
How to install: pipx install harlequin
Visit: https://harlequin.sh/docs/getting-started
}]
