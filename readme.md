## sandbox

This is the Lab for playing around with GitHub AND several new tools I would like to add to my development environment.

|  WebServer | GIT Repo | References | [Changelog][] |
|---|---|---|---|



### WebServer:

##### Setting up the  DEV ENVIRONMENT with OSX Server

+ Install OSX Server from Apple´s App Store
+ Launch OSX Server
+ Activate the Websites and create the Default Server Website for both the 80 and 443 ports
+ Tick the php checkbox
+ Create a Github folder under User/Github
+ Create a Sites folder to store all the dev websites there -> User/Github/Sites
+ Go to *Terminal* to Link the DEVENV in the local user instead the admin and paste:  
  ``javascript
  ln -s /Users/danish/Github/Sites /Library/Server/Web/Data/Sites/Default/
  ``


### GIT Repo:
##### Setting up the REPOSITORY in Github

Launch Github desktop app
Create a new Repository (+)

  name: sandbox

  Path: User/Github/Sites/

  The result will be a local folder -> User/Github/Sites/sandbox
  

Add the basic file to setup the Repo
+  Add this readme.md file
+  Add .gitignore file - see https://github.com/github/gitignore
+  Add license file - see http://choosealicense.com



### References:
http://undefinedvalue.com/2014/05/25/os-x-server-local-websites-web-developers

http://php-osx.liip.ch

http://stackoverflow.com/questions/2526085/how-do-i-upgrade-php-in-mac-os-x

https://getgrav.org/blog/mac-os-x-apache-setup-multiple-php-versions


[Changelog]:https://github.com/danielserranoh/sandbox/releases
