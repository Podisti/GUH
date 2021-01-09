# Instalace Pascalu do VSC

## Instalace Visual Studio Code (https://code.visualstudio.com/download)
![](images/download.png)

## Instalace Free Pascalu (https://www.freepascal.org/download.html)
![](images/freepascal.png)

## Rozšíení pro Visual Studio Code
![](images/extension_icon.png)

### Pascal
![](images/pascal_extension.png)

### FreePascal Toolkit
![](images/toolkit_extension.png)

### GDB Debugger - Beyond
![](images/gdb_debugger_extension.png)

## Založení projektu
1. Otevřít VSC, přetáhnout novou složku projektu do VSC
V sekci FPC PROJECTS zvolit Create New Project.

![](images/create_project.png)

2. Vytvořit task pro kompilaci projektu (debug) - uvedena [ukázka](tasks.json), vytvořit se však sám.


3. Nakopírovat soubor [launch.json](launch.json) do podadresáře .vscode

_Pokud se vyskytne problém se znakovou sadou, nastavte ji na Central Europian (CP 852) (u Windows)_

![](images/encoding_position.png)
![](images/encoding_selection.png)
![](images/encoding.png)
