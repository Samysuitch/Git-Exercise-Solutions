# Git Exercises
this project aims to get familiar with git comands
## boundle 1
### exercise 1
``` bash
PS C:\Users\IYAKAREMYE Samuel\OneDrive\Desktop\html-practice\html-practice\samy.htmlpractice\GIT Exercise12> git init
Reinitialized existing Git repository in C:/Users/IYAKAREMYE Samuel/OneDrive/Desktop/html-practice/html-practice/samy.htmlpractice/GIT Exercise12/.git/
PS C:\Users\IYAKAREMYE Samuel\OneDrive\Desktop\html-practice\html-practice\samy.htmlpractice\GIT Exercise12> git branch -M main
PS C:\Users\IYAKAREMYE Samuel\OneDrive\Desktop\html-practice\html-practice\samy.htmlpractice\GIT Exercise12> git status
On branch main

No commits yet

nothing to commit (create/copy files and use "git add" to track)
PS C:\Users\IYAKAREMYE Samuel\OneDrive\Desktop\html-practice\html-practice\samy.htmlpractice\GIT Exercise12> git add .
PS C:\Users\IYAKAREMYE Samuel\OneDrive\Desktop\html-practice\html-practice\samy.htmlpractice\GIT Exercise12> git status
On branch main

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md

PS C:\Users\IYAKAREMYE Samuel\OneDrive\Desktop\html-practice\html-practice\samy.htmlpractice\GIT Exercise12> git commit -m "first and my main commit"
[main (root-commit) 190e1f8] first and my main commit
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 README.md
PS C:\Users\IYAKAREMYE Samuel\OneDrive\Desktop\html-practice\html-practice\samy.htmlpractice\GIT Exercise12> git remote add origin https://github.com/Samysuitch/Git-Exercise-Solutions.git
PS C:\Users\IYAKAREMYE Samuel\OneDrive\Desktop\html-practice\html-practice\samy.htmlpractice\GIT Exercise12> git push --set-upstream origin main
To https://github.com/Samysuitch/Git-Exercise-Solutions.git
 ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'https://github.com/Samysuitch/Git-Exercise-Solutions.git'
hint: Updates were rejected because the remote contains work that you do not
hint: have locally. This is usually caused by another repository pushing to
hint: the same ref. If you want to integrate the remote changes, use
hint: 'git pull' before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.
PS C:\Users\IYAKAREMYE Samuel\OneDrive\Desktop\html-practice\html-practice\samy.htmlpractice\GIT Exercise12> git ccheckout -b dev
git: 'ccheckout' is not a git command. See 'git --help'.

The most similar command is
        checkout
PS C:\Users\IYAKAREMYE Samuel\OneDrive\Desktop\html-practice\html-practice\samy.htmlpractice\GIT Exercise12> git checkout -b dev

Switched to a new branch 'dev'
PS C:\Users\IYAKAREMYE Samuel\OneDrive\Desktop\html-practice\html-practice\samy.htmlpractice\GIT Exercise12> git checkout -b test
Switched to a new branch 'test'
PS C:\Users\IYAKAREMYE Samuel\OneDrive\Desktop\html-practice\html-practice\samy.htmlpractice\GIT Exercise12> git branch -d test
error: cannot delete branch 'test' used by worktree at 'C:/Users/IYAKAREMYE Samuel/OneDrive/Desktop/html-practice/html-practice/samy.htmlpractice/GIT Exercise12'
PS C:\Users\IYAKAREMYE Samuel\OneDrive\Desktop\html-practice\html-practice\samy.htmlpractice\GIT Exercise12> git status
On branch test
nothing to commit, working tree clean
PS C:\Users\IYAKAREMYE Samuel\OneDrive\Desktop\html-practice\html-practice\samy.htmlpractice\GIT Exercise12> git checkout dev
Switched to branch 'dev'
PS C:\Users\IYAKAREMYE Samuel\OneDrive\Desktop\html-practice\html-practice\samy.htmlpractice\GIT Exercise12> git branch -d test
Deleted branch test (was 190e1f8).
PS C:\Users\IYAKAREMYE Samuel\OneDrive\Desktop\html-practice\html-practice\samy.htmlpractice\GIT Exercise12> git push
fatal: The current branch dev has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin dev

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.

PS C:\Users\IYAKAREMYE Samuel\OneDrive\Desktop\html-practice\html-practice\samy.htmlpractice\GIT Exercise12> git push-- set-upstream origin dev
git: 'push--' is not a git command. See 'git --help'.
PS C:\Users\IYAKAREMYE Samuel\OneDrive\Desktop\html-practice\html-practice\samy.htmlpractice\GIT Exercise12> git --help
usage: git [-v | --version] [-h | --help] [-C <path>] [-c <name>=<value>]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p | --paginate | -P | --no-pager] [--no-replace-objects] [--bare]
           [--git-dir=<path>] [--work-tree=<path>] [--namespace=<name>]
           [--config-env=<name>=<envvar>] <command> [<args>]

These are common Git commands used in various situations:

start a working area (see also: git help tutorial)
   clone     Clone a repository into a new directory
   init      Create an empty Git repository or reinitialize an existing one

work on the current change (see also: git help everyday)
   add       Add file contents to the index
   mv        Move or rename a file, a directory, or a symlink
   restore   Restore working tree files
   rm        Remove files from the working tree and from the index

examine the history and state (see also: git help revisions)
   bisect    Use binary search to find the commit that introduced a bug
   diff      Show changes between commits, commit and working tree, etc
   grep      Print lines matching a pattern
   log       Show commit logs
   show      Show various types of objects
   status    Show the working tree status

grow, mark and tweak your common history
   branch    List, create, or delete branches
   commit    Record changes to the repository
   merge     Join two or more development histories together
   rebase    Reapply commits on top of another base tip
   reset     Reset current HEAD to the specified state
   switch    Switch branches
   tag       Create, list, delete or verify a tag object signed with GPG

collaborate (see also: git help workflows)
   fetch     Download objects and refs from another repository
   pull      Fetch from and integrate with another repository or a local branch
   push      Update remote refs along with associated objects

'git help -a' and 'git help -g' list available subcommands and some
concept guides. See 'git help <command>' or 'git help <concept>'
to read about a specific subcommand or concept.
See 'git help git' for an overview of the system.
PS C:\Users\IYAKAREMYE Samuel\OneDrive\Desktop\html-practice\html-practice\samy.htmlpractice\GIT Exercise12> git help git
PS C:\Users\IYAKAREMYE Samuel\OneDrive\Desktop\html-practice\html-practice\samy.htmlpractice\GIT Exercise12> 
```
