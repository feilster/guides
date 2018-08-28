## General
1. git repo always points to **/source** folder 

## Check for any changes etc
> git status

## Pull down repo
> git clone https://github.com/feilster//`<repo name/>`   \\\ not sure if necessary but do inside target dir

## Checkout \ switch branch
> git checkout gh-pages

## New changes
> git add <. or specific pages>  \\\ mark to be committed  
> git commit -m "<any descriptive commit message>"   \\\  commit with message to local repo  
> git push   \\\ commits to github repo


## Add folder to existing repo:
> git init  
> git add .  
> git commit -m "Initial Commit"  
> git remote add github https://github.com/feilster/\<repo-name>'.git  
> git push -u origin master   

## Pull down latest changes:
> git pull origin master
* if you see 'origin' does not appear to be a git repository
git remote add origin https://github.com/feilster/Angular4

## Git keeps asking for username password

In the folder where you've pulled down the repo go to the **.git** folder and change the **config** file. Change the url variable to
> url = https://feilster:Tazz$4$4@github.com/feilster/guides.git
