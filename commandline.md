# Command line
Shortcuts |Function
---     |---
`Ctrl` + r     |search for past commands used
`Ctrl` + k  |cut everything after the cursor
`Ctrl`+ y|paste everything that has been cut
`Option`+left/right| move by one word
`Ctrl`+l|clear past commands except current
`Ctrl`+c|stop any process
`Ctrl`+a/e|move to the beginning or the end




### Get Info
`man`: print manual (help) for a command

`pwd`: print working directory

`ls`: list directory contents
- -a: show all
- -l: long detailed list
- -h: human readable

`ps`: view running processes

`tree`: needs to brew install. Shows folder directory in a tree diagram.

`curl`: downloads data from the internet
- -O: outputs into a file

### Manipulate
`cd`: change working directory [cd .. move one level up]
- cd .. : move one level up

`touch`: create a file

`mkdir`: create a directory

`cp my_source_file my_target_directory`: copy

`mv my_file target_directory`: move or rename

`ln`: link

`gunzip`: unzips file

### Redirect and Pipe
`<`: redirect stdin

`>`: redirect stdout
- eg: head file.csv > newfile.csv

`>>`: appends to the file
- eg: tail file.csv >> newfile.csv

`|`: pipe content of one command to the next command

### Read
`head`: read the start of the file
- -n [number]: show number of lines

`tail`: read the end of the file
- -n [number]: show number of lines

`cat`: read a file or concatenate files

`less`: show as much as you can show on screen. press q to quit

`csvlook`: need to brew install. shows csv in nice format

`vim`: edit a csv file
- `:q` :quit
- `:q!`: quit without saving
- `i` : insert
- `V`: visualise. Go to the line you want to copy and use `V ` and then use `y` to copy the highlighted lines. Use `p` to paste, `c` to cut.
- `:w` : write
- `:wq` : save and quit

### Using Linux command in the cloud
`screen`: Use `screen` to switch between processes. You can run certain processes and it will continue to run while you can use another screen to do something else.
- Use `screen` to start a screen session. You can use -S option to give it a name
- Run your processes in the screen
- Use `Ctrl+a` `Ctrl+d` to detach from the screen and return to your home terminal. The process in the screen continues to run.
- Use `Ctrl+a` `c` to create new screens in case their are multiple processes
- Use `Ctrl+a` `A` to rename this new session
- Use `screen -ls` to see the list of screens you created
- Use `screen -r` and the name of the session to restore the screen
- Use `exit` to close down the screen


### End

`rm`: remove

`kill`: end a process

### Search
`grep`: search

`ag`: search

### Archive
`tar`: join multiple files into one file

`history`: see all the commands typed
