# Woman BASH script v 0.0.1 Beta 

About

This script is created in fact that in UNIX like systems has a command named "man" (manual), but no "woman" command.
The command can not be alias to man (or any other command) because the women are very special in our life. 
The Linux role is to control the hardware, but never forget your role in the real life.
Use this script if you want to surprise your wife, girlfriend or daughter. The women are the source of life.

AND REMEMBER, ONLY LINUX/UNIX USERS CAN UNDERSTAND IT!!!!!!

License 
This software is distributed under GNU/GPL v2.0 or any later

Install

Use root user to install in bin path like /usr/bin or /usr/local/bin
$ sudo cp woman /usr/local/bin
$ sudo chmod +x /usr/local/bin/woman

Make sure that the path in in your $PATH: echo $PATH

Usage
simple ask woman do nothing :) You can add a line in your .bashrc file (or woman's bash files) like:
woman checkdate # to surprise your girl

Reminder: there to commands for you: add2reminder and reminder
$ woman add2reminder mymother # This will create, if not exist, $HOME/.woman file and save mymother   
$ woman add2reminder JaneSmith # The script works only with one word names 

Add to your cronjob, if you wish:
$ crontab -e

On new line add similar line:

0 8 8 3 * woman reminder
# every 8:00 8th March, or one day before: 0 8 7 3 * woman reminder
You will receive email (regarding your installtions and rules) contains reminder message

Source code

Author
Rossen Karpuzov

