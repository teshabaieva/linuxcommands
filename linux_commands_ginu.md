> # `sudo`
*The `sudo` command in Unix-like operating systems allows a permitted user to execute a command as the superuser (or another user, depending on configuration)*
## syntax
`sudo`[options] `command`[arguments]
 
- **sudo**: The command itself that grants elevated privileges.
- **[options]**: Optional flags that modify the behavior of the sudo command. For instance, -u to specify a different user or -i for a login shell.
- **command**: The actual command you want to execute with elevated privileges.
- **[arguments]**: Any arguments or options specific to the command you're running under sudo.

## Examples
To update the package list using apt-get with elevated privileges, you might use:

`sudo apt-get update`

## Usages
 `sudo command` : *Running a Command as the Superuser*

 `sudo -u username command`:
 *Running a Command as Another User*

## Reference
https://www.digitalocean.com/community/tutorials/linux-commands

> # `whoami`
*The `whoami` command in Unix-like operating systems is used to display the username associated with the current user who is logged in. When you execute whoami, it returns the username of the current use.*
## Syntax
`whoami`
## Examples
`whoami` : *Display Current User's Username*
## Usages
`ls -l /home/$(whoami)` : *Check permissions or user-specific configurations*

## Reference
https://www.digitalocean.com/community/tutorials/linux-commands

> # `man`
*The man command in Linux is used to display the manual page for a particular command.* 
## Syntax
`man [options] [command]`
## Examples
`man ls` : *This displays the manual page for the ls command, showing its usage, options, and explanations.*
## Usages
`man -f ls` : *This will provide a short description of the ls command.*

## Reference
https://www.digitalocean.com/community/tutorials/linux-commands

> # `pwd`
*The pwd command in Unix-like operating systems stands for "print working directory." It is used to display the current working directory.* 
## Syntax
`pwd`


