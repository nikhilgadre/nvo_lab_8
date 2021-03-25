# NVO_Lab_8


Edit the required environment variables found in the admin-openrc.sh in the .py file
![image](https://user-images.githubusercontent.com/63819430/112406993-e2288e80-8cda-11eb-9f9e-379594b9a90f.png)

Run the .py file and select the required option
### Objective 1: Automate the creation of multiple virtual networks (VNs) within the hypervisor and their connection to the public network
![image](https://user-images.githubusercontent.com/63819430/112407309-78f54b00-8cdb-11eb-8a80-9fe218b434fe.png)

Select the required sub option:

Created 2 networks net1 - 192.168.1.0/24 and net2 - 192.168.2.0/24
![image](https://user-images.githubusercontent.com/63819430/112407502-ce315c80-8cdb-11eb-8aab-85a41e913b17.png)
![image](https://user-images.githubusercontent.com/63819430/112407541-e3a68680-8cdb-11eb-9ba9-8d7df00b372c.png)
![image](https://user-images.githubusercontent.com/63819430/112407622-0769cc80-8cdc-11eb-8b9a-6e533bdc908c.png)
![image](https://user-images.githubusercontent.com/63819430/112407665-1fd9e700-8cdc-11eb-90f1-bf9a0186d876.png)

Created 1 router r1
Connected the router r1 to the public subnet
Connected the router r1 to networks net1 and net2
### Objective 2: Automate the creation of multiple VMs within the hypervisor-
a. Both single tenant (same VN) and multi-tenant (different VNs)
b. All VMs should be accessible from the host server and be able to access the Internet
### Objective 3: Automate the security groups and port security configuration to make intra-VN and inter-VN communication possible
### Objective 4: Automate spinning up and configuring a Quagga/FRR BGP router as a Docker container
a. Automate its BGP configuration to peer with the SDN controller in the next objective.
### Objective 5: Automate spinning up and configuring an SDN controller as another Docker container
a. Automate its BGP speaker configuration to peer with Quagga/FRR.


