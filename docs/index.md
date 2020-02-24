# How to upload your project on github ?

### Open git -bash or terminal accourding to OS

#### Step 1

git init 

#### Step 2

curl -u "UserName" https://api.github.com/user/repos -d "{\"name\":\"repo-name\"}"

#### Step 3 

Create .gitignore file on your project 

#### Step 4

git add -all

#### Step 5 (not recommendation : for check your status  )

git status 

#### Step -6

git commit -m "First Commit"



#### Step 7 
repo for (your repositry name )
User for (your username on github )
git remote add origin https://github.com/user/repo.git


#### Step 8 

git push origin master
 



