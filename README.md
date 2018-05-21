#Navigation Terminal
**cd** -> Change directory
- cd ~ -> change directory to Home
**ls** -> display what is in current directory with short list
**l** -> display complete file information in directory
**pwd** -> print working directory, the where the hell am I command.
**open** -> command will open a file in default program or directory in finder

#File Manipulation
**man** -> will pull up manual for commands - q to exit
- `man [command here]` -- will display tons of information about the command
**|** -> pipe will execute command on left first then execute command on right
- `[command here] | [second command here]` - does not work for every command
**>** -> redirects output to a File
- `echo 'text to add' > [File name]` - output directed into file !!!Will overwrite whats in there.
- `echo 'text to add' >> [File name]` - output appended into file
**mkdir** -> create new directory from current position
**touch** -> create new file within current directory
**mv** -> move files
- `mv [current file name] [new file name]` -- will rename the file
- `mv [current file name] ./newdirectory/[new file name]` -- will move the file and rename, directory MUST exist. period in directory indicates current directory
**rm** -> removes files or directories --!!! scary cannot undo
- `rm [file name]` -- removes file from system
- `rm -r [directory name]` -- removes directory and all subsequent files
**grep** -> will search through documents for strings
- `cat [file name] | grep 'string to search'` -- will search contents of file and return if grep string found
-  `-n` -- will display line number of found strings
- `A [number here]` -- will display trailing number of lines specified
- `-B [Number here]` -- will display preceding number of lines specified
**cat** -> reads a file(s) and outputs to Terminal
- `cat [file name]` - will display file contents
- `cat [file name] [file name] ....` will display file contents of all files selected in order

#Git commands
