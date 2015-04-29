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
```
To flip through previously used commands.

```
⌥ + click
```
To place your cursor inside of a line in your terminal. Shout out to [@kelseyinnis](https://twitter.com/kelseyinnis) for this gem. Applaud her.

```
$ ls
```
This command lists the contents of the directory you're currently in.

```
$ (Tab) ↹
```
The tab key allows you to autocomplete a string or path you're typing out in your terminal. This shortcut is a good incentive to make sure you're naming things without spaces in-between words (i.e. Bad: "Personal Projects" vs. Good: "personal-projects").

```
$ which ruby
```
The `which` command allows you to check to see if a gem or package is installed on your machine.

```
$ ruby -v
```
The `-v` command asks your computer which version of something you have installed. This can be super useful when managing and updating "dependencies".

```
$ sudo gem install
```
`sudo` allows you to bypass permissions on your computer and install things using just your system password (the terminal will prompt you for this after you run the command).

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
Here appending the `-A` to the `add .` command  tells the terminal to create (or, add) any files you've added to your project (images included) and simultaneously to delete any files (or images) that you removed. This can be super helpful when you're getting started with a project and adding and deleting a ton of assets.

```
$ git commit -m"your commit message here"
```
This command allows you to write your commit message 
You can search more git commands on http://git-scm.com/.
