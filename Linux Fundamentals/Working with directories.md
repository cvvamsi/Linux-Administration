# Working with Directories

**Directory Shortcuts**

| . | This directory |
| --- | --- |
| .. | The parent directory |
| cd  | change to the previous directory |

To change the directory we use the cd command

cd /home/vamsi 

pwd - displays the present working directory

The environment variable $OLDPWD holds the value of the directory we were previously in.

cd - takes us to the directory we were previously in

./command is used to execute a command in the present directory

**Creating and removing directories**

| mkdir [-p] directory | Creates a directory |
| --- | --- |
| rmdir [-p] directory | Remove a directory |
| rm -rf directory | Recursively removes a directory |

The -p is optional. If we want to create a directory