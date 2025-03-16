# cisco-cybersecurity-basics
Notes and labs from my introduction to Cybersecurity course with Cisco, covering foundational cybersecurity principals.

<div data-iframe-width="150" data-iframe-height="270" data-share-badge-id="901e8e05-1092-4b94-aa28-e14877b25958" data-share-badge-host="https://www.credly.com"></div><script type="text/javascript" async src="//cdn.credly.com/assets/utilities/embed.js"></script>

# What is Cybersecurity?

Is the ongoing effort to protect individuals, organisations and governments from digital attacks by protecting networked systems and data from unorthorised use or harm.

# Types of Malware

Malware is any code that can be used to steal data, bypass access controls, or cause harm to or compromise a system.

- Spyware
- Adware
- Backdoor
- Ransomeware
- Scareware
- Rootkit
- Virus
- Trojan Horse
- Worms

# Methods of Infiltration

1. Social engineering
   - Pretexting
   - Tailgating
   - Something for Something (quid pro Quo)
2. Denial of Services (DoS Attack)
   - Overwhelming Quantity of traffic
   - Maliciously Formatted Packets
3. Distributed (DoS)
4. Botnet
5. On-Path Attacks
   - Man in the Middle (MITM)
   - Man in the Mobile (MITMO)
6. SEO Poisoning
7. Wifi-Password Cracking

# Security Vunerability and Exploits
Security vulnerabilities are any kind of software or hardware defect. A program written to take advantage of a known vulnerability is referred to as an exploit.

- Hardware Vunerablities
- Software Vunerabilities: Usually introduced by errors in the operating system or application code.
  - Buffer Overflow
  - Non-Validated Input
  - Race Condition
  - Weakness in Security Practices
  - Access Control Problems
    
# Cybersecurity Landscape

Cryptocurrency:- Cryptocurrency is digital money that can be used to buy goods and services, using strong encryption techniques to secure online transactions.

Cryptojacking:- Cryptojacking is an emerging threat that hides on a user’s computer, mobile phone, tablet, laptop or server, using that machine’s resources to 'mine’ cryptocurrencies without the user's consent or knowledge.

# Proctecting Your Computing Devices and Network

1. Protecting your Computing Devices

- Turn on Firewall
- Install Antivirus and Spyware
- Manage your Operationg System and Browser
- Set Up Password Protection

2. Wireless Security Network at Home
   
  Wireless networks allow Wi-Fi enabled devices, such as laptops and tablets, to connect to the network by way of a preset network identifier, known as the 
  service 
  set identifier (SSID). Although a wireless router can be configured so that it doesn’t broadcast the SSID, this should not be considered adequate security for a 
  wireless network.

  Hackers will be aware of the preset SSID and default password. Therefore, these details should be changed to prevent intruders from entering your home wireless 
  network. Furthermore, you should encrypt wireless communication by enabling wireless security and the WPA2 encryption feature on your wireless router. But be 
  aware, even with WPA2 encryption enabled, a wireless network can still be vulnerable.

  - Key Reinstallation Attacks:- An attacker within range of a victim can exploit these weaknesses using key reinstallation attacks (KRACKs). Concretely, 
    attackers can use this novel attack technique to read information that was previously assumed to be safely encrypted. This can be abused to steal sensitive 
    information such as credit card numbers, passwords, chat messages, emails, photos, and so on. The attack works against all modern protected Wi-Fi networks.

  To make the situation less Severe, the following steps should be taken:
  - Update all wireless devices as soon as updates become available.
  - Use a wired connection for any devices with a Network Interface Card (NIC)
  - Use trusted Virtual Private Network (VPN) when accessing any wifi

# What is Encryption?

Encryption is the process of converting information into a form in which unauthorized parties cannot read it. Only a trusted, authorized person with the secret key or password can decrypt the data and access it in its original form.

# Behaviour-based Security

Behavior-based security is a form of threat detection that involves capturing and analyzing the flow of communication between a user on the local network and a local or remote destination. Any changes in normal patterns of behavior are regarded as anomalies, and may indicate an attack.

*Honeypots:-* Behaviour-based detection tool, lures an attacker in by appealing to their predicted pattern of malicous behaviour. Once the attakcer is inside the 
honeypot, the network administrator can capture, log and analyse their behaviour so that they can build a better defense.

*Cisco's cyber threat defense solution Architecture:-* This security architechture uses behaviour based detection and indicators to provide greater visibility, context and control. The aim is to know who is carrying our the attack, what type of attack they're performing and where, when and how the attack is taking place.

# Netflow

NetFlow technology is used to gather information about data flowing through a network, including who and what devices are in the network, and when and how users and devices access the network.

# Penetration Testing 

Penetration testing, commonly known as pen testing, is the act of assessing a computer system, network or organization for security vulnerabilities. A pen test seeks to breach systems, people, processes and code to uncover vulnerabilities which could be exploited. This information is then used to improve the system’s defenses to ensure that it is better able to withstand cyber attacks in the future.

   - Planning
   - Scanning
   - Gaining Access
   - Maintaining Access
   - Analysis and Reporting

# Risk Management 

Risk management is the formal process of continuously identifying and assessing risk in an effort to reduce the impact of threats and vulnerabilities. You cannot eliminate risk completely but you can determine acceptable levels by weighing up the impact of a threat with the cost of implementing controls to mitigate it. The cost of a control should never be more than the value of the asset you are protecting.

   - Frame
   - Assess
   - Respond
   - Monitor

# Tools for incident detection

SIEM:- Security Information and event Management collects and analyses secuirty alerts, logs and other real-time historical data from security devices on the network to facilitate early detection of cyber attacks.

DLP:- Data Loss Prevention is a system design to stop sensitive data from being stolen from or escaping a network.
      It monitors data in 3 different states:
      - Data in Use:- Data being accessed by User
      - Data in Motion:- Data travelling through the network
      - Data at Rest:- Data stored in a computer network or device

# Cisco'c ISE and TrustSec

Cisco Identity Services Engine (ISE) and TrustSec enforce user access to network resources by creating role-based access control policies.
