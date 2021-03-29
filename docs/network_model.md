---
authors:
    - Jiaqi Xiao & Drake Lamp
date: 2021-02-21
---
## During the MSIS program

During your time in the MSIS program you will be required to learn about the fundamentals of IT Architecture. It is expected that you have taken coursework in the past which has provided you a strong foundation for this topic, however, this module hopes to provide you a brief refresher on the OSI model, the different types of networks, as well as diving into more detail surrounding DNS and IP routing.

## Major Concepts

**You should have an understanding of the different network layers making up the OSI model** as well as an understanding of the different types of networks.

1. Be able to _**explain the client-server model.**_
2. Explain the layers within the  _**OSI model**_
3. Understand the _**movement of data**_ between layers.
4. Know the _**different network types.**_

### Key Terms

*  **Data Communication**: Movement of computer information by means of electrical or optical transmission systems
*  **Telecommunication**: Broader than data communication - it includes the transmission of data as well as voice, video, images and graphics and can represent the transmission of these elements over long distances.
*  **Client:** User device used to access data from the network
*  **Server:** Device that stores and transmits data to client(s)
*  **Protocol:** Set of rules which permit how data is transmitted between multiple devices within the same network

Below you will find a graphic which represents the Client-Server model. The Sender is known as the Server, while the Smartphone, PC, Laptop, and Tablet are the Clients.

![Client-Server Model Diagram](/images/Client-Server_Model.png)

### Type of Networks

Networks can be categorized by different scope; when categorizing networks by _geographic scope_, there are three types of networks:

*  **Local Area Network (LAN)**: Network that link devices in close proximity to one another.
*   **Backbone Network (BN):** Interconnects multiple networks and provides a pathway for them to exchange information.
*  **Wide Area Network (WAN)**: Network covering large geographic areas which connects devices that are far apart.

To understand more about the details and differences between these networks, you can read the following articles:

*  [What Is a LAN?](https://www.cisco.com/c/en/us/products/switches/what-is-a-lan-local-area-network.html) (from Cisco)

*  [What is a Network Backbone?](https://blog.stackpath.com/network-backbone/) (from StackPath)

*  [What is WAN?](https://www.cisco.com/c/en/us/products/switches/what-is-a-wan-wide-area-network.html) (from Cisco)

*  [What Is The Difference Between A LAN And WAN?](https://network-support.com/what-is-the-difference-between-a-lan-and-wan-network/) (from Network Support)

When categorizing networks by _different user groups_, we get two types of networks:

*  **Intranet:** Internet technology that is used to share information **within** an organizations.
*  **Extranet:** Internet technology that is used to share information **between** organizations.

### Network Layers

As previously mentioned, **Protocol** is the language of transmission or the rule of device communication.

Read the following article, [Protocol](https://techterms.com/definition/protocol), from "TechTerms" to learn more about network protocols.

*  **Protocol Data Unit (PDU)**: Contains layer-specific information necessary for a message to be transmitted throughout a network.
*  **Layers**: A framework outlining how network interactions occur between the multiple layers in a model.

### Internet models

#### OSI

The _**Open Systems Interconnection Model**_, otherwise known as OSI, is a framework which describes the functions within a networking system. It contains seven (7) layers which make up a set of rules allowing for interoperability between different hardware and software. Below you will find those layers:

<table>
  <tr>
    <th> Layer # </th>
    <th> Layer Name </th>
  </tr>
  <tr>
    <td>7</td>
    <td>Application Layer</td>
  </tr>
  <tr>
    <td>6</td>
    <td>Presentation Layer</td>
  </tr>
  <tr>
    <td>5</td>
    <td>Session Layer</td>
  </tr>
  <tr>
    <td>4</td>
    <td>Transport Layer</td>
  </tr>
  <tr>
    <td>3</td>
    <td>Network Layer</td>
  </tr>
  <tr>
    <td>2</td>
    <td>Data Link Layer</td>
  </tr>
  <tr>
    <td>1</td>
    <td>Physical Layer</td>
  </tr>
</table>

*  [The OSI model explained](https://www.networkworld.com/article/3239677/the-osi-model-explained-and-how-to-easily-remember-its-7-layers.html) (from NetworkWorld)

*  [CompTIA Network + Microsoft MTA Networking: OIS model](https://asmed.com/comptia-network-osi-model/) (from ASMEd)

<iframe width="560" height="315" src="https://www.youtube.com/embed/LANW3m7UgWs" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

#### TCP/IP Model

The TCP/IP model is a much more concise version of the OSI model. This model has brought together the seven previously outlined layers into four, much more encompassing layers. Those layers are as follows:

<table>
  <tr>
    <th> Layer # </th>
    <th> Layer Name </th>
  </tr>
    <td>4</td>
    <td>Network Access Layer</td>
  </tr>
  <tr>
    <td>3</td>
    <td>Internet Layer</td>
  </tr>
  <tr>
    <td>2</td>
    <td>Transport Layer</td>
  </tr>
  <tr>
    <td>1</td>
    <td>Application Layer</td>
  </tr>
</table>

*  [TCP/IP Model: Layers & Protocol](https://www.guru99.com/tcp-ip-model.html) (from Guru99)

*  [TCP/IP Protocol Architecture Model](https://docs.oracle.com/cd/E19683-01/806-4075/ipov-10/index.html) (from Oracle)

**Please note:** It is important that you are familiar with the different layers of _both_ the OSI and TCP/IP model; you should be able to speak on their functionality and applicable protocols.

#### General Internet Model Resources

*  [The Network Layers Explained](https://www.plixer.com/blog/network-layers-explained/) (from Plixer)

### How DNS and IP addresses work

Interested in how DNS (Domain Name System) works? Below we have identified a handful of resources for you to be able to better understand the topic:

*  [What is DNS?](https://www.cloudflare.com/learning/dns/what-is-dns/) (from Cloudflare)

*  [How DNS Works in Six Steps](https://www.verisign.com/en_US/website-presence/online/how-dns-works/index.xhtml) (from Verisign)

*  [What is the Internet? (Free Course!)](https://www.khanacademy.org/computing/code-org/computers-and-the-internet/internet-works/v/what-is-the-internet) (from Khan Academy)

<iframe width="560" height="315" src="https://www.youtube.com/embed/Rck3BALhI5c" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

Understanding how DNS works can be difficult without an understanding of how IP addresses work together to assist in the routing process. Below we have identified a set of resources which touch on IPv4/IPv6, IP Addresses as well as the role they play with DNS:

<iframe width="560" height="315" src="https://www.youtube.com/embed/aor29pGhlFE" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<iframe width="560" height="315" src="https://www.youtube.com/embed/LIzTo6e4FgY" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<iframe width="560" height="315" src="https://www.youtube.com/embed/MwxMsaFFycg" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## Practice

Below you will find a small number of questions; these are meant to simply test your knowledge of the material previously outlined.

1.	How many layers are in the OSI model? Please name the layers.
<details class="example">
<summary>Answer</summary>
  There are seven layers within the OSI model - the layers are as follows: Physical, Data link, Network, Transport, Session, Presentation, and  Application Layer.
</details>
2.	What is the purpose of a WAN (Wide Area Network)?
<details class="example">
<summary>Answer</summary>
  The purpose of a WAN is to connect devices that are spread out over large geographic distances.
</details>
3.	What is the purpose of DNS?
<details class="example">
<summary>Answer</summary>
  DNS translates a domain name to an IP address so that a browser is able to load a page. DNS servers eliminate the need to memorize a webpages IP address. Please note, IP addresses are unique to the entity in which they are assigned.
</details>
4.	Is the OSI model a descriptive model?
<details class="example">
<summary>Answer</summary>
  No, the OSI model is a prescriptive model which means it gives strict directions on how to do the work each time. However, the TCP/IP model is a descriptive model which means that it gives a basic outline of how things should be done.
</details>
5.	Are the internet layers of both the OSI and TCP/IP models equivalent?
<details class="example">
<summary>Answer</summary>
  Yes, devices and protocols interacting with IP packets and getting them to their destinations sit within the internet layer.
</details>
6.	What type of network is used to transmit information and data internally?
<details class="example">
<summary>Answer</summary>
  Intranet, this is a network which can be used strictly for internal communications and has no connection to an outside network.
</details>
7.	What are the four layers of the TCP/IP model?
<details class="example">
<summary>Answer</summary>
  Application, Transport, Internet, and Network Access Layer
</details>
8.	Define Encapsulation:
<details class="example">
<summary>Answer</summary>
  This is where the application interacts with the application layer, passing data to the transport and internet layers before being moving onto the physical layer for transmission. Once this data is received the process will occur, but in reverse, on the receiving device.
</details>
9.	What is the responsibility of the Transport Layer?
<details class="example">
<summary>Answer</summary>
  The Transport Layer ensures accurate delivery of data with flow control, segmentation and reassembly, error correction, and acknowledgment.
</details>
10.	What is the primary scope of identifying the type of network needed?
<details class="example">
<summary>Answer</summary>
  Keeping in mind your geographic scope is increasingly important when dictating how you will configure your network. Not only does it require you to think about your current needs, it also means you must consider how the network might expand overtime.
</details>
11.	What is TCP?
<details class="example">
<summary>Answer</summary>
  Transmission Control Protocol, commonly referred to as TCP, is used to organize data in a way which ensures secure transmissions within the client-server model. Additionally, it guarantees the integrity of data in all sizes.
</details>
12.	Describe the responsibilities of the Network Layer.
<details class="example">
<summary>Answer</summary>
  The responsibilities of the Network Layer are to establish connections, while translating network addresses to determine appropriate routing.  
</details>
13.	What type of network might IU use on campus to connect the buildings via campus wifi?
<details class="example">
<summary>Answer</summary>
  IU utilizes a backbone network run throughout the Bloomington campus to connect each building to the private network.
</details>
14.	Is the Application Layer a software application?
<details class="example">
<summary>Answer</summary>
  No, the Application Layer is not an actual software application. Instead it interfaces between applications and networks while interpreting user requests and requirements.
</details>
15.	What is the purpose of a protocol?
<details class="example">
<summary>Answer</summary>
  The primary purpose of a protocol is the lay out a set of rules which permit how data is transmitted between devices.
</details>
