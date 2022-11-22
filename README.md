# SmartDew Readme

This file structure was taken from the Hello World example which can be found following these instructions here: https://docs.espressif.com/projects/esp8266-rtos-sdk/en/latest/get-started/index.html#get-started

Some important notes about that setup:
 - You will need to extract the xtensa-lx106-elf-gcc8_4_0-esp-2020r3-win32.zip to C:\msys32\opt
 - You will need to run this command to add that bin directory to the shell path: 
 
 export PATH=$PATH:"C:\msys32\opt\xtensa-lx106-elf\bin"
 
 AFTER GOING THROUGH THOSE INSTRUCTIONS:
 - Download Git here: https://git-scm.com/downloads
 - go to C:\msys32\home\<user>\esp and create the directory SmartDew
 - right-click on that directory and choose "git bash here"
 Run these commands in Git Bash:
 1) git init 
    #this creates the .git file that will track all of the changes in this directory and it's subdirectories
 
