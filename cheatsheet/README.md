**pwd**

Print working directory.

Save the current working directory in a variable with command substitution:

```
d=$( pwd )			# save cwd
cd /somewhere/else		# go somewhere else
				# do something else
cd $d			        # go back to where the script originally started
```

**cd**

Change directory.

```
cd /some/path/			# move to directory
cd				# go $HOME
cd /				# go to root directory
cd ..			        # move one directory back toward root
cd -			        # cd into the previous directory
cd ..			        # move one directory back toward root
```

**ls**

List files and directories.

**mkdir, rmdir**

Create or remove directory

**echo**

Print string

**cat, zcat, tac**


cp**

Copy file

**mv**

Rename file or directory

**rm**

Remove file

**shred**

Remove by overwritting then removing

**man**

Show manual for a command

**head, tail**

**less, zless, more**

**grep, egrep**
