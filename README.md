#Project Title
Vagrant

##Getting started 
instructions to run vagrant inside a linux based system
1 open the terminal application
 now you will execute command line in your Terminal(each of them start with $)
2 install VirtualBox: $ sudo apt-get install virtualbox
3 install vagrant:    $ sudo apt-get install vagrant
4 Add the Ubuntu 20.04 (Focal) image to your box list: $ vagrant box add ubuntu/focal64
~~warning this step can take time~~
5 creat your first virtual machine
	$ vagrant init ubuntu/focal64--> it will generate a vagrantfile with base= "ubuntu/focal64"- you dont have to execute this command line everday, only once to create a new virtual machine
	$vagrant up -> it will start your virtual machine
	$vagrant ssh-->now you are inside your virtual machine
#prerequisities
virtualbox
vagrant
8gb ram pc
disc space 5gb to spare

##contrinution
in future this is to contain guidelines for contribution

##license
more info to be displayed later on

##Acknowledgements
The ALX Community for making this dream lucid
