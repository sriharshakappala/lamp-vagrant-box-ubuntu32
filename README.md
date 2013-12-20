lamp-vagrant-box-ubuntu32
=========================

LAMP Vagrant Box(Ubuntu 32-bit) - Pre Installed with Apache, MYSQL and PHP

You can download this Vagrant Box here https://www.dropbox.com/s/rr1uk4r7hyfreyh/lamp-precise32.rar


Pre Installed Stuff
===================

This Vagrant box gives you a ready-to-use PHP environment(LAMP Environment) on any kind of Operating System(Windows, Mac or Linux).

This has been pre installed with the following softwares...

1. PHP

2. MYSQL (password for root user is mysql)

3. Apache

4. VIM editor


How to use?
===========

(Before following the below steps make sure that you have already installed Virtual Box and Vagrant)

1. Extract the downloaded file into .vagrant.d/boxes folder.
   Based on your operating system the location of .vagrant.d/boxes folder may differ
   For Windows it is, C:\Users\<user_name>\.vagrant.d\boxes

2. Open the command prompt and type `vagrant box list` to make sure that the box got activated. You must be able to see the name of the current box(lamp-precise32) in the output.

3. That's it! You are all set to go! You can start using the new box by following the same way how you use any normal vagrant box.