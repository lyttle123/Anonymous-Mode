# Anonymous-Mode
This is tool used in BackBox linux (OS for penetration testing and ethical hacking),it will help you have secure
on the internet.It can change MAC address,your computer name or host name,hide your IP and connected with Tor network.
Working very simple and easy.

# Required
* tor

# Usage
* Execute Script

		$ chmod +x anonymous.sh
	 
* To start and stop script

		$ ./anonymous.sh start
	 
* Check status

		$ ./anonymous.sh status
	 

To executable your script everywhere in terminal just add this line into your ~/.bashrc file

	export PATH=$PATH:</path/to/file>

# Installation
- sudo su
- git clone https://github.com/t7hm1/Anonymous-Mode.git && cp Anonymous-Mode/anonymous.sh /usr/bin/anonymous
- chmod +x /usr/bin/anonymous
- sudo anonymous
