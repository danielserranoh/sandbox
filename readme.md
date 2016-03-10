## sandbox

This is the Lab for playing around with GitHub AND several new tools I would like to add to my development environment.

|  [WebServer] | [GIT Repo] | [Changelog][] |
|---|---|---|



[WebServer]:

##### Setting up the  DEV ENVIRONMENT with OSX Server

+ Install OSX Server from Apple´s App Store
+ Launch OSX Server
+ Activate the Websites and create the Default Server Website for both the 80 and 443 ports
+ Create a Github folder under User/Github
+ Create a Sites folder to store all the dev websites there -> User/Github/Sites
+ Go to *Terminal* to Link the DEVENV in the local user instead the admin:
  
  Paste:  
  ``javascript
  ln -s /Users/danish/Github/Sites /Library/Server/Web/Data/Sites/Default/
  ``


[GIT Repo]:
##### Setting up the REPOSITORY in Github

Launch Github desktop app
Create a new Repository (+)
  name: sandbox
  Path: User/Github/Sites/
  The result will be a local folder -> User/Github/Sites/sandbox

Add the basic file to setup the Repo
  Add this readme.md file
  Add .gitignore file - see https://github.com/github/gitignore
  Add license file - see http://choosealicense.com


[Changelog]:https://github.com/danielserranoh/sandbox/releases
