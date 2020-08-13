# Origin Feature

This is a mirror of http://www.vim.org/scripts/script.php?script\_id=4151

This script is used for automatically generating verilog instance from the file. When you type the given hot-key, instance will be copied to system clipboard, and display or not by  its working mode. Once your file can access syntax check, this plunin will work, or there must be a bug. It's encouraged to share it with me and all other people.

Supported working mode:
    mode 0(default): 
        copy inst to clipboard and echo inst in commandline
    mode 1:
        only copy to clipboard
    mode 2:
        copy to clipboard and echo inst in split window
    mode 3:
        copy to clipboard and update inst\_comment to file
    
  To change the default working mode, you should modify the line in this script "let g:vlog\_inst\_gen\_mode=x", x is the default working mode; or you can add  "let g:vlog\_inst\_gen\_mode=x" to your \_vimrc or .vimrc file.

User defined command:
        VlogInstGen : generate verilog instance
        VlogInstMod : change working mode
Default hot-keys:
        ,ig         : VlogInstGen
        ,im        : VlogInstMod
Contact:
        mingforregister@163.com

# New Feature

Add user define prefix and suffix for Instance. 
