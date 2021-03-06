## General
1. git repo always points to **/source** folder 

## Check for any changes etc
> git status

## Pull down repo
> git clone https://github.com/feilster/< repo name >   \\\ not sure if necessary but do inside target dir

## Checkout \ switch branch
> git checkout < branch name > 

## New changes
> git add <. or specific pages>  \\\ mark to be committed  
> git commit -m "< any descriptive commit message >"   \\\  commit with message to local repo  
> git push   \\\ commits to git repo

## Add folder to existing repo:
> git init  
> git add .  
> git commit -m "initial commit"  
> git remote add < remote name > https://github.com/feilster/< repo-name >  
> git push -u < remote name > master
 
## Pull down latest changes:
> git pull < remote name > master

## Git keeps asking for username password

In the folder where you've pulled down the repo go to the **.git** folder and change the **config** file. Change the url variable to
> url = https://< username >:< password >@github.com/feilster/< repo name >

If getting a 400 when doing a pull run the following command first
> git remote set-url origin https://github.com/feilster/< repo name >

## Check what remote name was used and which remote repo is present
> git remote -v
