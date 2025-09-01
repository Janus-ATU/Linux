When configuring servers 
1. Assign them a static IP address
2. Register this in DNS
3. Load the file 99 into /etc/cloud
4. Create a backup of /etc/netplan/50.
5. Edit the repo file 50 with appropriate IPv4 information and copy it to /etc/netplan
6. Type the command **sudo netplan apply** and test. 
