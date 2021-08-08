*********************************************************************************
!!! REMEMBER, this code is available under license Apache-2.0 License. 
You are responsible for all the changes youmake to your operating system.No guarantees. 
Be careful.
*********************************************************************************


The repository contains scripts for  add virtual host of Nginx in Debian 9 for PC
There are different versions of scripts:

1) nginx_add_vhost                #default script
2) nginx_add_vhost_with_phpfpm    #default script + php-fpm

Choose the one you like best.

For run scripts you need to put them in folders:

/usr/bin
OR
/usr/local/bin

And set the scripts as executed.

Then you can to run them from anywhere from the terminal.
Just write the name of the script in terminal.

Alternatively, you can to copy them to any folder and run as root in console as:
***********************
bash nginx_add_vhost

OR

bash nginx_add_vhost_with_phpfpm 

***********************

It is also necessary to have such packages as installed in Debian:

1) packages: coreutils, nginx( nginx_add_vhost ).
OR 
2) packages: coreutils, nginx, php7.2, php7.2-fpm ( for nginx_add_vhost_with_phpfpm ).

Enjoy!
