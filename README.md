# how-to-install-the-fatrat-on-nethunter
## This is going to be a tutorial on how to install THEFATRAT on NetHunter
First were going to go through the process of git cloning the fat rat off GitHub If that doesn't work you can open Kali NetHunter and download it from the browser And for whatever reason you can't download it from the browser you can give Kali NetHunter access to your phone storage and after that you can download it on your phone and move it to the directory you want it to be in And after that you can unzip it and do the usual process of install For more details visit https://github.com/screetsec/TheFatRat

If you want to know how to give Kali Netrunner access to your storage, you can go to this repo https://github.com/dhgclt/Give-NetHunter-access-to-your-storage

And for you to install THEFATRAT you're going to have to make XTerm work as root which you're going to find the fix for that in this repo https://github.com/dhgclt/xterm-fix-for-kali-nethunter By the way after you make sure XTERM works as root close the window so the fat rat has the ability to open it

Now while running the installation script you might encounter an error related to apt-update or apt-upgrade which is fixed in this repo https://github.com/dhgclt/Common-Error-fix-apt-get-update-apt-get-upgrade

And also you may encounter errors related to installing Backdoor Factory The fix in this repo https://github.com/dhgclt/Common-Error-Fix-Installing-Backdoor-Factory

Also these are the packages that most of the time will not install automatically You can run command  to make them install `sudo apt-get install mono-complete -y && sudo apt-get install openjdk-11-jdk -y`

### And that's it Hopefully it worked for you like it worked for me
