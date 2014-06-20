git-cheat
==========

Because i like git, but it has too many commands.

`git-cheat` is a dependency free git helper in your command-line. Of course here is not full list of git commands and their keys, here is the set of commands which i'm using almost every day. If i'm missing something, please, feel free to contribute.

usage
--------

1. Clone `git-cheat` with:

```
git clone git@github.com:0xAX/git-cheat.git
```

2. Install it to any place which is in your `$PATH`

3. Try to use:

```shell
./git-cheat
Usage: git-cheat [option]

Mandatory arguments:

  --setup -s          --> git setup and configuration 
  --init -i           --> cration of new project 
  --add -a            --> adding files to git 
  --delete -d         --> deleting files from git 
  --commit -c         --> git commit helper 
  --branch -b         --> git branching info 
  --merge -m          --> git merging info 
  --update -u         --> updating current repo 
  --stash -st         --> stashing in current repo 
  --inspect -in       --> git inspection, log,show... 
  --remote -r         --> git remote helper 
  --patch -p          --> git patching helper 
  --debug -dg         --> git debugging 
  --email -e          --> git email helper 
  --tags -t           --> git tags helper 
  --reset -rs         --> git reset helper 
  --conflict -cn      --> git conflict resolving helper 
  --revert -rv        --> git reverting helper 
  --fix-mistakes -f   --> fix mistakes in git 
  --submodules -sm    --> git submodules helper 
  --archive -ar       --> archive your repo 

  --help -h ?         --> prints usage of git-cheat
  --version -v        --> prints version of git-cheat 

Report bugs and contribution at: https://github.com/0xAX/git-cheat
```

```shell
./git-cheat --commit

git commiting
=============

git commit <file1> <file2> ... [-m <msg>]
    commit <file1>, <file2>, etc..., optionally using commit message <msg>.
    otherwise opening your editor to let you type a commit message

git commit -a
    commit all files changed since your last commit

git commit -v
    commit verbosely, i.e. includes the diff of the contents being committed in
    the commit message screen
```

todo
-----

  * add github cheats
  * add missed git cheats
  * more plumbing git cheats
  * add bash completion

contribution
------------

if i missed something you can easily to contribute to `git-cheat`:

  * Fork [repo](https://github.com/0xAX/git-cheat)
  * Make you changes
  * Send pull request
  * Thank you :)

author
---------

[@0xAX](https://twitter.com/0xAX)
