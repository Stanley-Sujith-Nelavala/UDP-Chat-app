# UDP-Chat-app
This repo contains the code and relevant explanation of the simple udp chat application made using java and some simple socket programming along with the analysis using the wireshark tool and simulation using Cisco Packet Tracer

## Installation
1. Install and setup Eclipse latest version, Since it is the convinient IDE for java importing and editing all these codes would be more easy.
2. Open a new project with any desired name, anyhow relevent name according to the naming standards of java is suggested.
3. Import / copy these 3 files into the default package.
4. Run the server code first and you can observe the port 2020 open in the console.
5. After the server is started, Run the client code and enter the ip address, it is local i,e 127.0.0.1 by default.

![Screenshot](https://github.com/Stanley-Sujith-Nelavala/UDP-Chat-app/blob/main/gh.png)

## Wireshark Analysis 
The analysis of the the following chat by two clients in thew server is analysed using the wireshark tool.
![Chat](https://github.com/Stanley-Sujith-Nelavala/UDP-Chat-app/blob/main/Screenshot%20(9).png)
 
 since this is the udp we can not clearly see the establishment of the connection, and due to lack to encryption we will be able to read the message in that chat from the captured packets directly without any decoding
 
 First message: Hey this is stanley
 
 ![First message](https://github.com/Stanley-Sujith-Nelavala/UDP-Chat-app/blob/main/Screenshot%20(7).png)
 
 reply from the other client: this is sanjay
 
 ![reply message](https://github.com/Stanley-Sujith-Nelavala/UDP-Chat-app/blob/main/Screenshot%20(8).png)


## Cisco Packet Tracer Simulation
'loading..'

## Contributors
1. Vidya Sri Gummadi [coe19b040@iiitdm.ac.in](coe19b040@iiitdm.ac.in)
2. Vennela Kudala [coe19b032@iiitdm.ac.in](coe19b032@iiitdm.ac.in)
3. G V Sanjay Reddy [ced19i042@iiitdm.ac.in](coed9i042@iiitdm.ac.in)
4. Stanley Sujith Nelavala [coe19b043@iiitdm.ac.in](coe19b043@iiitdm.ac.in) 'Thats ME'
