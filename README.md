Tell me how to remove them locally and remotely.
a. locally:
git branch -d dev
git branch -d test
b. remotely
git push origin :dev
git push origin :test
/
/
Tell me how to checkout another branch without commit changes
- by using this command: git stash
/
/
Tell me how to list tags.
- by using this command: git tag
/
/
Tell me how to delete tag locally and remotely.
a. locally
by using this command: git tag -d <tag name>
a. remotely
by using this command: git push --delete origin <tag name>
/
/
Add an image in the README.md file.
![My Image](Git-Icon-1788C)
