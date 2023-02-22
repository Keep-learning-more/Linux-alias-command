# Linux-Commands
Repository for Basic Linux Commands 
1. **Alias**
Alias is a command used to create custom shortcuts to represent a actuall commands or a set of commands executeding with or without custom options. 
It is like a shortcut command which will have same functionality as if we are writing the whole command  

**Syntax**
$ alias NAME=VALUE

To see all defined aliases in the shell execute below command 

> $ alias -p 

***Creating a Temporary Alias in Linux***

**Examples**

> $ alias .=cd

In the above command we have created an alias for ***cd*** command, which is used for change the directory.  \
From now we no need to execute ***cd*** command to change the directory, we can just use ***.*** to change the directory.  

> $ alias  c=clear

In the above command we have created an alias for ***clear*** command, which is used for clearing the on screen text in the shell/terminal \
From now we can just use ***c*** for clearing the on screen text in the shell/terminal

***Creating a Permanent Alias in Linux***

To make an alias permanent you need to add it to your shell configuration file \
If your using the **bash** shell, you need to add the custom alias to the ***~/.bashrc*** file

**Example**

> #Custom aliases \
alias c=clear \
alias .=cd \
alias vi=vim \
alias 'ls -l'=ll
