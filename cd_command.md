# _CD_ Command

## Discription
- cd = change directory
- cd is the command with wich you are able to move between your folders and files. It´s maybe the most used command on Linux.

## Syntax
 `cd <foldername>` = change directory to destination

 `cd ..` = change directory out of current folder

## Example
 > `cd home`

 > `cd Desktop`

 > `cd Home && cd Desktop`

 > `cd Home/Desktop/` 

## Variations
```
    -L	    force symbolic links to be followed: resolve symbolic
    		links in DIR after processing instances of `..'
    -P	    use the physical directory structure without following
    		symbolic links: resolve symbolic links in DIR before
    		processing instances of `..'
    -e	    if the -P option is supplied, and the current working
    		directory cannot be determined successfully, exit with
    		a non-zero status
    -@	    on systems that support it, present a file with extended
    		attributes as a directory containing the file attributes
```

## Sources
>> <span style="color:#9f0">Terminal Manual</span> `cd --help` `man cd`