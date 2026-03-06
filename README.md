<h1>AWS Solutions Architect </h1>

<h2>Creating a NAT Gateway in AWS - Linux server</h2>

- <b>Create a Virtual Private Cloud (VPC) in the US East (N. Virginia) us-east-1 region  </b>
- <b>Create private and public subnets </b>
- <b>Create Internet Gateway </b>
- <b> Create a public Route table and configure  </b>
- <b>Launch a Linux EC2 instance using the public subnet </b>
- <b>Launch a Linux EC2 instance using the private subnet </b>
- <b>Connect to both the public and private EC2 instances and test internet connectivity </b>
- <b>Create a NAT Gateway </b>
- <b>Update Route table and configure NAT Gateway </b>
- <b>Test internet connectivity for the EC2 instance using the private subnet </b>

<h2>Expected Outcomes</h2>
The EC2 instance using the private subnet does not connect to the internet until the NAT Gateway is set up and connected to the Route table
<br />

<h2>Languages and Utilities Used</h2>

- <b>AWS Interface </b>
- <b> Virtual Machine (Linux server) </b>

<h2>Project walk-through:</h2>
<p align="center">
Creating a VPC <br/>
<img width="940" height="437" alt="image" src="https://github.com/user-attachments/assets/71493bc1-b120-4522-8eea-21e8650229a3" />
<img width="940" height="501" alt="image" src="https://github.com/user-attachments/assets/9dfd788d-cff8-43ef-b117-cbb5b6822f6d" />
<br />

<p align="center">
Creating a Subnet <br/>
<img width="940" height="503" alt="image" src="https://github.com/user-attachments/assets/4b6fe75c-f282-4d4a-81dc-f5e274bbb356" />
<img width="940" height="471" alt="image" src="https://github.com/user-attachments/assets/9dff0455-b3fe-40ea-b74d-bf1a84526637" />
<br />

<p align="center">
Edit Public subnet to assign public IP allocation <br/>
<img width="940" height="422" alt="image" src="https://github.com/user-attachments/assets/7408e7f2-03ec-41b5-941e-9e9805a90dc8" />
<img width="940" height="204" alt="image" src="https://github.com/user-attachments/assets/e6739911-d1af-408e-a392-b6a8041475c6" />
<br />

<p align="center">
Create Internet Gateway and attach to VPC <br/>
<img width="940" height="330" alt="image" src="https://github.com/user-attachments/assets/d0efcf26-243b-48ea-b49d-9b0b9dba026a" />
<img width="940" height="165" alt="image" src="https://github.com/user-attachments/assets/b0028733-57b8-461a-8ddf-44b0bed7df75" />
<img width="940" height="250" alt="image" src="https://github.com/user-attachments/assets/4731f442-a81e-4332-8fd4-1d6d8d259d84" />
<br />

<p align="center">
Create a Route table and edit <br/>
<img width="940" height="346" alt="image" src="https://github.com/user-attachments/assets/a4cbe169-2525-4059-b964-93844c4887b6" />
<img width="940" height="241" alt="image" src="https://github.com/user-attachments/assets/33069521-581f-478f-a1be-2ea5967aafb8" />
<img width="940" height="242" alt="image" src="https://github.com/user-attachments/assets/f28193fb-768f-4d54-80a4-25fe1cbaf6b1" />
<img width="940" height="274" alt="image" src="https://github.com/user-attachments/assets/752eabe2-a580-45af-ada3-8e3b2153dea0" />
<img width="940" height="282" alt="image" src="https://github.com/user-attachments/assets/2342be62-e7e0-4e9f-8b4d-e8494e4d68d2" />
<br />

<p align="center">
Create a public EC2 instance <br/>
<img width="940" height="502" alt="image" src="https://github.com/user-attachments/assets/f184b99c-5ac0-4875-8038-894259fa6227" />
<img width="940" height="476" alt="image" src="https://github.com/user-attachments/assets/b3600e3c-49ea-416f-87a6-516382416fdc" />
<img width="940" height="502" alt="image" src="https://github.com/user-attachments/assets/9b911195-f24c-4247-b955-23ec2fcf5210" />
<img width="940" height="478" alt="image" src="https://github.com/user-attachments/assets/ca2759c7-5759-4a9a-a798-2daa1774b9e0" />
<br />

<p align="center">
Create a private EC2 instance <br/>
<img width="940" height="502" alt="image" src="https://github.com/user-attachments/assets/36fc46d9-4426-426c-b6fd-d3e1c1377148" />
<img width="940" height="506" alt="image" src="https://github.com/user-attachments/assets/0b222820-6876-4ad3-872b-e72e8d88188d" />
<img width="940" height="444" alt="image" src="https://github.com/user-attachments/assets/04418abb-16cb-40aa-9c37-9da6ca7841f9" />

<br />


<p align="center">
Connect to EC2 instance <br/>
<img width="940" height="423" alt="image" src="https://github.com/user-attachments/assets/8256ca02-d254-4d6e-9232-8d49eeadbb20" />
<br />

<p align="center">
Testing Internet connectivity for EC2 instance using the public subnet<br/>
<img width="940" height="430" alt="image" src="https://github.com/user-attachments/assets/3ca4884c-2f1e-4e56-b0e6-d218acfaff66" />
<br />

<p align="center">
Connect to the EC2 instance using the private subnet, from the one using the public subnet <br/>
<img width="940" height="348" alt="image" src="https://github.com/user-attachments/assets/7cfe9195-be31-439d-af89-2e58a8bc80d8" />
<img width="920" height="792" alt="image" src="https://github.com/user-attachments/assets/17c7a689-5334-48d4-a79d-5d3939e6a0bd" />
<img width="820" height="795" alt="image" src="https://github.com/user-attachments/assets/038660c9-c41f-486f-a84f-c0ad0943372a" />
<img width="940" height="361" alt="image" src="https://github.com/user-attachments/assets/7592cfc5-a8c5-4f84-abd5-dad0968d0194" />
<br />

<p align="center">
Testing Internet connectivity for EC2 instance using the private subnet<br/>
<img width="940" height="356" alt="image" src="https://github.com/user-attachments/assets/fade81de-502a-478a-b647-cb45cd73795e" />
<img width="940" height="321" alt="image" src="https://github.com/user-attachments/assets/9c604f56-67a1-4790-812a-2cf7bb741290" />
<br />


<p align="center">
Create NAT Gateway<br/>
<img width="940" height="478" alt="image" src="https://github.com/user-attachments/assets/7b0a3c1d-0b20-46f7-800a-9e6a9f9eb2ca" />
<img width="940" height="410" alt="image" src="https://github.com/user-attachments/assets/35dcc363-ae5d-4d7b-96c7-2015a21d82a1" />
<img width="940" height="151" alt="image" src="https://github.com/user-attachments/assets/5151e44a-f3c1-4b87-8f99-6e74ce3b84da" />
<br />

<p align="center">
Connect NAT Gateway to the default Route table<br/>
<img width="940" height="250" alt="image" src="https://github.com/user-attachments/assets/7098c629-82f0-4cc4-9fc8-ea3c2cd78ee9" />
<img width="940" height="236" alt="image" src="https://github.com/user-attachments/assets/1aedda8f-2def-47ec-a2a2-be5500d7d31a" />
<br />

<p align="center">
Testing Internet connectivity for EC2 instance using the private subnet after connecting the NAT Gateway to the Route table <br/>
<img width="940" height="264" alt="image" src="https://github.com/user-attachments/assets/f635b0b7-1a5c-4c2e-8506-96d3af532eda" />

<br />


