**Creating a Meteor environment with Nitrous.io**

Create a n.io box (e.g. South East Asis): select Node.js, no Git URL

Add Box to GitHub:
http://help.nitrous.io/github-add-key/

Adding Repo
$ cd workspace/
$ mkdir meteor-tutorials
$ cd meteortutorials 
push the readme.md in there and change it on your behalf

on Github create a new repo called meteor-tutorials
Click on Boxes, Reveal key, add to github ...

$ git remote add origin https://github.com/Claudiooo/meteor-tutorials.git
$ git add . 
$ git config --global user.name "Your Name"
git config --global user.email "you@example.com"
$ git commit -m "initial commit"
$ git push origin master

http://stackoverflow.com/questions/18869828/how-do-you-push-from-nitrous-io-to-git

Setting up Meteor
http://help.nitrous.io/meteor-app/

$ parts install meteor
$ meteor update
=> Installed. Run 'meteor update' inside of a particular project directory to update that project to Meteor 0.8.3.

$ npm install -g meteorite

$ meteor create meteorapp
$ cd meteorapp
$ meteor

( it will take a while till mongo db runs )

[[[[[ ~/workspace/meteor-tutorials/meteorapp ]]]]] => Started proxy. => Started MongoDB. => Started your app. => App running at: http://localhost:3000/

---
*** For the next commits: ***

$ git add . 
$ git commit -m "what changed"
$ git push origin master

