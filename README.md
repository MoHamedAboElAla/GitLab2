# My GitLab2 
## delete Local branches
1-git branch -d dev<br>
2-git branch -d test
## delete Remote branches
1-git push origin :dev<br>
2-git push origin :test

## Annotated tags vs Lightweight Tags
1-Annotated tags:contain metadata about the user creating the tag, such name, email address, and date.
for create=> git tag -a [tag name]<br>
2-Lightweight tags:not contain any additional metadata.It just points to a commit. 
for create=> git tag [tag name]

## When to use Rebase
1-clean up commit history<br>
2-when working on a feature branch<br>
3-not shared your branch with others.

## How to list tags?
1-git tag => List all tags.<br>
2-git tag -n => List tags with annotations.

## How to delete tag locally and remotely? 
### To delete remote tag
git push origin --delete v1.0

### To delete local tags
git tag -d v1.0 <br>

## Create secret file and ignore it by Git
1-echo "This is a secret file" > NameFile(secret.txt) 
<br>
2-echo "secret.txt" >> .gitignore
## Add an image
<img src="./image/2.jpg">





