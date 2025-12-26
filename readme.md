#git course
This is a complete git course
# This is the Bug 
# for sample purpose
# git course
This is a complete git course

# This is the change from feature branch 
# this is feature 2.0

<!-- PS C:\Users\Dharasree\Desktop\Git>  git config --global use.name 'Shree' 
PS C:\Users\Dharasree\Desktop\Git> git config --global use.email 'subasree3008@gmail.com'
PS C:\Users\Dharasree\Desktop\Git> git config use.name
Shree
PS C:\Users\Dharasree\Desktop\Git> git config use.email
subasree3008@gmail.com
PS C:\Users\Dharasree\Desktop\Git> git config --global init.defaultBranch main
PS C:\Users\Dharasree\Desktop\Git> git init
Initialized empty Git repository in C:/Users/Dharasree/Desktop/Git/.git/
PS C:\Users\Dharasree\Desktop\Git>  git status
On branch main

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        index.html
        index.js
        readme.md

nothing added to commit but untracked files present (use "git add" to track)
PS C:\Users\Dharasree\Desktop\Git> git add readme.md
PS C:\Users\Dharasree\Desktop\Git> git commit -m 'readme'
[main (root-commit) 433f62e] readme
 1 file changed, 2 insertions(+)
 create mode 100644 readme.md
PS C:\Users\Dharasree\Desktop\Git> git log
commit 433f62eb9854d1fc96ab61112c402861b4f65361 (HEAD -> main)
Author: Sree3008 <22cs100@nandhaengg.org>
Date:   Thu Dec 25 20:11:31 2025 +0530

    readme
PS C:\Users\Dharasree\Desktop\Git> git status
On branch main
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        index.html
        index.js

nothing added to commit but untracked files present (use "git add" to track)
PS C:\Users\Dharasree\Desktop\Git> git add .
PS C:\Users\Dharasree\Desktop\Git> git commit -m 'initial commit'
[main 68ed108] initial commit
 2 files changed, 60 insertions(+)
 create mode 100644 index.html
 create mode 100644 index.js
PS C:\Users\Dharasree\Desktop\Git> git log
commit 68ed108d23fa51ee008efd8d70bb225fa1049421 (HEAD -> main)
Author: Sree3008 <22cs100@nandhaengg.org>
Date:   Thu Dec 25 20:15:32 2025 +0530

    initial commit

commit 433f62eb9854d1fc96ab61112c402861b4f65361
Author: Sree3008 <22cs100@nandhaengg.org>
Date:   Thu Dec 25 20:11:31 2025 +0530

    readme
PS C:\Users\Dharasree\Desktop\Git> git checkout 433f62eb9854d1fc96ab61112c402861b4f65361
Note: switching to '433f62eb9854d1fc96ab61112c402861b4f65361'.

You are in 'detached HEAD' state. You can look around, make experimental
changes and commit them, and you can discard any commits you make in this
state without impacting any branches by switching back to a branch.

If you want to create a new branch to retain commits you create, you may
do so (now or later) by using -c with the switch command. Example:

  git switch -c <new-branch-name>

Or undo this operation with:

  git switch -

Turn off this advice by setting config variable advice.detachedHead to false

HEAD is now at 433f62e readme
PS C:\Users\Dharasree\Desktop\Git> git checkout main
Previous HEAD position was 433f62e readme
Switched to branch 'main'
PS C:\Users\Dharasree\Desktop\Git> git checkout 433f62eb9854d1fc96ab61112c402861b4f65361
Note: switching to '433f62eb9854d1fc96ab61112c402861b4f65361'.

You are in 'detached HEAD' state. You can look around, make experimental
changes and commit them, and you can discard any commits you make in this

Or undo this operation with:

  git switch -

Turn off this advice by setting config variable advice.detachedHead to false

HEAD is now at 433f62e readme
PS C:\Users\Dharasree\Desktop\Git> git checkout main
Previous HEAD position was 433f62e readme
Switched to branch 'main'
PS C:\Users\Dharasree\Desktop\Git> git checkout 433f62eb9854d1fc96ab61112c402861b4f65361
Note: switching to '433f62eb9854d1fc96ab61112c402861b4f65361'.

You are in 'detached HEAD' state. You can look around, make experimental
changes and commit them, and you can discard any commits you make in this

HEAD is now at 433f62e readme
PS C:\Users\Dharasree\Desktop\Git> git checkout main
Previous HEAD position was 433f62e readme
Switched to branch 'main'
PS C:\Users\Dharasree\Desktop\Git> git checkout 433f62eb9854d1fc96ab61112c402861b4f65361
Note: switching to '433f62eb9854d1fc96ab61112c402861b4f65361'.

You are in 'detached HEAD' state. You can look around, make experimental
changes and commit them, and you can discard any commits you make in this
Switched to branch 'main'
PS C:\Users\Dharasree\Desktop\Git> git checkout 433f62eb9854d1fc96ab61112c402861b4f65361
Note: switching to '433f62eb9854d1fc96ab61112c402861b4f65361'.

You are in 'detached HEAD' state. You can look around, make experimental
changes and commit them, and you can discard any commits you make in this
PS C:\Users\Dharasree\Desktop\Git> git checkout 433f62eb9854d1fc96ab61112c402861b4f65361
Note: switching to '433f62eb9854d1fc96ab61112c402861b4f65361'.

You are in 'detached HEAD' state. You can look around, make experimental
changes and commit them, and you can discard any commits you make in this

You are in 'detached HEAD' state. You can look around, make experimental
changes and commit them, and you can discard any commits you make in this
changes and commit them, and you can discard any commits you make in this
state without impacting any branches by switching back to a branch.

If you want to create a new branch to retain commits you create, you may
do so (now or later) by using -c with the switch command. Example:

  git switch -c <new-branch-name>

Or undo this operation with:

PS C:\Users\Dharasree\Desktop\Git> git checkout main
M       readme.md
Previous HEAD position was 433f62e readme
Switched to branch 'main'
PS C:\Users\Dharasree\Desktop\Git> git checkout -f main
Already on 'main'
PS C:\Users\Dharasree\Desktop\Git> git status
On branch main
nothing to commit, working tree clean
PS C:\Users\Dharasree\Desktop\Git> git config --global user.email "subasree3008@gmail.com"
PS C:\Users\Dharasree\Desktop\Git> git config --global user.email "22cs100@nandhaengg.org"
PS C:\Users\Dharasree\Desktop\Git> git remote add origin https://github.com/Sree3008/Git.git
PS C:\Users\Dharasree\Desktop\Git> git push -u origin main
info: please complete authentication in your browser...
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 12 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (7/7), 965 bytes | 321.00 KiB/s, done.
Total 7 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/Sree3008/Git.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.
PS C:\Users\Dharasree\Desktop\Git> git branch bug
PS C:\Users\Dharasree\Desktop\Git> git checkout bug
Switched to branch 'bug'
PS C:\Users\Dharasree\Desktop\Git> git checkout -b features
Switched to a new branch 'features'
PS C:\Users\Dharasree\Desktop\Git> git add .
PS C:\Users\Dharasree\Desktop\Git> git commit -m 'Update ReadMe'
[features d521e7d] Update ReadMe
 1 file changed, 4 insertions(+), 2 deletions(-)
PS C:\Users\Dharasree\Desktop\Git> git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
PS C:\Users\Dharasree\Desktop\Git> git checkout bug
Switched to branch 'bug'
PS C:\Users\Dharasree\Desktop\Git> git add .
PS C:\Users\Dharasree\Desktop\Git> git commit -m 'ReadMe Bug'
[bug e9be461] ReadMe Bug
 1 file changed, 2 insertions(+), 1 deletion(-)
PS C:\Users\Dharasree\Desktop\Git> git checkout features
Switched to branch 'features'
PS C:\Users\Dharasree\Desktop\Git> git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
PS C:\Users\Dharasree\Desktop\Git> git checkout features
Switched to branch 'features'
PS C:\Users\Dharasree\Desktop\Git> git checkout -b features2
Switched to a new branch 'features2'
PS C:\Users\Dharasree\Desktop\Git> git branch new_bug bug
PS C:\Users\Dharasree\Desktop\Git> git checkout new_bug
Switched to branch 'new_bug'
PS C:\Users\Dharasree\Desktop\Git> git push --set -upstream origin new_bug 
error: unknown switch `p'
usage: git push [<options>] [<repository> [<refspec>...]]

    -v, --[no-]verbose    be more verbose
    -q, --[no-]quiet      be more quiet
    --[no-]repo <repository>
                          repository
    --[no-]all            push all branches
    --[no-]branches       alias of --all
    --[no-]mirror         mirror all refs
    -d, --[no-]delete     delete refs
    --[no-]tags           push tags (can't be used with --all or --branches or --mirror)
    -n, --[no-]dry-run    dry run
    --[no-]porcelain      machine-readable output
    -f, --[no-]force      force updates
    --[no-]force-with-lease[=<refname>:<expect>]
                          require old value of ref to be at this value      
    --[no-]force-if-includes
                          require remote updates to be integrated locally   
    --[no-]recurse-submodules (check|on-demand|no)
                          control recursive pushing of submodules
    --[no-]thin           use thin pack
    --[no-]receive-pack <receive-pack>
                          receive pack program
    --[no-]exec <receive-pack>
                          receive pack program
    -u, --[no-]set-upstream
                          set upstream for git pull/status
    --[no-]progress       force progress reporting
    --[no-]prune          prune locally removed refs
    --no-verify           bypass pre-push hook
    --verify              opposite of --no-verify
    --[no-]follow-tags    push missing but relevant tags
    --[no-]signed[=(yes|no|if-asked)]
                          GPG sign the push
    --[no-]atomic         request atomic transaction on remote side
    -o, --[no-]push-option <server-specific>
                          option to transmit
    -4, --ipv4            use IPv4 addresses only
    -6, --ipv6            use IPv6 addresses only

PS C:\Users\Dharasree\Desktop\Git> git push --set-upstream origin new_bug 
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 294 bytes | 294.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.        
remote:
remote: Create a pull request for 'new_bug' on GitHub by visiting:
remote:      https://github.com/Sree3008/Git/pull/new/new_bug
remote:
To https://github.com/Sree3008/Git.git
 * [new branch]      new_bug -> new_bug
branch 'new_bug' set up to track 'origin/new_bug'.
PS C:\Users\Dharasree\Desktop\Git> git checkout fea
error: pathspec 'fea' did not match any file(s) known to git
PS C:\Users\Dharasree\Desktop\Git> git checkout features
Switched to branch 'features'
PS C:\Users\Dharasree\Desktop\Git> git push -u origin features
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 318 bytes | 318.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.        
remote:
remote: Create a pull request for 'features' on GitHub by visiting:
remote:      https://github.com/Sree3008/Git/pull/new/features
remote:
To https://github.com/Sree3008/Git.git
 * [new branch]      features -> features
branch 'features' set up to track 'origin/features'.
PS C:\Users\Dharasree\Desktop\Git> git add .
PS C:\Users\Dharasree\Desktop\Git> git push
Everything up-to-date
PS C:\Users\Dharasree\Desktop\Git> git commit -m 'New Feature' 
[features 94463b4] New Feature
 1 file changed, 2 insertions(+), 1 deletion(-)
PS C:\Users\Dharasree\Desktop\Git> git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 298 bytes | 298.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.       
To https://github.com/Sree3008/Git.git
   d521e7d..94463b4  features -> features
PS C:\Users\Dharasree\Desktop\Git> git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
PS C:\Users\Dharasree\Desktop\Git> git pull
remote: Enumerating objects: 1, done.
remote: Counting objects: 100% (1/1), done.
remote: Total 1 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)       
Unpacking objects: 100% (1/1), 889 bytes | 25.00 KiB/s, done.
From https://github.com/Sree3008/Git
   68ed108..7cf8079  main       -> origin/main
Updating 68ed108..7cf8079
Fast-forward
 readme.md | 7 +++++--
 1 file changed, 5 insertions(+), 2 deletions(-)
PS C:\Users\Dharasree\Desktop\Git> */-->

# this is commit 1

# this is commit 2

# this is commit 3

# this is commit 4