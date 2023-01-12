# Demo Git Repository

This is the first file in repo.


Last login: Wed Jan 11 18:48:15 on ttys000
bjavvadhi@22634 ~ % mate
zsh: command not found: mate
bjavvadhi@22634 ~ % bash

The default interactive shell is now zsh.
To update your account to use zsh, please run `chsh -s /bin/zsh`.
For more details, please visit https://support.apple.com/kb/HT208050.
bash-3.2$ mate
bash: mate: command not found
bash-3.2$ chsh -s /bin/zsh
Changing shell for bjavvadhi.
Password for bjavvadhi: 
chsh: no changes made
bash-3.2$ chsh -s /bin/zsh
Changing shell for bjavvadhi.
Password for bjavvadhi: 
chsh: Credentials could not be verified, username or password is invalid.  Credentials could not be verified, username or password is invalid.
bash-3.2$ chsh -s /bin/zsh
Changing shell for bjavvadhi.
Password for bjavvadhi: 
chsh: no changes made
bash-3.2$ 
bash-3.2$ 
bash-3.2$ 
bash-3.2$ 
bash-3.2$ exit
bjavvadhi@22634 ~ % mate
zsh: command not found: mate
bjavvadhi@22634 ~ % mate
bjavvadhi@22634 ~ % mate
bjavvadhi@22634 ~ % mate
bjavvadhi@22634 ~ % mate README.md
bjavvadhi@22634 ~ % git status
fatal: not a git repository (or any of the parent directories): .git
bjavvadhi@22634 ~ % cd projects/git-demo 
bjavvadhi@22634 git-demo % git status          
On branch master

No commits yet

nothing to commit (create/copy files and use "git add" to track)
bjavvadhi@22634 git-demo % mate README.md      
bjavvadhi@22634 git-demo % git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	README.md

nothing added to commit but untracked files present (use "git add" to track)
bjavvadhi@22634 git-demo % ls -lrt
total 8
-rw-r--r--@ 1 bjavvadhi  staff  54 Jan 11 18:52 README.md
bjavvadhi@22634 git-demo % git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	README.md

nothing added to commit but untracked files present (use "git add" to track)
bjavvadhi@22634 git-demo % git add
Nothing specified, nothing added.
hint: Maybe you wanted to say 'git add .'?
hint: Turn this message off by running
hint: "git config advice.addEmptyPathspec false"
bjavvadhi@22634 git-demo % git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	README.md

nothing added to commit but untracked files present (use "git add" to track)
bjavvadhi@22634 git-demo % git add README.md 
bjavvadhi@22634 git-demo % git status       
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
	new file:   README.md

bjavvadhi@22634 git-demo % git commit -m "Initial commit"
[master (root-commit) ed0a598] Initial commit
 1 file changed, 3 insertions(+)
 create mode 100644 README.md
bjavvadhi@22634 git-demo % git status                    
On branch master
nothing to commit, working tree clean
bjavvadhi@22634 git-demo % mate README.md                
bjavvadhi@22634 git-demo %  
