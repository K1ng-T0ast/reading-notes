# **What is a Text Editor?**

+ A piece of software that lets you manage lines of text, most often in tandem with code creation and manipulation
+ Important features include code completion, syntax highlighting, variety of themes, and extension selection
+ __*code completion*__ can be especially useful, as this will prevent typos and allow your workflow to be faster
+ Themes will increase productivity by reducing eye fatigue by allowing the contrast of colors and darker backdrops
+ Many text editors come preinstalled but lack feature sets and upgradeability

## __*List of Text Editing Software*__
1. Notepad++
   - Windows only
2. Text Wrangler/BB Edit
   - Mac only
3. Visual Studio Code
   - Has Emmet shorthand for HTML and CSS already built-in with no additional work
4. Atom
5. Brackets
6. Sublime Text
   - Costs money

## **Text Editors versus IDEs**

- IDE (integrated development environment) works as a software suite like microsoft outlook
- A text editor edits texts
- An IDE can be a text editor, a file manager, a compiler, and a debugger all in one

# **The Command Line**

* AKA a terminal, it is a text based interface to the system
* You interact with the system by entering commands by typing them on the keybaord and getting text feedback of the results
* Typically there's a prompt or an issuance of command followed by a prompt
* Commands are usually followed by arguments, or sub commands that tell the system the intention. Also known as an option. Options typically start with a dash

## The Shell, Bash

+ Within a terminal is the shell which is the part of the operating system that defines how the terminal will behave and will look to run or execute commands
+ Various shells exist but the most common is called bash or bourne again shell
+ You can use the command __echo__ to see which shell you are using, echo is a command which is used to display messages

__*MISC*__ 

Commands are stored in a history which can be traversed by using the up and down arrow keys. No need to reenter commands, just hit the up or down arrow key, these commands can be edited using the left or right arrow key or the cursor

## Command Line Navigation

+ PWD = print working directory. Tells you where you are currently.
+ Is = List. What is there currently.
+ Is (insert) = list within a directory folder
+ Is -l = argument command list. Detailed contents of directory.
+ clear = clear. Clears terminal.
+ cd (insert) = change directory with path
+ cd ..= back one directory level
+ cd ...= back two directory levels
+ cd = takes you to home directory
+ mkdir (insert) = make new directory. When making directories use caution with spaces.
+ touch (insert)(name of extension) = create new file with extension name
+ . = here
+ tree = visual tree of your current directory

### Files in Linux/Terminal

- Everything under the hood is a file. Text, directory, keyboard, monitor, all files.
- We specify a file or directory on the command line as **path**. Path is a means to get to a particular location in the system and that location is a file.
- __*LINUX IS CASE SENSITIVE*__
- A space can be considered two separate commands so be careful when using them. You can separate items by using quotes (single or double) or a backslash followed by a space which nullifies (escape) the special meaning of the next character. If you use the escape before encountering the space the terminal will automatically escape any spaces in the name for you
- the command full stop is denoted by a period and will hide files in the directory and can be included or discluded before the file name. -a  will show hidden files and directories. *example: la -a Documents*
