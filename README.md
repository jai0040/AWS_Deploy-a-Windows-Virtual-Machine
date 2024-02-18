**Deploy a Windows Virtual Machine**

Following the steps you should follow

Step 1: Open your AWS console. <br>
Step 2: Search EC2. <br>
Step 3: Select your region. <br>
Step 4: Open instances. <br>
Step 5: Create your instance. <br>
	- Enter the name of the instance. <br>
	- Select AMI (operating system) you want on your server. <br>
		Note: For beginners, select only the Free Tier. <br>
	- Select your instance type (Free Tier). <br>
	- Select your key pair or create your key pair.<br>
	- Select Network Settings.<br>
	- Firewall (security groups).<br>
	- Congigure storage.<br>
	- Click on the Launch instance.
Step 6: Go to your instance page, where you will see your instance, which was created by you.<br>

**==> for connecting your instance <==**<br>

Step 7: Select your instance.<br> 
	- On the top side of the page, you see "Connect Option." Click on it.<br>
	- Now you can see your instance ID, public IP, and user name. Take the default user name and click on Connect.<br>
	- Now you can see a screen like a terminal. <br>
	- Write some commands.<br>
		Command - Whoami<br>
		Output- user_name

		Command - python --version (your application version check)
		Output - Python 2.7.18 (see your application version).
	- Close black screen (terminal).
Step 8: Now we can see Session manager, RDP client, and EC2 serial console.<br>
Step 9: Now go to RDP Client and download the remote desktop file.<br>
	
	Note for operating systems 
		Windows: If you have the Windows operating system, search "Remote Desktop" on your PC.
		Mac: You should download "Remote Desktop Application" from microsoft Microsoft Store.


Step 10: Open Remote desktop.<br>
Step 11: Click on Show Options.<br>
Step 12: Select the open option and select your downloaded file. <br>
Step 13: Now the system automatically gives the user name.<br>
Step 14: Go to your console and click on Get Password. Browse your key pair (select the key pair that is selected when you create an instance). <br>
Step 15: Copy your password and paste it on your remote desktop.<br> 
Step 16: Then click on Connect. <br>
Step 17: Your system or PC asks for a password, then enters your password. Then click on "Yes" for tursh. <br>
Step 18: Your virtual server is open. <br>
Step 19: To check if your server is running or not, just run "winver."<br>
Step 20: We can see the version of the virtual server or machines. <br>
Step 21: Then close it<br>
Step 22: Now your virtual server or machines are connected.<br>
Step 23: Now open the instance page, and you can see so many things.<br>
	- Instance field<br>
	- Details :- we see instance summary like instance ID, public IP, private IP, instance status, key pair details, etc.<br>
	- Security :- we can see inbound rules and outbound rules. <br>
	- Network :- we can see public IP and private IP addresses, VPC IDs, and subnets.<br>
	- Storage :- we can see hardware details and device details , virtual drive <br>
	- Status checks :- currante stutus check<br>
	- Monitoring :- all the metrics of things like CPU utilization, network utilization, disk utilization, etc...<br>
	- Tags :- we can create our own tags for understanding.<br>
