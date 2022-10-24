# Terminal

Install a software
* brew install software_name

Find a path in Finder
* command + shift + g

Copy file path in Finder
* right click or two finger click a file on finder
* while in right-click menu hold down the OPTIONS key
* select copy "file" as pathname

zsh: command not found: pip
  * open ~/.zshrc
  * add your edits
  * command + S to save
  
Update getawstempcredentials

* brew upgrade sre-aws-helpers

OR Manual Method

* go to https://github.com/massmutual/sre-aws-helpers/blob/master/bin/getAWSTempCredentials
* download the file to your Downloads folder
* On Terminal, cd Downloads
* ls -lrta
* if on the left hand side it says -rw-r--r--@ 
* Owner: read write only, (not executible because there is a dash)
* Group: read only
* Other read only

* here is what that means

* -rwxrwxrwx
*  OOOGGGOOO
 
* Owner: Read, Write, Execute
* Group: Read, Write, Execute
* Other: Read, Write, Execute
 
* to change for the file to become executible
 
* chmod u+x getAWSTempCredentials
 
* -rwxr-xr-x@ 
 
*  file is now executible
 
*  ./getAWSTempCredentials --activate
 
*  ^^^ To execute the file
 
  New Tab
  * Command + t
  
  Zoom In
  * Command + +
  
  Zoom Out
  * Command + -
  
  
  Execute a file
  
 *  ./filename
  
  To check a files permissions in current directory
  
  * ls -lrta
  
  To change a files permission
  
  * For Users: chmod u=rwx myfile               
  
  * For Group: chmod g=rwx myfile
  
  * For Others: chmod o=rwx myfile
  
  Create a file
  * touch filename.extension
  * ex.) touch miko.py


Halt the Current Command
* ctrl + c


Test a webhook
* sudo curl -X POST -H 'Content-type: application/json' --data '{"text":"Testing Webhook Hello World!"}' https://hooks.slack.com/services/T01L44B6VNH/B04495Y4E02/UH8lC2bo2yUmjHvV8M3y

* Replace this webhook url with your webhook url
  
  
  
  
  
