git --version = checks the version of git 
git config --global user.name mohammedfaizan10
git config --global user.email mfaizan070707@gmail.com
git config --list
git init = initializes git in working directory
git status = gives status of git areas
git add --filename = adds particua;r fiele in staging area
git add . = adds all files in staging area
git commit -m "message" = git commit tracked the changes
git log = gives log 
git log --oneline --graph --all
git branch = list branches
git branch dev = to amke a dev branch
git checkout -b dev = create and switch to dev
git checkout main = switches to main
git switch main = switches to amin
git merge dev = merges dev changes to main from main
git reset <id> --soft  = it will remain the commit in staged
git reset <id> = mixed = it will remain the commits untracked
git reset <id> --hard = it will remove commits hardly
git rm --cached --filename
git remote -v  
git remote add origin <url>
git remote set-url origin https://TOKEN@github.com/usernmae/repo.git
git push origin main
git pull origin main
git clone https
git clone ssh
git revert <id>
git revert --continue = continue the revert process
git revert --abort = stops the revert process
git stash
git stash apply  = gives latest stash
git stash list  = list all stashes
git stash pop index-number = pops the specific stash
git stash clear  = clears all stashes
git cherry-pick <id> = always do form where you want changes
git switch feature = comes to feature
git rebase main = feature changes come top of main changes
#more commands are their to come in future soon
