# git-commands
Whatever I learned

```
From git intro:
echo "# lolz" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin git@github.com:mbkasder/lolz.git

git pull --rebase

git push -u origin master


Initializations:
git init .
ssh-keygen -t ecdsa -b 521
cat ~/.ssh/id_ecdsa.pub
(Add this public key to cloud repo)
git pull git@github.com:mbkasder/lolz.git 

git status
git log

To add stuff and upload to cloud repo:
git add --all
git commit -m "comment on update"
git config --global user.email "mbk@mail.com"
git config --global user.name "mbkmbsit"
git push --set-upstream git@github.com:mbkasder/lolz.git master
git push

To delete last commit or undo:
git log -5
git reset --hard HEAD~1 #previous , change 1 to specific to change head to that of previous commit and loose current data but use --soft for otherwise
git push -f


To add branch:


To merge branch:

To rebase:

To 
```
