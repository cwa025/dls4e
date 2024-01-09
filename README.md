# dls4e
always pull before push
git fetch --all -prune

git clone https://github.com/cwa025/dls4e

# git branch -a
git checkout b1

"git pull" (better to use fetch!!) is like

"git fetch" then
"git merge" or "git rebase"

# To push to git
git status

git add  .

git commit -m “type your sample commit message about commit hear”

git push -u origin b1

# To create branch
git branch dev b1

git stash -u

git checkout dev

git merge A

git stash pop

git add .

git commit -m "..."

# To create new worktree
git worktree add pathX

# Push a project to existing Repository
git init

git add -A

git commit -m “my first commit comments’

git remote add origin https://github.com/cwa025/dls4e/

git push -u origin dev