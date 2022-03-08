# Report on Firewall

# Introduction to Firewall

A firewall is a software program or piece of hardware that helps to defend hackers , viruses and worms that try to attack over the internet.


## Firewall are of 2 Types
  1. ## Software Firewall
  1. ## Hardware Firewall


  # Software Firewall
 * A Software Firewall is a program that is installed on your pc.
 * Software firewall is a special type of computer software runs on a computer/server.
 * It’s main purpose is to protect your computer/server from outside attempts to control or gain access and depending on your choice of software firewall.
 * Software firewall can also be configured for checking any suspicious outgoing requests. 
 * All the Windows operating System like window xp , window vista window 8, window 10 , window 11 all operating System have an inbuilt software firewall. 
 * Software firewalls can monitor traffic trying to leave your computer as well, preventing it from being used to attack other networks or devices.
 * A software firewall has to be installed on each computer in the network. Therefore, a software firewall can only protect one computer at a time.

 # Hardware Firewall
 * Hardaware Firewall is a device placed in between your network and untrusted internet.
 * It is physical piece of equipment planned to perform firewall duties. A hardware firewall can be a computer or a dedicated piece of equipment which serve as a firewall. Hardware firewall are already installed  into the router that is situated between the computer and the internet .
 *  hardware firewall is a system that works independently from the computer it is protecting as it filters information coming from the internet into the system. If you have a broadband internet router, it likely has its own firewall.
 * To protect your system, a hardware firewall checks the data coming in from the various parts of the internet and verifies that it is safe. 
 * Hardware firewalls that use packet filtering examine each data packet and check to see where it is coming from and its location. The data the firewall collects about each packet is then compared to a permissions list to see if it fits the profile of data that should be discarded. A hardware firewall can protect all the computers attached to it.

 # How does the firewall works 
 * The basic task of firewall is to regulate the flow of traffic in between computer network of different trust levels.
 * For example home network (zone of trust)  ==> Firewall  == > untrusted internet (which is zone of no trust).
 *  All incoming messages are passed through the firewall and firewall checks that it satisfy the security criteria and if they are passed then they are passed through the firewall otherwise they are block by firewall
 * If we turn off the Firewall then all messages are passed freely without the firewall as a result hackers can easily hack our computer and obtain the sensitive data like banks details , login ids and pass etc.

 ___

 ## Firewalls use different methods to protect your network or computer. They include the following:
     1. Packet Filtering 
     2. Proxy Firewall
     3. Statefull Inspection

___

# Packet Filtering:
* Data is organized in packets. When a firewall executes packet filtering, it examines the packets of data, comparing it against filters, which consist of information used to identify malicious data. 
* If a data packet meets the parameters of a threat as defined by a filter, then it is discarded and your network is protected. Data packets that are deemed safe are allowed to pass through.
___

#  Proxy Filtering:
* With a proxy the firewall acts as a go-between positioned between your computer and anything that tries to connect to it. A proxy firewall is like a mirror of your computer and detects malicious actors attempting to get through to your device. 

* Proxy firewalls are a secure solution because of the separation they provide between your computer and the internet. Attackers often need to connect directly to your computer to attack it. Because a proxy is between your computer and the internet, hackers cannot form a direct connection to it, rendering their attack useless.

* Proxy firewalls are a secure solution because of the separation they provide between your computer and the internet. Attackers often need to connect directly to your computer to attack it. Because a proxy is between your computer and the internet, hackers cannot form a direct connection to it, rendering their attack useless.

___
# Stateful Inspection :

 * A stateful inspection firewall inspects every data packet and compares it against a threat database.
 * During the inspection process, the firewall checks where the data is coming from, the ports it uses, and the applications it is associated with. If the data packet checks out, it is allowed to pass. Otherwise, it is discarded.
 * Stateful inspection can also collect information about the data packets that go through it and use that to gain more insights into data that may cause potential threats in the future.


 # How Does a Firewall Protect Data
 * Firewall filters keep harmful data outside your computer. Some of the top risks from which firewalls protect your computer include backdoors, denial-of-service (DoS) attacks, macros, remote logins, spam, and viruses.
 *  By putting protective filters in place around your network and devices, firewalls can help to prevent a number of different security risks. These can include:
 ## Backdoors
 * While certain applications are designed to be accessed remotely, others may have bugs that give potential hackers a “backdoor” , or a hidden way to access and exploit the program for malicious purposes.

 * Some operating systems may also contain bugs that provide backdoors for skilled hackers to manipulate to their own benefit.

 # Denial of service Attack
 *  This increasingly popular type of cyberattack can slow or crash a server.
 * Hackers utilize this method by requesting to connect to the server, which sends an acknowledgment and attempts to establish a connection.
 * However, as part of the attack, the server will not be able to locate the system that initiated the request.
 * Flooding a server with these one-sided session requests allows a hacker to slow down server performance or take it offline entirely.

 * While there are ways firewalls can be used to identify and protect against certain forms of denial of service attacks, they tend to be easily fooled and are usually ineffective.

 # Macros

 * Macros are scripts that applications can run to streamline a series of complicated procedures into one executable rule. Should a hacker gain access to your customers’ devices, they can run their own macros within the applications. This can have drastic effects, ranging from data loss to system failure.
 *  These executable fragments can also be embedded data attempting to enter your network, which firewalls can help identify and discard.


 #  Remote logins
 * Remote logins can vary in severity, but always refer to someone connecting to and controlling your computer.
 * They can be a useful technique for allowing IT professionals to quickly update something on a specific device without being physically present—but if performed by bad actors, they can be used to access sensitive files or even execute unwanted programs.

 # Spam
 *  While most spam is harmless, some spam can also be incredibly malicious. Spam often will include links which should absolutely never be clicked! .
 * By following links in spam mail, users may accept cookies onto their systems that create backdoor functionality for hackers.
 * It is important that your customers receive cybersecurity awareness training in order to reduce vulnerabilities from within their network.

 # Viruses
 * Viruses are small programs that replicate themselves from computer to computer, allowing them to spread between devices and across networks.
 * he threat posed by some viruses can be relatively small, but others are capable of doing more damage—such as erasing your customers’ data. 
 Some firewalls include virus protection, but using a firewall alongside antivirus software is a smarter and more secure choice.

# There are 3 Types of Firewall

## 1. Packet Filtering Firewall
## 2. Application or Proxy Firewall
## 3. Hybrid Firewall

___

# 1. Packet Filtering Firewall :-
* It is a technique used to control network access by monitoring outgoing and incoming packets and allowing them to pass or halt based on the source and destination Internet Protocol (IP) addresses, protocols, and ports.  
* This firewall is also known as a static firewall.
* Packet filtering checks source and destination IP addresses. If both IP addresses match, the packet is considered secure and verified. Because the sender may use different applications and programs, packet filtering also checks source and destination protocols, such as User Datagram Protocol (UDP) and Transmission Control Protocol (TCP). 
* Packet filters also verify source and destination port addresses.

Packet filtering is usually an effective defense against attacks from computers outside a local area network (LAN). As most routing devices have integrated filtering capabilities, packet filtering is considered a standard and cost-effective means of security. 

# 2.  Application or Proxy Firewall :-
* A proxy firewall is the most secure form of firewall, which filters messages at the application layer to protect network resources.
* A proxy firewall, also known as an application firewall or a gateway firewall, limits the applications that a network can support, which increases security levels but can affect functionality and speed. 
* A proxy firewall is considered the most secure form of firewall because it prevents networks from directly contacting other systems. 
* It has its own Internet Protocol (IP) address, which means an external network connection cannot receive packets directly from the network. 

___

## Advantages of Proxy Firewalls 
* The main goal of a proxy firewall is to provide a single point of access. This enables organizations to assess the level of threat posed by application protocols, effectively detect threats, and check the validity of network traffic. 
* A proxy firewall also enables refined setup control, which allows organizations to fine-tune it to their network needs and corporate policies.

## Disadvantage of Proxy Firewall:-
* One of the main disadvantages is that a proxy firewall creates a new connection for each outgoing and incoming packet. This can result in the firewall creating a bottleneck in traffic flow, significantly slowing down the process and negatively affecting network performance, and creating a single point of failure. 
* Some proxy firewalls might only support particular network protocols, which limits the applications that the network can support and secure. 

___

# Hybrid Firewall:-
 * This Firewall is the combination of both packet filtering and application firewall. They are both used in the series and hence provide the best security.
* This kind of firewall is useful for educational institute, Banking, Hospitals, Mid-High level companies and others who has important data and runs a business where a high risk of data is involved.

___

# Advantages of Firewall:-

## 1.Monitor Traffic
* A major responsibility of a firewall is to monitor the traffic passing through it. Whatever the information traveling through a network is in the form of packets. 
* Firewall inspects each of these packets for any hazardous threats. If any chance the firewall happens to find them it will immediately block them.

## 2. Protection against Trojans
* Malwares especially the type Trojans are dangerous to a user. A Trojan silently sits on your computer spying over all the works you do with it. Whatever the information they gather will be sent to a web server. Obviously you will not know their presence until the strange behaviours of your computer. 
* A firewall in this instance will immediately block Trojans before they cause any damages to your system. 

## 3. Prevent Hackers 
* Hackers on the internet constantly look for computers in order for carrying out their illegal activities. When the hackers happen to find such computers they will start to do even malicious activities such as spreading viruses.
* Apart from those hackers there can be unknown people such as the neighbours looking out for an open internet connection. Hence, to prevent such intrusions it is a good idea to be with a firewall security.

## 4. Access Control
* Firewalls comes with an access policy that can be implemented for certain hosts and services. Some hosts can be exploited with the attackers. 
* So the best in case is to block such hosts from accessing the system. If a user feels that they need protection from these types of unwanted access, this access policy can be enforced. 

## 5. Better Privacy

* Privacy is one of the major concerns of a user. Hackers constantly look out for privacy informations for getting clues about the user.
* But by using a firewall many of the services offered by a site such as the domain name service and the finger can be blocked. 
* Hence, the hackers are with no chance of getting privacy details. Additionally firewalls can block the DNS informations of the site system. Due to this the names and the IP address will not be visible to the attackers. 

# Disadvantages of Firewall

## 1.Cost
* Firewalls does have an investment depending on the types of it. In general hardware firewalls are more expensive than the software firewalls. 
* Besides that hardware firewalls require installations and maintenance which can be costly. 
* These types of configurations cannot be done without an expert IT employee. Comparing this to a software firewall, there is no much investment and it is easy enough for an average user to deploy them.

## 2.User Restriction

* It is no doubt that firewalls prevent unauthorized access to your system from the network. While this can be advantageous for an average user, this can actually be a problem for large organizations.
* The policies used by the firewall cab be strict enough to prevent employees from doing certain operations. As a result of this, the overall productivity of the company an be affected severely.
* Sometimes this can also prompt employees from using backdoor exploits. However this can lead to security problems since the data travelled through these backdoor exploits are not examined properly.

##  3. Performance
* Firewalls especially the software based has the capability to limit your computer's overall performance. The processing power and the RAM resources are some of the factors which decides the computer's overall performance. 
* When the software firewalls constantly run on the background they consume more the processing power and the RAM resources. This can lead to a diminished system performance. 
* However hardware firewalls does not impact the system performance since they do not rely upon the computer resources.

## 4. Malware Attacks

Even though firewalls has the capability to block the basic types of trojans, it is proved to be defenseless against other types of malwares. These types of malwares can enter your system in the form of trusted data. Therefore, even if you have firewall, it is still recommended to have an anti-malware software installed on your PC. Because the only way to remove them is through an anti-malware scan.

## References  :

1. https://www.techopedia.com/definition/4038/packet-filtering


1. https://www.fortinet.com/resources/cyberglossary/proxy-firewall

 1. https://www.hitechwhizz.com/2020/03/5-advantages-and-disadvantages-drawbacks-benefits-of-firewall.html

 1. https://www.n-able.com/blog/how-do-firewalls-work

 1. [Firewall Vedios](https://www.youtube.com/watch?v=eO6QKDL3p1I&list=PLBbU9-SUUCwV7Dpk7GI8QDLu3w54TNAA6)
















 
 

