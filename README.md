# tp-bachelor
Déplacement dans github_kelyddon_diemunsch 
Puis utilisations de git clone pour cloner le git important
utilisations de :git remote set-url origin https://github.com/Kelyddon/github_kelyddon_diemunsch.git  
pour déplacer l'origine du texte
kelyddondiemunsch@ip-172-31-20-231:~/sites/github/github_kelyddon_diemunsch/tp-bachelor$ git add .  
kelyddondiemunsch@ip-172-31-20-231:~/sites/github/github_kelyddon_diemunsch/tp-bachelor$ git push origin main
kelyddondiemunsch@ip-172-31-20-231:~/sites/github/github_kelyddon_diemunsch/tp-bachelor$ git status
problème pour transporter les docs local en docs distant:
To https://github.com/Kelyddon/github_kelyddon_diemunsch.git
 ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'https://github.com/Kelyddon/github_kelyddon_diemunsch.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

code entier:

kelyddondiemunsch@ip-172-31-20-231:~$ cd sites/github/github_kelyddon_diemunsch
bash: cd: sites/github/github_kelyddon_diemunsch: No such file or directory
kelyddondiemunsch@ip-172-31-20-231:~$ cd sites/github/github_kelyddon_diemunsch
kelyddondiemunsch@ip-172-31-20-231:~/sites/github/github_kelyddon_diemunsch$ git clone https://github.com/cecilev-axe/tp-bachelor.git
Cloning into 'tp-bachelor'...
remote: Enumerating objects: 10, done.
remote: Counting objects: 100% (10/10), done.
remote: Compressing objects: 100% (6/6), done.
remote: Total 10 (delta 0), reused 10 (delta 0), pack-reused 0 (from 0)
Receiving objects: 100% (10/10), done.
kelyddondiemunsch@ip-172-31-20-231:~/sites/github/github_kelyddon_diemunsch$ git remote set-url origin https://github.com/Kelyddon/github_kelyddon_diemunsch.git
fatal: not a git repository (or any parent up to mount point /home)
Stopping at filesystem boundary (GIT_DISCOVERY_ACROSS_FILESYSTEM not set).
kelyddondiemunsch@ip-172-31-20-231:~/sites/github/github_kelyddon_diemunsch$ git init
hint: Using 'master' as the name for the initial branch. This default branch name
hint: is subject to change. To configure the initial branch name to use in all
hint: of your new repositories, which will suppress this warning, call:
hint: 
hint:   git config --global init.defaultBranch <name>
hint: 
hint: Names commonly chosen instead of 'master' are 'main', 'trunk' and
hint: 'development'. The just-created branch can be renamed via this command:
hint: 
hint:   git branch -m <name>
Initialized empty Git repository in /home/kelyddondiemunsch/sites/github/github_kelyddon_diemunsch/.git/
kelyddondiemunsch@ip-172-31-20-231:~/sites/github/github_kelyddon_diemunsch$ cd tp-bachelor
kelyddondiemunsch@ip-172-31-20-231:~/sites/github/github_kelyddon_diemunsch/tp-bachelor$ git add .
kelyddondiemunsch@ip-172-31-20-231:~/sites/github/github_kelyddon_diemunsch/tp-bachelor$ git remote -v
origin  https://github.com/cecilev-axe/tp-bachelor.git (fetch)
origin  https://github.com/cecilev-axe/tp-bachelor.git (push)
kelyddondiemunsch@ip-172-31-20-231:~/sites/github/github_kelyddon_diemunsch/tp-bachelor$ git remote set-url origin https://github.com/Kelyddon/github_kelyddon_diemunsch.git                                                                      
kelyddondiemunsch@ip-172-31-20-231:~/sites/github/github_kelyddon_diemunsch/tp-bachelor$ git remote -v
origin  https://github.com/Kelyddon/github_kelyddon_diemunsch.git (fetch)
origin  https://github.com/Kelyddon/github_kelyddon_diemunsch.git (push)
kelyddondiemunsch@ip-172-31-20-231:~/sites/github/github_kelyddon_diemunsch/tp-bachelor$ git add .                                                                                                                                                
kelyddondiemunsch@ip-172-31-20-231:~/sites/github/github_kelyddon_diemunsch/tp-bachelor$ git bracnh
git: 'bracnh' is not a git command. See 'git --help'.

The most similar command is
        branch
kelyddondiemunsch@ip-172-31-20-231:~/sites/github/github_kelyddon_diemunsch/tp-bachelor$ git branch
* main
kelyddondiemunsch@ip-172-31-20-231:~/sites/github/github_kelyddon_diemunsch/tp-bachelor$ git push origin main
Username for 'https://github.com': Kelyddon
Password for 'https://Kelyddon@github.com': 
Enumerating objects: 10, done.
Counting objects: 100% (10/10), done.
Delta compression using up to 2 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (10/10), 2.03 KiB | 159.00 KiB/s, done.
Total 10 (delta 0), reused 10 (delta 0), pack-reused 0
To https://github.com/Kelyddon/github_kelyddon_diemunsch.git
 * [new branch]      main -> main
kelyddondiemunsch@ip-172-31-20-231:~/sites/github/github_kelyddon_diemunsch/tp-bachelor$ git add .                                                                                                                                                
kelyddondiemunsch@ip-172-31-20-231:~/sites/github/github_kelyddon_diemunsch/tp-bachelor$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   index.html

kelyddondiemunsch@ip-172-31-20-231:~/sites/github/github_kelyddon_diemunsch/tp-bachelor$ git push origin main                                                                                                                                     
Username for 'https://github.com': Kelyddon     
Password for 'https://Kelyddon@github.com': 
Everything up-to-date
kelyddondiemunsch@ip-172-31-20-231:~/sites/github/github_kelyddon_diemunsch/tp-bachelor$ git push origin main
Username for 'https://github.com': Kelyddon
Password for 'https://Kelyddon@github.com': 
To https://github.com/Kelyddon/github_kelyddon_diemunsch.git
 ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'https://github.com/Kelyddon/github_kelyddon_diemunsch.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.
kelyddondiemunsch@ip-172-31-20-231:~/sites/github/github_kelyddon_diemunsch/tp-bachelor$ git remote -v
origin  https://github.com/Kelyddon/github_kelyddon_diemunsch.git (fetch)
origin  https://github.com/Kelyddon/github_kelyddon_diemunsch.git (push)
kelyddondiemunsch@ip-172-31-20-231:~/sites/github/github_kelyddon_diemunsch/tp-bachelor$ git add .
kelyddondiemunsch@ip-172-31-20-231:~/sites/github/github_kelyddon_diemunsch/tp-bachelor$ git status                                                                                                                                               
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   css/style.css
        modified:   index.html

kelyddondiemunsch@ip-172-31-20-231:~/sites/github/github_kelyddon_diemunsch/tp-bachelor$ git status                                                                                                                                               
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   css/style.css
        modified:   index.html

kelyddondiemunsch@ip-172-31-20-231:~/sites/github/github_kelyddon_diemunsch/tp-bachelor$ git add .
kelyddondiemunsch@ip-172-31-20-231:~/sites/github/github_kelyddon_diemunsch/tp-bachelor$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   css/style.css
        modified:   index.html

kelyddondiemunsch@ip-172-31-20-231:~/sites/github/github_kelyddon_diemunsch/tp-bachelor$ git commit -m "feat(image):Add a new image"
[main bb56e1e] feat(image):Add a new image
 2 files changed, 12 insertions(+), 2 deletions(-)
kelyddondiemunsch@ip-172-31-20-231:~/sites/github/github_kelyddon_diemunsch/tp-bachelor$ git status
On branch main
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean
kelyddondiemunsch@ip-172-31-20-231:~/sites/github/github_kelyddon_diemunsch/tp-bachelor$ git push origin main
Username for 'https://github.com': Kelyddon
Password for 'https://Kelyddon@github.com': 
To https://github.com/Kelyddon/github_kelyddon_diemunsch.git
 ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'https://github.com/Kelyddon/github_kelyddon_diemunsch.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.
kelyddondiemunsch@ip-172-31-20-231:~/sites/github/github_kelyddon_diemunsch/tp-bachelor$ git add .                                                                                                                                                
kelyddondiemunsch@ip-172-31-20-231:~/sites/github/github_kelyddon_diemunsch/tp-bachelor$ git status                                                                                                                                               
On branch main
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean
kelyddondiemunsch@ip-172-31-20-231:~/sites/github/github_kelyddon_diemunsch/tp-bachelor$ git push origin main                                                                                                                                     
Username for 'https://github.com': Kelyddon
Password for 'https://Kelyddon@github.com': 
To https://github.com/Kelyddon/github_kelyddon_diemunsch.git
 ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'https://github.com/Kelyddon/github_kelyddon_diemunsch.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.
kelyddondiemunsch@ip-172-31-20-231:~/sites/github/github_kelyddon_diemunsch/tp-bachelor$ git branch                                                                                                                                               
* main
kelyddondiemunsch@ip-172-31-20-231:~/sites/github/github_kelyddon_diemunsch/tp-bachelor$ git remote -v                                                                                                                                            
origin  https://github.com/Kelyddon/github_kelyddon_diemunsch.git (fetch)
origin  https://github.com/Kelyddon/github_kelyddon_diemunsch.git (push)
kelyddondiemunsch@ip-172-31-20-231:~/sites/github/github_kelyddon_diemunsch/tp-bachelor$ git pull origin main
remote: Enumerating objects: 7, done.
remote: Counting objects: 100% (7/7), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 4 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
Unpacking objects: 100% (4/4), 1.05 KiB | 2.00 KiB/s, done.
From https://github.com/Kelyddon/github_kelyddon_diemunsch
 * branch            main       -> FETCH_HEAD
   d94cb86..5dee8ce  main       -> origin/main
hint: You have divergent branches and need to specify how to reconcile them.
hint: You can do so by running one of the following commands sometime before
hint: your next pull:
hint: 
hint:   git config pull.rebase false  # merge (the default strategy)
hint:   git config pull.rebase true   # rebase
hint:   git config pull.ff only       # fast-forward only
hint: 
hint: You can replace "git config" with "git config --global" to set a default
hint: preference for all repositories. You can also pass --rebase, --no-rebase,
hint: or --ff-only on the command line to override the configured default per
hint: invocation.
fatal: Need to specify how to reconcile divergent branches.
kelyddondiemunsch@ip-172-31-20-231:~/sites/github/github_kelyddon_diemunsch/tp-bachelor$ git add .
