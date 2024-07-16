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
Use "Github Dark Default" theme and add this code in settings.json:
'
  "workbench.colorCustomizations": {
    "[Github Dark Default]": {
      "editor.background": "#0c0c0c",
    }
  }
'
}]

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
