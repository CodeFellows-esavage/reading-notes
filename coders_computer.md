# The Coder's Computer
## Summary
Text editors are personal choices, and ultimately it doesn't matter which editor you choose, as they are all realtively similar. Choose an editor that allows you to successfully complete the project at hand with one tool. And at the end of the day the best text editor is the one you enjoy using and are proficeint with.

## Text Editor
A text editor is a tool in the form of software that allows a software developer to effienctly code websites, apps, or pretty much anythind coding related. They provide a variety of features that make it easier to code from code completion to plug ins.

Top Features as noted by "The Older Coder"
1. Code Completion
    - The ability for the code to auto complete certain features of a piece of code, such as closing brackets, quotations, or even providing suggestions based on the code typed.
3. Syntax Highlighting
    - Applying color coding to certain portions of the code to make it easier to consume visually.
5. Theme Variety
    - Selection of different themes e.g. night theme vs standard, to reduce eye fatigue.
7. Extension Availability
    - The ability for your text editor to grow (as needed) through plug-ins.

It is advised to avoid the native text editors to your Windows, Mac, or Linux machine, as they are considered "bare bones" and do not provide any of the features listed above. On the otherhand there are a variety of third party text editors that can provide all of those features and are even free (VS Code, Notepad++, Atom, etc). Take into consideration to which editors are conpatible with the OS your are using (for example Notepad++ is Windows only). I personally prefer the text editors that are available across all operating systems, as I will always have a familiar environment reglardless of the hardware I am writing code on.

## Terminal
Terminal (also know as the Command Line) runs BASH (bourne again shell) and is a text based interface system opposed to the typical graphical user interface most are more commonly associated with.

[Mac Terminal Cheat Sheet](https://github.com/0nn0/terminal-mac-cheatsheet#english-version)

- Commands are typically the first thing you type
- arguements typically come seconds and there must be a space between the command and the argument
- The first command line argument is typically refered to as an option, which are typically listed before other arguments and begin with a dash (-)

### Commands
- pwd (print working directory): shows current working directory, use this to keep track of where you are as you move around in the terminal.
- ls (list): displays what is in the current location
- cd (change directories): move to another directory
- file [path]: obtain information about the file type of a file or directory
- ls -a (list all): list contents of a directory including hidden files

### Paths
- getting to a particular file or directory on the system
- Two (2) types, absolute or relative
    - absolute, begin from the **root** directory and always begin with a "/"
    - relative, specifies a location from the current location in the system
- Multiple approaches to specifying a path
    - tilde (~): short cut to home directory
    - dot (.): references current directory
    - dotdot (..): reference to parent directory 

- everything is a file
- Linux doesn't care about the file extensions (.jpg, .txt, etc.) but instead looks within the file to determine the file type
- Linux is case sensitive, so it is possible to have more than one file with the same name but different casing on the letters.
- Linux allows for spaces in file names, but requires pathing to these files using quotations or escape characters.
    - backslash (\) is an escape character which cancels out the meaning of the next character
