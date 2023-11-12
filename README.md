# Simple-Network-Project

## In this project I will be creating a simple network for a small company to connect the “Accounts” and “Delivery” departments.


We will need 1 Router and 2 Switches, one switch for each department.

<br>

<img width="838" alt="Part 1 - 1 Router 2 Switches" src="https://github.com/michaelcronk/Simple-Network-Project/assets/32269513/eee21e0d-78b8-4744-8f02-52aa708446b3">

<br>
<br>

Each department will have 2 PCs and 1 Printer. After that we can then connect the devices with the appropriate cables.

<br>

<img width="920" alt="Part 2 - PCs and Printers" src="https://github.com/michaelcronk/Simple-Network-Project/assets/32269513/baf230fb-7686-4076-8c89-2661cd3a9f32">

<br>
<br>

Now given a Network of 192.168.40.0, we will create 2 subnets from this because we have 2 departments.

The *first subnet mask* will be 255.255.255.128 with a *Network ID* of 192.168.40.0 with a range of valid hosts from 192.168.40.1 - 192.168.40.126 and it will have a *Broadcast ID* of 192.168.40.127

The *second subnet mask* will be 255.255.255.128 with a *Network ID* of 192.168.40.128 with a range of valid hosts from 192.168.40.129 - 192.168.40.254 and it will have a *Broadcast ID* of 192.168.40.255

<br>

<img width="1005" alt="Part 3 - Subnet Mask" src="https://github.com/michaelcronk/Simple-Network-Project/assets/32269513/27d14a8b-5d6c-4b78-a7c4-7a485d76015d"><br>

<br>

Then we assign the Interface IPs from the *Router* to the *Switches*

<br>

<img width="207" alt="Part 4 - Assigning IPs" src="https://github.com/michaelcronk/Simple-Network-Project/assets/32269513/eb45a354-7a34-469a-ac5d-11fa661f194d"><br>

<br>

Now we configure all the devices with appropriate IPs and test the connections.

<br>

<img width="899" alt="Part 5 - IP Configuring" src="https://github.com/michaelcronk/Simple-Network-Project/assets/32269513/2673740c-77ca-4837-b25a-f2f5553ed4f6"><br>

<br>

Testing 192.168.40.130(computer - PC2) to see if we can ping 192.168.40.2 (computer - PC0)

<br>

<img width="280" alt="Part 6 - Testing 130 from 2" src="https://github.com/michaelcronk/Simple-Network-Project/assets/32269513/57f3d544-9d87-4344-b490-e8095efe1142"><br>

<br>

Testing 192.168.40.131(computer - PC3) to see if we can ping 192.168.40.4 (printer - Printer0)

<br>

<img width="289" alt="Part 6 - Testing 131 to 4" src="https://github.com/michaelcronk/Simple-Network-Project/assets/32269513/878f91aa-95b0-4c3b-8068-5844f0c259ec"><br>

<br>

Everything in our network seems to be connected and running well.

<br>

**Our network is now complete.**
