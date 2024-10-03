java cELEC5517: Software Defined Networks Project II with ONOS controller and P4 language
  Background
 Considering a company is developing a network topology, and we are going to simulate the deployment. This company has three departments, and each department owns several devices. These three departments have different responsibilities and network requirements: (a) department owns one device, and only handle basic data transmit tasks (e.g., email). (b) department owns two devices and requires access streaming media. (c) department owns two devices and handle a small amount of data transmit tasks only during certain times.
Task 1:
Design and create a topology, enabling:
I. ONOS (or other learnt in this unit) as the controller.
II. Networkrequirementsaresatisfied.
III.The communication between different departments is only available under permissions.
IV. Send HTTP amongst nodes and capture the OpenFlow packets. Analyze the captured packets for each department and show possible similarities and differences of the results.
Task 2:
Based on new requirements, the company decides to divide the network into two to support inter-communication amongst two industries. In this customized topology, two departments (a, b) are allowed to communicate with each other while the third department should not be able communication with the others.
Perform the following tasks based on the new sliced topology:
I. Use ONOS flow endpoint API to代 写ELEC5517、c++，Java
代做程序编程语言 achieve isolation of the third department from the rest of the network.
II. Display and analyze flow statistics at each of the edge switch (close to the device) using ONOS flow statistics end point API.
III. Using host endpoint API please add a new host to department a.
IV. Show the flows and demonstrate the designed network is achieved.
  
Task 3:
Review this designed network, think from the functions and controller perspectives:
I. Identify one disadvantage, this disadvantage could be some functions have not been supported by the current network, potential missing monitoring, etc.
II. Provide discussion about the disadvantage and potential risk,
III. Achieve improvement.
Task 4:
Based on the requirements, we are required to achieve the following requirements through P4 language.
I. Drop the NetFlow once the IP equals to h1(the one belongs to department a).
II. Enable the IPV4 forwarding function.
III. Increase the survivability in IP headers (TTL)
Based on the requirements, please complete the coding block.
       control MyIngress( )
    {
}
 Please provide screenshots and descriptions to demonstrate that you have achieved the objectives. The report should be compiled and submitted as a group, similar to Assignment 1. Ensure you include the names, SIDs, and the Group ID of all group members in your report.
Good luck!
ELEC5517 Teaching Team

         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
