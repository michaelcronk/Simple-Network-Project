# Simple-Network-Project
In this project I will be creating a simple network for a small company to connect the “Accounts” and “Delivery” departments.


We will need 1 Router and 2 Switches, one switch for each department.

<img width="838" alt="Part 1 - 1 Router 2 Switches" src="https://github.com/michaelcronk/Simple-Network-Project/assets/32269513/eee21e0d-78b8-4744-8f02-52aa708446b3">


Each department will have 2 PCs and 1 Printer. After that we can then connect the devices with the appropriate cables.

<img width="920" alt="Part 2 - PCs and Printers" src="https://github.com/michaelcronk/Simple-Network-Project/assets/32269513/baf230fb-7686-4076-8c89-2661cd3a9f32">


Now given a Network of 192.168.40.0, we will create 2 subnets from this because we have 2 departments.

The first subnet mask will be 255.255.255.128 with a Network ID of 192.168.40.128 with a range of valid hosts from 192.168.40.1 - 192.168.40.126 and it will have a Broadcast ID of 192.168.40.127

The second subnet mask will be 255.255.255.128 with a Network ID of 192.168.40.0 with a range of valid hosts from 192.168.40.129 - 192.168.40.254 and it will have a Broadcast ID of 192.168.40.255

<img width="1005" alt="Part 3 - Subnet Mask" src="https://github.com/michaelcronk/Simple-Network-Project/assets/32269513/27d14a8b-5d6c-4b78-a7c4-7a485d76015d">
