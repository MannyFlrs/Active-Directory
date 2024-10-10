# Active Directory

## Objective
Build a home lab to simulating how to manage resources such as users, computers, and groups. Enhance the security posture of the Active Directory environment against unauthorized access and data breaches.  It aims to provide insights into identity management by focusing on user roles and permissions management.This hands on experience was designed to deepen my understanding of indentity management, security policy implementation along with monitoring and auditing.


### Skills Learned 



### Tools Used 



## Steps
1. Create a logical diagram to map out how the lab will be built along with the hardware requirements.
   - Open up Draw.io to create the diagram needed to map everything out. Start by using the search feature to look for a server icon and add 2 of them onto the diagram.
   - One will be used for Splunk and the other for the Active Directory. Using the same searching feature, look up a computer icona and 2 of them . One of them is going to be the target machine which is a Windows 10 machine and the other is going th be the attacker machine.
   - Click on one of the computers and on the right side there is an option to color it red, that one will be the attacker machine and can now begin to differentiate between both machines.
   - The last couple of icons to add onto the diagram is a switch, router, and a cloud to signify the internet.
   - At this point, hover over an icon and select the arrow that appears on itand drag it to start connecting the icons to each other.
   - Connect the two computers and the two servers to the switch, then connect the switch to the router, and the router to the internet (cloud icon).
   - Once the diagram is formatted, add in the network information by double clicking the screen and select "text". For this I used:
     * Domain: Blythe
     * Network: 192.168.10.0/24
     * Splunk Server: 192.168.10.10
     * Active Directory: 192.168.10.7
     * Attacker: 192.168.10.250
     
   - Now we can add data onto our icons by double clicking it. The following image will show what was used for the labeling the data.
   - We'll also be connecting our Windows machine icon to the splunk server to indicate that is forwarding data over. Do the same for the Active Directory server.
     ![Screenshot 2024-10-10 114240](https://github.com/user-attachments/assets/73a9b6bf-2bc4-4d4a-b6f9-130510b1a739) ![Screenshot 2024-10-10 114410](https://github.com/user-attachments/assets/d770af89-5a5d-4d75-a0e6-d69f551b94af)

2. 

