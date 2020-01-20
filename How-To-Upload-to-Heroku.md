# How to deploy dialogflow bot on heroku
### 1) Download and install Heroku cli and Gitbash 
### 2) Create account on heroku website. Link to heroku locally by typing "heroku login" in cmd. Log in using web browser
### 3) Create a new repo using github gui. Copy the github repo link. Open gitbash on pc, make a new folder and navigate to it using "cd folder-path/".
### 4) Copy link from web demo <iframe html code under dialogflow integrations tab 
### 5) Type "git clone https-link-of-github-repo" in gitbash.
### 6) type as follows
###    git init
###    git echo "replace-with-iframe-code-found-in-dialogflow-integrations-tab-under-web-demo" >> index.html
###    git echo "\<?php header( 'Location: /index.html' ) ;  ?>" >> index.php
###    heroku apps:create website-name-yolo
###    git add .
###    git commit -m "yolo"
###    git push heroku master
### 7) The hosted website link = website-name-yolo.herokuapps.com/
