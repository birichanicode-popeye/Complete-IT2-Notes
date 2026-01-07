
# **IT 2 Lecture Notes**

---

## **1. Introduction to the Internet**

### **1.1 Definition of the Internet**

The Internet is a global system of interconnected computer networks using **TCP/IP (Transmission Control Protocol / Internet Protocol)**. It enables billions of devices worldwide to exchange data reliably and efficiently.

**Uses:**

* Communication
* Information sharing
* Data transfer
* Access to websites, email, cloud platforms

**Reference:** [Internet Society – Brief History of the Internet](https://www.internetsociety.org/internet/history-internet/brief-history-internet/)

---

### **1.2 Brief History of the Internet**

* **1960s:** ARPANET by US Department of Defense for reliable communication
* **1980s:** TCP/IP standardization connected networks globally
* **1990s:** Tim Berners-Lee created the **World Wide Web (WWW)**
* **2000s-Present:** Expansion to social media, cloud computing, e-learning, mobile internet

**References:**

* [Britannica – Internet](https://www.britannica.com/topic/Internet)
* [CERN – Birth of the Web](https://home.cern/science/computing/birth-web)

---

### **1.3 Importance of the Internet**

* Supports education and research via online libraries, journals, databases
* Enables real-time global communication via email, video calls, messaging
* Supports e-commerce, cloud storage, collaborative tools
* Critical for science students: virtual labs, bioinformatics, research sharing

**References:**

* [UNESCO – Digital Education](https://www.unesco.org/en/digital-education)
* [NCBI](https://www.ncbi.nlm.nih.gov/)

---

### **1.4 Internet vs World Wide Web (WWW)**

| Feature    | Internet                            | WWW                         |
| ---------- | ----------------------------------- | --------------------------- |
| Definition | Network infrastructure              | Service on internet         |
| Components | Routers, servers, cables, protocols | Web pages, hyperlinks       |
| Services   | Email, FTP, VoIP, Streaming         | Web browsing via HTTP/HTTPS |

**Reference:** [W3 – FAQ by Tim Berners-Lee](https://www.w3.org/People/Berners-Lee/FAQ.html)

---

### **1.5 Internet Services**

* **Email:** Sending/receiving messages
* **WWW:** Accessing web pages
* **File Transfer:** FTP, cloud storage
* **Communication:** VoIP, chat applications
* **Streaming:** Audio and video content

**Reference:** [Cloudflare – Internet Learning](https://www.cloudflare.com/learning/)

---

### **1.6 How the Internet Works**

1. Enter a URL in browser
2. DNS converts domain name to IP
3. Browser sends request via TCP/IP
4. Server processes request
5. Data returned and displayed

**Reference:** [Cloudflare – What is DNS?](https://www.cloudflare.com/learning/dns/what-is-dns/)

---

### **1.7 Internet Protocols**

| Protocol   | Function                              |
| ---------- | ------------------------------------- |
| HTTP/HTTPS | Web communication                     |
| TCP/IP     | Core data transmission                |
| FTP/SFTP   | File transfer                         |
| SMTP       | Sending emails                        |
| POP3/IMAP  | Receiving emails                      |
| DNS        | Resolves domain names to IP addresses |

**Reference:** [IBM – Network Protocols](https://www.ibm.com/topics/network-protocols)

---

### **1.8 IP Addresses & Domain Names**

* **IP Address:** Unique identifier

  * IPv4: 32-bit (e.g., 192.168.1.1)
  * IPv6: 128-bit (e.g., 2001:db8::1)
* **Domain Name:** Human-readable address mapped via DNS

  * Example: `www.jkuat.ac.ke` → IP

**Reference:** [ICANN – IP Address](https://www.icann.org/resources/pages/what-is-an-ip-address-2019-03-04-en)

---

### **1.9 Advantages of the Internet**

* Fast global communication
* Access to vast information
* Supports collaboration across borders
* Cost-effective data sharing

---

### **1.10 Challenges & Risks**

* Cybersecurity threats (hacking, malware)
* Data privacy concerns
* Spread of misinformation
* Over-dependence may affect productivity

**References:**

* [Kaspersky Resource Center](https://www.kaspersky.com/resource-center)
* [World Economic Forum – Cybersecurity](https://www.weforum.org/topics/cybersecurity/)

---

## **2. Introduction to Networking**

### **2.1 Definition of a Network**

A **network** is a collection of interconnected devices that communicate to share **resources** (files, internet, printers).

**Purpose:**

* Device communication
* Resource sharing
* Centralized data management
* Remote access

**Reference:** [StackOverflow – Computer Network](https://stackoverflow.com/)

---

### **2.2 Types of Networks**

| Network Type | Description      | Advantages                    | Examples            |
| ------------ | ---------------- | ----------------------------- | ------------------- |
| LAN          | Local area       | High speed, low cost          | School lab, office  |
| WAN          | Wide area        | Supports global communication | Internet            |
| MAN          | City/campus      | High-speed connections        | University campuses |
| PAN          | Personal devices | Convenient sharing            | Bluetooth, USB      |
| WLAN         | Wireless LAN     | Mobility, flexibility         | Wi-Fi in offices    |

---

### **2.3 Network Topologies**

* **Bus:** Single cable, simple, low cost, but single point of failure
* **Star:** Central hub, scalable, hub failure affects network
* **Ring:** Closed loop, data flows one way, single failure disrupts
* **Mesh:** Every device connected to every other, reliable, expensive
* **Hybrid:** Combination of topologies

---

### **2.4 Networking Devices**

| Device       | Function                       | Example          |
| ------------ | ------------------------------ | ---------------- |
| Router       | Connects networks using IP     | Home router      |
| Switch       | Connects LAN devices using MAC | Office switch    |
| Hub          | Broadcasts data                | Small office hub |
| NIC          | Connects device to network     | Ethernet card    |
| Access Point | Wireless connectivity          | Wi-Fi AP         |
| Firewall     | Monitors/controls traffic      | Cisco ASA        |

---

### **2.5 Network Models**

* **Client-Server:** Centralized resources; examples: email, database servers
* **Peer-to-Peer:** Equal devices; example: BitTorrent

---

### **2.6 Network Protocols**

| Protocol       | Function              | Layer                |
| -------------- | --------------------- | -------------------- |
| TCP/IP         | Reliable transmission | Transport & Internet |
| UDP            | Fast, connectionless  | Transport            |
| HTTP/HTTPS     | Web communication     | Application          |
| FTP/SFTP       | File transfer         | Application          |
| SMTP/POP3/IMAP | Email                 | Application          |
| DNS            | Resolves domains      | Application          |

---

### **2.7 OSI Model**

| Layer           | Function                    | Example          |
| --------------- | --------------------------- | ---------------- |
| 7. Application  | User services               | HTTP, FTP, Email |
| 6. Presentation | Data encryption/translation | SSL/TLS          |
| 5. Session      | Session management          | NetBIOS, RPC     |
| 4. Transport    | End-to-end delivery         | TCP, UDP         |
| 3. Network      | Routing via IP              | IP, ICMP         |
| 2. Data Link    | MAC addressing              | Ethernet, PPP    |
| 1. Physical     | Transmission of bits        | Cables, Wi-Fi    |

---

### **2.8 Advantages of Networking**

* Resource sharing
* Centralized management
* Remote access & collaboration
* Efficient communication

---

### **2.9 Common Networking Issues**

* Downtime: Hardware failure, misconfiguration
* Latency: Transmission delays
* Packet Loss: Congestion, faulty devices

**Solutions:** Upgrade hardware, increase bandwidth, load balancing, regular maintenance

**References:**

* [Cisco – Networking Fundamentals](https://www.cisco.com/c/en/us/solutions/small-business/resource-center/networking/networking-basics.html)
* [GeeksforGeeks – OSI Model](https://www.geeksforgeeks.org/layers-of-osi-model/)

---

## **3. Web Development**

### **3.1 Definition**

Building and maintaining websites or web applications accessible over the internet. Includes web design, content creation, client-side & server-side scripting, networking.

---

### **3.2 Types**

* **Front-end:** User interface/UX; HTML, CSS, JavaScript
* **Back-end:** Server logic, database; Node.js, Python, PHP, Java
* **Full-stack:** Combination of front-end & back-end

---

### **3.3 HTML (HyperText Markup Language)**

* Standard language for web pages
* Key elements: `<h1>`-`<h6>`, `<p>`, `<ul>/<ol>/<li>`, `<table>`, `<a>`

**Reference:** [MDN – HTML Basics](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML)

---

### **3.4 CSS (Cascading Style Sheets)**

* Styles HTML content: layout, colors, fonts
* Types: Inline, Internal, External
* Example:

```css
body { font-family: Arial; background-color: #f0f0f0; }
table { border-collapse: collapse; }
```

**Reference:** [CSS-Tricks – CSS Basics](https://css-tricks.com/)

---

### **3.5 JavaScript**

* Adds interactivity
* Examples: form validation, dynamic content

```javascript
document.getElementById("btn").onclick = function() {
    alert("Button clicked!");
}
```

**Reference:** [MDN – JavaScript Guide](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide)

---

### **3.6 Dynamic vs Static Websites**

| Type    | Definition                   | Example                   |
| ------- | ---------------------------- | ------------------------- |
| Static  | Fixed content                | Personal portfolio        |
| Dynamic | Content generated on-the-fly | Online learning platforms |

---

### **3.7 Responsive Design**

* Web pages adjust to all device sizes
* Techniques: Media queries, flexible grids, fluid images
  **Reference:** [W3Schools – Responsive Design](https://www.w3schools.com/css/css_rwd_intro.asp)

---

## **4. Cybersecurity**

### **4.1 Definition**

Protection of computer systems, networks, and data from theft, damage, or unauthorized access

---

### **4.2 Types of Cyber Threats**

* Malware (viruses, worms, trojans)
* Phishing attacks
* Denial of Service (DoS)
* Man-in-the-middle attacks

---

### **4.3 Security Measures**

* Firewalls, antivirus software
* Strong passwords, multi-factor authentication
* Secure coding practices
* HTTPS & SSL/TLS

**Reference:** [OWASP – Top Ten Security Risks](https://owasp.org/)

---

## **5. Cloud Computing**

### **5.1 Definition**

Delivery of computing services (servers, storage, databases, networking, software) over the internet

---

### **5.2 Types**

* **IaaS:** Virtual servers & storage (AWS EC2)
* **PaaS:** Platform for applications (Heroku)
* **SaaS:** Hosted software online (Google Workspace)

---

### **5.3 Advantages**

* Scalability
* Cost savings
* Remote access
* Automatic updates

**Reference:** [IBM – Cloud Computing Basics](https://www.ibm.com/topics/cloud-computing)

---

## **6. Internet & Online Services**

### **6.1 Key Services**

* Email (SMTP, IMAP, POP3)
* WWW (HTTP/HTTPS)
* Cloud Storage (Google Drive, Dropbox)

---

### **6.2 Safety Measures**

* Strong, unique passwords
* Enable 2FA
* Keep software updated
* Avoid suspicious links

---

## **7. JavaScript Form Validation**

**Definition:** Checks form inputs before submission

```javascript
function validateForm() {
    var name = document.forms["myForm"]["name"].value;
    if (name == "") {
        alert("Name must be filled out");
        return false;
    }
}
```

**Reference:** [StackOverflow – JS Form Validation](https://stackoverflow.com/questions/tagged/javascript+form-validation)

---

## **8. Networking Protocols (Summary)**

| Protocol       | Function                      |
| -------------- | ----------------------------- |
| TCP/IP         | Reliable, connection-oriented |
| UDP            | Fast, connectionless          |
| HTTP/HTTPS     | Web communication             |
| FTP/SFTP       | File transfers                |
| SMTP/IMAP/POP3 | Email                         |
| DNS            | Domain resolution             |

---

## **9. References / Further Reading**

* [StackOverflow – Networking](https://stackoverflow.com/)
* [MDN – HTML, CSS, JS](https://developer.mozilla.org/)
* [OWASP – Cybersecurity](https://owasp.org/)
* [IBM – Cloud Computing](https://www.ibm.com/topics/cloud-computing)
* [GeeksforGeeks – OSI Model](https://www.geeksforgeeks.org/layers-of-osi-model/)
* [Cisco – Networking Fundamentals](https://www.cisco.com/c/en/us/solutions/small-business/resource-center/networking/networking-basics.html)

---
