## Terminal Shortcuts & Commands

```
$ cd
```
This command stands for "change directory" and allows you to navigate through directories via the terminal.

```
$ cd ..
```
`..` roughly translates to "back one folder". By using `cd ..` we're telling the terminal to jump back one directory, or to the parent folder of where we currently are.

```
arrow up key
Ctrl + p
```
To flip up through previously used commands.

```
arrow down key
Ctrl + n
```
To flip down through following commands.

```
Ctrl + a
Ctrl + e
```
To quickly jump to beginning or end of line.

```
Alt (meta) + f
Alt (meta) + b
```
To jump a word forward and backwards.

```
⌥ + click
```
Use option+click to place your cursor inside of a line in your terminal. Shout out to [@kelseyinnis](https://twitter.com/kelseyinnis) for this gem. Applaud her.

```
Ctrl + c
Ctrl + d
```
Use this command to quit or cancel a process in your terminal.

```
Ctrl + z
```
Use this command to push running process to background.

```
$ ls
```
This command lists the contents of the directory you're currently in.

```
$ ls -lah
```
This command also lists the contents of your active or current directory (with human-readable filesize) but it also shows hidden files & dotfiles. This tip gifted by [@_dte](https://twitter.com/_dte).

```
$ (Tab) ↹
```
The tab key allows you to auto-complete a string or path you're typing out in your terminal. This shortcut is a good incentive to make sure you're naming things without spaces in-between words (i.e. Bad: "Personal Projects" vs. Good: "personal-projects").

```
$ which ruby
```
The `which` command allows you to check to see if a gem (or a package) is installed on your machine. In addition, it returns the call path.

```
$ ruby -v
```
The `-v` command asks your computer which version of something you have installed. This can be super useful when managing and updating "dependencies".

```
$ sudo gem install
```
`sudo` allows you to bypass permissions on your computer and install things using just your system password (the terminal will prompt you for this after you run the command).

```
sudo !!
```
If you run a command and forget to add sudo to it, run `sudo !!` and it'll prepend the previous command with your `sudo`. Compliments of [@joericho](https://twitter.com/joericho).

```
!?<keyword>
```
Run a command (in history) that starts with <keyword>

## Useful Git Commands

Git is a type of version control that we can interact with via the terminal.

```
$ git status
```

`Git status` will tell you if you've made any local changes, as well as what branch you're currently working on by returning something like: 

```
On branch gh-pages
Your branch is up-to-date with 'origin/gh-pages'
```
This command also returns info about whether or not your branch is up-to-date with its "parent" branch.

```
$ git add .
```
`.` tells the terminal to add all changed or edited files to be to be committed.

```
$ git add . -A
```
Here appending the `-A` to the `add .` command  tells the terminal to create (or stage) any files you've added to your project (images included) and simultaneously to delete any files (or images) that you removed. This can be super helpful when you're getting started with a project and adding and deleting a ton of "assets".

```
$ git commit -m "your commit message here"
```
This command allows you to write your commit message inline.

```
$ git checkout -b your-new-branch
```
This command allows you to create, name, and switch to a new branch at the same time. Super handy.

```
$ git co -
```
This command allows you to check out the branch you just switched from. From the mind and workflow of [@__Neha ](https://twitter.com/__Neha)

Get more git commands <a href="http://git-scm.com/">here!</a>