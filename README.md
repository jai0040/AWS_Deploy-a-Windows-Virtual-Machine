**Deploy a Windows Virtual Machine**

Following the steps you should follow

Step 1: Open your AWS console. 
Step 2: Search EC2. 
Step 3: Select your region.
Step 4: Open instances.
Step 5: Create your instance.
	- Enter the name of the instance.
	- Select AMI (operating system) you want on your server.
		Note: For beginners, select only the Free Tier. 
	- Select your instance type (Free Tier).
	- Select your key pair or create your key pair.
	- Select Network Settings
	- Firewall (security groups)
	- Congigure storage
	- Click on the Launch instance.
Step 6: Go to your instance page, where you will see your instance, which was created by you.

==> for connecting your instance <==

Step 7: Select your instance.
	- On the top side of the page, you see "Connect Option." Click on it.
	- Now you can see your instance ID, public IP, and user name. Take the default user name and click on Connect.
	- Now you can see a screen like a terminal. 
	- Write some commands.
		Command - Whoami
		Output- user_name

		Command - python --version (your application version check)
		Output - Python 2.7.18 (see your application version).
	- Close black screen (terminal).
Step 8: Now we can see Session manager, RDP client, and EC2 serial console.
Step 9: Now go to RDP Client and download the remote desktop file.
	
	Note for operating systems 
		Windows: If you have the Windows operating system, search "Remote Desktop" on your PC.
		Mac: You should download "Remote Desktop Application" from microsoft Microsoft Store.


Step 10: Open Remote desktop.
Step 11: Click on Show Options.
Step 12: Select the open option and select your downloaded file. 
Step 13: Now the system automatically gives the user name.
Step 14: Go to your console and click on Get Password. Browse your key pair (select the key pair that is selected when you create an instance). 
Step 15: Copy your password and paste it on your remote desktop. 
Step 16: Then click on Connect. 
Step 17: Your system or PC asks for a password, then enters your password. Then click on "Yes" for tursh. 
Step 18: Your virtual server is open. 
Step 19: To check if your server is running or not, just run "winver."
Step 20: We can see the version of the virtual server or machines. 
Step 21: Then close it
Step 22: Now your virtual server or machines are connected.
Step 23: Now open the instance page, and you can see so many things.
	- Instance field
	- Details :- we see instance summary like instance ID, public IP, private IP, instance status, key pair details, etc.
	- Security :- we can see inbound rules and outbound rules. 
	- Network :- we can see public IP and private IP addresses, VPC IDs, and subnets.
	- Storage :- we can see hardware details and device details , virtual drive 
	- Status checks :- currante stutus check
	- Monitoring :- all the metrics of things like CPU utilization, network utilization, disk utilization, etc...
	- Tags :- we can create our own tags for understanding.
