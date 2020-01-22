# How to deploy dialogflow bot on heroku
### 1) Download and install Heroku cli and Gitbash 
### 2) Create account on heroku website. Link to heroku locally by typing ">>heroku login" in cmd. Log in using web browser
### 3) Open DialogFlow and Copy HTML5 code found under web demo under integrations tab (<iframe blah blah)
### 4) Create a new repo using github gui. Copy the github repo link. Open gitbash on pc, make a new folder and navigate to it using ">>cd *folder-path/*".
### 5) Type ">>git clone *https-link-of-github-repo*" in gitbash.
### 6) type as follows in gitbash
###    >>git init
###    >>echo "*paste code copied in step 3*" >> index.html
###    >>echo "\<?php header( 'Location: /index.html' ) ;  ?>" >> index.php
###    >>heroku apps:create website-name-yolo
###    >>git add .
###    >>git commit -m "yolo"
###    >>git push heroku master
### 7) The hosted website link = *website-name-yolo*.herokuapps.com/
