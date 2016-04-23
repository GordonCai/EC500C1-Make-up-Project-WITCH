# EC500C1 Make-up Project:WITCH

The outcome of this project is to use AWS to host a web app that allow the photos end users upload from the computer to be processed in the server side. The processes is to help user to try out make-up online and make purchase through the app or in other linked online shops.

## Introduction
* Web app design
* Host web app and Python code on Amazon AWS
* Virtual effect processed through Python with dlib and OpenCV
* Link to Amazon Product advertising API

The following files are used to maintian all subject related documents
* AWS -- Amazon Web Service & Product Advetising API (Zhe Cai, QiuXuan Lin)
* Datebase -- MySQL files (QiuXuan Lin)
* Python code -- Python code (Yang Ming, YuanKun Li)
* Webdesign -- all files related to dynamic website design (Zhe Cai, QiuXuan Lin)

--------------------------------------------------------------------------------------
## AWS -- Amazon Web Service & Product Advetising API (Zhe Cai, QiuXuan Lin)

--------------------------------------------------------------------------------------
## Datebase -- MySQL files (QiuXuan Lin)

--------------------------------------------------------------------------------------
## Python code -- Python code (Yang Ming, YuanKun Li)

--------------------------------------------------------------------------------------
## Webdesign -- (Zhe Cai, QiuXuan Lin)

There are five folders, the first one is the learning notes I wrote for this project.
And the subsequent folders are the four versions of the websites I have done for the four sprints.

This README.txt file is mainly focusing on the final version (pres4 presentation).

AWS screenshot -- the screenshot of content in AWS

cc.txt -- the color code the frontend sent for python script

contact.php -- all webpage use this, it is the contact section of the frontend

error.jpg -- error message is sent frontend if no face or more than one face is detected

eyebrow.json -- due to the limited time, this is used to replace the actual database section for eyebrow

eyebrow.py -- done by Yang Ming and Yuankun Li. It is the python script for changing eyebrow color

facedect.py -- done by Yang Ming and Yuankun Li. It is the python script for lip color

faceEffect.php -- the webpage for changing color

getcolorindo.php -- extract lipstick data from database and send to frontend

geteyebrow.php -- send eyebrow data to frontend

index.php -- homepage

mysqli_connection.php --  done by Qiuxuan Lin. log into database

nav.php -- all webpage use this, it is the nav section of the frontend

protfolio.php -- all webpage use this, it is the protfolio section of the frontend

savePicture.php -- receive the picture from the frontend and save it

sendpyimg -- triggered by the frontend; receive the color code and save it as cc.txt; evoke python script; send processed picture to frontend

sendpyimgeye --  similar to sendpyimg, but process eyebrow instead of lip