# Imane Lamine / 12.07.2021


## Executive Summary 
In this chapter, we will be learning more about internet architecture, HTML5 and CSS, and finally, URLs and file paths.  

## Internet Architecture
Internet architecture is a meta-network, which refers to a congregation of thousands of distinct networks interacting with a standard protocol. In simple terms, it is referred to as internetwork connected using protocols. The protocol used is TCP/IP.
### Internet Protocol
#### IP Address
"IP address" is a shorter way of saying "Internet Protocol address." IP addresses are the numbers assigned to computer network interfaces. Although we use names to refer to the things we seek on the Internet, such as www.example.org, computers translate these names into numerical addresses so they can send data to the right location. So when you send an email, visit a website, or participate in a video conference, your computer sends data packets to the IP address of the other end of the connection and receives packets destined for its IP address
#### ICANN
ICANN Internet Corporation for Assigned Names and Numbers.
The Internet Corporation for Assigned Names and Numbers is an American multistakeholder group and nonprofit organization responsible for coordinating the maintenance and procedures of several databases related to the namespaces and numerical spaces of the Internet, ensuring the network's stable and secure operation. 
### TCP/IP
TCP/IP stands for "Transmission Control Protocol / Internet Protocol." It is a network protocol that defines how data is sent and received through network adapters, hubs, switches, routers, and other network communications hardware. The US Department of Defense developed it to connect government computer systems through a global, fault-tolerant network. The defense department network was opened up to research institutions and eventually the general public to create the Internet. The TCP/IP protocol was also placed in the public domain so that any software company could develop networking software based on the protocol. Because it is the primary protocol used on the Internet and is in the public domain, it has become the most popular networking protocol worldwide. It is therefore well supported by almost all computer systems and networking hardware.
#### Responsibility of TCP/IP
TCP is the component that collects and reassembles the data packets, while IP is responsible for making sure the packages are sent to the right destination.
#### Client-Server Model and TCP/IP
TCP/IP connections work like a telephone call where someone has to initiate the connection by dialing the phone. At the other end of the relationship, someone has to be listening for calls and then pick up the line when a call comes in. In TCP/IP communications, the IP Address is analogous to a telephone number, and the port number would be equivalent to a particular extension once the call has been answered. The "Client" in a TCP/IP connection is the computer or device that "dials the phone," and the "Server" is the computer that is "listening" for calls to come in. In other words, the Client needs to know the IP Address of whatever Server it wants to connect to, and it also needs to see the port number that it wants to send and receive data through after a connection has been established. The Server only has to listen for connections and either accept them or reject them when a client initiates them.
#### Layers
Layers are helpful because they allow you to move and manipulate parts of an image to see how your changes affect the whole.
#### Application Layer
The application layer defines standard Internet services and network applications that anyone can use. These services work with the transport layer to send and receive data. Many application layer protocols exist. The following list shows examples of application layer protocols:
Standard TCP/IP services such as the ftp, tftp, and telnet commands
UNIX "r" commands, such as login.
Name services, such as NIS and the domain name system (DNS)
Directory services (LDAP)
File services, such as the NFS service
Simple Network Management Protocol (SNMP), which enables network management
Router Discovery Server protocol (RDISC) and Routing Information Protocol (RIP) routing protocols

## Internet Security

### HTTP and Client-Server Model
The HTTP is the Web's application layer protocol that works on the Client-Server technology. In this, the Client requests pages and objects through its agent, and the Server responds to them with the requested things by displaying. The Client requested the HTML pages towards the Server and responded with HTML pages.
### Protocols for Secure HTTP
Hypertext Transfer Protocol Secure is an extension of the Hypertext Transfer Protocol. It is used for secure communication over a computer network and is widely used on the Internet. In HTTPS, the communication protocol is encrypted using Transport Layer Security or, formerly, Secure Sockets Layer.

## Securing your Web Browser
Some software features that provide the functionality to a web browser, such as ActiveX, Java, Scripting (JavaScript, VBScript, etc.), may also introduce vulnerabilities to the computer system. These vulnerabilities may stem from poor implementation, poor design, or an insecure configuration. It would help if you understood which browsers support which features and the risks they could introduce for these reasons. Some web browsers permit you to fully disable the use of these technologies, while others may help you to enable features on a per-site basis.
This section provides links that show you how to configure a few of the most popular web browsers securely and disable features that can cause vulnerabilities. We encourage you to visit the vendor's website for each browser you use to learn more. If a vendor does not provide documentation on securing the browser, we encourage you to contact the vendor and request more information.
People may install multiple web browsers on your computer. Other software applications on your computer, such as email clients or document viewers, may use a different browser than the one you usually use to access the Web. Also, certain file types may be configured to open with a different web browser. Using one web browser to interact with websites manually does not mean other applications will automatically use the same browser. For this reason, it is essential to securely configure each web browser that it may install on your computer. One advantage of having multiple web browsers is that one browser can be used for only sensitive activities such as online banking. It can use the other for general purpose web browsing. Using multiple browsers can minimize the chances of using a vulnerability in a particular web browser, website, or related software to compromise sensitive information.
Web browsers are frequently updated. Depending on the version of your software, the features and options may move or change.
### Reasons to Secure Browser
Many users tend to click on links without considering the risks of their actions.
Web page addresses can be disguised or take you to an unexpected site.
Many web browsers are configured to provide increased functionality at the cost of decreased security.
New security vulnerabilities are often discovered after the manufacturer configures and packages the software.
Computer systems and software packages may be bundled with additional software, increasing the number of vulnerabilities it may attack.
Third-party software may not have a mechanism for receiving security updates.
Many websites require that users enable certain features or install more software, putting the computer at additional Risk.
Many users do not know how to configure their web browsers securely.
Many users are unwilling to enable or disable functionality as required to secure their web browser.

### Risk Explained
ActiveX has been plagued with various vulnerabilities and implementation issues. One problem with using ActiveX in a web browser is that it dramatically increases the attack surface, or "attack ability," of a system. Installing any Windows application introduces the possibility of new ActiveX controls being established. Vulnerabilities in ActiveX objects may be exploited via Internet Explorer, even if the thing was never designed to be used in a web browser (VU#680526). In 2000, the CERT/CC held a workshop to analyze security in ActiveX. It may view the results from that workshop at http://www.cert.org/reports/activeX_report.pdf. Many vulnerabilities concerning ActiveX controls lead to severe impacts. Often an attacker can take control of the computer. You can search the Vulnerability Notes Database for ActiveX vulnerabilities at http://www.kb.cert.org/vuls/byid?searchview&query=activex.
Java is an object-oriented programming language that can develop dynamic content for websites. A Java Virtual Machine, or JVM, is used to execute the Java code, or "applet," provided by the website. Some operating systems come with a JVM, while others require a JVM to be installed before using Java. Java applets are operating system independent.
Java applets usually execute within a "sandbox" where the interaction with the rest of the system is limited. However, various implementations of the JVM contain vulnerabilities that allow an applet to bypass these restrictions. Signed Java applets can also bypass sandbox restrictions, but they generally prompt the user before executing. You can search the Vulnerability Notes Database for Java vulnerabilities at http://www.kb.cert.org/vuls/byid?searchview&query=java.
Plug-ins are applications intended for use in the web browser. Plug-ins are similar to ActiveX controls but cannot be executed outside a web browser. Netscape has developed the NPAPI standard for developing plug-ins, but this standard is used by multiple web browsers, including Mozilla Firefox and Safari. Adobe Flash is an example of an application available as a plug-in.
Plug-ins can contain programming flaws such as buffer overflows, or they may have design flaws such as cross-domain violations, which arise when the same-origin policy is not followed.
Cookies are files placed on your system to store data for specific websites. A cookie can contain any information that a website is designed to put in it. Cookies may collect information about the sites you visited or may even have credentials for accessing the site. Cookies are designed to be readable only by the website that created the cookie. Session cookies are cleared when the browser is closed, and persistent cookies will remain on the computer until the specified expiration date is reached.
Cookies can be used to uniquely identify visitors of a website, which some people consider a violation of privacy. If a website uses cookies for authentication, then an attacker may acquire unauthorized access to that site by obtaining the cookie. Persistent cookies pose a higher risk than session cookies because they remain on the computer longer.
JavaScript, also known as ECMAScript, is a scripting language that is used to make websites more interactive. There are specifications in the JavaScript standard that restrict certain features, such as accessing local files.
VBScript is another scripting language that is unique to Microsoft Windows Internet Explorer. VBScript is similar to JavaScript, but it is not as widely used in websites because of limited compatibility with other browsers.


## Internet Programming

### World Wide Web Consortium
W3C is led by Tim Berners-Lee, inventor of the World Wide Web and Director, and Dr. Jeffrey Jaffe, W3C CEO. They are supported by a staff of technical experts who help coordinate technology development and manage the operations of the Consortium.
W3C Evangelists represent W3C in various locations and extend W3C's Business Development Team. They are responsible for identifying and recruiting new W3C Members, running local events, promoting W3C Training, and fostering Sponsorship. An Evangelist may cover all W3C technologies in a particular geographic region or be responsible for a specific Vertical Industry within the assigned geography.
The Advisory Committee, composed of one representative from each W3C Member. The Advisory Committee has several review roles in the W3C Process, and they elect the Advisory Board and TAG.

### HTML5 and CSS
HTML stands for HyperText Markup Language
HTML is the standard markup language for creating Web pages
HTML describes the structure of a Web page
HTML consists of a series of elements
HTML elements tell the browser how to display the content
HTML elements label pieces of content such as "this is a heading," "this is a paragraph," "this is a link," etc.
### HTML and XML
XML (Extensible Markup Language) is a markup language similar to HTML but without predefined tags to use. Instead, you define your tags explicitly designed for your needs. This is a powerful way to store data in a format that can be stored, searched, and shared.
## Components of a URL
The four main components of URLs are the protocol, domain, path, and query.
## Conclusion
In this chapter, I have learned more about internet architecture, HTML5 and CSS, and finally, URLs and file paths.  
