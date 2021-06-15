# lite-fsutils

This plugin introduces a few commands related to the filesystem (rename / move, recursive delete (`rm -r`), recursive create directory (`mkdir -p`)) to lite.

It also exports a few wrapper filesystem functions so that other plugins may use it.

This plugin is required for [`lite-contextmenu`](https://github.com/takase1121/lite-contextmenu) to work with TreeView.

### Note : 

fsutils.delete() depends on os.remove() for deleting files and directories. While this works for files everywhere, it doesnot delete directories on Windows.

