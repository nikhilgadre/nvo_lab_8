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

![image](https://user-images.githubusercontent.com/63819430/112407806-59125700-8cdc-11eb-9855-f5657df35414.png)

Connected the router r1 to the public subnet

![image](https://user-images.githubusercontent.com/63819430/112408963-4862e080-8cde-11eb-84ae-e13737b4e7f1.png)


Connected the router r1 to networks net1 and net2

![image](https://user-images.githubusercontent.com/63819430/112409184-a7285a00-8cde-11eb-9122-df74d3708c92.png)
![image](https://user-images.githubusercontent.com/63819430/112409262-caeba000-8cde-11eb-979a-59329805dda1.png)

![image](https://user-images.githubusercontent.com/63819430/112409306-e35bba80-8cde-11eb-8abb-6af0b9286629.png)



### Objective 2: Automate the creation of multiple VMs within the hypervisor-
a. Both single tenant (same VN) and multi-tenant (different VNs)

b. All VMs should be accessible from the host server and be able to access the Internet

Upon creation of VM, Floating IPs are automatically created and assigned to VM

![image](https://user-images.githubusercontent.com/63819430/112410045-2c603e80-8ce0-11eb-95eb-b8bd827e5fc6.png)
![image](https://user-images.githubusercontent.com/63819430/112410078-3c781e00-8ce0-11eb-9c11-b6423c1c712d.png)
![image](https://user-images.githubusercontent.com/63819430/112410605-0f783b00-8ce1-11eb-8654-3a0c59cbf0b3.png)
![image](https://user-images.githubusercontent.com/63819430/112410704-42223380-8ce1-11eb-9634-0d6dfb377f64.png)


### Objective 3: Automate the security groups and port security configuration to make intra-VN and inter-VN communication possible
This security group configuration allows all intra-VN and inter-VN communication possible
![image](https://user-images.githubusercontent.com/63819430/112409459-2b7add00-8cdf-11eb-9697-553d6b804e6b.png)
![image](https://user-images.githubusercontent.com/63819430/112409507-3c2b5300-8cdf-11eb-993b-0a65ac4563e5.png)
![image](https://user-images.githubusercontent.com/63819430/112409605-6d0b8800-8cdf-11eb-84a0-31ab180277ee.png)


### Objective 4: Automate spinning up and configuring a Quagga/FRR BGP router as a Docker container
a. Automate its BGP configuration to peer with the SDN controller in the next objective.
### Objective 5: Automate spinning up and configuring an SDN controller as another Docker container
a. Automate its BGP speaker configuration to peer with Quagga/FRR.


