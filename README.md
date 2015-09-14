# Documentations
This doc's  will carry, basic set up and work arounds of diffrent frameworks and platforms. 


After install add your Identity.
 git config --global user.name "John Doe"
 git config --global user.email johndoe@example.com

Clone:
  git clone https://github.com/FormsDirect/toolkit.git

Step 1 :

Branch:
 git branch newbranchaname master 

checkout: 
 git checkout newbranchaname

git commit:
 Before doing commit in case of addition of files/folder use 
  git add foldername 
  git commit -am "the message"

Push the newbranch to remote server for code review/merge to master 
 git push origin newbranchaname

Step 2 :
Git master needs to merge the branch to master and delete the branch or ask the user to delete the branch...

Step 3:
Make sure remote master and local master are up to date:
 git fetch --all or 
 git fetch origin master

 git pull origin  or
 git pull --all 

verify or to track remote and local git.
 git remote show origin 
 git fetch -p 

In case if you still find the local is not updated with remote then reset/head master
  git clean -i
  git reset --hard origin/master
  git pull --all
  git remote show origin

Step 4:

Tagging the source:
git tag -a aic-15-sep-2015 -m 'tagging aic-15-sep-1015 for release'  
git push aic-15-sep-2015

Step 5: 
Release the war:
Under the relese tab add the release notes and upload the war. 
