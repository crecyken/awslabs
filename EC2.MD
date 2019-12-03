- Create a key Pair with the name MyFirstKeyPair
- Create a 3 Security Group with name WebSG , APPSG , DBSG
     - Allow SSh,Icmp in WebSG
     
     - Allow ssh, Httpd and https in AppSG
     
     - Allow MySQl in DBSG
	
- Launch 3 instances in three different security groups with existing keypair MyFirstKeyPair
- Connect to the public instance and test the Communcations amoung all three.
- connect to each instance and check the internet, all private instances should access the internet.
- Add 5 Gb EBS volume and add data to it 
- Tale snapshot of teh volume and restore adn see if it works
- create your own ami.			
