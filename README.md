There is a #pre-commit git hook that looks like the following. 

```
#!/bin/sh

# hooks are run from the root of the repository

# overwrite README with contributing instruction
cat CONTRIBUTING.md > README.md
# echo image names in markdown-rendery format to README
for file in */*.jpg */*.png; do 
    echo "![$file]($file)" >> README.md
done
```

It'll automatically add all the .png/.jpg files in the repo to the README for previewing. __So all you've got to do to contribute is clone, add a picture, commit twice, and push!__



![etc/original.jpg](etc/original.jpg)
![html/html5_cheatsheet.jpg](html/html5_cheatsheet.jpg)
![shell/command_sheet.jpg](shell/command_sheet.jpg)
![sql/mysqlstatchart_1180.jpg](sql/mysqlstatchart_1180.jpg)
![design/Tabla_de_colores_ilatela_v1.0.png](design/Tabla_de_colores_ilatela_v1.0.png)
![design/emoji_l1.png](design/emoji_l1.png)
![design/material-design-color-chart.png](design/material-design-color-chart.png)
![git/git-cheat-sheet-large-blue.png](git/git-cheat-sheet-large-blue.png)
![html/html5_cheat_sheet_tags.png](html/html5_cheat_sheet_tags.png)
![js/jquery_cheatsheet.png](js/jquery_cheatsheet.png)
![rails/Rails Controller tests.png](rails/Rails Controller tests.png)
![rails/Rails Unit tests.png](rails/Rails Unit tests.png)
![shell/CLICheatSheetWallpaper.png](shell/CLICheatSheetWallpaper.png)
![vim/border-vim-cheet-sheet.png](vim/border-vim-cheet-sheet.png)
![vim/rsz_vim_shortcuts_dark_2560x1600.png](vim/rsz_vim_shortcuts_dark_2560x1600.png)
![vim/vi-vim-cheat-sheet.png](vim/vi-vim-cheat-sheet.png)
![etc/original.jpg](etc/original.jpg)
![html/html5_cheatsheet.jpg](html/html5_cheatsheet.jpg)
![shell/command_sheet.jpg](shell/command_sheet.jpg)
![sql/mysqlstatchart_1180.jpg](sql/mysqlstatchart_1180.jpg)
![./logic-operators.jpg](./logic-operators.jpg)
![./*.png](./*.png)
![design/Tabla_de_colores_ilatela_v1.0.png](design/Tabla_de_colores_ilatela_v1.0.png)
![design/emoji_l1.png](design/emoji_l1.png)
![design/material-design-color-chart.png](design/material-design-color-chart.png)
![git/git-cheat-sheet-large-blue.png](git/git-cheat-sheet-large-blue.png)
![html/html5_cheat_sheet_tags.png](html/html5_cheat_sheet_tags.png)
![js/jquery_cheatsheet.png](js/jquery_cheatsheet.png)
![rails/Rails Controller tests.png](rails/Rails Controller tests.png)
![rails/Rails Unit tests.png](rails/Rails Unit tests.png)
![shell/CLICheatSheetWallpaper.png](shell/CLICheatSheetWallpaper.png)
![vim/border-vim-cheet-sheet.png](vim/border-vim-cheet-sheet.png)
![vim/rsz_vim_shortcuts_dark_2560x1600.png](vim/rsz_vim_shortcuts_dark_2560x1600.png)
![vim/vi-vim-cheat-sheet.png](vim/vi-vim-cheat-sheet.png)
