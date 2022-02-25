# Ada
Teaching myself how to program using ADA following 

https://learn.adacore.com/courses/intro-to-ada/index.html#

1. Using my Macbook (ARM), I used a tool called Parallels to spin up a virtual machine of Debian Linux.

2. I opened Terminal and used the following commands

apt search libaws
apt search gprbuild
sudo apt install gprbuild

3. and then continued to make an ada folder on the desktop of my VM

4. I then downloaded VIM for my text editor and called the directory of my project folder

cd /home/parallels/Desktop/ada/helloWorld

5. while in this directory I create a new file using vim

vim greet.adb

6. press I for Insert Mode

7. write the hello world application

8. press ESC to go back to normal mode (from insert mode)

9. use the :wq command (for write, quit)

10. gprbuild greet.adb (to compile the file)

11. /.greet (to run the program and test the output)
