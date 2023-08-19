# Common-VSCode-Issues-Tips

## Mac VS code error — permission denied writing to file!

Solution is to Give the folder 777 permission.

In the terminal, the command to use to change file permission is “ chmod “.

In short, “chmod 777” means making the file readable, writable and executable by everyone.

```sudo chmod -R 777 <project_dir_name>```

In my 👨‍💻 case I solved it by running command in terminal like this …👇

```sudo chmod -R 777 ankitmaheshwari/git/hello-world```
