
create a new repository on the command line
echo "# my-git-demo" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin <url>
git remote add origin https://github.com/nkpaudel/my-git-demo.git
git push -u origin main

push an existing repository from the command line
git remote add origin https://github.com/nkpaudel/my-git-demo.git
git branch -M main (Move/rename branch name)
git push -u origin main

to review remote branch
git remote -v
IE:  git remote -v
origin  https://github.com/nkpaudel/my-git-demo.git (fetch)
origin  https://github.com/nkpaudel/my-git-demo.git (push)

rename/delete
git remote rename <old> <new>
git remote remove <name>

Pushing: git push command push the local repo to remote branch:
IE git push -u origin main