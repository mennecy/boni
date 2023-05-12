<<<<<<< HEAD
# Giraffe Academy - Hugo Theme
A "Hugo - Static Site Generator" theme used in Giraffe Academy's Hugo course

## Usage
Clone this repository into the themes/ folder. If you want you can rename it to something of your choosing, then modify the config.toml file with the following line:

theme = "ga-hugo-theme" 
=======
# Some git issues ---

Giraffe Academy - Hugo Theme

A "Hugo - Static Site Generator" theme used in Giraffe Academy's Hugo course

## Usage

Clone this repository into the themes/ folder. If you want you can rename it to something of your choosing, then modify the config.toml file with the following line:

theme = "ga-hugo-theme"

########## git #######################################
Create new personal token in your github account at

Settings -> Developer Settings -> Personal access token -> Generate Token

Change your remote url with:

git remote set-url origin https://[token]@github.com/[username]/[repository]

######################################################
git fetch origin main
git merge main

Then, do this ...

git fetch origin main:tmp
git rebase tmp
git push origin HEAD:main
git branch -D tmp
##############################

########### latest ##############
git init

git branch -M main

git remote add origin https://github.com/mennecy/meb.git

git remote set-url origin https://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@github.com/mennecy/meb

git push -u origin main
#############

