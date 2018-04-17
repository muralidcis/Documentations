# Documentations
This doc's  will carry, basic set up and work in git repo.


<b>After install add your Identity.</b>
 git config --global user.name "John Doe"
 git config --global user.email johndoe@example.com

<b>Clone:</b>
  git clone https://github.com/whatever/wteverapp.git

<b>Step 1 :</b>

<b>Branch:</b>
 git branch newbranchaname master 

<b>checkout: </b>
 git checkout newbranchaname

<b>git commit:</b>
Before doing commit in case of addition of files/folder use 
git add foldername 
git commit -am "the message"

<b>Push the newbranch to remote server for code review/merge to master </b>
 git push origin newbranchaname

<b>Step 2 :</b>
Git master needs to merge the branch to master and delete the branch or ask the user to delete the branch...

<b>Step 3:</b>
Make sure remote master and local master are up to date:
  git fetch --all or 
  git fetch origin master
  git merge origin/master
  
<b>Else </b>
 git pull origin  or
 git pull --all 

<b>verify or to track remote and local git.</b>
 git remote show origin 
 git fetch -p 

In case if you still find the local is not updated with remote then reset/head master
  git clean -i
  git reset --hard origin/master
  git pull --all
  git remote show origin

<b>Step 4:</b>

Tagging the source:
git tag -a app-15-sep-2015 -m 'tagging app-15-sep-2015 for release'  
git push app-15-sep-2015

<b>Step 5: </b>
Release the war:
Under the relese tab add the release notes and upload the war. 

##
## Addition of changes
## 
