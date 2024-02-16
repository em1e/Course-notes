| Started: 09.02.24 | Finished: xx.xx.xx |
| ----------        | ------------       |

<div align="center">

# Networking Essentials
</div>

## Module 1: Communications in a Connected World

<details>
<summary> 1.1 Network Types ✅ </summary>
<br>
  
- People think of the internet as a formless collection of connections, a "place" where people go to find or share information.
- The internet isn't owned by any individual or group, instead it is a worldwide collection of interconnected networks, cooperating with each other to exchange information using common standards.

#### Local Networks:

| Small Home Networks | Small Office and Home Office Networks aka SOHO | Medium to Large Networks | World wide Networks |
| ----                | ----                                           | ----                     | ----                |
| connect a few computers to each other and to the internet | Allows computers in a home office or a remote office to connect to a corporate network, or access centralized, shared resources | Networks used by corporations and schools, can have many locations with hundreds or thousands of interconnected hosts | Network of networks that connects computers world-wide |

- Many different devices cnnect to the internet:
  - Some obvious ones are: Computers, smartphones, smart TV, tablets, smartwatches, smart glasses and gaming console.
  - Home Devices: Security system and appliances (fridge, ovens, dishwasher).
  - Other: Smaart cars, RFID tags (can be **placed in or on objects to track them**), sensors and medical devices.

<br>
</details>

<details>
<summary> 1.2 Data Transmission ✅ </summary>
<br>

#### Types of Personal Data:

| Volunteer data | Inferred data | Observed data |
| ----           | ----          | ----          |
| Data that you offer yourself, know is being collected and you agree to share | Data that you generate by your activities, that you may not concent to | Data collected by observing and recording events, behaviors, or phenomena as they naturally occur |
| e.g. social network profiles; videos, pictures, text or audio files | e.g. Credit score; which is based on analysis of volunteered or observed data | e.g. location data when using cell phones |  

- A bit (**binary digit**) is the **smallest unit of data** that a computer can process and store.
  - E.g. Every input device (mouse, keyboard, voice-activated receiver) will translate human interaction into binary code for the CPU to process and store.
  - CPU = a complex set of electronic circuitry that **runs the machine's operating system and apps**.

#### Common Methods of data Transmission:

- ***Media*** refers to the physical medium on which the signals are transmitted. e.g. **copper wire, fiber-optic cable, and electromagnetic waves** through the air.
- Signals may be converted multiple times before reaching the destination, as **corresponding media changes along the way**.

| Electrical signals | Optical signals | Wireless signals | 
|  ---- | ---- | ----- |
| Transmission is achieved by representing data as **electrical pulses on copper wire **| Transmission is achieved by converting the **electrical signals into light pulses** | Transmission is **achieved by using infrared, microwave, or radio waves through the air** |

<br>
</details>

<details>
<summary> 1.3 Bandwith and Throughtput ✅ </summary>
<br>

- Bandwidth is the capacity of a medium to carry data. Digital bandwidth measures the amount of data that can flow from one place to another in a given amount of time.
  
NOTE: Physical media properties, current technologies, and the laws of physics all play a role in determining available bandwidth.

| Unit of Bandwidth | abbreviation | Equivalence | 
| -- | -- | -- |
| Bits per second | bps | 1bps = fundamental unit of bandwidth |
| Bilobits per second | Kbps | 1kbps = 1,000 bps = 10^3 bps |
| Megabits per second | Mbps | 1kbps = 1,000,000 bps = 10^6 bps |
| Gigabits per second | Gbps | 1kbps = 1,000,000,000 bps = 10^9 bps |
| Terabits per second | Tbps | 1kbps = 1,000,000,000,000 bps = 10^12 bps |

#### Throughput:
- Throughput is the measure of the transfer of bits across the media over a given period of time. It measured the amount of data sent and recieved over a connection, and any delays in either dirrection.
- Some influencing factors:
  - The amount of data being sent and received over the connection
  - The types of data being transmitted
  - The latency created by the number of network devices encountered between source and destination
- Latency = **the amount of time**, including delays, for data to travel from one given point to another.

<br>
</details>

<details>
<summary> 1.4 Clients and Servers ✅ </summary>
<br>
  
- All computers connected to a network that participate directly in network communication are classified as hosts. Hosts can send and receive messages on the network. In modern networks, computer hosts can act as a client, a server, or both.
  - The software installed on the computer determines which role the computer plays.
- Servers are hosts that have software installed which enable them to provide information, like email or web pages, to other hosts on the network. Each service requires separate server software.
  - e.g. A host requires web server software in order to provide web services to the network. Every destination that you visit online is provided to you by a server located somewhere on a network that is connected to the global internet.
- Clients are computer hosts that have software installed that enables the hosts to request and display the information obtained from the server.
<br>

- peer-to-peer (P2P) network = where one computer runs both client and server software at the same time.
  - The **simplest P2P network consists of two directly connected computers using either a wired or wireless connection**. Both computers are then able to use this simple network to exchange data and services with each other, acting as either a client or a server as necessary.

| Advantages: | Disadvantages: |
| -- | -- |
| + Easy to set up | - No centralized administration |
| + Less complex | - Not as secure |
| + Lower cost because network devices and dedicated servers may not be required | - All devices may act as both clients and servers which can slow their performance |
| + Can be used for simple tasks such as transferring files and sharing printers | |

- A computer with **server software can provide services simultaneously to one or many clients**.
- Additionally, **a single computer can run multiple types of server software**. In a home or small business, it may be necessary for one computer to act as a file server, a web server, and an email server.
<br>
</details>

<details>
<summary> 1.5 Network Components ✅ </summary>
<br>
  
### Network Infrastructure:
NOTE: Devices and media are the physical elements, or hardware, of the network. 
- Hardware = visible components of the network platform such as a laptop, PC, switch, router, wireless access point, or the cabling used to connect the devices.

- Network Media
  - Wireless Media, LAN Media, WAN Media, Cloud
- End Devices
  - The network devices that people are most familiar with are called end devices, or hosts.
  - An end device (or host) is either the source or destination of a message transmitted over the network
  - e.g. Computer, Laptop, Printer, IP Phone, Smart Phone, Tablet, Server, Security Camera
- Intermediary Devices
  - Router, Wireless Router, LAN Switch, Wireless Access Point, Call Manager, Multilayer Switch, Firewall Appliance

<br>
</details>

<details>
<summary> 1.6 Communications in a Connected World Summary ✅ </summary>
<br>
  
### Network Types:
> The internet is a worldwide collection of interconnected networks, cooperating with each other to exchange information using common standards. Using the internet, we can exchange information through telephone wires, fiber-optic cables, wireless transmissions, and satellite links. The internet is considered a "network of networks" because it is literally made up of thousands of local networks that are connected to each other. The internet connects more computing devices than just desktop and laptop computers. There are devices all around that you may interact with on a daily basis that are also connected to the internet.

### Data Transmission:
> Volunteered data is created and explicitly shared by individuals, such as social network profiles. Inferred data, such as a credit score, is based on analysis of volunteered or observed data. Observed data is captured by recording the actions of individuals, such as location data when using cell phones. A bit can only have one of two possible values, 0 or 1. Each group of eight bits, such as the representations of letters and numbers, is known as a byte. There are three common methods of signal transmission used in networks: electrical, optical, and wireless.

### Bandwidth and Throughput:
> The rate of data transfer is usually discussed in terms of bandwidth and throughput. Bandwidth is typically measured in the number of bits that (theoretically) can be sent across the media in a second. Throughput measures the transfer of bits across the media over a given period of time. Many factors influence throughput including the amount of data being sent and received over the connection, the types of data being transmitted, and the latency created by the number of network devices encountered between source and destination. Latency is the amount of time, including delays, for data to travel from one given point to another.

### Clients and Servers:
> Servers are hosts that have software installed that enable them to provide information, like email or web pages, to other hosts on the network. Clients are computer hosts that have software installed that enable them to request and display the information obtained from the server. In small businesses and homes, many computers function as the servers and clients on the network. This type of network is called a peer-to-peer (P2P) network. The simplest peer-to-peer network consists of two directly connected computers using either a wired or wireless connection. A P2P application allows a device to act as both a client and a server within the same communication. In this model, every client is a server and every server is a client. In a home or small business, it may be necessary for one computer to act as a file server, a web server, and an email server. A single computer can also run multiple types of client software. There must be client software for every service used.

### Network Components:
> The network infrastructure contains three categories of hardware components: intermediate devices, end devices, and network media. Devices and media are the physical elements, or hardware, of the network. Hardware is often the visible components of the network platform such as a laptop, PC, switch, router, wireless access point, or the cabling used to connect the devices. The network devices that people are most familiar with are called end devices, or hosts. These devices form the interface between users and the underlying communication network. An end device (or host) is either the source or destination of a message transmitted over the network.

<br>
</details>
<br>

## Module 2: Online Connections

<details>
<summary> 2.1 Wireless Netowrks ✅ </summary>
- Most mobile phones can be connected to many different types of networks simultaneously

talk => e.g. landlines, cell phones, business
data => e.g. data plan (phone network)
wifi => e.g. hotspots, or home wireless
location services => e.g. gps, maps, places near me
pay services => e.g. cash registers, payment pads
  
#### Cellular providor network = ??
- The most common type of cellular telephone network is called a GSM network, an abbreviation of the title “Global System for Mobile Communications”

Wi-Fi network = **Wi-Fi transmitters and receivers located within the smartphone enable the phone to connect to local networks and the internet.** In order to receive and send data on a Wi-Fi network, the phone needs to be w**ithin the range of the signal** from a wireless network access point. Wi-Fi networks are **usually privately owned** but often provide guest or public access hotspots. A **hotspot is an area where Wi-Fi signals are available.** Wi-Fi network connections on the phone are similar to the network connections on a laptop computer.

Near Field Communications = NFC is a wireless communication technology that enables data to be exchanged by devices that are in **very close proximity to each other**, usually less than a **few centimeters**. For example, NFC can be used to **connect a smartphone and a payment system**. NFC **uses electromagnetic fields to transmit data**.

Bluetooth = A **low-power, shorter range** wireless technology that is **intended to replace wired connectivity** for accessories such as speakers, headphones, and microphones. Bluetooth can also be used to connect a smartwatch to a smartphone. Because Bluetooth technology can be used to transmit both data and voice, **it can be used to create small local networks**. Bluetooth is wireless technology that allows devices to communicate over short distances. Multiple devices can be connected at the same time with Bluetooth.

GPS = The GPS uses satellites to transmit signals that cover the globe. The smart phone can receive these signals and calculate the phone’s location to an accuracy of within 10 meters.

</details>

<details>
<summary> 2.2 Local Networks Connections </summary>
NOTES
</details>

<details>
<summary> 2.3 Network Documntation </summary>
NOTES
</details>

<details>
<summary> 2.4 Online Connections Summary </summary>
NOTES
</details>

<br>

## Module 3: Explore Networks with Packet Tracker


<details>
<summary> 3.1 Packet Tracer Network Simulator </summary>
NOTES
</details>

<details>
<summary> 3.2 Packet Tracer Installation </summary>
NOTES
</details>

<details>
<summary> 3.3 The Packet Tracer User Interface </summary>
NOTES
</details>

<details>
<summary> 3.4 packet Tracer Network Configuration </summary>
NOTES
</details>

<details>
<summary> 3.5 Explore Networks with Packet Tracer Summary </summary>
NOTES
</details>

<br>

## Module 4: Build a Simple network


<details>
<summary> 4.1 Network Media types </summary>
NOTES
</details>

<details>
<summary> 4.2 Ethernet Cabling </summary>
NOTES
</details>

<details>
<summary> 4.3 Coaxial and Fiber-Optic Cabling </summary>
NOTES
</details>

<details>
<summary> 4.4 Twisted-Pair Operation </summary>
NOTES
</details>

<details>
<summary> 4.5 Verify Connectivity </summary>
NOTES
</details>

<details>
<summary> 4.6 Build a Simple Network Summary </summary>
NOTES
</details>

