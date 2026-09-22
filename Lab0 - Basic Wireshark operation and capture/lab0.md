# 1. Website packet capture

### Which website did you access?

- https://e-campus.enac.fr/moodle/login/index.php

### What are the IP address and port number of the website server?

- IP adress: 195.220.158.133
- Port: 443

### What are the IP address and source port number of your PC when initially accessing the website?

- IP adress: 10.119.181.99
- Port: 63078

### What is the process of the TCP three-way handshake?

1. SYN: the client sends a synchronize packet to the server
2. SYN, ACK: the server answers with a synchronise packet sent along with an acknowledgement of reception of the first SYN packet. 
3. ACK: the client acknowledges the server's SYN packet. Connection is established.

<img width="1101" height="91" alt="Capture d’écran 2026-09-22 à 13 47 16" src="https://github.com/user-attachments/assets/7730c004-92d2-4d82-8404-b2af116b231c" />

# 2. DNS Packet analysis

I switched websites to use https://fr.wikipedia.org. 

### What are the IP address and port number of the DNS server?

- IP adress: 168.95.1.1
- Port: 53

### What is the domain name in the DNS query?

- fr.wikipedia.org

### Which protocols does this DNS packet use? List the protocols from Layer 2 to Layer 5 in the TCP/IP five-layer model:

<img width="1124" height="75" alt="Capture d’écran 2026-09-22 à 14 02 53" src="https://github.com/user-attachments/assets/22213b1b-56b6-4d01-bb54-b0b3f843943a" />

- **Layer 2** (Link): Ethernet II
- **Layer 3** (Network): IPv4 (Internet Protocol Version 4)
- **Layer 4** (Transport): UDP (User Datagram Protocol)
- **Layer 5** (Application): DNS (Domain Name System)

# 3. Access an HTTP page

### Which HTTP page did you access?

- For this section, we will use the website: http://www.gzxyzn.com/Article/bjrk2/1644.html

### What are the IP address and port number of the server hosting the page?

- IP adress: 61.183.8.129
- Port: 80

<img width="1254" height="978" alt="Capture d’écran 2026-09-22 à 14 09 55" src="https://github.com/user-attachments/assets/3f3aa3f3-1190-41e1-b426-a895b7378bfb" />

### What is the HTTP request method?

- HTTP uses the GET request method.

<img width="1254" height="978" alt="Capture d’écran 2026-09-22 à 14 13 22" src="https://github.com/user-attachments/assets/58601126-f124-4605-a2f8-ebcf6e765ba1" />

### What is the HTTP response status code, and what does it mean?

- The response status code is 200 OK. It means that the request succeeded and the server correctly returned the webpage. 

<img width="1254" height="978" alt="Capture d’écran 2026-09-22 à 14 14 15" src="https://github.com/user-attachments/assets/9dded3b6-dfc1-422a-88c1-0cf163e301e2" />

