I have created a new branch to help me work on the seir models to be added to 
the main Irritator examples and nmode-editor files

to do this, I have used git in the following way

git init
git add .
git commit --options
git branch seirmodels
git checkout seirmodels
here i have made all my modifications, added and committed the modifications
swicthwd back to the main master baranch using git checkout master
merged the head branch with the base branch using git merge seirmodels while in master branch

Now I have changed the name of master to mainseir...git branch -m oldname newname

I then added a tis readme file to the new renamed master branch. aded and committed same

now i will attempt to compare and dp a pull request