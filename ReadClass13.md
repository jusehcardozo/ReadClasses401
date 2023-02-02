Jose Cardozo
02/01/2023

https://www.cloudflare.com/learning/cdn/glossary/reverse-proxy/

What is a reverse proxy?
A reverse proxy is a server that sits in front of web servers and forwards client (e.g. web browser) requests to those web servers. Reverse proxies are typically implemented to help increase security, performance, and reliability. In order to better understand how a reverse proxy works and the benefits it can provide, let’s first define what a proxy server is.

What is a proxy server?
A forward proxy, often called a proxy, proxy server, or web proxy, is a server that sits in front of a group of client machines. When those computers make requests to sites and services on the Internet, the proxy server intercepts those requests and then communicates with web servers on behalf of those clients, like a middleman.

For example, let’s name 3 computers involved in a typical forward proxy communication:

A: This is a user’s home computer
B: This is a forward proxy server
C: This is a website’s origin server (where the website data is stored)

How is a reverse proxy different?
A reverse proxy is a server that sits in front of one or more web servers, intercepting requests from clients. This is different from a forward proxy, where the proxy sits in front of the clients. With a reverse proxy, when clients send requests to the origin server of a website, those requests are intercepted at the network edge by the reverse proxy server. The reverse proxy server will then send requests to and receive responses from the origin server.

The difference between a forward and reverse proxy is subtle but important. A simplified way to sum it up would be to say that a forward proxy sits in front of a client and ensures that no origin server ever communicates directly with that specific client. On the other hand, a reverse proxy sits in front of an origin server and ensures that no client ever communicates directly with that origin server.


Operationalize Ransomware Detections Quickly and Easily with Splunk

According to a report from Emisoft, 113 State and municipal governments and agencies, 764 healthcare providers, and 1233 individual educational environments were affected by ransomware in 2019. While this certainly inconvenienced each organization, the impact on healthcare providers had real consequences, often with life or death implications. Doctors lost access to vital information as patients' records were unavailable, and surgical procedures were either postponed or moved to other hospitals.

For some organizations, paying the ransom was more cost efficient than restoring from backups (if restoration from backups was even possible).  Some question if paying the requested ransom is even legal, and we’re seeing legislation being introduced to specifically prohibit ransomware payments. 

Further complicating the landscape is the increasingly nefarious nature of the most recent strains detected. It's no longer just about simply encrypting files. Now ransomware operators have added a spoliation phase, which effectively destroys an organization’s capability to use the Windows System Restore capability, making restoration a much larger endeavor. If that's not enough, sensitive files are also being exfiltrated and publicly released if the ransom is not paid quickly.

There are 35 ransomware use cases provided with the ES Content updates. In the interest of brevity, we’ll highlight one — Deleting Shadow Copies. The newer ransomware strains go to great lengths to ensure Windows victims have little choice when faced with paying a ransom demand. As part of the spoliation phase of the attack, ransomware leverages the Windows utility vssadmin.exe to delete Shadow Volume Copies so they can’t be used to recover files. Detecting this activity quickly provides an opportunity to interrupt the ransomware kill chain, saving your data from being held hostage, or leaked.
