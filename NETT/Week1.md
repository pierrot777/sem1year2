Review Questions: 
## Section 1.1
###### *R1. What is the difference between a host and an end system? List several different types of end systems. Is a Web server an end system?*

There is no difference. The words host and end system are used interchangeably. End systems include PCs, workstations, Web servers, mail servers, PDAs. Internet-connected game consoles etc.

###### *R2. Describe the protocol that might be used by two people having a telephonic conversation to initiate and end the conversation, i.e., the way that they talk.*

Goku calls Vegeta and she answers, saying “Hello?”. Since it’s their first time speaking, Goku confirms he has reached the right person and introduces himself. They then have their conversation. When they finish, Goku says “bye,” Vegeta replies “bye,” and they both hang up, ending the call.

###### *R3. Why are standards important for protocols?*

Standards are important for protocols so that people can create networking systems and products that can work in conjunction with each other.

## Section 1.2

###### *R4. List four access technologies. Classify each one as home access, enterprise access, or wide-area wireless access.*

Dial-up modem over telephone line: home; 2. DSL over telephone line: home or small
office; 3. Cable to HFC: home; 4. 100 Mbps switched Ethernet: enterprise.

###### *R5. Is HFC transmission rate dedicated or shared among users? Are collisions possible in a downstream HFC channel? Why or why not?*

In an HFC network, the bandwidth is shared among all users in the neighbourhood. For the downstream channel, all data comes from one central device called the headend. Because there is only one sender on the downstream path, collisions do not occur.

###### *R6. What access network technologies would be most suitable for providing internet access in rural areas?*

In rural areas, 3G, 4G, or LTE can be used if there is cellular coverage. DSL or dial-up may also be possible if telephone lines are available. However, both options require existing infrastructure nearby. If no infrastructure is available, satellite Internet can be used to provide access.

###### *R7. Dial-up modems and DSL both use the telephone line (a twisted-pair copper cable) as their transmission medium. Why then is DSL much faster than dial-up access?*

Dial-up Internet uses the same telephone network that carries voice calls, which limits the bandwidth to about 56 Kbps. DSL is faster because it only uses the telephone line between the home and the DSLAM, not the full voice network. It also uses higher frequency signals, allowing much higher speeds (for example, up to 24 Mbps).

###### *R8. What are some of the physical media that Ethernet can run over?

###### R9. HFC, DSL, and FTTH are all used for residential access. For each of these access technologies, provide a range of transmission rates and comment on whether the transmission rate is shared or dedicated.*



###### *R10. Describe the different wireless technologies you use during the day and their characteristics. If you have a choice between multiple technologies, why do you prefer one over another?*



Tutorial Problem:

# Lab: 

1. List 3 different protocols that appear in the protocol column in the unfiltered packet-listing window in step 7 above.

UDP, ARP, TCP

2. How long did it take from when the HTTP GET message was sent until the HTTP OK reply was received? (By default, the value of the Time column in the packet- listing window is the amount of time, in seconds, since Wireshark tracing began. To display the Time field in time-of-day format, select the Wireshark View pull down menu, then select Time Display Format, then select Time-of-day.)

![[Pasted image 20260303185134.png]]

It took roughly 35 milliseconds between HTTP GET message to be sent and HTTP OK reply was received.

3. What is the Internet address of the gaia.cs.umass.edu (also known as www- net.cs.umass.edu)? What is the Internet address of your computer?

Internet address of gaia.cs.umass.edu is = 2404:6800:4006:804: : 200e
Internet address of my computer is = 2001:8004:1d73:3d4f:d537:51d5:b65b: 9e8b

4. Print the two HTTP messages (GET and OK) referred to in question 2 above. To do so, select Print from the Wireshark File command menu, and select the “Selected Packet Only” and “Print as displayed” radial buttons, and then click OK

DONE ON HOME PC
