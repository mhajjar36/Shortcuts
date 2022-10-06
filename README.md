# Terminal

Install a software
* brew install software_name

zsh: command not found: pip
  * open ~/.zshrc
  * add your edits
  * command + S to save
  
Update getawstempcredentials
brew upgrade sreawshelpers


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
  
  
  
  
  
