Git is a version control system.
Git is free software.

git init
git config --global user.mail "xxxx"
git config --global user.name "xxxx"

git add xxx.xx
git commit xxx.xx -m "add xxx"
git commit -a -m "all xxx"

git status
git diff

git reset --hard xxxx
git reset --hard HEAD~1
git reset --hard HEAD~100

git log
git reflog

git checkout -- file

ssh-keygen -t rsa -C "770185288@qq.com"
C:\Users\admin\.ssh

git remote add origin git@github.com:Gutwql/git.git

git pull git@github.com:Gutwql/git.git
git push -u origin master
git clone git@github.com:Gutwql/Personal-Homepage.git

git pull git@github.com:Gutwql/myHomePage.git
git push -u origin-myHomePage master
git clone git@github.com:Gutwql/myHomePage.git

git checkout -b dev
git branch dev
git checkout dev

git merge dev
git log --graph --pretty=oneline --abbrev-commit

git merge --no-ff -m "merge with no-ff" dev
git log --graph --pretty=oneline --abbrev-commit

/*dev Already up-to-data*/
git merge --no-ff -m "merge with no-ff" master
git push


/*dev add new contain*/
git add readme.txt
/*dev commit new contain*/
git commit -m "add new contain"
/*dev push new contain*/
git push

/*dev checkout to master*/
git checkout master
/*master merge from dev*/
git merge --no-ff -m "merge with no-ff" dev
/*master push*/
git push
