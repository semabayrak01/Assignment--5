

Assignment # 5

In this assignment I tested managing network traffic targeting Azure virtual machines in the hub and spoke network topology,.This testing needs to include implementing connectivity between spokes by relying on user defined routes that force traffic to flow via the hub, as well as traffic distribution across virtual machines by using load balancers.  

I completed the assignment in 6 steps. These steps are: 

1-Provision the environment
	In this step virtual machines, networks, subnets, and their componentes have been created.

2-Configure hub and spoke network topology
	All peerings with vnet one  to two and vnet one to three have been done.

3-Test transitivity of virtual networking peering
	Peerings have been controlled with network watcher connection. 

4-Configure routing in the hub and spoke topology
	Vm0 was configured on portal and remote desktop. Then created route tables and added some routes on them. And route tables have been tested with network watcher as well.

5-Implement Azure Load Balancer
	A load balancer between vm0 and vm1 was made and tested on browser by connecting with public IP. 

6-Implement Azure Application Gateway
	First I created resource group, subnet under vnet1 and public IP,  then I created app gateway between vm2 and vm3. In app gateway is defined as frontend ,routing rule and backend pool setting. Finally I tested it from browser  with public IP, entered vm2 and vm3.


Details and screenshots are added to GitHub repository.


