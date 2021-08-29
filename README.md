# Customize your terminal

This script will allow you to customize your terminals without the need of installing anything.

It will display the current user, the current path, and when inside a git repository, it will display the branch name and the number of modified files.

## Requirements
- GIT

## Setup
- Clone this repository
- Edit the file `~/.bashrc` or `~/.profile` and add the following code at the end of the file:

```
CUSTOM_BASH_DESIGN_FILE_PATH=~/.bash_design 
if [ -f $CUSTOM_BASH_DESIGN_FILE_PATH ]; then
    . $CUSTOM_BASH_DESIGN_FILE_PATH
fi

```

Please make sure to replace `~/.bash_design` with the path for `.bash_design` file from your cloned repository.

## Screenshots

###  Terminal in a non GIT folder
![terminal 1](https://github.com/nicumicle/terminal/blob/master/screenshots/1.png)

###  Terminal in a GIT folder with no files modified
![terminal 2](https://github.com/nicumicle/terminal/blob/master/screenshots/2.png)

### Terminal in a GIT folder with one modified file
![terminal 3](https://github.com/nicumicle/terminal/blob/master/screenshots/3.png)

## Tested on OS:
- Ubuntu 20.04
- Ubuntu 18.04

## Tested with terminals
- gnome-terminal
- Terminator
