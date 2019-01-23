Answer 1: git version 2.17.1

Answer 2: user.name=Sam Adams
user.email=sa324515@ohio.edu

Answer 3:usage: git [--version] [--help] [-C <path>] [-c <name>=<value>]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p | --paginate | --no-pager] [--no-replace-objects] [--bare]
           [--git-dir=<path>] [--work-tree=<path>] [--namespace=<name>]
           <command> [<args>]

These are common Git commands used in various situations:

start a working area (see also: git help tutorial)
   clone      Clone a repository into a new directory
   init       Create an empty Git repository or reinitialize an existing one

work on the current change (see also: git help everyday)
   add        Add file contents to the index
   mv         Move or rename a file, a directory, or a symlink
   reset      Reset current HEAD to the specified state
   rm         Remove files from the working tree and from the index

examine the history and state (see also: git help revisions)
   bisect     Use binary search to find the commit that introduced a bug
   grep       Print lines matching a pattern
   log        Show commit logs
   show       Show various types of objects
   status     Show the working tree status

grow, mark and tweak your common history
   branch     List, create, or delete branches
   checkout   Switch branches or restore working tree files
   commit     Record changes to the repository
   diff       Show changes between commits, commit and working tree, etc
   merge      Join two or more development histories together
   rebase     Reapply commits on top of another base tip
   tag        Create, list, delete or verify a tag object signed with GPG

collaborate (see also: git help workflows)
   fetch      Download objects and refs from another repository
   pull       Fetch from and integrate with another repository or a local branch
   push       Update remote refs along with associated objects

'git help -a' and 'git help -g' list available subcommands and some
concept guides. See 'git help <command>' or 'git help <concept>'

Answer 4: On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)

	README.md
	answers.md


nothing added to commit but untracked files present (use &quot;git add&quot; to track)</pre>

Answer 5: On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

	new file:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)

	answers.md


Answer 6: On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

	new file:   README.md
	new file:   answers.md

Answer 7: On branch master
nothing to commit, working tree clean

Answer 8: On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

	new file:   README.md
	new file:   answers.md

sadams@odd27:~/2400/git-lab$ git commit -m "Initial commit"
[master (root-commit) fb9615f] Initial commit
 2 files changed, 2 insertions(+)
 create mode 100644 README.md
 create mode 100644 answers.md
sadams@odd27:~/2400/git-lab$ git status
On branch master
nothing to commit, working tree clean
sadams@odd27:~/2400/git-lab$ git log
commit fb9615fadd5acd0e1f1ab26f1db61af1d3488a97 (HEAD -> master)
Author: Sam Adams <sa324515@ohio.edu>
Date:   Tue Jan 22 18:21:37 2019 -0500

    Initial commit

Answer 9: On branch master
Your branch is up to date with 'origin/master'.

nothing to commit, working tree clean

Answer 10: Online changes were not reflected in the local copy

Answer 11: To https://github.com/sa324515/git-lab.git
 ! [rejected]        master -> master (fetch first)
error: failed to push some refs to 'https://github.com/sa324515/git-lab.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

Answer 12: Yes the changes from online appeared on the local copy

Answer 13: .  ..  .git  .gitignore  README.md



