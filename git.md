# git reference

### creating a repo
`git init`: starts a new git repository on your local machine
(if you use create-react-app, you don't need to do this)

Make a new repo on GitHub.com so you can copy the URL:

`git remote add origin https://github.com/USERNAME/REPO.git`


### pushing to git:
`git add .`: adds all files in current folder
ß
`git commit -m "message"`: commits!

`git push origin master`: push to GitHub.com!!!


### notes:

`.gitignore`: this file lets you set which files and folders are ignored by git
(create-react-app makes this for you)

want to have node modules and gitignore when making new things

### pulling from git

`git clone ...`: clone a repo

`git pull origin master`: pulling new changes from git
