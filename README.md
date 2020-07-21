# Deploy spring boot application to heroku

## Prepare

Open a heroku account
Install heroku CLI

## Heroku CLI
Create an heroku applicatoin from CLI
command: heroku create

Creating app... done, ⬢ fierce-basin-30910
https://fierce-basin-30910.herokuapp.com/ | 
https://git.heroku.com/fierce-basin-30910.git

## Application local 
git init
git add .
git commit -m "init commit"

link the applicatoin from the local to the heroku remote
git remote add heroku https://git.heroku.com/fierce-basin-30910.git

link the application from the local to the remote git master
git remote add origin https://github.com/yichunzhao/demo-deploy-heroku.git

## Deploy to heroku

git push heroku master

## Reqest to heroku

https://fierce-basin-30910.herokuapp.com/hello


