git init
git config --local user.name
git config --local user.email

git add <filename>
git add -a (don't do this)

git commit -m "Message" // commits everything in staging area
git commit <filename1> <filename2...> -m "Message" // commit specific file(s)

git diff // see difference between tracked files committed version and current version

never nest git repos!
git init at only the topmost directory
if you do do this, just remove the .git repository in the nested git repo

branching
git branch
git checkout <branchname>
git merge <branchname> // merges branchname into current branch