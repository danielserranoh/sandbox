This is the Lab for playing around with GitHub AND several new tools I would like to add to my development environment.


##### Setting up the  DEVENV with OSX Server #####

Install OSX Server from Apple´s App Store
Launch OSX Server
Activate the Websites and create the Default Server Website for both the 80 and 443 ports
Create a Github folder under User/Github
Create a Sites folder to store all the dev websites there -> User/Github/Sites
Link the DEVENV is the local user instead the admin:
    Go to Terminal
    Paste:  ln -s /Users/danish/Github/Sites /Library/Server/Web/Data/Sites/Default/

#####

Create the sanbox folder -> User/Github/Sites/sandbox
Add this readme.md file
Add .gitignore file
Add license file

Launch Github desktop app
Create a new Repository -> User/Github/Sites/sandbox
