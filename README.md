# DNS_practice
 
Domain Name: www.angel-pagan.tech

A Record: Value = 35.225.138.255, TTL: 28800

Cloud Vendor: GCP


#Step 1: Acquire .tech domain name

1. Go to get.tech 
2. in the text box write the name of the domain name you wat and click search
3.if available then click proceed
4. Click on the add-on you would like or proceed again to continue
5. sign into github desktop to reduce the $50 charge to free 
6. sign up to the service to acquire login credentials

#Step 2: Set up VM

1. create a Cloud Virtual Machine (Ubunto OS)
2. update VM using 'sudo apt-get update'
3. install pip3 using 'sudo apt-get install python3-pip'
4. install Flask using 'pip3 install Flask'
5. git clone a flask app.py repo 
6. cd in the working directory
7. Run the flask app using 'sudo python3 app.py'

#Step 3: Setting and assigning .tech domain to the cloud external IP Address 

1. Go to get.tech 
2. Click on the hamburger icon on the top right and Login using login credentials
3.Click on your name to expand the drop down menu and click my account
4.enter the domain name you created in the Jump to domain text box and click on the 2 arrow button
5.Click on the Manage DNS from the DNS management section 
6.Click on A records and 'Add A record'
7.add the prefix host name and assign the IPv4 address to the Cloud VM External IP address
8.  Click add record
9. Type the website address to confirm if it is configured properly.
