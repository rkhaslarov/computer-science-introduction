# Essentials of Networking and the Internet
> Task 2

```Homework
Prepare a presentation or a schema about Web and the Internet. 

It should include the answers to the questions below:

What's the Internet?
How does it work?
What's a protocol?
What protocols are vital for the Internet?
What's a server and a client?

Using the command-line interface
and ping utility just Google website (google.com).

Using the command-line interface and traceroute utility,
gather the information about the way to the Google website (google.com). 

Using the command-line interface and nslookup utility 
provide the IP address of the Google website (google.com).
```

The module itself mostly focused on the essentials of the Internet and WWW. A student is going to understand how it works under the hood and learn a bunch of new terms.

**Self-study materials**

* <a href="https://www.youtube.com/watch?v=7_LPdttKXPc" target="_blank">How the Internet Works in 5 Minutes (Watch)</a>
* <a href="https://www.youtube.com/watch?v=hJHvdBlSxug" target="_blank">How The Web Works - The Big Picture (Watch)</a>
* <a href="https://roadmap.sh/guides/what-is-internet" target="_blank">How does the Internet work? (Read and Watch)</a>
* <a href="https://www.youtube.com/watch?v=3QhU9jd03a0&list=PL8dPuuaLjXtNlUrzyH5r6jN9ulIgZBpdo&index=29" target="_blank">Computer Networks (Watch)</a>
* <a href="https://www.youtube.com/watch?v=AEaKrq3SpW8&list=PL8dPuuaLjXtNlUrzyH5r6jN9ulIgZBpdo&index=30" target="_blank">The Internet (Watch)</a>
* <a href="https://www.youtube.com/watch?v=guvsH5OFizE&list=PL8dPuuaLjXtNlUrzyH5r6jN9ulIgZBpdo&index=31" target="_blank">The World Wide Web (Watch)</a>
* <a href="https://medium.com/@yatskovavd/the-very-very-basics-of-web-development-websites-and-a-browser-43c2cf5f6c38" target="_blank">The very-very basics of web development: websites and a browser (Read)</a>
* <a href="https://developers.google.com/web/shows/ttt/series-2/windows-commandline" target="_blank">Windows Command-line Tools</a>

**Additional materials**

* <a href="https://www.youtube.com/watch?v=QKfk7YFILws" target="_blank">Computer Networking Complete Course - Beginner to Advanced by Google (Watch)</a>
* <a href="https://www.freecodecamp.org/news/how-the-web-works-a-primer-for-newcomers-to-web-development-or-anyone-really-b4584e63585c/" target="_blank">How the Web Works: A Primer for Newcomers to Web Development. (Read)</a>
* <a href="https://www.freecodecamp.org/news/how-the-web-works-part-ii-client-server-model-the-structure-of-a-web-application-735b4b6d76e3/" target="_blank">How the Web Works Part II: Client-Server Model & the Structure of a Web Application (Read)</a>
* <a href="https://www.freecodecamp.org/news/how-the-web-works-part-iii-http-rest-e61bc50fa0a/" target="_blank">How the Web Works Part III: HTTP & REST (Read)</a>

## Essentials of Networking and the Internet notes

__Networking__

**Internet** - The physical connection of the computers and wires around the world;
**Web** - Information on the internet. Ways to access the internet - Web, Email, Chat, File-sharing programs;

**The Internet** is composed of a massive network of satellites, cellular networks, and physical cables buried beneath the ground;
Computers called **servers** connect to the internet directly and not all pc, desktops;
**Servers** - store the websites we use - wikipedia, google, etc. These websites serve the content requested by the client (mobile phines, laptops, etc). Internet (Satellites/Cellular networks/cables) -> Server -> Websites (Google, wikipedia) -> Client (phone, desktop);
  
**Clients** don't connect directly to the internet, but connect to a network run by the ISP (Internet Service Provider) like - Beltelecom (Minsk), and etc;
 
**ISPs** have built networks and run all the necessary physical cabling that connects millions of computers together in one network.
They also connect to other networks and ISPs; The other network connect to google, universities, etc. Together form the Internet;
 
Computers on a network have an identifier called an **IP address** which is composed of digits and dots. To access websites like - www.coursera.org - go to the IP address. Devices that can connect to the network have another unique identifier **MAC address** permanemt ad hardcoded onto a device. Eg: - 82:4f:23:59:47:4. When data is sent or received on a network both IP and MAC address must be available.
Data sent through a network is sent in **packets** (bits of binary data); 

__Networking Hardware__

The ways to connect to the Internet:

* Ethernet cable - physically connect to the network through a cable;
* WIFI - wireless networking, through radios and antennas;
* Fiber optics - expensive and allow greater speed that other methods, contains of glass fibers that move data through light instead of electricity;
    
**Router** - connects lots of different devices together and helps route the network traffic. Router utilizes network protocols to determine where to send the data packet;
**Switches** and **hubs** are devices that help the data travel;
 
**Network Stack** - a set of hardware or software that provides the infrastructure for a computer;

__The Language of the Internet__

Network protocols - Set of rules in order to route data through a network. Route efficiently, aren't corrupted, secure, destination, names appropriately;
  
TCP (Transmission Control Protocol) and the IP (Interpet Protocol) - TCP/IP:

* **IP** - delivers packets to the right computers;
* **TCP** - handles reliable data transfer between networks;

__Web__

Many ways to access the internat - web, mail, chat, file sharing, etc;

All websites can be access through the Web. **Websites** are text documents that are formatted with HTML - hypertext markup language - coding language used by web browsers. **Web pages** - made of very basic components, multimedia content.

To navigate into a website you type a url - www.google.com. **URL** - Uniform Resource Locator - is a web address.

**Domain Name** - can be registered to ICANN (Internet Corporation for Assigned Names and Numbers).
**Domain Endings**

* .edu - education institutions;
* .org - organizations, etc;
 
172.217.6.46 - maps to google homepage through a protocal called DNS (Domain Name System). DNS - acts like the Internet's directory and uses human readable words to map to an IP address.
  
__Limitations__

* IPv4 - It is an address that consist of 32 bits separated into four groups; (Totally < 4.3 billion IP address # websites , users more);
* IPv6 - consists of 128bits (4 times of IPv4); - 379f:3e7d:4860:0370:7334:0000; (possibilities 2 power 128);

**NAT** - Network Address Translation - Lets organizations use one public IP address and many private IP addresses within the network
The router may need to be configured with NAT to facilitate communication between the company's network and the outside world.
