# Course 7: Cybersecurity & Ethical Hacking Fundamentals

## Course Description

This course provides a foundational understanding of cybersecurity principles and an introduction to the world of ethical hacking. It is designed for individuals looking to start a career in cybersecurity, IT professionals wanting to broaden their security knowledge, or anyone interested in learning how to protect digital assets and understand common cyber threats. We will cover core cybersecurity concepts, threat landscapes, network and web application security, cryptography, and the methodologies used by ethical hackers to identify and mitigate vulnerabilities.

## Prerequisites

*   Basic understanding of computer systems and networks.
*   Familiarity with common operating systems (Windows, Linux).
*   Strong desire to learn and a commitment to ethical conduct.
*   No prior cybersecurity or hacking experience is required.

## Course Outline

### Module 1: Introduction to Cybersecurity (Expanded)

This module introduces the fundamental concepts of cybersecurity, its importance, the common terminology used in the field, and the ethical and legal landscape, now with expanded detail.

*   **Lesson 1.1: Defining Cybersecurity - The Scope and Importance**
    *   What is Cybersecurity? The practice of protecting systems, networks, programs, devices, and data from cyber-attacks, damage, or unauthorized access.
    *   Why is Cybersecurity Critically Important Today?
        *   Increasing reliance on digital systems in all aspects of life (personal, business, government).
        *   Growth of interconnected devices (IoT).
        *   Value of data (personal, financial, intellectual property).
        *   Sophistication and frequency of cyber threats.
        *   Potential impact of breaches (financial loss, reputational damage, operational disruption, national security).
    *   The broad scope of cybersecurity: technical measures, processes, policies, user education, legal frameworks.
    *   <YouTube videoId="oNq1dSkDyjI" title="What is Cybersecurity? by SANS Institute" /> (Recap)
    *   <YouTube videoId_ THE_IMPORTANCE_OF_CYBERSECURITY_IN_THE_DIGITAL_AGE_by_TED_Talks title="The Importance of Cybersecurity in the Digital Age by TED Talks" /> (Placeholder - look for a relevant TED talk)

*   **Lesson 1.2: The CIA Triad - Confidentiality, Integrity, Availability**
    *   The foundational model for information security.
    *   **Confidentiality:** Ensuring that information is not disclosed to unauthorized individuals, entities, or processes.
        *   Mechanisms: Encryption, access controls, authentication, data classification.
        *   Breaches: Data theft, eavesdropping.
    *   **Integrity:** Maintaining the accuracy, consistency, and trustworthiness of data over its entire lifecycle. Data should not be improperly modified (unauthorized or accidental).
        *   Mechanisms: Hashing, digital signatures, version control, input validation, audit trails.
        *   Breaches: Data tampering, unauthorized modification.
    *   **Availability:** Ensuring that systems, applications, and data are accessible to authorized users when needed.
        *   Mechanisms: Redundancy (servers, networks, storage), backups, disaster recovery plans, DoS/DDoS protection.
        *   Breaches: Denial of Service attacks, hardware failures, natural disasters.
    *   Understanding the balance and potential conflicts between these three principles.
    *   <YouTube videoId="inWWhr5tnEA" title="The CIA Triad - CompTIA Security+ SY0-601 by Professor Messer" /> (Recap)
    *   <YouTube videoId_ CONFIDENTIALITY_INTEGRITY_AVAILABILITY_REAL_WORLD_EXAMPLES_by_Cybrary title="Confidentiality, Integrity, Availability: Real World Examples by Cybrary" /> (Placeholder)

*   **Lesson 1.3: Extending Security Principles - The Parkerian Hexad & Other Concepts**
    *   **The Parkerian Hexad:** An alternative/extension to the CIA Triad, proposed by Donn Parker, adding:
        *   **Possession or Control:** Having physical control over the media on which data is stored.
        *   **Authenticity:** Verifying that data is genuine and from a legitimate source, and that users are who they claim to be.
        *   **Utility:** Ensuring that data is useful and serves its purpose.
    *   **Non-Repudiation:** Ensuring that a party cannot deny having sent or received a message or performed an action. Achieved through digital signatures, audit logs.
    *   **Accountability:** The ability to trace actions performed on a system to a specific entity (user or process).
    *   **Least Privilege:** Granting users and processes only the minimum necessary access rights and permissions required to perform their job functions.
    *   **Defense in Depth:** Layering multiple security controls so that if one fails, others are still in place.
    *   <YouTube videoId_ THE_PARKERIAN_HEXAD_BEYOND_CIA_TRIAD_by_Security_Now_Steve_Gibson title="The Parkerian Hexad: Beyond CIA Triad by Security Now (Steve Gibson)" /> (Placeholder - Steve Gibson often covers these concepts)
    *   <YouTube videoId_ PRINCIPLE_OF_LEAST_PRIVILEGE_EXPLAINED_by_SANS_Institute title="Principle of Least Privilege Explained by SANS Institute" /> (Placeholder)

*   **Lesson 1.4: Key Cybersecurity Terminology - Threats, Vulnerabilities, Risks, Exploits**
    *   **Asset:** Anything of value to an organization (data, hardware, software, reputation, intellectual property).
    *   **Threat:** Any potential danger or event that could harm an asset by exploiting a vulnerability. Can be natural, accidental, or intentional.
    *   **Vulnerability:** A weakness or flaw in a system, application, design, or process that can be exploited by a threat.
    *   **Risk:** The likelihood (probability) of a threat exploiting a vulnerability, and the resulting impact or damage. Risk = Likelihood * Impact.
    *   **Exploit:** A piece of software, data, or sequence of commands that takes advantage of a bug or vulnerability to cause unintended or unanticipated behavior on computer software or hardware.
    *   **Attack Vector:** The path or means by which an attacker can gain access to a computer or network server in order to deliver a payload or malicious outcome.
    *   **Attack Surface:** The sum of the different points (attack vectors) where an unauthorized user (the attacker) can try to enter data or extract data from an environment.
    *   **Countermeasure/Control:** A safeguard or action taken to reduce risk by mitigating a threat or reducing a vulnerability.
    *   <YouTube videoId_ THREAT_VS_VULNERABILITY_VS_RISK_EXPLAINED_by_Professor_Messer title="Threat vs Vulnerability vs Risk Explained by Professor Messer" /> (Placeholder)
    *   <YouTube videoId_ UNDERSTANDING_CYBERSECURITY_ATTACK_VECTORS_AND_SURFACES_by_Cybrary title="Understanding Cybersecurity Attack Vectors and Surfaces by Cybrary" /> (Placeholder)

*   **Lesson 1.5: Threat Actors - Who Are the Attackers?**
    *   **Cybercriminals:** Motivated by financial gain. Engage in activities like ransomware, data theft for sale, phishing, credit card fraud. Can be individuals or organized crime groups.
    *   **Hacktivists:** Motivated by political, social, or ideological causes. Use hacking techniques to promote their agenda, deface websites, leak data, or disrupt services (e.g., Anonymous).
    *   **State-Sponsored Actors / Advanced Persistent Threats (APTs):** Sponsored by national governments. Highly sophisticated, well-funded, target specific entities for espionage, sabotage, or intelligence gathering. Long-term campaigns.
    *   **Insider Threats:** Individuals within an organization (employees, contractors, partners) who pose a threat.
        *   Malicious Insiders: Intentionally steal data, sabotage systems.
        *   Negligent/Accidental Insiders: Unintentionally cause harm through errors, carelessness, or falling victim to social engineering.
    *   **Script Kiddies:** Less skilled individuals who use existing tools, scripts, and exploits created by others to launch attacks. Often motivated by curiosity, bragging rights, or causing mischief.
    *   **Terrorist Groups:** May use cyberattacks to disrupt critical infrastructure, spread propaganda, or fund activities.
    *   **Competitors (Corporate Espionage):** Seeking to gain an advantage by stealing trade secrets or intellectual property.
    *   <YouTube videoId="au4g4t0h7gM" title="Types of Hackers & What They Do by Computerphile" /> (Recap)
    *   <YouTube videoId_ UNDERSTANDING_ADVANCED_PERSISTENT_THREATS_APTS_by_Mandiant title="Understanding Advanced Persistent Threats (APTs) by Mandiant" /> (Placeholder)

*   **Lesson 1.6: Common Cyber Threats - Malware (Viruses, Worms, Trojans, Ransomware)**
    *   **Malware (Malicious Software):** Any software intentionally designed to cause damage to a computer, server, client, or computer network.
    *   **Viruses:** Malicious code that attaches itself to legitimate programs or files. Requires user action (e.g., opening an infected file) to execute and spread.
    *   **Worms:** Self-replicating malware that can spread across networks automatically without user intervention, exploiting vulnerabilities.
    *   **Trojans (Trojan Horses):** Disguise as legitimate or useful software but contain a hidden malicious payload. Can create backdoors, steal data, or install other malware.
    *   **Ransomware:** Encrypts a victim's files or entire system, making them inaccessible. Attackers demand a ransom payment (usually in cryptocurrency) for the decryption key.
        *   Examples: WannaCry, Ryuk, Conti.
    *   **Spyware:** Secretly gathers information about a user's activities (keystrokes, browsing history, credentials) and transmits it to an attacker.
    *   **Adware:** Displays unwanted advertisements, often aggressively, and may track user behavior for targeted ads.
    *   **Rootkits:** Designed to gain privileged (root/admin) access to a system and hide their presence and malicious activities from detection.
    *   **Keyloggers:** Record every keystroke made by a user, capturing passwords, messages, etc.
    *   **Bots/Botnets:** A network of compromised computers (bots or zombies) controlled remotely by an attacker (botmaster). Used for DDoS attacks, spamming, click fraud, crypto mining.
    *   <YouTube videoId="YOFgArHzIuA" title="Common Types of Cyber Attacks by PowerCert Animated Videos" /> (Recap malware section)
    *   <YouTube videoId_ RANSOMWARE_EXPLAINED_AND_HOW_TO_PROTECT_YOURSELF_by_Kaspersky title="Ransomware Explained and How to Protect Yourself by Kaspersky" /> (Placeholder)

*   **Lesson 1.7: Common Cyber Threats - Social Engineering and Phishing**
    *   **Social Engineering:** The art of manipulating people into performing actions or divulging confidential information. Exploits human psychology (trust, fear, curiosity, helpfulness).
    *   **Phishing:** A type of social engineering where attackers send fraudulent emails, messages, or create fake websites that appear to be from legitimate sources to trick victims into revealing sensitive information (passwords, credit card numbers, SSNs) or downloading malware.
        *   **Spear Phishing:** Highly targeted phishing attacks aimed at specific individuals or organizations, often using personalized information.
        *   **Whaling:** Spear phishing specifically targeting high-profile individuals (CEOs, CFOs, executives).
        *   **Vishing (Voice Phishing):** Phishing conducted over the phone.
        *   **Smishing (SMS Phishing):** Phishing attacks delivered via text messages.
    *   Other Social Engineering Techniques: Pretexting, Baiting, Quid Pro Quo, Tailgating.
    *   Recognizing red flags and defense mechanisms (user education, technical controls).
    *   <YouTube videoId_ SOCIAL_ENGINEERING_THE_ART_OF_HUMAN_HACKING_by_DEFCON_Talks title="Social Engineering: The Art of Human Hacking by DEFCON Talks (e.g., Chris Hadnagy)" /> (Placeholder)
    *   <YouTube videoId="tillerk2x0I" title="Social Engineering - CompTIA Security+ SY0-601 by Professor Messer" /> (Recap)

*   **Lesson 1.8: Common Cyber Threats - Network and Web-Based Attacks**
    *   **Denial of Service (DoS) / Distributed Denial of Service (DDoS):** Overwhelming a target system or network with traffic from one (DoS) or multiple (DDoS) compromised computer systems (botnet), making it unavailable to legitimate users.
    *   **Man-in-the-Middle (MitM) Attack:** Attacker secretly intercepts and possibly alters communications between two parties who believe they are directly communicating with each other. (e.g., on unsecured Wi-Fi).
    *   **SQL Injection (SQLi):** Injecting malicious SQL code into web application inputs to manipulate backend databases (steal data, modify, delete).
    *   **Cross-Site Scripting (XSS):** Injecting malicious scripts (usually JavaScript) into web pages viewed by other users, allowing attacker to execute code in victim's browser (steal session cookies, deface sites).
    *   **Zero-Day Exploits:** Attacks that exploit a previously unknown vulnerability for which no patch or fix is yet available.
    *   **Password Attacks:**
        *   Brute Force: Trying all possible password combinations.
        *   Dictionary Attack: Trying common words and phrases.
        *   Credential Stuffing: Using breached username/password pairs from one site on other sites.
    *   <YouTube videoId_ DDOS_ATTACKS_EXPLAINED_by_Cloudflare title="DDoS Attacks Explained by Cloudflare" /> (Placeholder)
    *   <YouTube videoId_ MAN_IN_THE_MIDDLE_ATTACKS_MITM_EXPLAINED_by_PowerCert_Animated_Videos title="Man-in-the-Middle Attacks (MitM) Explained by PowerCert Animated Videos" /> (Placeholder)

*   **Lesson 1.9: Introduction to Ethical Hacking and Penetration Testing**
    *   What is Ethical Hacking? Authorized, simulated cyberattacks against an organization's systems to identify vulnerabilities before malicious attackers can exploit them. Also known as penetration testing, white-hat hacking.
    *   Purpose: To evaluate the security posture of a system, network, or application and provide recommendations for improvement.
    *   Ethical Hacker vs. Malicious Hacker (Black Hat) vs. Grey Hat Hacker (may operate without permission but for non-malicious reasons or to expose vulnerabilities).
    *   Key Principles of Ethical Hacking:
        1.  **Legality & Authorization:** Always obtain explicit, written permission from the target organization before conducting any testing. Define a clear scope.
        2.  **Scope:** Clearly define what systems, networks, and applications are in scope and what actions are permitted. Stick to the scope.
        3.  **Reporting:** Thoroughly document all findings, vulnerabilities discovered, steps taken, and provide actionable recommendations for remediation.
        4.  **Do No Harm / Confidentiality:** Avoid causing damage to systems or data. Respect privacy and confidentiality of information encountered.
    *   <YouTube videoId="VympPy62wGk" title="What is Ethical Hacking? by EC-Council" /> (Recap)
    *   <YouTube videoId_ ETHICAL_HACKING_VS_PENETRATION_TESTING_WHATS_THE_DIFFERENCE_by_Cybrary title="Ethical Hacking vs Penetration Testing: What's The Difference? by Cybrary" /> (Placeholder - often used interchangeably but can have nuances)

*   **Lesson 1.10: Phases of Ethical Hacking / Penetration Testing Methodology**
    *   A structured approach is crucial for effective and ethical testing. Common phases include:
        1.  **Reconnaissance (Footprinting & Information Gathering):** Collecting as much information as possible about the target organization and its systems, both passively (OSINT - Open Source Intelligence) and actively (probing systems).
        2.  **Scanning and Enumeration:** Identifying live hosts, open ports, running services, operating systems, and potential vulnerabilities on the target network/systems.
        3.  **Gaining Access (Exploitation):** Attempting to exploit identified vulnerabilities to compromise a system or gain unauthorized access.
        4.  **Maintaining Access (Persistence):** Establishing a foothold on the compromised system for continued access, potentially escalating privileges. (Ethical hackers do this to demonstrate impact and test detection).
        5.  **Covering Tracks (Anti-Forensics - with extreme caution and permission):** Removing evidence of the penetration test activities to avoid interfering with actual incident response if a real attack occurred, or to test the organization's detection capabilities. **Must be explicitly authorized.**
        6.  **Analysis and Reporting:** Analyzing findings, assessing risk, and creating a comprehensive report with vulnerabilities and remediation recommendations.
    *   Different methodologies exist (e.g., PTES, OSSTMM, NIST SP 800-115).
    *   <YouTube videoId="WptQkSUi6oA" title="The Penetration Testing Process - CompTIA PenTest+ PT0-002 by Professor Messer" /> (Recap)
    *   <YouTube videoId_ PENETRATION_TESTING_EXECUTION_STANDARD_PTES_OVERVIEW_by_HackerSploit title="Penetration Testing Execution Standard (PTES) Overview by HackerSploit" /> (Placeholder)

*   **Lesson 1.11: Legal Frameworks in Cybersecurity (CFAA, GDPR, etc.)**
    *   Understanding the legal landscape is crucial for all IT and cybersecurity professionals.
    *   **Computer Fraud and Abuse Act (CFAA) - USA:** Federal law prohibiting unauthorized access to computer systems. Key legislation for prosecuting hacking.
    *   **General Data Protection Regulation (GDPR) - European Union:** Comprehensive data privacy law regulating the processing of personal data of EU residents. Significant fines for non-compliance. Concepts like data subject rights, consent, data breach notification.
    *   **Digital Millennium Copyright Act (DMCA) - USA:** Addresses copyright infringement, including circumvention of copy protection measures.
    *   **Health Insurance Portability and Accountability Act (HIPAA) - USA:** Protects sensitive patient health information (PHI).
    *   **Payment Card Industry Data Security Standard (PCI DSS):** Security standards for organizations that handle credit card information. Not a law, but contractual obligation.
    *   Local/National Cybercrime Laws: Vary by country, criminalizing activities like hacking, malware distribution, DoS attacks.
    *   Importance of understanding and complying with relevant laws in your jurisdiction and the jurisdictions where data resides or is processed.
    *   <YouTube videoId_ OVERVIEW_OF_KEY_CYBERSECURITY_LAWS_AND_REGULATIONS_by_SANS_Institute title="Overview of Key Cybersecurity Laws and Regulations by SANS Institute" /> (Placeholder)
    *   <YouTube videoId_ GDPR_EXPLAINED_FOR_BEGINNERS_by_The_Plain_Bagel title="GDPR Explained for Beginners by The Plain Bagel" /> (Placeholder)

*   **Lesson 1.12: Ethics in Cybersecurity and Ethical Hacking Codes of Conduct**
    *   Beyond legality, ethical behavior is paramount.
    *   Key Ethical Principles for Cybersecurity Professionals:
        *   Protect society, the common good, necessary public trust and confidence, and the infrastructure.
        *   Act honorably, honestly, justly, responsibly, and legally.
        *   Provide diligent and competent service to principals.
        *   Advance and protect the profession.
        *   (Based on (ISC)² Code of Ethics Canons).
    *   Ethical Dilemmas in Cybersecurity (e.g., discovering a vulnerability in a system you're not authorized to test, balancing security with privacy).
    *   Codes of Conduct from professional organizations:
        *   (ISC)² Code of Ethics.
        *   SANS IT Code of Ethics.
        *   EC-Council Code of Ethics (for certifications like CEH).
    *   Responsible Disclosure of Vulnerabilities: Process for reporting vulnerabilities to vendors/organizations in a way that allows them to fix it before public disclosure, minimizing harm.
    *   The potential impact of your actions as a security professional.
    *   <YouTube videoId_ ETHICS_FOR_CYBERSECURITY_PROFESSIONALS_by_Cybrary title="Ethics for Cybersecurity Professionals by Cybrary" /> (Placeholder)
    *   <YouTube videoId_ RESPONSIBLE_VULNERABILITY_DISCLOSURE_WHAT_IT_IS_AND_WHY_IT_MATTERS_by_OWASP title="Responsible Vulnerability Disclosure: What It Is and Why It Matters by OWASP" /> (Placeholder)

*   **Lesson 1.13: Setting Up Your Virtual Lab Environment - VirtualBox/VMware**
    *   Recap: Importance of an isolated lab.
    *   **Virtualization Software Options:**
        *   Oracle VM VirtualBox: Free, open-source, cross-platform. Good for beginners.
        *   VMware Workstation Player (Windows/Linux): Free for personal use.
        *   VMware Workstation Pro (Windows/Linux): Paid, more features.
        *   VMware Fusion (macOS): Paid.
        *   Parallels Desktop (macOS): Paid.
    *   Step-by-step installation of VirtualBox (or VMware Player) on host OS.
    *   Understanding key virtualization concepts: Host OS, Guest OS, Virtual Hard Disk, Snapshots (for saving VM state), Network Adapters (NAT, Bridged, Host-only, Internal Network).
    *   Configuring VM settings (RAM, CPU cores, storage, network adapter type).
    *   <YouTube videoId_ HOW_TO_INSTALL_VIRTUALBOX_STEP_BY_STEP_by_Techquickie title="How to Install VirtualBox Step-by-Step by Techquickie" /> (Placeholder)
    *   <YouTube videoId_ VMWARE_WORKSTATION_PLAYER_INSTALLATION_AND_OVERVIEW_by_TheCyberMentor title="VMware Workstation Player Installation and Overview by The Cyber Mentor" /> (Placeholder)

*   **Lesson 1.14: Installing Kali Linux in Your Virtual Lab**
    *   What is Kali Linux? A Debian-derived Linux distribution designed for digital forensics and penetration testing. Pre-installed with numerous security tools.
    *   Downloading the official Kali Linux VM image (e.g., .ova for VirtualBox/VMware) from kali.org.
    *   Importing the Kali Linux VM into VirtualBox/VMware.
    *   Initial setup and configuration of Kali:
        *   Default credentials (often kali/kali - change immediately!).
        *   Updating and upgrading packages: `sudo apt update && sudo apt upgrade -y`.
        *   Basic navigation of the Kali desktop environment (GNOME, Xfce, KDE).
        *   Finding and launching tools.
    *   Importance of using official sources for Kali downloads to avoid tampered images.
    *   <YouTube videoId="rYg490124oE" title="Build Your Own Hacking Lab with VirtualBox - Kali Linux & Metasploitable by David Bombal" /> (Focus on Kali install part)
    *   <YouTube videoId_ KALI_LINUX_2023_INSTALLATION_AND_FIRST_LOOK_by_HackerSploit title="Kali Linux 2023 Installation and First Look by HackerSploit" /> (Placeholder for a recent version)

*   **Lesson 1.15: Installing Vulnerable Target Machines (Metasploitable, OWASP WebGoat)**
    *   **Metasploitable 2 or 3:** Intentionally vulnerable Linux virtual machines designed for penetration testing practice.
        *   Download from SourceForge or Rapid7.
        *   Import into VirtualBox/VMware.
        *   Network configuration: Often best to use a Host-only or Internal network for isolation with your Kali VM.
    *   **OWASP WebGoat / Juice Shop:** Intentionally insecure web applications for practicing web application security testing.
        *   WebGoat: Java-based, often run as a JAR file or Docker container.
        *   Juice Shop: Node.js based, often run via Docker or locally with Node.js.
        *   Accessing them via a browser from your Kali VM (or host, if network configured appropriately).
    *   Other vulnerable VMs from VulnHub.com.
    *   **Crucial Reminder: Only use these vulnerable machines within your isolated lab environment. Never expose them to the internet.**
    *   <YouTube videoId_ INSTALLING_METASPLOITABLE_2_IN_VIRTUALBOX_FOR_HACKING_LAB_by_TheCyberMentor title="Installing Metasploitable 2 in VirtualBox for Hacking Lab by The Cyber Mentor" /> (Placeholder)
    *   <YouTube videoId_ OWASP_JUICE_SHOP_SETUP_AND_INTRODUCTION_FOR_WEB_PENTESTING_by_InsiderPhD title="OWASP Juice Shop Setup and Introduction for Web Pentesting by InsiderPhD" /> (Placeholder)

This completes the expansion for Module 1 of Course 7.
---
### Module 2: Networking Fundamentals for Cybersecurity (Expanded)

A strong understanding of networking is crucial for cybersecurity professionals. This module covers the basics with expanded detail.

*   **Lesson 2.1: The OSI Model - A Layered Approach to Networking**
    *   **OSI (Open Systems Interconnection) Model:** A conceptual framework that standardizes the functions of a telecommunication or computing system in terms of seven abstraction layers.
    *   The 7 Layers (Mnemonic: "Please Do Not Throw Sausage Pizza Away"):
        1.  **Physical Layer:** Transmission of raw bits over a physical medium (cables, radio waves). Deals with voltage levels, pin layouts, data rates. (Hubs, Repeaters, Cables).
        2.  **Data Link Layer:** Reliable transmission of data frames between two directly connected nodes. Handles physical addressing (MAC addresses), error detection/correction (e.g., CRC), flow control. (Switches, Bridges, NICs). Sublayers: LLC and MAC.
        3.  **Network Layer:** Logical addressing (IP addresses), routing of packets across networks, path determination. (Routers, Layer 3 Switches).
        4.  **Transport Layer:** End-to-end connections, reliable (TCP) or unreliable (UDP) data delivery, segmentation and reassembly, port numbers, flow control, error control. (TCP, UDP).
        5.  **Session Layer:** Establishes, manages, and terminates connections (sessions) between applications. Synchronization, dialog control. (NetBIOS, RPC).
        6.  **Presentation Layer:** Data translation, formatting, encryption/decryption, compression. Ensures data is in a usable format for the Application Layer. (SSL/TLS, JPEG, ASCII, EBCDIC).
        7.  **Application Layer:** Network services directly supporting user applications. Provides interface between applications and the network. (HTTP, FTP, SMTP, DNS, DHCP).
    *   Encapsulation (data wrapped with headers at each layer on sending) and Decapsulation (headers stripped at each layer on receiving).
    *   <YouTube videoId="vv4y_uOneC0" title="OSI Model Explained | Real World Example by Practical Networking" /> (Recap)
    *   <YouTube videoId_ OSI_MODEL_LAYERS_AND_PROTOCOLS_IN_DETAIL_by_PowerCert_Animated_Videos title="OSI Model Layers and Protocols in Detail by PowerCert Animated Videos" /> (Placeholder)

*   **Lesson 2.2: The TCP/IP Model (Internet Protocol Suite)**
    *   A more practical, widely implemented networking model compared to OSI.
    *   Typically described with 4 Layers (can sometimes be 5 if Link is split):
        1.  **Network Interface Layer (or Link Layer / Network Access Layer):** Combines OSI Physical and Data Link Layers. How data is physically sent through the network (Ethernet, Wi-Fi).
        2.  **Internet Layer:** Corresponds to OSI Network Layer. Responsible for logical addressing (IP), routing packets across networks. (IP, ICMP, ARP).
        3.  **Transport Layer:** Corresponds to OSI Transport Layer. Provides end-to-end communication services. (TCP, UDP).
        4.  **Application Layer:** Combines OSI Session, Presentation, and Application Layers. Provides protocols for specific applications. (HTTP, SMTP, FTP, DNS, DHCP).
    *   Mapping TCP/IP layers to OSI layers.
    *   Focus on how these models help in understanding network communication and troubleshooting.
    *   <YouTube videoId="s_n9qX8Nws8" title="TCP/IP Model (Internet Protocol Suite) | A Real World View by Practical Networking" /> (Recap)
    *   <YouTube videoId_ TCP_IP_VS_OSI_MODEL_KEY_DIFFERENCES_by_Eli_the_Computer_Guy title="TCP/IP vs OSI Model: Key Differences by Eli the Computer Guy" /> (Placeholder)

*   **Lesson 2.3: IP Addressing - IPv4 Addresses, Classes, and Private vs. Public**
    *   **IPv4 Addresses:** A 32-bit numerical label assigned to each device participating in a computer network that uses the Internet Protocol for communication.
        *   Dotted-decimal notation (e.g., 192.168.1.100).
        *   Each octet is 8 bits (0-255).
    *   **IP Address Classes (Historical context, largely superseded by CIDR):**
        *   Class A: 1.0.0.0 to 126.255.255.255 (Large networks). Default mask /8 (255.0.0.0).
        *   Class B: 128.0.0.0 to 191.255.255.255 (Medium networks). Default mask /16 (255.255.0.0).
        *   Class C: 192.0.0.0 to 223.255.255.255 (Small networks). Default mask /24 (255.255.255.0).
        *   Class D (Multicast: 224.0.0.0 to 239.255.255.255), Class E (Experimental: 240.0.0.0 to 255.255.255.255).
    *   **Private IP Address Ranges (RFC 1918):** Not routable on the public internet, used for internal networks.
        *   10.0.0.0 to 10.255.255.255 (10.0.0.0/8)
        *   172.16.0.0 to 172.31.255.255 (172.16.0.0/12)
        *   192.168.0.0 to 192.168.255.255 (192.168.0.0/16)
    *   **Public IP Addresses:** Routable on the internet, assigned by ISPs or Regional Internet Registries (RIRs).
    *   Special Addresses: Loopback (127.0.0.1), APIPA (169.254.x.x).
    *   <YouTube videoId="5WfiTHiU4x8" title="IP Addresses and Subnetting by Practical Networking" /> (Focus on IPv4 addresses and classes)
    *   <YouTube videoId_ PRIVATE_VS_PUBLIC_IP_ADDRESSES_EXPLAINED_by_PowerCert_Animated_Videos title="Private vs Public IP Addresses Explained by PowerCert Animated Videos" /> (Placeholder)

*   **Lesson 2.4: Subnetting and CIDR (Classless Inter-Domain Routing)**
    *   **Subnet Mask:** A 32-bit number used to distinguish the network portion of an IP address from the host portion.
        *   Example: 255.255.255.0 (Network bits are 1s, Host bits are 0s).
    *   **Subnetting:** The process of dividing a larger network into smaller, logical subnetworks (subnets).
        *   Benefits: Improved organization, reduced network traffic (broadcast domains), enhanced security (isolating segments).
        *   "Borrowing" bits from the host portion to create subnet bits.
        *   Calculating number of subnets and hosts per subnet.
    *   **CIDR (Classless Inter-Domain Routing):** Replaced classful addressing. Allows for variable-length subnet masking (VLSM).
        *   Notation: IP_Address/Prefix_Length (e.g., 192.168.1.0/24). Prefix length is the number of bits in the network portion.
        *   Enables more efficient allocation of IP addresses.
    *   Hands-on examples of subnetting calculations.
    *   <YouTube videoId="5WfiTHiU4x8" title="IP Addresses and Subnetting by Practical Networking" /> (Focus on Subnetting and CIDR)
    *   <YouTube videoId_ SUBNETTING_MASTERY_STEP_BY_STEP_TUTORIAL_by_Professor_Messer title="Subnetting Mastery: Step-by-Step Tutorial by Professor Messer" /> (Placeholder - Messer is excellent for this)

*   **Lesson 2.5: IPv6 Addressing - Structure and Need**
    *   Why IPv6? Exhaustion of IPv4 address space.
    *   **IPv6 Addresses:** 128-bit addresses, providing a vastly larger address pool (2^128 addresses).
    *   Hexadecimal Notation: Represented as eight groups of four hexadecimal digits, separated by colons (e.g., `2001:0db8:85a3:0000:0000:8a2e:0370:7334`).
    *   Abbreviation Rules:
        *   Leading zeros in a group can be omitted (e.g., `0db8` -> `db8`, `0000` -> `0`).
        *   One sequence of consecutive groups of zeros can be replaced by a double colon `::` (only once per address).
            *   Example: `2001:0db8:0000:0000:0000:ff00:0042:8329` -> `2001:db8::ff00:42:8329`
    *   Address Types: Unicast (one-to-one), Multicast (one-to-many selected), Anycast (one-to-nearest of many). No broadcast in IPv6.
    *   Special Addresses: Loopback (`::1`), Link-Local (`fe80::/10`), Unique Local (`fc00::/7`), Global Unicast.
    *   Transition mechanisms from IPv4 to IPv6 (Dual Stack, Tunneling, Translation).
    *   <YouTube videoId="Ni9nKeC33sE" title="Understanding IPv6: Everything you need to know by David Bombal" /> (Recap)
    *   <YouTube videoId_ IPV6_ADDRESS_TYPES_AND_NOTATION_by_Practical_Networking title="IPv6 Address Types and Notation by Practical Networking" /> (Placeholder)

*   **Lesson 2.6: TCP (Transmission Control Protocol) - Reliable Delivery**
    *   Operates at the Transport Layer (OSI Layer 4).
    *   **Connection-Oriented:** Establishes a connection before data transfer using a **Three-Way Handshake**:
        1.  Client sends SYN (synchronize) packet.
        2.  Server responds with SYN-ACK (synchronize-acknowledge) packet.
        3.  Client responds with ACK (acknowledge) packet. Connection established.
    *   **Reliable Delivery:**
        *   Sequence Numbers: TCP segments data into packets and assigns sequence numbers.
        *   Acknowledgements (ACKs): Receiver acknowledges receipt of packets.
        *   Retransmission: Sender retransmits lost or unacknowledged packets.
        *   Error Detection (Checksums).
    *   **Flow Control:** Manages the rate of data transmission to prevent overwhelming the receiver (using windowing).
    *   **Congestion Control:** Manages network congestion.
    *   Used by applications requiring reliable data transfer (HTTP/HTTPS, FTP, SMTP, SSH).
    *   TCP Header fields (Source Port, Destination Port, Sequence Number, Acknowledgement Number, Flags - SYN, ACK, FIN, RST, PSH, URG).
    *   <YouTube videoId="uwoD5YsGACg" title="TCP vs UDP Explained by PowerCert Animated Videos" /> (Focus on TCP)
    *   <YouTube videoId_ TCP_THREE_WAY_HANDSHAKE_EXPLAINED_by_Practical_Networking title="TCP Three-Way Handshake Explained by Practical Networking" /> (Placeholder)

*   **Lesson 2.7: UDP (User Datagram Protocol) - Fast, Connectionless Delivery**
    *   Operates at the Transport Layer (OSI Layer 4).
    *   **Connectionless:** No handshake to establish a connection before sending data. Packets (datagrams) are just sent.
    *   **Unreliable Delivery (Best-Effort):**
        *   No acknowledgements.
        *   No retransmission of lost packets.
        *   No guaranteed order of packet arrival.
        *   Minimal error checking (optional checksum).
    *   **Low Overhead:** Smaller header than TCP, faster transmission.
    *   Used by applications where speed is more critical than perfect reliability, or where error handling/retransmission is managed by the application layer:
        *   Streaming media (video, audio - can tolerate some packet loss).
        *   Online gaming.
        *   DNS (Domain Name System - typically uses UDP for queries).
        *   DHCP (Dynamic Host Configuration Protocol).
        *   VoIP (Voice over IP).
    *   UDP Header fields (Source Port, Destination Port, Length, Checksum).
    *   <YouTube videoId="uwoD5YsGACg" title="TCP vs UDP Explained by PowerCert Animated Videos" /> (Focus on UDP)

*   **Lesson 2.8: Common Network Ports and Their Associated Services**
    *   What are Ports? Numbers (0-65535) used to identify specific processes or applications running on a host in a TCP/IP network. Allows multiple applications to share a single IP address.
    *   Well-Known Ports (0-1023): Assigned by IANA to common services (require admin/root privileges to use).
        *   FTP: 20 (Data), 21 (Control)
        *   SSH: 22
        *   Telnet: 23 (insecure, avoid)
        *   SMTP: 25 (Email sending)
        *   DNS: 53 (UDP and TCP)
        *   DHCP: 67 (Server), 68 (Client)
        *   HTTP: 80
        *   POP3: 110 (Email retrieval)
        *   NTP: 123 (Network Time Protocol)
        *   IMAP: 143 (Email retrieval)
        *   SNMP: 161, 162 (Network management)
        *   HTTPS: 443
        *   RDP: 3389 (Remote Desktop Protocol)
    *   Registered Ports (1024-49151): Can be registered by software vendors.
    *   Dynamic/Private/Ephemeral Ports (49152-65535): Used by clients for temporary connections.
    *   Understanding common ports is crucial for firewall configuration, network troubleshooting, and identifying services during reconnaissance.
    *   <YouTube videoId="Ka8vG5xNaFQ" title="Common Network Ports - CompTIA Security+ SY0-601 by Professor Messer" />
    *   <YouTube videoId_ NETWORK_PORTS_EXPLAINED_FOR_BEGINNERS_by_NetworkChuck title="Network Ports Explained for Beginners by NetworkChuck" /> (Placeholder)

*   **Lesson 2.9: DNS (Domain Name System) - The Internet's Phonebook**
    *   Purpose: Translates human-readable domain names (e.g., `www.google.com`) into machine-readable IP addresses (e.g., `172.217.160.142`).
    *   Hierarchical and Distributed System:
        *   Root Name Servers.
        *   Top-Level Domain (TLD) Servers (.com, .org, .net, .uk, etc.).
        *   Authoritative Name Servers (for specific domains).
        *   Recursive Resolvers (usually provided by ISP or public DNS like Google 8.8.8.8, Cloudflare 1.1.1.1).
    *   DNS Query Process (Simplified):
        1.  Client asks local resolver.
        2.  Resolver queries root server (if not cached).
        3.  Root directs to TLD server.
        4.  TLD server directs to authoritative server for the domain.
        5.  Authoritative server provides IP address.
        6.  Resolver caches and returns IP to client.
    *   Common DNS Record Types: A, AAAA, CNAME, MX, NS, TXT, SOA, PTR.
    *   DNS Security: DNS Spoofing, Cache Poisoning, DNSSEC (Domain Name System Security Extensions).
    *   <YouTube videoId="Wj0od2tu5_A" title="How DNS Works by Cloudflare" /> (Recap)
    *   <YouTube videoId_ DNS_RECORDS_EXPLAINED_A_AAAA_CNAME_MX_TXT_by_GoDaddy title="DNS Records Explained (A, AAAA, CNAME, MX, TXT) by GoDaddy" /> (Placeholder)

*   **Lesson 2.10: DHCP (Dynamic Host Configuration Protocol) - Automatic IP Configuration**
    *   Purpose: Automatically assigns IP addresses and other network configuration parameters (subnet mask, default gateway, DNS servers) to devices on a network.
    *   Prevents manual IP configuration errors and simplifies network administration.
    *   DHCP Process (DORA):
        1.  **D**iscover: Client broadcasts a DHCPDISCOVER message to find a DHCP server.
        2.  **O**ffer: DHCP server(s) respond with a DHCPOFFER message, offering an IP address lease.
        3.  **R**equest: Client selects an offer and broadcasts a DHCPREQUEST message to accept it.
        4.  **A**cknowledge: DHCP server sends a DHCPACK message, confirming the lease and providing other configuration info.
    *   IP Address Leasing: IPs are assigned for a specific duration (lease time). Client must renew before expiry.
    *   DHCP Scopes, Reservations.
    *   DHCP Security: Rogue DHCP servers, DHCP starvation attacks.
    *   <YouTube videoId_ DHCP_EXPLAINED_DYNAMIC_HOST_CONFIGURATION_PROTOCOL_by_PowerCert_Animated_Videos title="DHCP Explained (Dynamic Host Configuration Protocol) by PowerCert Animated Videos" /> (Placeholder)

*   **Lesson 2.11: NAT (Network Address Translation) and PAT (Port Address Translation)**
    *   **NAT:** Allows multiple devices in a private network (using private IP addresses) to share a single public IP address to access the internet.
        *   Translates private source IP addresses to the public IP address of the NAT device (router) for outgoing traffic, and vice-versa for incoming traffic (using a translation table).
        *   Helps conserve IPv4 addresses.
        *   Provides a basic level of security by hiding internal IP addresses.
    *   **PAT (Port Address Translation) / NAPT (Network Address Port Translation) / IP Masquerading:** Most common form of NAT.
        *   Uses different source port numbers on the public IP address to distinguish between different internal devices' connections.
        *   Allows many internal devices to use one public IP simultaneously.
    *   Types of NAT: Static NAT (one-to-one mapping), Dynamic NAT (pool of public IPs), PAT (many-to-one with ports).
    *   <YouTube videoId_ NAT_AND_PAT_EXPLAINED_NETWORK_ADDRESS_TRANSLATION_by_Practical_Networking title="NAT and PAT Explained (Network Address Translation) by Practical Networking" /> (Placeholder)
    *   <YouTube videoId_ HOW_NAT_WORKS_TO_SAVE_IPV4_ADDRESSES_by_Computerphile title="How NAT Works to Save IPv4 Addresses by Computerphile" /> (Placeholder)

*   **Lesson 2.12: ICMP (Internet Control Message Protocol) - Diagnostics and Errors**
    *   Used by network devices (like routers) to send error messages and operational information indicating, for example, that a requested service is not available or that a host or router could not be reached.
    *   Operates at the Network Layer (alongside IP).
    *   Common ICMP Messages:
        *   Echo Request / Echo Reply (used by `ping` utility to test connectivity).
        *   Destination Unreachable (Host Unreachable, Port Unreachable, Protocol Unreachable).
        *   Time Exceeded (TTL expired in transit, fragment reassembly time exceeded).
        *   Redirect (informs host of a better route).
    *   Tools using ICMP: `ping`, `traceroute` (uses ICMP Time Exceeded messages from routers).
    *   Security implications: ICMP can be used for network reconnaissance (ping sweeps), DoS attacks (ICMP flood, Smurf attack - older). Firewalls often filter some ICMP messages.
    *   <YouTube videoId_ ICMP_PROTOCOL_EXPLAINED_PING_TRACEROUTE_by_PowerCert_Animated_Videos title="ICMP Protocol Explained (Ping, Traceroute) by PowerCert Animated Videos" /> (Placeholder)

*   **Lesson 2.13: ARP (Address Resolution Protocol) - Mapping IP to MAC Addresses**
    *   Operates at the Data Link Layer / Network Interface Layer.
    *   Purpose: To resolve an IP address to a physical MAC (Media Access Control) address on a local network segment.
    *   How it works (on an Ethernet LAN):
        1.  Host A wants to send data to Host B on the same LAN, knows Host B's IP but not its MAC.
        2.  Host A broadcasts an ARP Request message: "Who has IP address [IP_B]? Tell [IP_A]."
        3.  Host B (or a device knowing Host B's MAC) unicasts an ARP Reply message to Host A: "[IP_B] is at [MAC_B]."
        4.  Host A caches this IP-to-MAC mapping in its ARP table (ARP cache) for future use.
    *   ARP Cache Poisoning/Spoofing: A Man-in-the-Middle attack where an attacker sends forged ARP messages to associate their MAC address with the IP address of another host (e.g., the default gateway), allowing them to intercept traffic.
    *   <YouTube videoId_ ARP_PROTOCOL_ADDRESS_RESOLUTION_PROTOCOL_EXPLAINED_by_Sunny_Classroom title="ARP Protocol (Address Resolution Protocol) Explained by Sunny Classroom" /> (Placeholder)
    *   <YouTube videoId_ HOW_ARP_WORKS_AND_ARP_SPOOFING_by_Computerphile title="How ARP Works and ARP Spoofing by Computerphile" /> (Placeholder)

*   **Lesson 2.14: Network Devices - Routers, Switches, Hubs, Firewalls, WAPs (Deep Dive)**
    *   **Hubs (Layer 1):** Simplest connectivity device. Receives a signal on one port and repeats/broadcasts it out to all other ports. Creates a single collision domain and single broadcast domain. (Largely obsolete).
    *   **Switches (Layer 2):** Smarter than hubs. Learn MAC addresses of connected devices and forward traffic only to the specific port where the destination device is connected (reduces collisions). Each port is a separate collision domain. Creates a single broadcast domain by default (VLANs can segment this).
    *   **Routers (Layer 3):** Connect different networks together (e.g., LAN to WAN/internet). Make forwarding decisions based on IP addresses and routing tables. Break up broadcast domains.
    *   **Firewalls (Network Layer / Application Layer):** Security devices that filter network traffic based on predefined rules.
        *   Packet Filtering Firewalls (Stateless/Stateful).
        *   Proxy Firewalls.
        *   Next-Generation Firewalls (NGFWs - DPI, IPS, application awareness).
    *   **Wireless Access Points (WAPs):** Allow wireless devices to connect to a wired network using Wi-Fi. Often integrated with routers in home setups.
    *   Modems (Modulator-Demodulator): Convert digital signals from a computer to analog signals for transmission over phone lines/cable, and vice-versa.
    *   <YouTube videoId="1z0ULvg_pVQ" title="Networking Devices - Hub, Switch, Router Explained by PowerCert Animated Videos" /> (Recap)
    *   <YouTube videoId_ LAYER_2_VS_LAYER_3_SWITCHES_EXPLAINED_by_Practical_Networking title="Layer 2 vs Layer 3 Switches Explained by Practical Networking" /> (Placeholder)

*   **Lesson 2.15: Introduction to Network Sniffing with Wireshark (Practical Basics)**
    *   What is Network Sniffing (Packet Capturing)? Intercepting and logging network traffic passing over a digital network or part of a network.
    *   **Wireshark:** A free and open-source packet analyzer. Used for network troubleshooting, analysis, software and communications protocol development, and education.
    *   Key Wireshark Features:
        *   Capturing live packet data from a network interface (Ethernet, Wi-Fi).
        *   Opening saved capture files (e.g., .pcap, .pcapng).
        *   Displaying packet data in detail, decoding numerous protocols.
        *   Filtering captured traffic (display filters, capture filters).
        *   Following TCP streams.
        *   Generating statistics.
    *   Wireshark Interface: Packet List Pane, Packet Details Pane, Packet Bytes Pane.
    *   Basic capture and display filter examples (e.g., `ip.addr == x.x.x.x`, `tcp.port == 80`, `dns`).
    *   Ethical considerations: Only capture traffic on networks you own or have explicit permission to monitor. Sniffing on public/corporate networks without authorization is illegal and unethical.
    *   <YouTube videoId="K4TpX1N5GZc" title="Wireshark Tutorial For Beginners by The Cyber Mentor" /> (Recap)
    *   <YouTube videoId_ WIREDSHARK_DISPLAY_FILTERS_CHEAT_SHEET_AND_EXAMPLES_by_Chris_Greer title="Wireshark Display Filters Cheat Sheet and Examples by Chris Greer" /> (Placeholder)

This completes the expansion for Module 2 of Course 7.
---
### Module 3: Cryptography Fundamentals (Expanded)

Cryptography is the bedrock of modern security. This module introduces core cryptographic concepts with expanded detail.

*   **Lesson 3.1: Introduction to Cryptography - History, Goals, and Terminology**
    *   What is Cryptography? The science and practice of secure communication techniques that allow only the sender and intended recipient of a message to view its contents. Derived from Greek "kryptos" (hidden) and "graphein" (to write).
    *   Brief History:
        *   Ancient Ciphers (Caesar Cipher, Scytale, Vigenère Cipher).
        *   Mechanical/Electromechanical Ciphers (Enigma machine in WWII).
        *   Modern Cryptography (Shannon's information theory, public-key cryptography).
    *   Core Goals of Cryptography:
        *   **Confidentiality:** Ensuring data is secret and only accessible by authorized parties. (Achieved via Encryption).
        *   **Integrity:** Ensuring data has not been altered in transit or storage. (Achieved via Hashing, MACs, Digital Signatures).
        *   **Authentication:** Verifying the identity of users or a message's origin. (Achieved via Digital Signatures, MACs, Passwords).
        *   **Non-Repudiation:** Providing proof that a specific party sent/received a message or performed an action, preventing them from denying it. (Achieved via Digital Signatures).
    *   Key Terminology: Plaintext, Ciphertext, Encryption, Decryption, Cipher (Algorithm), Key, Cryptanalysis (breaking codes), Cryptology (study of cryptography and cryptanalysis).
    *   <YouTube videoId_ WHAT_IS_CRYPTOGRAPHY_INTRODUCTION_TO_CRYPTOGRAPHY_by_Simplilearn title="What is Cryptography? | Introduction To Cryptography by Simplilearn" /> (Recap)
    *   <YouTube videoId_ THE_HISTORY_OF_CRYPTOGRAPHY_FROM_CAESAR_TO_QUANTUM_by_TED_Ed title="The History of Cryptography: From Caesar to Quantum by TED-Ed" /> (Placeholder)

*   **Lesson 3.2: Symmetric Key Cryptography - Principles and Algorithms**
    *   Uses a single, shared secret key for both encryption and decryption. Sender and receiver must have the same key.
    *   Analogy: A locked box where both parties have identical keys.
    *   Pros: Generally very fast and efficient for encrypting large amounts of data.
    *   Cons:
        *   **Key Distribution Challenge:** How to securely share the secret key between parties without it being intercepted.
        *   **Key Management:** Managing a large number of unique keys if many pairs of users need to communicate securely.
        *   Doesn't provide non-repudiation or strong authentication on its own (because either party with the key could have created the message).
    *   Types of Symmetric Ciphers:
        *   **Block Ciphers:** Encrypt data in fixed-size blocks (e.g., 64-bit, 128-bit).
            *   Examples: DES, 3DES, AES, Blowfish, Twofish.
        *   **Stream Ciphers:** Encrypt data one bit or byte at a time. Often faster for continuous data streams.
            *   Examples: RC4 (older, vulnerabilities found), ChaCha20.
    *   <YouTube videoId="vXM4s4zC5iE" title="Symmetric vs. Asymmetric Encryption by Fireship" /> (Recap Symmetric part)
    *   <YouTube videoId="Rk0NIQfEXkM" title="Symmetric Encryption - CompTIA Security+ SY0-601 by Professor Messer" /> (Recap)

*   **Lesson 3.3: Symmetric Key Cryptography - DES, 3DES, and AES**
    *   **DES (Data Encryption Standard):**
        *   Developed in the 1970s. Uses a 56-bit key and 64-bit block size.
        *   Considered insecure today due to its small key size, making it vulnerable to brute-force attacks. (Largely historical interest).
    *   **3DES (Triple DES):**
        *   Applies DES three times with two or three different keys (Encrypt-Decrypt-Encrypt or EDE). Effective key length of 112 or 168 bits.
        *   More secure than DES, but significantly slower due to multiple DES operations.
        *   Being phased out in favor of AES.
    *   **AES (Advanced Encryption Standard):**
        *   Current global standard, adopted by U.S. government.
        *   Block cipher with a 128-bit block size.
        *   Key sizes: 128-bit, 192-bit, or 256-bit.
        *   Strong, efficient, and widely implemented in hardware and software.
        *   Based on the Rijndael algorithm.
    *   Understanding key length and its impact on security (longer key = more possible combinations, harder to brute-force).
    *   <YouTube videoId_ AES_EXPLAINED_ADVANCED_ENCRYPTION_STANDARD_by_Computerphile title="AES Explained (Advanced Encryption Standard) by Computerphile" /> (Placeholder)
    *   <YouTube videoId_ DES_3DES_AND_AES_SYMMETRIC_ENCRYPTION_ALGORITHMS_COMPARISON_by_Cryptography_Lectures title="DES, 3DES, and AES Symmetric Encryption Algorithms Comparison by Cryptography Lectures" /> (Placeholder)

*   **Lesson 3.4: Symmetric Key Cryptography - Block Cipher Modes of Operation**
    *   Block ciphers encrypt fixed-size blocks. How do you encrypt messages larger than one block? Modes of operation define this.
    *   Common Modes:
        *   **ECB (Electronic Codebook):** Simplest mode. Each block is encrypted independently. Identical plaintext blocks result in identical ciphertext blocks (reveals patterns). **Not recommended for most uses.**
        *   **CBC (Cipher Block Chaining):** Each plaintext block is XORed with the previous ciphertext block before being encrypted. Uses an Initialization Vector (IV) for the first block. More secure than ECB as identical plaintext blocks will produce different ciphertext blocks.
        *   **CTR (Counter Mode):** Turns a block cipher into a stream cipher. Encrypts successive values of a "counter" and XORs the result with plaintext blocks. Allows parallel encryption/decryption.
        *   **GCM (Galois/Counter Mode):** An authenticated encryption mode (AEAD - Authenticated Encryption with Associated Data). Provides both confidentiality and integrity/authenticity. Widely used (e.g., in TLS 1.2/1.3).
        *   Other modes: CFB (Cipher Feedback), OFB (Output Feedback).
    *   Importance of using a unique, unpredictable Initialization Vector (IV) for modes like CBC, CTR.
    *   <YouTube videoId_ BLOCK_CIPHER_MODES_OF_OPERATION_ECB_CBC_CTR_EXPLAINED_by_Christof_Paar title="Block Cipher Modes of Operation (ECB, CBC, CTR) Explained by Christof Paar" /> (Placeholder - Paar has great crypto lectures)
    *   <YouTube videoId_ WHY_ECB_MODE_IS_BAD_FOR_ENCRYPTION_by_Computerphile title="Why ECB Mode is Bad for Encryption by Computerphile" /> (Placeholder)

*   **Lesson 3.5: Asymmetric Key Cryptography (Public Key Cryptography) - Principles**
    *   Uses a pair of mathematically related keys for each user: a **public key** and a **private key**.
        *   Public Key: Can be shared openly with anyone.
        *   Private Key: Must be kept secret by the owner.
    *   How it works:
        *   **For Confidentiality (Encryption):** Data encrypted with a recipient's public key can *only* be decrypted with that recipient's corresponding private key. (Ensures only the intended recipient can read it).
        *   **For Authentication/Digital Signatures:** Data signed (effectively encrypted) with a sender's private key can be verified (decrypted) using the sender's public key. (Proves the sender's identity and data integrity).
    *   Solves the key distribution problem of symmetric cryptography (no need to securely share a secret key beforehand for encryption).
    *   Much slower computationally than symmetric cryptography, so not typically used to encrypt large amounts of data directly. Often used in a hybrid approach (encrypt a symmetric session key with asymmetric crypto).
    *   <YouTube videoId="vXM4s4zC5iE" title="Symmetric vs. Asymmetric Encryption by Fireship" /> (Recap Asymmetric part)
    *   <YouTube videoId="NttW221-p7Q" title="Asymmetric Encryption - CompTIA Security+ SY0-601 by Professor Messer" /> (Recap)

*   **Lesson 3.6: Asymmetric Key Cryptography - RSA Algorithm**
    *   RSA (Rivest-Shamir-Adleman): One of the first practical public-key cryptosystems, widely used for secure data transmission and digital signatures.
    *   Based on the mathematical difficulty of factoring large prime numbers.
    *   Key Generation:
        1.  Choose two large distinct prime numbers, p and q.
        2.  Compute n = p * q (modulus).
        3.  Compute Euler's totient function: φ(n) = (p-1)(q-1).
        4.  Choose an integer e (public exponent) such that 1 < e < φ(n) and gcd(e, φ(n)) = 1.
        5.  Compute d (private exponent) such that (d * e) mod φ(n) = 1 (modular multiplicative inverse).
        *   Public Key: (n, e). Private Key: (n, d). (p, q, φ(n) are kept secret).
    *   Encryption: Ciphertext C = (Plaintext P)^e mod n.
    *   Decryption: Plaintext P = (Ciphertext C)^d mod n.
    *   Key lengths typically 2048 bits or 3072 bits for good security.
    *   <YouTube videoId_ RSA_ENCRYPTION_EXPLAINED_SIMPLY_by_Art_of_the_Problem title="RSA Encryption Explained Simply by Art of the Problem" /> (Placeholder)
    *   <YouTube videoId_ HOW_RSA_ALGORITHM_WORKS_STEP_BY_STEP_by_Savjee title="How RSA Algorithm Works Step-by-Step by Savjee" /> (Placeholder)

*   **Lesson 3.7: Asymmetric Key Cryptography - Diffie-Hellman Key Exchange**
    *   A method for two parties to securely establish a shared secret key over an insecure communication channel, without prior shared secrets.
    *   The shared secret can then be used as a key for symmetric encryption.
    *   Based on the difficulty of computing discrete logarithms.
    *   How it works (Simplified):
        1.  Alice and Bob publicly agree on a large prime number (p) and a generator (g).
        2.  Alice chooses a secret private number (a), computes A = g^a mod p, sends A to Bob.
        3.  Bob chooses a secret private number (b), computes B = g^b mod p, sends B to Alice.
        4.  Alice computes Shared Secret S = B^a mod p = (g^b)^a mod p.
        5.  Bob computes Shared Secret S = A^b mod p = (g^a)^b mod p.
        *   Both arrive at the same shared secret S, which an eavesdropper cannot easily compute from p, g, A, B.
    *   Vulnerable to Man-in-the-Middle attacks if A and B are not authenticated (often used with digital signatures or certificates).
    *   <YouTube videoId_ DIFFIE_HELLMAN_KEY_EXCHANGE_EXPLAINED_by_Computerphile title="Diffie-Hellman Key Exchange Explained by Computerphile" /> (Placeholder)

*   **Lesson 3.8: Asymmetric Key Cryptography - Elliptic Curve Cryptography (ECC)**
    *   An approach to public-key cryptography based on the algebraic structure of elliptic curves over finite fields.
    *   Provides similar (or greater) security levels with significantly smaller key sizes compared to RSA or traditional Diffie-Hellman based on discrete logarithms.
        *   Example: A 256-bit ECC key offers similar security to a 3072-bit RSA key.
    *   Benefits of smaller key sizes:
        *   Faster computations.
        *   Lower power consumption.
        *   Reduced storage and bandwidth requirements.
        *   Particularly advantageous for resource-constrained devices (mobile phones, IoT devices).
    *   ECC variants of Diffie-Hellman (ECDH) and Digital Signature Algorithm (ECDSA) are widely used.
    *   Used in many modern applications, including TLS, cryptocurrencies (Bitcoin, Ethereum use ECDSA).
    *   <YouTube videoId_ ELLIPTIC_CURVE_CRYPTOGRAPHY_ECC_EXPLAINED_by_Savjee title="Elliptic Curve Cryptography (ECC) Explained by Savjee" /> (Placeholder)
    *   <YouTube videoId_ WHY_ELLIPTIC_CURVE_CRYPTOGRAPHY_IS_BETTER_THAN_RSA_by_Christof_Paar title="Why Elliptic Curve Cryptography is Better Than RSA by Christof Paar" /> (Placeholder)

*   **Lesson 3.9: Hashing Functions - Properties and Use Cases (MD5, SHA Family)**
    *   Recap: Cryptographic hash functions produce a fixed-size, unique "fingerprint" of input data. One-way, deterministic, collision-resistant.
    *   **MD5 (Message Digest 5):** Produces a 128-bit hash. Widely used in the past for integrity checks, but now considered cryptographically broken due to known collision vulnerabilities. **Should not be used for security purposes.** Still sometimes used for non-security checksums.
    *   **SHA (Secure Hash Algorithm) Family:** Developed by NIST.
        *   **SHA-1:** Produces a 160-bit hash. Also considered weakened and deprecated for most security uses due to collision attacks.
        *   **SHA-2 Family:** Includes SHA-224, SHA-256, SHA-384, SHA-512, SHA-512/224, SHA-512/256. Currently considered secure and widely used.
            *   SHA-256 is very common (e.g., Bitcoin, TLS certificates).
        *   **SHA-3 Family:** Newer standard (Keccak algorithm), designed as an alternative to SHA-2, not a replacement due to SHA-2 weakness. Different internal structure.
    *   Use Cases Revisited:
        *   Password Storage (with salting and key stretching like PBKDF2, bcrypt, scrypt, Argon2).
        *   Data Integrity Verification (checksums, file integrity).
        *   Digital Signatures (hash the message then sign the hash).
        *   Blockchain (linking blocks, Merkle trees).
        *   Message Authentication Codes (MACs - next lesson).
    *   <YouTube videoId="yoO_1Fj3w4c" title="Hashing - CompTIA Security+ SY0-601 by Professor Messer" /> (Recap)
    *   <YouTube videoId_ MD5_VS_SHA1_VS_SHA256_WHICH_HASH_FUNCTION_TO_USE_by_Simply_Explained title="MD5 vs SHA1 vs SHA256: Which Hash Function to Use? by Simply Explained" /> (Placeholder)

*   **Lesson 3.10: Message Authentication Codes (MACs) and HMAC**
    *   What is a MAC? A short piece of information used to authenticate a message—in other words, to confirm that the message came from the stated sender (its authenticity) and has not been changed (its integrity).
    *   MACs use a secret key shared between sender and receiver.
    *   How it works: Sender calculates MAC value for the message using the secret key and appends it to the message. Receiver recalculates MAC on the received message using the same secret key and compares it to the received MAC. If they match, message is authentic and intact.
    *   Different from digital signatures (which use asymmetric keys and provide non-repudiation). MACs do not provide non-repudiation because either party with the secret key could have generated the MAC.
    *   **HMAC (Hash-based Message Authentication Code):** A specific type of MAC calculated using a cryptographic hash function (like SHA-256) in combination with a secret key.
        *   HMAC-SHA256 is very common.
    *   Used in various protocols (e.g., TLS, IPsec) to ensure data integrity and authenticity.
    *   <YouTube videoId_ MESSAGE_AUTHENTICATION_CODES_MACS_AND_HMAC_EXPLAINED_by_Christof_Paar title="Message Authentication Codes (MACs) and HMAC Explained by Christof Paar" /> (Placeholder)

*   **Lesson 3.11: Digital Signatures - Ensuring Authenticity, Integrity, and Non-Repudiation**
    *   Recap: Digital signatures use asymmetric cryptography (private key to sign, public key to verify).
    *   Process:
        1.  Sender creates a hash of the message/document.
        2.  Sender encrypts the hash with their **private key**. This encrypted hash is the digital signature.
        3.  Sender sends the original message + the digital signature to the receiver.
        4.  Receiver uses the sender's **public key** to decrypt the signature, revealing the original hash.
        5.  Receiver calculates a new hash of the received message.
        6.  Receiver compares the decrypted hash with the newly calculated hash. If they match, the signature is valid.
    *   Provides:
        *   **Authenticity:** Only the owner of the private key could have created the signature.
        *   **Integrity:** If the message was altered, the hashes wouldn't match.
        *   **Non-Repudiation:** Sender cannot deny signing the message, as only they have the private key.
    *   Common Digital Signature Algorithms: RSA, DSA (Digital Signature Algorithm), ECDSA (Elliptic Curve Digital Signature Algorithm - used in Bitcoin/Ethereum).
    *   <YouTube videoId="NAX352Y2w3o" title="Digital Signatures - CompTIA Security+ SY0-601 by Professor Messer" /> (Recap)
    *   <YouTube videoId_ HOW_DIGITAL_SIGNATURES_WORK_IN_PLAIN_ENGLISH_by_Savjee title="How Digital Signatures Work in Plain English by Savjee" /> (Placeholder)

*   **Lesson 3.12: Digital Certificates and Public Key Infrastructure (PKI)**
    *   Recap: Digital Certificates (X.509 standard) are electronic documents that bind a public key to an identity (individual, organization, server).
    *   Issued by a trusted third party called a **Certificate Authority (CA)** (e.g., Let's Encrypt, DigiCert, GlobalSign).
    *   Contents of a Digital Certificate:
        *   Subject's Public Key.
        *   Subject's Identifying Information (Name, Organization, Domain Name).
        *   Issuing CA's Name.
        *   CA's Digital Signature (signing the certificate to vouch for its authenticity).
        *   Serial Number.
        *   Validity Period (Start and End Dates).
        *   Key Usage information.
    *   **Public Key Infrastructure (PKI):** The framework of hardware, software, policies, procedures, and people used to create, manage, distribute, use, store, and revoke digital certificates and manage public-key encryption.
    *   Hierarchy of CAs: Root CAs, Intermediate CAs. Chain of trust.
    *   Certificate Revocation Lists (CRLs) and Online Certificate Status Protocol (OCSP) for checking if a certificate has been revoked before its expiry.
    *   How HTTPS (SSL/TLS) relies on digital certificates and PKI to authenticate websites and establish secure connections.
    *   <YouTube videoId="T4dPas2629M" title="Digital Certificates and PKI - CompTIA Security+ SY0-601 by Professor Messer" /> (Recap)
    *   <YouTube videoId_ HOW_SSL_TLS_CERTIFICATES_AND_PKI_WORK_by_Cloudflare title="How SSL/TLS Certificates and PKI Work by Cloudflare" /> (Placeholder)

*   **Lesson 3.13: SSL/TLS - Securing Web Communication (HTTPS)**
    *   **SSL (Secure Sockets Layer) / TLS (Transport Layer Security):** Cryptographic protocols designed to provide secure communication over a computer network. TLS is the successor to SSL.
    *   Primary goal of HTTPS (HTTP over TLS): Encrypt communication between a web browser (client) and a web server to protect confidentiality and integrity of data exchanged. Also authenticates the website.
    *   **TLS Handshake Process (Simplified):**
        1.  Client sends "ClientHello" (supported TLS versions, cipher suites).
        2.  Server responds with "ServerHello" (chosen TLS version, cipher suite), its digital certificate (containing public key), and "ServerHelloDone".
        3.  Client verifies server's certificate (checks CA signature, validity, domain name).
        4.  Client generates a pre-master secret (symmetric session key), encrypts it with the server's public key, and sends it to the server ("ClientKeyExchange").
        5.  Client sends "ChangeCipherSpec" (will start using symmetric key) and "Finished" (encrypted hash of handshake messages).
        6.  Server decrypts pre-master secret with its private key, derives symmetric session key.
        7.  Server sends "ChangeCipherSpec" and "Finished" (encrypted).
        8.  Secure symmetric encryption session established for data transfer.
    *   Uses both asymmetric (for key exchange and server authentication) and symmetric (for bulk data encryption) cryptography.
    *   <YouTube videoId="j9QmUgiB-gA" title="How SSL works (Full Handshake)" by Hussein Nasser /> (Recap)
    *   <YouTube videoId_ TLS_HANDSHAKE_EXPLAINED_STEP_BY_STEP_by_Sunny_Classroom title="TLS Handshake Explained Step-by-Step by Sunny Classroom" /> (Placeholder)

*   **Lesson 3.14: Cryptographic Attacks - Brute Force, Dictionary, Rainbow Tables, Man-in-the-Middle**
    *   **Brute-Force Attack:** Trying every possible key or password combination until the correct one is found. Feasibility depends on key/password length and complexity.
    *   **Dictionary Attack:** Using a precompiled list of common words, phrases, or known passwords. More efficient than pure brute-force for weak passwords.
    *   **Rainbow Tables:** Precomputed tables of hash values for common passwords. Can speed up cracking of (unsalted) password hashes. Salting makes rainbow tables largely ineffective.
    *   **Man-in-the-Middle (MitM) Attack (in cryptographic context):** Attacker intercepts communication and relays messages, potentially altering them, making both parties believe they are communicating directly. (e.g., SSL Stripping, intercepting Diffie-Hellman exchange if not authenticated).
    *   **Known Plaintext Attack:** Attacker has access to both plaintext and its corresponding ciphertext, tries to deduce the key.
    *   **Ciphertext-Only Attack:** Attacker only has access to ciphertext.
    *   **Side-Channel Attacks:** Exploit information gained from the physical implementation of a cryptosystem (e.g., timing information, power consumption, electromagnetic leaks).
    *   <YouTube videoId_ COMMON_CRYPTOGRAPHIC_ATTACKS_EXPLAINED_by_Cybrary title="Common Cryptographic Attacks Explained by Cybrary" /> (Placeholder)
    *   <YouTube videoId_ HOW_RAINBOW_TABLES_CRACK_PASSWORDS_by_Computerphile title="How Rainbow Tables Crack Passwords by Computerphile" /> (Placeholder)

*   **Lesson 3.15: Quantum Cryptography and Post-Quantum Cryptography (Brief Introduction)**
    *   **Quantum Computing's Threat to Current Cryptography:** Large-scale quantum computers (if built) could potentially break widely used asymmetric algorithms like RSA and ECC (using Shor's algorithm) and weaken symmetric algorithms (using Grover's algorithm).
    *   **Quantum Cryptography (Quantum Key Distribution - QKD):** Uses principles of quantum mechanics (e.g., properties of photons) to establish a secure shared secret key between two parties in a way that is theoretically immune to eavesdropping (any attempt to measure disturbs the quantum state). Not for encrypting data itself, but for secure key exchange.
    *   **Post-Quantum Cryptography (PQC) / Quantum-Resistant Cryptography:** Development of new classical cryptographic algorithms that are believed to be secure against attacks by both classical and quantum computers.
        *   NIST is running a standardization process for PQC algorithms.
        *   Categories: Lattice-based, code-based, hash-based, multivariate polynomial, isogeny-based.
    *   This is an emerging field, preparing for the future.
    *   <YouTube videoId_ QUANTUM_COMPUTING_S_THREAT_TO_ENCRYPTION_AND_POST_QUANTUM_CRYPTO_by_Quanta_Magazine title="Quantum Computing's Threat to Encryption and Post-Quantum Crypto by Quanta Magazine" /> (Placeholder)
    *   <YouTube videoId_ WHAT_IS_QUANTUM_KEY_DISTRIBUTION_QKD_by_Toshiba title="What is Quantum Key Distribution (QKD)? by Toshiba" /> (Placeholder)

This completes the expansion for Module 3 of Course 7.
---
### Module 4: Malware, Social Engineering, and Physical Security (Expanded)

This module covers common attack vectors that exploit human behavior and physical vulnerabilities, as well as malicious software, with expanded detail.

*   **Lesson 4.1: Malware - Viruses and Worms**
    *   Recap Malware: Malicious Software.
    *   **Viruses:**
        *   Characteristics: Malicious code that attaches itself to legitimate executable files or documents (e.g., macros in Office files). Requires a host program to run.
        *   Propagation: Spreads when the infected host file is executed or opened, often through user action (email attachments, infected USB drives, downloaded files).
        *   Payload: Can be destructive (delete files, corrupt system), steal data, or create backdoors.
        *   Types: File infectors, boot sector viruses, macro viruses, polymorphic/metamorphic viruses (change their code to evade detection).
    *   **Worms:**
        *   Characteristics: Standalone malware that can replicate itself and spread across networks automatically without user intervention, by exploiting vulnerabilities in operating systems or applications.
        *   Propagation: Actively seek out vulnerable systems to infect.
        *   Payload: Can consume bandwidth, install backdoors, launch DoS attacks, deliver other malware (like ransomware).
        *   Examples: ILOVEYOU, Code Red, SQL Slammer, Conficker.
    *   Difference: Viruses need a host and user action to spread; worms are self-propagating.
    *   <YouTube videoId_ VIRUSES_VS_WORMS_VS_TROJANS_MALWARE_EXPLAINED_by_PowerCert_Animated_Videos title="Viruses vs Worms vs Trojans - Malware Explained by PowerCert Animated Videos" /> (Placeholder - focus on Virus/Worm)

*   **Lesson 4.2: Malware - Trojans, Rootkits, and Keyloggers**
    *   **Trojans (Trojan Horses):**
        *   Disguise as legitimate or desirable software (e.g., games, utilities, software updates) to trick users into installing them.
        *   Contain a hidden malicious payload that executes once the "legitimate" part is run.
        *   Payloads: Remote Access Trojans (RATs - give attacker full control), data theft, botnet participation, ransomware delivery, disabling security software.
    *   **Rootkits:**
        *   Designed to gain privileged (root/administrator) access to a computer system and hide their presence and malicious activities from detection by the OS or security software.
        *   Can modify core system files, drivers, or firmware.
        *   Very difficult to detect and remove.
        *   Types: Kernel-mode, user-mode, bootkits, firmware rootkits.
    *   **Keyloggers (Keystroke Loggers):**
        *   Software or hardware that records every keystroke made by a user.
        *   Used to capture sensitive information like passwords, credit card numbers, personal messages.
        *   Can be part of spyware or Trojan payloads.
    *   <YouTube videoId_ WHAT_IS_A_TROJAN_HORSE_VIRUS_EXPLAINED_by_Kaspersky title="What is a Trojan Horse Virus? Explained by Kaspersky" /> (Placeholder)
    *   <YouTube videoId_ ROOTKITS_HOW_THEY_WORK_AND_HOW_TO_DETECT_THEM_by_Malwarebytes_Labs title="Rootkits: How They Work and How to Detect Them by Malwarebytes Labs" /> (Placeholder)

*   **Lesson 4.3: Malware - Ransomware, Spyware, and Adware**
    *   **Ransomware:**
        *   Encrypts a victim's files or entire system, making them inaccessible.
        *   Attackers demand a ransom payment (usually in cryptocurrency like Bitcoin) for the decryption key.
        *   Modern ransomware often involves data exfiltration (stealing data before encrypting) with threats to publish it if ransom isn't paid (double extortion).
        *   Delivery methods: Phishing emails, exploiting vulnerabilities, compromised RDP.
        *   Examples: WannaCry, Ryuk, Conti, LockBit.
    *   **Spyware:**
        *   Secretly gathers information about a user, their computer activities, and browsing habits without their consent.
        *   Can capture login credentials, financial information, personal data.
        *   Transmits this information to an attacker.
    *   **Adware (Advertising-supported software):**
        *   Software that automatically displays or downloads advertising material (pop-ups, banners) when a user is online.
        *   Can be legitimate (if user consents) or malicious (if installed without consent, tracks aggressively, or is hard to remove).
        *   Malicious adware can redirect browsers to unwanted sites or install further malware.
    *   <YouTube videoId="VbC08f023jE" title="Malware - CompTIA Security+ SY0-601 by Professor Messer" /> (Recap different types)
    *   <YouTube videoId_ THE_EVOLUTION_OF_RANSOMWARE_AND_DOUBLE_EXTORTION_by_CrowdStrike title="The Evolution of Ransomware and Double Extortion by CrowdStrike" /> (Placeholder)

*   **Lesson 4.4: Malware - Bots, Botnets, and Logic Bombs**
    *   **Bots (Robots/Zombies):** Compromised computers or devices infected with malware that allows an attacker (botmaster) to control them remotely.
    *   **Botnets (Robot Networks):** A network of bots controlled by a single botmaster or group.
        *   Used for large-scale malicious activities:
            *   Distributed Denial of Service (DDoS) attacks.
            *   Sending spam emails or phishing campaigns.
            *   Click fraud.
            *   Cryptocurrency mining (cryptojacking).
            *   Distributing other malware.
        *   Command and Control (C&C or C2) servers are used by botmasters to issue commands to the botnet.
    *   **Logic Bombs:**
        *   A piece of malicious code intentionally inserted into a software system that will set off a malicious function when specified conditions are met (e.g., a specific date/time, a particular event occurring, or a condition no longer being met - like an employee being terminated).
        *   Often deployed by disgruntled insiders.
        *   Can be difficult to detect before they trigger.
    *   <YouTube videoId_ WHAT_IS_A_BOTNET_AND_HOW_DOES_IT_WORK_by_FSecure title="What is a Botnet and How Does it Work? by F-Secure" /> (Placeholder)
    *   <YouTube videoId_ LOGIC_BOMBS_IN_CYBERSECURITY_EXPLAINED_by_Cybrary title="Logic Bombs in Cybersecurity Explained by Cybrary" /> (Placeholder)

*   **Lesson 4.5: Social Engineering Principles - Authority, Scarcity, Liking, etc.**
    *   Recap: Social engineering manipulates human psychology.
    *   Dr. Robert Cialdini's Six Principles of Influence (often exploited by social engineers):
        1.  **Authority:** People tend to obey authority figures or those perceived as having authority (e.g., impersonating a CEO, IT admin, police officer).
        2.  **Scarcity:** Perceived scarcity generates demand (e.g., "Limited time offer!", "Only 2 left in stock!"). Creates urgency.
        3.  **Liking:** People are more easily persuaded by those they like (e.g., building rapport, finding common ground, flattery).
        4.  **Social Proof / Consensus:** People tend to do things they see other people doing (e.g., "Everyone else has provided this information," fake testimonials).
        5.  **Consistency / Commitment:** People like to be consistent with things they have previously said or done. Attackers may ask for small commitments first, then larger ones.
        6.  **Reciprocity:** People feel obliged to return favors (e.g., attacker offers "help" or a small gift, then asks for something in return).
    *   Other principles: Urgency, Fear, Trust, Greed.
    *   Understanding these helps in recognizing manipulation attempts.
    *   <YouTube videoId_ CIALDINI_S_6_PRINCIPLES_OF_PERSUASION_IN_SOCIAL_ENGINEERING_by_SocialEngineerOrg title="Cialdini's 6 Principles of Persuasion in Social Engineering by Social-Engineer.org" /> (Placeholder - Chris Hadnagy's org)

*   **Lesson 4.6: Phishing Deep Dive - Types and Red Flags**
    *   Recap: Phishing, Spear Phishing, Whaling, Vishing, Smishing.
    *   **Angler Phishing:** Attackers impersonate customer service accounts on social media to intercept user complaints and trick them into divulging information.
    *   **Clone Phishing:** Using a legitimate, previously delivered email containing an attachment or link, but replacing it with a malicious version, then resending from a spoofed address appearing to come from the original sender.
    *   **Red Flags in Phishing Emails/Messages:**
        *   Suspicious Sender Address (misspellings, wrong domain, generic address for a known contact).
        *   Generic Greetings ("Dear Customer," "Valued User").
        *   Urgency, Threats, or Exciting Offers (pressure to act quickly).
        *   Poor Grammar and Spelling (though some are becoming more sophisticated).
        *   Suspicious Links (hover to check actual URL, mismatched display text and link, URL shorteners).
        *   Unexpected Attachments (especially .exe, .zip, .js, or Office docs asking to enable macros).
        *   Requests for Sensitive Information (login credentials, financial details - legitimate companies rarely ask for this via email).
        *   Unusual Tone or Content from a known sender.
    *   <YouTube videoId="doyq-_0a9oE" title="How to Recognize and Avoid Phishing Scams by FTC" /> (Recap)
    *   <YouTube videoId_ ADVANCED_PHISHING_TECHNIQUES_AND_HOW_TO_SPOT_THEM_by_KnowBe4 title="Advanced Phishing Techniques and How to Spot Them by KnowBe4" /> (Placeholder - KnowBe4 specializes in security awareness)

*   **Lesson 4.7: Other Social Engineering Techniques - Pretexting, Baiting, Tailgating**
    *   **Pretexting:** Creating a fabricated scenario (a pretext) to gain trust and obtain information from a target. Often involves research to make the pretext believable. (e.g., attacker pretends to be from IT support needing your password to fix an issue).
    *   **Baiting:** Luring victims with something enticing (e.g., leaving a malware-infected USB drive labeled "Employee Salaries" in a common area, offering free movie downloads that contain malware). Exploits curiosity or greed.
    *   **Quid Pro Quo ("Something for Something"):** Attacker offers a supposed service or benefit in exchange for information or action. (e.g., calling random numbers in a company claiming to be IT support and offering to "fix" a non-existent problem if user provides login details).
    *   **Tailgating / Piggybacking:** Following an authorized person into a restricted physical area without proper authorization.
    *   **Dumpster Diving:** Sifting through an organization's trash (physical or digital) to find sensitive information (documents, old hard drives, notes).
    *   **Shoulder Surfing:** Observing someone as they enter sensitive information (passwords, PINs) over their shoulder.
    *   <YouTube videoId_ TOP_5_SOCIAL_ENGINEERING_ATTACKS_AND_HOW_THEY_WORK_by_Cyberspatial title="Top 5 Social Engineering Attacks and How They Work by Cyberspatial" /> (Placeholder)

*   **Lesson 4.8: Defending Against Social Engineering - User Education and Technical Controls**
    *   **User Education and Awareness Training (Most Critical Defense):**
        *   Train employees and individuals to recognize social engineering tactics and red flags.
        *   Simulated phishing campaigns to test awareness.
        *   Clear policies on information sharing and verifying requests.
        *   Encourage a culture of skepticism ("Verify, then trust").
    *   **Technical Controls:**
        *   Email filtering and anti-spam solutions (to block phishing emails).
        *   Web filtering (to block malicious websites).
        *   Multi-Factor Authentication (MFA) (makes stolen credentials less useful).
        *   Endpoint security (to detect/prevent malware delivered via social engineering).
        *   Principle of Least Privilege (limits damage if an account is compromised).
        *   Regularly patching software to fix vulnerabilities exploited by malware.
    *   Physical security measures to prevent tailgating, etc.
    *   <YouTube videoId_ HOW_TO_PREVENT_SOCIAL_ENGINEERING_ATTACKS_TIPS_FOR_INDIVIDUALS_AND_ORGANIZATIONS_by_SANS_Institute title="How to Prevent Social Engineering Attacks: Tips for Individuals and Organizations by SANS Institute" /> (Placeholder)

*   **Lesson 4.9: Physical Security Controls - Perimeter, Building, Room/Asset**
    *   Recap: Importance of physical security.
    *   **Perimeter Security:** First line of defense.
        *   Fences, Walls, Gates, Bollards.
        *   Lighting.
        *   Signage (warnings, private property).
        *   Security Guards, Patrols.
        *   CCTV Surveillance.
    *   **Building Access Control:**
        *   Locks (mechanical, electronic).
        *   Access Control Systems: Key cards, fobs, PIN pads, biometric readers (fingerprint, iris, facial recognition).
        *   Reception/Security Desk.
        *   Visitor Management Systems.
        *   Alarm Systems and Motion Detectors.
    *   **Room/Asset Security (Securing sensitive areas within a building):**
        *   Data Centers: Stronger access controls, mantraps.
        *   Server Racks: Locked cabinets.
        *   Individual Asset Security: Cable locks for laptops/desktops, safes for media.
        *   Clean Desk Policy.
    *   <YouTube videoId="WGBi91t0qK4" title="Physical Security Controls - CompTIA Security+ SY0-601 by Professor Messer" /> (Recap)

*   **Lesson 4.10: Physical Security - Surveillance, Environmental Controls, Data Destruction**
    *   **Surveillance:**
        *   CCTV (Closed-Circuit Television): Cameras for monitoring and recording activity. Placement, resolution, recording retention.
        *   Security Guards: Monitoring, patrols, incident response.
    *   **Environmental Controls (Protecting against natural/man-made environmental threats):**
        *   Fire Detection and Suppression Systems (smoke detectors, sprinklers, gas-based systems for data centers).
        *   HVAC (Heating, Ventilation, Air Conditioning): Temperature and humidity control to prevent equipment damage.
        *   Power Protection: UPS (Uninterruptible Power Supply), backup generators to prevent data loss/downtime from power outages.
        *   Water/Flood Detection.
    *   **Data Destruction (Secure Disposal of Media):**
        *   To prevent data remanence (residual data left on media after deletion).
        *   Paper: Shredding (cross-cut recommended).
        *   Hard Drives/SSDs: Degaussing (for magnetic media), physical destruction (shredding, crushing, incineration), cryptographic erasure.
        *   CDs/DVDs: Shredding, breaking.
        *   USB Drives: Physical destruction.
    *   <YouTube videoId_ DATA_DESTRUCTION_METHODS_AND_BEST_PRACTICES_by_Iron_Mountain title="Data Destruction Methods and Best Practices by Iron Mountain" /> (Placeholder - Iron Mountain is a leader in this)
    *   <YouTube videoId_ ENVIRONMENTAL_CONTROLS_IN_DATA_CENTERS_by_Schneider_Electric title="Environmental Controls in Data Centers by Schneider Electric" /> (Placeholder)

*   **Lesson 4.11: Antivirus/Anti-malware Software - How They Work and Limitations**
    *   **Signature-Based Detection:**
        *   AV software maintains a database of known malware signatures (unique patterns of code or behavior).
        *   Scans files and compares them against this database.
        *   Effective against known threats, but ineffective against new/zero-day malware or polymorphic malware.
        *   Requires regular updates of signature definitions.
    *   **Heuristic Analysis (Behavioral Detection):**
        *   Analyzes the behavior of programs or code to identify suspicious actions (e.g., trying to modify system files, encrypting many files rapidly, connecting to known malicious C&C servers).
        *   Can detect new or unknown malware based on its behavior.
        *   Prone to false positives (flagging legitimate software as malicious).
    *   **Sandbox Analysis:** Executing suspicious files in an isolated virtual environment to observe their behavior safely.
    *   **Cloud-Based Threat Intelligence:** Leveraging data from a global network of sensors to identify emerging threats.
    *   **Limitations:** Cannot detect all malware, can be bypassed by sophisticated attackers, can impact system performance.
    *   Importance of a layered security approach (AV is just one layer).
    *   <YouTube videoId_ HOW_ANTIVIRUS_SOFTWARE_REALLY_WORKS_by_Techquickie title="How Antivirus Software Really Works by Techquickie" /> (Placeholder - Techquickie often has good explanations)

*   **Lesson 4.12: Endpoint Detection and Response (EDR) and Extended Detection and Response (XDR)**
    *   **Endpoint Detection and Response (EDR):**
        *   Goes beyond traditional AV by continuously monitoring and collecting endpoint data (processes, network connections, file activity, user logins).
        *   Uses behavioral analysis, machine learning, and threat intelligence to detect suspicious activities and potential breaches that AV might miss.
        *   Provides investigation tools (e.g., process trees, event timelines) and response capabilities (e.g., isolate endpoint, kill process, remediate files).
    *   **Extended Detection and Response (XDR):**
        *   Extends EDR capabilities by correlating data from multiple security layers (endpoints, network, cloud, email, identity) to provide a more holistic view of threats.
        *   Aims to improve threat detection accuracy and speed up incident response by breaking down security silos.
    *   These are more advanced solutions typically found in enterprise environments.
    *   <YouTube videoId_ WHAT_IS_EDR_ENDPOINT_DETECTION_AND_RESPONSE_by_CrowdStrike title="What is EDR (Endpoint Detection and Response)? by CrowdStrike" /> (Placeholder - CrowdStrike is an EDR vendor)
    *   <YouTube videoId_ XDR_EXPLAINED_EXTENDED_DETECTION_AND_RESPONSE_by_Palo_Alto_Networks title="XDR Explained: Extended Detection and Response by Palo Alto Networks" /> (Placeholder - PAN is an XDR vendor)

*   **Lesson 4.13: Security Operations Center (SOC) - People, Processes, Technology**
    *   What is a SOC? A centralized unit that deals with security issues on an organizational and technical level. It's a team of people responsible for continuously monitoring and improving an organization's security posture while preventing, detecting, analyzing, and responding to cybersecurity incidents.
    *   **People:** SOC Analysts (Tiers 1, 2, 3), Security Engineers, Threat Hunters, Incident Responders, Forensics Investigators, SOC Manager.
    *   **Processes:** Incident response plans, playbooks for common alerts, threat intelligence gathering, vulnerability management procedures, reporting.
    *   **Technology:**
        *   SIEM (Security Information and Event Management) - Core tool for log aggregation, correlation, alerting.
        *   SOAR (Security Orchestration, Automation and Response) - Automating SOC workflows.
        *   EDR/XDR tools.
        *   Threat Intelligence Platforms (TIPs).
        *   Vulnerability Scanners.
        *   Network monitoring tools.
    *   Key functions: Monitoring, detection, investigation, response, reporting, continuous improvement.
    *   <YouTube videoId_ WHAT_IS_A_SOC_SECURITY_OPERATIONS_CENTER_AND_HOW_IT_WORKS_by_IBM_Security title="What is a SOC (Security Operations Center) and How It Works? by IBM Security" /> (Placeholder)

*   **Lesson 4.14: Incident Response Plan (IRP) - Key Components and Importance**
    *   Recap: IRP is a documented, systematic approach to handling security incidents.
    *   **Why is an IRP crucial?**
        *   Minimizes damage and recovery time/costs.
        *   Ensures a consistent and effective response.
        *   Meets regulatory/compliance requirements.
        *   Maintains customer trust and reputation.
    *   **Key Components of an IRP:**
        1.  **Preparation:** Roles and responsibilities, communication plan (internal/external), tools and resources, training and drills.
        2.  **Identification:** How incidents are detected (alerts, user reports, logs) and verified. Initial assessment of scope and severity.
        3.  **Containment:** Limiting the spread and impact of the incident (e.g., isolating affected systems, blocking traffic, disabling accounts). Short-term and long-term containment strategies.
        4.  **Eradication:** Removing the threat from affected systems (e.g., removing malware, patching vulnerabilities, resetting credentials).
        5.  **Recovery:** Restoring systems to normal operation (e.g., restoring from backups, rebuilding systems, validating functionality). Monitoring for re-infection.
        6.  **Lessons Learned (Post-Incident Activity):** Analyzing the incident (root cause, effectiveness of response), documenting findings, updating IRP and security controls to prevent recurrence.
    *   Regularly testing and updating the IRP.
    *   <YouTube videoId_ CREATING_AN_EFFECTIVE_INCIDENT_RESPONSE_PLAN_by_SANS_Institute title="Creating an Effective Incident Response Plan by SANS Institute" /> (Placeholder)

*   **Lesson 4.15: Business Continuity (BCP) vs. Disaster Recovery (DR)**
    *   **Business Continuity Planning (BCP):** A holistic management process that identifies potential threats to an organization and the impacts to business operations those threats, if realized, might cause. Provides a framework for building organizational resilience with the capability for an effective response that safeguards the interests of its key stakeholders, reputation, brand, and value-creating activities. (Focuses on keeping the business running).
    *   **Disaster Recovery (DR):** A subset of BCP. Focuses specifically on the IT infrastructure and processes to recover and protect IT systems in the event of a disaster (natural or man-made). (Focuses on IT system recovery).
    *   Key DR Metrics:
        *   RTO (Recovery Time Objective): Maximum acceptable downtime.
        *   RPO (Recovery Point Objective): Maximum acceptable data loss.
    *   DR Strategies: Backups, cold/warm/hot sites, cloud-based DR.
    *   BCP includes DR but also covers broader business aspects like personnel, facilities, supply chain, communications.
    *   <YouTube videoId_ BUSINESS_CONTINUITY_VS_DISASTER_RECOVERY_EXPLAINED_by_Simplilearn title="Business Continuity vs Disaster Recovery Explained by Simplilearn" /> (Placeholder)

This completes the expansion for Module 4 of Course 7.
---
### Module 5: Web Application Security Fundamentals (Expanded)

Web applications are common targets. This module covers common web vulnerabilities and how to protect against them, with expanded detail.

*   **Lesson 5.1: OWASP Top 10 - Understanding Common Web Vulnerabilities**
    *   Recap: Open Web Application Security Project (OWASP) and the OWASP Top 10 as a standard awareness document for critical web application security risks.
    *   Purpose: To educate developers, designers, architects, managers, and organizations about the consequences of the most common and most important web application security weaknesses.
    *   The list is updated periodically (e.g., 2017, 2021 versions). We will generally refer to concepts from recent versions.
    *   Briefly introduce each of the (current or recent) Top 10 categories. For example, using the 2021 list:
        1.  A01:2021-Broken Access Control
        2.  A02:2021-Cryptographic Failures (Sensitive Data Exposure)
        3.  A03:2021-Injection
        4.  A04:2021-Insecure Design
        5.  A05:2021-Security Misconfiguration
        6.  A06:2021-Vulnerable and Outdated Components
        7.  A07:2021-Identification and Authentication Failures (Broken Authentication)
        8.  A08:2021-Software and Data Integrity Failures
        9.  A09:2021-Security Logging and Monitoring Failures
        10. A10:2021-Server-Side Request Forgery (SSRF)
    *   Understanding that these are categories, and specific vulnerabilities fall under them.
    *   <YouTube videoId="pEWfKV6yqlY" title="The OWASP Top 10 (2021) by Professor Messer" /> (Recap)
    *   <YouTube videoId_ OWASP_TOP_10_2021_DEEP_DIVE_OVERVIEW_by_OWASP_Foundation title="OWASP Top 10 2021 Deep Dive Overview by OWASP Foundation or a trusted security channel" /> (Placeholder)

*   **Lesson 5.2: A01:2021 - Broken Access Control**
    *   What is Access Control? Policies and mechanisms that restrict what authenticated users can do or access within an application.
    *   Broken Access Control: When restrictions on what authenticated users are allowed to do are not properly enforced. Attackers can exploit these flaws to access unauthorized functionality and/or data.
    *   Common Examples:
        *   Accessing other users' accounts or data by modifying URL parameters (e.g., changing `?user_id=123` to `?user_id=124`).
        *   Privilege escalation: Gaining admin rights when one shouldn't have them.
        *   Bypassing access control checks by modifying requests or using API endpoints directly without proper authorization.
        *   Insecure Direct Object References (IDOR): Exposing a direct reference to an internal object (e.g., file path, database key) and not verifying access.
        *   Missing function-level access control (e.g., admin functions accessible to regular users if they know the URL).
    *   Prevention:
        *   Enforce access controls on the server-side (never rely on client-side controls alone).
        *   Principle of Least Privilege.
        *   Deny by default.
        *   Thorough testing of access control mechanisms.
        *   Use centralized access control logic.
    *   <YouTube videoId_ OWASP_BROKEN_ACCESS_CONTROL_EXPLAINED_A01_2021_by_HackerSploit title="OWASP Broken Access Control Explained (A01:2021) by HackerSploit" /> (Placeholder)

*   **Lesson 5.3: A02:2021 - Cryptographic Failures (Sensitive Data Exposure)**
    *   Occurs when sensitive data is not properly protected, either at rest or in transit, leading to its compromise.
    *   Types of Sensitive Data: Passwords, credit card numbers, health records (PHI), personally identifiable information (PII), trade secrets.
    *   Common Failures:
        *   Transmitting sensitive data in plaintext (e.g., over HTTP instead of HTTPS).
        *   Storing sensitive data in plaintext or with weak/deprecated encryption algorithms (e.g., MD5 for passwords, weak ciphers for data).
        *   Improper key management (hardcoded keys, weak keys, keys stored with encrypted data).
        *   Using default crypto keys.
        *   Not encrypting backups.
        *   Exposing sensitive data in URLs, logs, or error messages.
    *   Prevention:
        *   Encrypt all sensitive data at rest and in transit using strong, standard algorithms (AES, TLS).
        *   Proper key management (use KMS, HSMs).
        *   Secure password hashing (bcrypt, scrypt, Argon2, PBKDF2 with strong salt).
        *   Data classification to identify what needs protection.
        *   Minimize data storage.
    *   <YouTube videoId_ OWASP_CRYPTOGRAPHIC_FAILURES_SENSITIVE_DATA_EXPOSURE_A02_2021_by_InsiderPhD title="OWASP Cryptographic Failures (Sensitive Data Exposure A02:2021) by InsiderPhD" /> (Placeholder)

*   **Lesson 5.4: A03:2021 - Injection (SQL Injection, NoSQL Injection, OS Command Injection, XSS)**
    *   Injection flaws occur when untrusted user input is sent to an interpreter as part of a command or query.
    *   **SQL Injection (SQLi):** (Recap from Module 2, but focus on web app context)
        *   Injecting malicious SQL queries via input fields, URL parameters.
        *   Impact: Data theft, modification, deletion, server compromise.
        *   Prevention: Parameterized queries (prepared statements), input validation/sanitization, ORMs.
    *   **NoSQL Injection:** Similar to SQLi, but targets NoSQL databases (MongoDB, CouchDB, etc.) by injecting malicious syntax specific to that database's query language.
    *   **OS Command Injection:** Injecting OS commands into an application, which are then executed by the server's operating system.
        *   Impact: Remote code execution, full server compromise.
        *   Prevention: Avoid calling OS commands directly with user input. Use built-in language functions if possible. Sanitize input rigorously.
    *   **Cross-Site Scripting (XSS):** (Covered in more detail in next lesson, but it's an injection type).
    *   LDAP Injection, XPath Injection.
    *   <YouTube videoId="ciNHn38qYjg" title="SQL Injection Attacks - CompTIA Security+ SY0-601 by Professor Messer" /> (Recap SQLi)
    *   <YouTube videoId_ OS_COMMAND_INJECTION_EXPLAINED_AND_PREVENTION_by_PortSwigger_Web_Security title="OS Command Injection Explained and Prevention by PortSwigger Web Security Academy" /> (Placeholder)
    *   <YouTube videoId_ NOSQL_INJECTION_VULNERABILITIES_by_OWASP_Foundation title="NoSQL Injection Vulnerabilities by OWASP Foundation" /> (Placeholder)

*   **Lesson 5.5: Cross-Site Scripting (XSS) - Stored, Reflected, DOM-based**
    *   Recap: Injecting malicious client-side scripts (usually JavaScript) into web pages viewed by other users.
    *   **Stored (Persistent) XSS:**
        *   Malicious script is stored on the target server (e.g., in a database via a comment field, forum post, user profile).
        *   Executed every time a user views the page containing the stored script.
        *   Most damaging type.
    *   **Reflected (Non-Persistent) XSS:**
        *   Malicious script is embedded in a URL (e.g., in a query parameter of a search result page) or other input that is immediately reflected back to the user by the server.
        *   Executed when a user clicks a specially crafted link or submits a form.
        *   Requires social engineering to get victim to click the link.
    *   **DOM-based XSS:**
        *   Vulnerability exists in the client-side JavaScript code that manipulates the Document Object Model (DOM).
        *   Malicious script is executed in the victim's browser as a result of modifying the DOM environment (e.g., using data from `document.location.hash` or `localStorage` insecurely).
        *   Server may not even see the payload.
    *   Impact: Stealing session cookies/tokens, defacing websites, redirecting users, keylogging, installing malware (via browser exploits).
    *   Prevention: Input validation/sanitization (especially of output that will be rendered), output encoding (HTML entity encoding, JavaScript encoding), Content Security Policy (CSP), using secure frameworks that auto-escape.
    *   <YouTube videoId="L5l9lSnNM2g" title="Cross-Site Scripting - CompTIA Security+ SY0-601 by Professor Messer" /> (Recap)
    *   <YouTube videoId_ STORED_VS_REFLECTED_VS_DOM_XSS_EXPLAINED_by_PortSwigger_Web_Security title="Stored vs Reflected vs DOM XSS Explained by PortSwigger Web Security Academy" /> (Placeholder)

*   **Lesson 5.6: A04:2021 - Insecure Design**
    *   Focuses on risks related to design and architectural flaws, rather than implementation bugs.
    *   Represents missing or ineffective security controls, or design choices that make the application inherently vulnerable.
    *   Examples:
        *   Lack of threat modeling during design phase (not considering potential threats and mitigations).
        *   Insecure business logic flows (e.g., allowing password reset without proper verification, flaws in multi-step processes).
        *   Exposing unnecessary functionality or sensitive data flows.
        *   Not designing for scalability in a way that maintains security.
        *   Over-reliance on client-side controls for security.
        *   Insufficient protection against automated attacks (e.g., credential stuffing, scraping).
    *   Prevention:
        *   Integrate security into the entire software development lifecycle (SDL/SSDLC).
        *   Conduct threat modeling.
        *   Use secure design patterns and principles.
        *   "Security by Design" and "Privacy by Design."
        *   Regular architectural reviews.
    *   <YouTube videoId_ OWASP_INSECURE_DESIGN_A04_2021_EXPLAINED_by_Application_Security_Weekly title="OWASP Insecure Design (A04:2021) Explained by Application Security Weekly" /> (Placeholder)
    *   <YouTube videoId_ INTRODUCTION_TO_THREAT_MODELING_FOR_DEVELOPERS_by_Microsoft_Security title="Introduction to Threat Modeling for Developers by Microsoft Security" /> (Placeholder)

*   **Lesson 5.7: A05:2021 - Security Misconfiguration**
    *   Common issue resulting from insecure default configurations, incomplete or ad-hoc configurations, open cloud storage, misconfigured HTTP headers, or verbose error messages containing sensitive information.
    *   Examples:
        *   Running software with default credentials (admin/admin).
        *   Unnecessary features or services enabled (e.g., directory listing on web server, debug modes in production).
        *   Error messages revealing stack traces or sensitive system information.
        *   Outdated software or unpatched systems (falls under "Vulnerable and Outdated Components" too, but initial setup is misconfiguration).
        *   Improper security headers (e.g., missing `Content-Security-Policy`, `Strict-Transport-Security`).
        *   Cloud service misconfigurations (e.g., publicly accessible S3 buckets, overly permissive firewall rules).
        *   Permissions on files and directories set too loosely.
    *   Prevention:
        *   Hardening processes: Remove unnecessary features, change default credentials.
        *   Use automated tools to verify configurations (CSPM for cloud).
        *   Regularly patch and update all software.
        *   Implement secure baselines and templates.
        *   Configure error handling to show minimal information.
    *   <YouTube videoId_ OWASP_SECURITY_MISCONFIGURATION_A05_2021_EXPLAINED_by_HackerSploit title="OWASP Security Misconfiguration (A05:2021) Explained by HackerSploit" /> (Placeholder)

*   **Lesson 5.8: A06:2021 - Vulnerable and Outdated Components**
    *   Using software components (libraries, frameworks, modules, OS) with known vulnerabilities.
    *   Applications often rely on many third-party components. If any of these have flaws, the entire application can be at risk.
    *   Sources of risk:
        *   Unpatched operating systems or web server software.
        *   Using outdated libraries with known CVEs (Common Vulnerabilities and Exposures).
        *   Not updating dependencies regularly.
        *   Using components from untrusted sources or with no active maintenance.
    *   Prevention:
        *   Inventory all components and their versions.
        *   Regularly scan for vulnerabilities in components (Software Composition Analysis - SCA tools, `npm audit`, `pip check`).
        *   Patch and update components promptly when security fixes are available.
        *   Remove unused dependencies.
        *   Subscribe to security advisories for components used.
        *   Use components from official and trusted sources.
    *   <YouTube videoId_ OWASP_VULNERABLE_AND_OUTDATED_COMPONENTS_A06_2021_by_Snyk title="OWASP Vulnerable and Outdated Components (A06:2021) by Snyk" /> (Placeholder - Snyk specializes in this)

*   **Lesson 5.9: A07:2021 - Identification and Authentication Failures (Broken Authentication)**
    *   Vulnerabilities related to how users are identified (username, email) and authenticated (proving they are who they say they are, typically with a password or other factor).
    *   Common Issues:
        *   Allowing weak or easily guessable passwords.
        *   Not enforcing password complexity or rotation (though rotation is debated).
        *   Storing passwords insecurely (plaintext, weak hashing like MD5/SHA1 without salt).
        *   Not protecting against credential stuffing or brute-force attacks (e.g., no rate limiting on login attempts, no account lockout).
        *   Weak or flawed session management (e.g., predictable session IDs, session IDs exposed in URL, sessions not expiring).
        *   Not implementing Multi-Factor Authentication (MFA) or implementing it poorly.
        *   Flaws in password reset/recovery mechanisms.
    *   Prevention:
        *   Implement strong password policies.
        *   Use strong, salted, and iterated hashing algorithms for passwords (bcrypt, scrypt, Argon2, PBKDF2).
        *   Implement MFA.
        *   Protect against automated attacks (rate limiting, CAPTCHAs, account lockout).
        *   Secure session management (random, long session IDs; HTTPS only; HttpOnly, Secure, SameSite cookies; session timeouts).
    *   <YouTube videoId_ OWASP_BROKEN_AUTHENTICATION_A07_2021_EXPLAINED_by_PortSwigger_Web_Security title="OWASP Broken Authentication (A07:2021) Explained by PortSwigger Web Security Academy" /> (Placeholder)
    *   <YouTube videoId="gTqboriX-7A" title="Authentication and Authorization - CompTIA Security+ SY0-601 by Professor Messer" /> (Recap Authentication part)

*   **Lesson 5.10: A08:2021 - Software and Data Integrity Failures**
    *   Relates to code and infrastructure that does not protect against integrity violations.
    *   Examples:
        *   **Insecure Deserialization:** Deserializing untrusted user-supplied data without proper validation, which can lead to remote code execution if the deserialization process can be manipulated.
        *   **Software Updates without Integrity Checks:** Downloading and installing updates (software, plugins, dependencies) from untrusted sources or without verifying their digital signatures. This can lead to installing malware.
        *   **CI/CD Pipeline Compromise:** If an attacker can inject malicious code into the build or deployment pipeline, they can compromise the integrity of the deployed application.
        *   Not validating the integrity of data received from external sources.
    *   Prevention:
        *   Use digital signatures to verify the integrity and authenticity of software updates and components.
        *   Avoid deserializing untrusted data if possible, or use safe deserialization methods and strict type checking.
        *   Secure CI/CD pipelines (access controls, code signing, vulnerability scanning).
        *   Perform integrity checks on critical data.
    *   <YouTube videoId_ OWASP_INSECURE_DESERIALIZATION_EXPLAINED_by_HackerSploit title="OWASP Insecure Deserialization Explained by HackerSploit" /> (Placeholder)
    *   <YouTube videoId_ SOFTWARE_SUPPLY_CHAIN_SECURITY_BEST_PRACTICES_by_CNCF title="Software Supply Chain Security Best Practices by CNCF" /> (Placeholder - relates to CI/CD integrity)

*   **Lesson 5.11: A09:2021 - Security Logging and Monitoring Failures**
    *   Insufficient logging, monitoring, or alerting can prevent or delay the detection of security breaches.
    *   Common Failures:
        *   Not logging important security events (logins, failed logins, access control failures, high-value transactions, admin actions, errors).
        *   Logs not being stored securely or for a sufficient period.
        *   Logs not being monitored or analyzed for suspicious activity.
        *   Lack of effective alerting for critical security events.
        *   Logs not providing enough context to understand an event.
    *   Prevention:
        *   Log all critical security events with sufficient detail (who, what, when, where, how).
        *   Use a centralized logging solution (e.g., SIEM).
        *   Implement real-time monitoring and alerting for suspicious activities and critical events.
        *   Regularly review logs and audit trails.
        *   Protect logs from tampering or unauthorized access.
        *   Ensure logs are in a format that can be easily analyzed.
    *   <YouTube videoId_ EFFECTIVE_SECURITY_LOGGING_AND_MONITORING_by_SANS_Institute title="Effective Security Logging and Monitoring by SANS Institute" /> (Placeholder)

*   **Lesson 5.12: A10:2021 - Server-Side Request Forgery (SSRF)**
    *   SSRF flaws occur whenever a web application is fetching a remote resource without validating the user-supplied URL.
    *   It allows an attacker to coerce the application to send a crafted request to an unexpected destination, even when protected by a firewall, VPN, or another type of network access control list (ACL).
    *   Impact:
        *   Attack internal systems behind a firewall (port scanning, accessing internal services).
        *   Access cloud provider metadata services (e.g., AWS EC2 instance metadata service at 169.254.169.254 to steal credentials).
        *   Exfiltrate data.
        *   Perform DoS attacks on other systems.
    *   Prevention:
        *   Validate and sanitize all user-supplied input URLs.
        *   Use allow-lists (whitelists) of permitted domains, protocols, and ports.
        *   Disable unused URL schemas.
        *   Ensure the server-side application does not directly send requests to user-provided URLs if possible. Use indirect methods or isolate the request-making component.
        *   Network segmentation to limit the impact if an SSRF occurs.
    *   <YouTube videoId_ SSRF_SERVER_SIDE_REQUEST_FORGERY_EXPLAINED_by_PortSwigger_Web_Security title="SSRF (Server-Side Request Forgery) Explained by PortSwigger Web Security Academy" /> (Placeholder)
    *   <YouTube videoId_ AWS_EC2_INSTANCE_METADATA_SERVICE_IMDSV2_AND_SSRF_PROTECTION_by_AWS title="AWS EC2 Instance Metadata Service (IMDSv2) and SSRF Protection by AWS" /> (Placeholder - shows mitigation)

*   **Lesson 5.13: Cross-Site Request Forgery (CSRF/XSRF)**
    *   An attack that forces an end user to execute unwanted actions on a web application in which they're currently authenticated.
    *   How it works: Attacker crafts a malicious request (e.g., in an email link, image tag on a malicious site) that, when the victim clicks or loads it, makes their browser send the request to the vulnerable application. The application thinks the request is legitimate because the victim is authenticated (e.g., has a valid session cookie).
    *   Impact: Can result in state-changing requests like transferring funds, changing email/password, deleting data, if the application relies solely on session cookies for authorization of these actions.
    *   Prevention:
        *   **Anti-CSRF Tokens (Synchronizer Token Pattern):** Server generates a unique, unpredictable token for each session or request, embeds it in forms/requests. Server validates this token on submission.
        *   **SameSite Cookie Attribute:** `SameSite=Lax` or `SameSite=Strict` can help mitigate by controlling when cookies are sent with cross-site requests.
        *   Checking `Origin` or `Referer` headers (can be unreliable).
        *   Requiring re-authentication for sensitive operations.
    *   <YouTube videoId_ CSRF_CROSS_SITE_REQUEST_FORGERY_EXPLAINED_by_Computerphile title="CSRF (Cross-Site Request Forgery) Explained by Computerphile" /> (Placeholder)
    *   <YouTube videoId_ OWASP_CSRF_PREVENTION_CHEAT_SHEET_OVERVIEW_by_OWASP_Foundation title="OWASP CSRF Prevention Cheat Sheet Overview by OWASP Foundation" /> (Placeholder)

*   **Lesson 5.14: Clickjacking (UI Redressing)**
    *   A malicious technique of tricking a user into clicking on something different from what the user perceives they are clicking on, thus potentially revealing confidential information or taking control of their computer while clicking on seemingly innocuous web pages.
    *   How it works: Attacker loads the target website in a transparent `<iframe>` overlaid on top of a decoy website. The user thinks they are clicking buttons on the decoy site, but are actually clicking buttons on the hidden, legitimate site (e.g., "Like" button, "Transfer Funds" button).
    *   Prevention:
        *   **X-Frame-Options HTTP Header:** Tells the browser whether a page can be rendered in an `<iframe>`, `<frame>`, or `<object>`.
            *   `DENY`: Page cannot be displayed in a frame.
            *   `SAMEORIGIN`: Page can only be displayed in a frame on the same origin.
            *   `ALLOW-FROM uri`: (Obsolete, don't use).
        *   **Content Security Policy (CSP) `frame-ancestors` directive:** More flexible and modern replacement for `X-Frame-Options`.
            *   `frame-ancestors 'none'`: Similar to `X-Frame-Options: DENY`.
            *   `frame-ancestors 'self'`: Similar to `X-Frame-Options: SAMEORIGIN`.
        *   Frame-busting JavaScript (less reliable).
    *   <YouTube videoId_ CLICKJACKING_EXPLAINED_AND_HOW_TO_PREVENT_IT_by_PortSwigger_Web_Security title="Clickjacking Explained and How to Prevent It by PortSwigger Web Security Academy" /> (Placeholder)

*   **Lesson 5.15: HTTP Security Headers - Best Practices**
    *   HTTP headers that web applications can use to instruct browsers on how to behave, enhancing security.
    *   **`Strict-Transport-Security` (HSTS):** Tells browsers to only communicate with the server using HTTPS, preventing SSL stripping attacks.
    *   **`Content-Security-Policy` (CSP):** Controls resources the browser is allowed to load for a given page (scripts, styles, images, etc.). Helps prevent XSS and data injection attacks.
    *   **`X-Content-Type-Options: nosniff`:** Prevents browsers from MIME-sniffing a response away from the declared content-type.
    *   **`X-Frame-Options` (or CSP `frame-ancestors`):** Prevents clickjacking.
    *   **`Referrer-Policy`:** Controls how much referrer information is sent with requests.
    *   **`Permissions-Policy` (formerly `Feature-Policy`):** Allows sites to enable or disable browser features and APIs (e.g., camera, microphone, geolocation).
    *   Tools like securityheaders.com to check a website's headers.
    *   <YouTube videoId_ HTTP_SECURITY_HEADERS_YOU_SHOULD_BE_USING_by_Scott_Helme title="HTTP Security Headers You Should Be Using by Scott Helme" /> (Placeholder - Scott Helme is an expert)
    *   <YouTube videoId_ INTRODUCTION_TO_CONTENT_SECURITY_POLICY_CSP_by_Google_Developers title="Introduction to Content Security Policy (CSP) by Google Developers" /> (Placeholder)

This completes the expansion for Module 5 of Course 7.
---
### Module 6: Ethical Hacking Methodology and Tools (Expanded)

This module introduces the structured approach used by ethical hackers and some of the common tools involved, with expanded details.

*   **Lesson 6.1: The Penetration Testing Execution Standard (PTES) - Overview**
    *   PTES: A standard designed to provide a common language and scope for penetration testing services.
    *   Seven Main Sections:
        1.  **Pre-engagement Interactions:** Defining scope, rules of engagement, legal agreements, communication plan.
        2.  **Intelligence Gathering (Reconnaissance):** OSINT, identifying target infrastructure and personnel.
        3.  **Threat Modeling:** Identifying potential threats and vulnerabilities based on target's business and architecture.
        4.  **Vulnerability Analysis:** Discovering flaws in systems and applications (active scanning, manual testing).
        5.  **Exploitation (Gaining Access):** Attempting to leverage vulnerabilities to gain unauthorized access.
        6.  **Post-Exploitation:** Determining value of compromised systems, maintaining access (if in scope), escalating privileges, pivoting to other systems.
        7.  **Reporting:** Documenting findings, vulnerabilities, impact, and remediation recommendations.
    *   How PTES provides a more detailed framework than basic "Phases of Hacking."
    *   <YouTube videoId_ INTRODUCTION_TO_THE_PENETRATION_TESTING_EXECUTION_STANDARD_PTES_by_HackerSploit title="Introduction to the Penetration Testing Execution Standard (PTES) by HackerSploit" /> (Placeholder)

*   **Lesson 6.2: Reconnaissance - Passive Techniques (OSINT)**
    *   Gathering information about a target without directly interacting with their systems.
    *   **Google Dorking (Google Hacking):** Using advanced Google search operators (`site:`, `filetype:`, `inurl:`, `intitle:`, etc.) to find sensitive information, login pages, exposed documents, vulnerable software versions.
    *   **WHOIS Lookup:** Finding domain registration information (registrant, admin/tech contacts, name servers).
    *   **DNS Enumeration (Passive):** Using public DNS records (MX, NS, TXT) to map out infrastructure. Tools like DNSdumpster.com.
    *   **Shodan / Censys / ZoomEye:** Search engines for internet-connected devices and services. Can find exposed servers, IoT devices, control systems.
    *   **Social Media Profiling:** Gathering information about employees (roles, interests, connections) from LinkedIn, Twitter, Facebook, etc. Useful for social engineering.
    *   **Company Website Analysis:** About Us, Careers, Investor Relations pages can reveal technologies used, employee names, company structure.
    *   **Job Postings:** Can reveal technologies and software used internally.
    *   **Public Code Repositories (GitHub, GitLab):** Searching for leaked credentials, sensitive information, or code related to the target.
    *   Tools: TheHarvester, Maltego (for visualizing relationships), Recon-ng.
    *   <YouTube videoId="JTfhYyTuT44" title="Passive Reconnaissance - CompTIA PenTest+ PT0-002 by Professor Messer" /> (Recap)
    *   <YouTube videoId_ OSINT_FOR_PENTESTERS_TOOLS_AND_TECHNIQUES_by_The_Cyber_Mentor title="OSINT for Pentesters: Tools and Techniques by The Cyber Mentor" /> (Placeholder)

*   **Lesson 6.3: Reconnaissance - Active Techniques (Scanning)**
    *   Directly interacting with target systems to gather information. Can be detected.
    *   **Port Scanning (Nmap):** Identifying open TCP/UDP ports and services running on them.
        *   TCP Connect Scan (`-sT`): Completes full TCP handshake. Reliable but easily logged.
        *   SYN Scan (`-sS` - Stealth Scan): Sends SYN packet, waits for SYN-ACK, sends RST. Faster, less likely to be logged by some systems. Requires root/admin.
        *   UDP Scan (`-sU`): Slower, less reliable due to UDP's connectionless nature.
        *   Version Detection (`-sV`): Tries to determine service versions.
        *   OS Detection (`-O`): Tries to identify the operating system.
    *   **Network Sweeping (Ping Sweeps):** Identifying live hosts on a network.
        *   Nmap: `nmap -sn <target_range>` (uses ICMP echo, TCP SYN to port 443, TCP ACK to port 80, ICMP timestamp request).
        *   Other tools like `fping`.
    *   **Banner Grabbing:** Connecting to open ports to retrieve service banners (which often reveal service type and version). Tools: `netcat`, `telnet`, Nmap scripts.
    *   Ethical considerations: Ensure active scanning is within scope and authorized.
    *   <YouTube videoId_ ACTIVE_RECONNAISSANCE_PORT_SCANNING_WITH_NMAP_by_HackerSploit title="Active Reconnaissance: Port Scanning with Nmap by HackerSploit" /> (Placeholder)

*   **Lesson 6.4: Enumeration - Discovering More Details**
    *   After initial scanning, enumeration involves more intrusive probing to gather detailed information about specific services, users, shares, and configurations.
    *   **NetBIOS Enumeration (Windows):** Identifying NetBIOS names, shares, users (e.g., `nbtscan`, Nmap `nbstat` script).
    *   **SNMP Enumeration (Network Devices, Servers):** Simple Network Management Protocol. Default community strings ("public", "private") can allow access to system information, routing tables, user accounts. (e.g., `snmpwalk`, Nmap SNMP scripts).
    *   **LDAP Enumeration (Directory Services):** Querying Lightweight Directory Access Protocol servers for user accounts, groups, organizational structure.
    *   **SMTP Enumeration:** Commands like `VRFY` (verify email address), `EXPN` (expand mailing list), `RCPT TO` can reveal valid email addresses/users (often disabled now).
    *   **DNS Zone Transfers (if misconfigured):** Attempting to get a full copy of a DNS zone's records from an authoritative name server.
    *   **RPC (Remote Procedure Call) Enumeration.**
    *   Tools: enum4linux, Nmap scripting engine (NSE).
    *   <YouTube videoId_ ENUMERATION_TECHNIQUES_IN_PENETRATION_TESTING_NETBIOS_SNMP_LDAP_by_The_Cyber_Mentor title="Enumeration Techniques in Penetration Testing (NetBIOS, SNMP, LDAP) by The Cyber Mentor" /> (Placeholder)

*   **Lesson 6.5: Vulnerability Scanning with Nessus/OpenVAS (Practical Use)**
    *   Recap: Automated tools for identifying known vulnerabilities.
    *   **Nessus Essentials:**
        *   Setting up a scan policy (e.g., Basic Network Scan, Web App Tests).
        *   Defining targets (IP addresses, ranges, hostnames).
        *   Running authenticated vs. unauthenticated scans (authenticated scans provide deeper visibility by logging into systems).
        *   Interpreting scan results: Vulnerability name, severity (Critical, High, Medium, Low, Info), CVE ID, description, solution/remediation advice, plugin output.
        *   Understanding false positives and false negatives.
    *   **OpenVAS (Greenbone Vulnerability Management):**
        *   Similar process: Target definition, scan configuration, result analysis.
    *   Integrating vulnerability scan results into the overall penetration testing process.
    *   <YouTube videoId_ NESSUS_TUTORIAL_FROM_INSTALLATION_TO_ADVANCED_SCANNING_by_HackerSploit title="Nessus Tutorial: From Installation to Advanced Scanning by HackerSploit" /> (Placeholder)
    *   <YouTube videoId_ OPENVAS_GREENBONE_VULNERABILITY_SCANNER_FULL_TUTORIAL_by_StationX title="OpenVAS (Greenbone) Vulnerability Scanner Full Tutorial by StationX" /> (Placeholder)

*   **Lesson 6.6: Exploitation Fundamentals - Concepts and Metasploit Introduction**
    *   What is Exploitation? The process of leveraging a vulnerability to gain unauthorized access, execute code, or achieve a specific malicious objective.
    *   Types of Exploits: Remote exploits, local exploits (require prior access).
    *   Payloads: The code delivered by the exploit that runs on the compromised system.
        *   Bind Shell: Opens a listener on the target system, attacker connects to it.
        *   Reverse Shell: Target system connects back to a listener on the attacker's machine (often better for bypassing firewalls).
        *   Meterpreter (Metasploit): Advanced, extensible payload with many post-exploitation capabilities.
    *   **Metasploit Framework:**
        *   Recap: Open-source penetration testing framework.
        *   `msfconsole`: The primary command-line interface.
        *   Key commands: `search` (for exploits/modules), `use <module_path>`, `show options`, `set <OPTION_NAME> <value>`, `exploit` (or `run`), `sessions`.
        *   Understanding module types: `exploit`, `payload`, `auxiliary`, `post`, `encoder`, `nop`.
    *   Ethical considerations: Only exploit systems you have explicit permission to test.
    *   <YouTube videoId_ METASPLOIT_FRAMEWORK_FOR_BEGINNERS_CORE_CONCEPTS_AND_MSFCONSOLE_by_The_Cyber_Mentor title="Metasploit Framework for Beginners: Core Concepts and msfconsole by The Cyber Mentor" /> (Placeholder)

*   **Lesson 6.7: Practical Exploitation Example with Metasploit (e.g., vsftpd Backdoor on Metasploitable)**
    *   Step-by-step walkthrough of exploiting a known vulnerability on Metasploitable 2.
    *   Target: vsftpd 2.3.4 backdoor (CVE-2011-2523).
    *   Process in `msfconsole`:
        1.  `search vsftpd`
        2.  `use exploit/unix/ftp/vsftpd_234_backdoor`
        3.  `show options` (to see RHOSTS, RPORT)
        4.  `set RHOSTS <metasploitable_ip>`
        5.  `show payloads` (optional, often a default command shell payload is selected)
        6.  `exploit`
        7.  If successful, a command shell session is opened on the target.
    *   Demonstrating basic commands on the compromised system.
    *   This lesson emphasizes responsible use in a lab environment.
    *   <YouTube videoId_ EXPLOITING_VSFTPD_BACKDOOR_WITH_METASPLOIT_ON_METASPLOITABLE_2_by_HackingSimplified title="Exploiting VSFTPD Backdoor with Metasploit on Metasploitable 2 by HackingSimplified" /> (Placeholder)

*   **Lesson 6.8: Post-Exploitation - Basics (Privilege Escalation, Pivoting - Conceptual)**
    *   What happens after initial access is gained.
    *   **Privilege Escalation:** Attempting to gain higher-level permissions on the compromised system (e.g., from a regular user to root/administrator).
        *   Techniques: Exploiting kernel vulnerabilities, misconfigured SUID/GUID binaries, weak service permissions, password harvesting.
    *   **Pivoting:** Using a compromised system to attack other systems within the internal network that were not directly accessible from the outside.
        *   Setting up routes or proxies through the compromised host.
    *   **Information Gathering (Internal Reconnaissance):** Exploring the compromised system and internal network.
    *   **Maintaining Access (Persistence):** Installing backdoors, creating scheduled tasks, adding user accounts (ethically, to demonstrate risk).
    *   **Data Exfiltration (Conceptual):** Extracting sensitive data (for a real attacker).
    *   These are advanced topics, introduced conceptually.
    *   <YouTube videoId_ POST_EXPLOITATION_TECHNIQUES_PRIVILEGE_ESCALATION_AND_PIVOTING_by_PentesterAcademy title="Post-Exploitation Techniques: Privilege Escalation and Pivoting by PentesterAcademy" /> (Placeholder)
    *   <YouTube videoId_ WINDOWS_PRIVILEGE_ESCALATION_BASICS_by_TheXSSrat title="Windows Privilege Escalation Basics by TheXSSrat" /> (Placeholder - example)

*   **Lesson 6.9: Web Application Hacking Tools - Burp Suite / OWASP ZAP (Introduction)**
    *   Tools specifically designed for testing web application security.
    *   **Burp Suite (Community Edition is free, Professional is paid):**
        *   Integrated platform for web app security testing.
        *   Key features: Intercepting Proxy (view and modify HTTP/S requests/responses), Repeater (manually resend and modify requests), Intruder (automate custom attacks), Scanner (automated vulnerability detection - Pro only), Decoder, Comparer.
        *   Setting up browser proxy to work with Burp.
    *   **OWASP ZAP (Zed Attack Proxy):**
        *   Free, open-source web application security scanner.
        *   Similar features: Intercepting proxy, active scanner, passive scanner, spider, fuzzer.
    *   Basic usage: Intercepting requests, modifying parameters, looking for common vulnerabilities like XSS, SQLi.
    *   <YouTube videoId_ BURP_SUITE_FOR_BEGINNERS_GETTING_STARTED_by_InsiderPhD title="Burp Suite for Beginners: Getting Started by InsiderPhD" /> (Placeholder)
    *   <YouTube videoId_ OWASP_ZAP_TUTORIAL_FOR_WEB_APPLICATION_PENTESTING_by_HackerSploit title="OWASP ZAP Tutorial for Web Application Pentesting by HackerSploit" /> (Placeholder)

*   **Lesson 6.10: Password Cracking Basics - Tools and Techniques (Hydra, John the Ripper)**
    *   Attacking authentication mechanisms by trying to guess or crack passwords.
    *   **Online Attacks (against live services):**
        *   Brute-force: Trying all combinations.
        *   Dictionary attack: Using lists of common words/passwords.
        *   Tools like **Hydra** can automate online password guessing against various protocols (HTTP, FTP, SSH, RDP, etc.). (Use only against authorized targets in lab).
    *   **Offline Attacks (against stolen password hashes):**
        *   If password hashes are obtained (e.g., from a database breach).
        *   Tools like **John the Ripper (JTR)** or **Hashcat** are used.
        *   Techniques: Dictionary attacks, brute-force (with masks), rainbow tables (less effective against salted hashes).
        *   Importance of strong password policies, MFA, and secure password hashing (salting, key stretching) to defend against these.
    *   <YouTube videoId_ PASSWORD_CRACKING_WITH_JOHN_THE_RIPPER_AND_HYDRA_by_The_Cyber_Mentor title="Password Cracking with John the Ripper and Hydra by The Cyber Mentor" /> (Placeholder)

*   **Lesson 6.11: Wireless Network Hacking Basics (Conceptual - WEP, WPA/WPA2)**
    *   **Disclaimer: Only test networks you own or have explicit permission for. Unauthorized Wi-Fi hacking is illegal.**
    *   Common Wi-Fi Security Protocols: WEP (broken), WPA, WPA2, WPA3 (strongest).
    *   **WEP Cracking:** Vulnerable due to weak IVs and RC4 algorithm flaws. Tools like Aircrack-ng can crack WEP keys relatively easily by capturing enough packets.
    *   **WPA/WPA2 PSK (Pre-Shared Key) Cracking:**
        *   Capturing the 4-way handshake (when a client connects).
        *   Using tools like Aircrack-ng with a wordlist (dictionary attack) to try and crack the PSK offline.
        *   Strength depends on the complexity of the PSK.
    *   WPS (Wi-Fi Protected Setup) PIN vulnerability (older routers).
    *   Rogue Access Points and Evil Twins.
    *   Deauthentication Attacks (to force clients to reconnect and capture handshake).
    *   This is a high-level overview of concepts.
    *   <YouTube videoId_ WIFI_HACKING_FOR_BEGINNERS_WEP_WPA_WPA2_CRACKING_WITH_AIRCRACK_NG_by_HackerSploit title="WiFi Hacking for Beginners (WEP, WPA/WPA2 Cracking with Aircrack-ng) by HackerSploit" /> (Placeholder - for conceptual understanding in a lab)

*   **Lesson 6.12: Social Engineering Toolkit (SET) - Overview**
    *   An open-source penetration testing framework designed for social engineering attacks.
    *   Automates many common social engineering attack vectors.
    *   Features:
        *   Spear-phishing attack vectors.
        *   Website attack vectors (e.g., credential harvester, Java applet attack).
        *   Infectious media generator (e.g., creating malicious payloads for USBs).
        *   Mass mailer.
        *   Creating fake login pages.
    *   Used by ethical hackers to test an organization's susceptibility to social engineering.
    *   **Emphasize ethical use and that this tool should only be used with explicit authorization.**
    *   <YouTube videoId_ SOCIAL_ENGINEERING_TOOLKIT_SET_TUTORIAL_AND_DEMO_by_Hak5 title="Social Engineering Toolkit (SET) Tutorial and Demo by Hak5" /> (Placeholder)

*   **Lesson 6.13: Introduction to Digital Forensics and Incident Response (DFIR)**
    *   **Digital Forensics:** The process of identifying, preserving, analyzing, and presenting digital evidence in a manner that is legally admissible.
        *   Investigating cybercrimes, data breaches, policy violations.
        *   Disk forensics, memory forensics, network forensics, mobile forensics.
    *   **Incident Response (IR):** (Recap from Module 4) The actions taken to deal with and manage the aftermath of a security breach or cyberattack.
    *   How DFIR and IR are related: Forensic analysis is often a key part of the "Detection & Analysis" and "Post-Incident Activity" phases of IR.
    *   Importance of evidence integrity (chain of custody).
    *   This is an awareness lesson, DFIR is a specialized field.
    *   <YouTube videoId_ WHAT_IS_DIGITAL_FORENSICS_AND_INCIDENT_RESPONSE_DFIR_by_SANS_Institute title="What is Digital Forensics and Incident Response (DFIR)? by SANS Institute" /> (Placeholder)

*   **Lesson 6.14: Writing Effective Penetration Testing Reports**
    *   Recap: The report is a critical deliverable of a penetration test.
    *   Key Sections of a Report:
        1.  **Executive Summary:** High-level overview for management. Focus on business impact, overall risk posture, key findings, and strategic recommendations. Avoid overly technical jargon.
        2.  **Introduction:** Scope of the test, timeframe, methodologies used, assumptions, limitations.
        3.  **Findings and Vulnerabilities:** Detailed description of each vulnerability found.
            *   Name of vulnerability, CVE ID (if applicable).
            *   Affected systems/applications/URLs.
            *   Severity rating (e.g., Critical, High, Medium, Low - often using CVSS).
            *   Detailed steps to reproduce the vulnerability (with screenshots/evidence).
            *   Potential impact if exploited.
        4.  **Remediation Recommendations:** Specific, actionable steps to fix each vulnerability. Prioritized based on severity.
        5.  **Conclusion:** Overall summary of security posture.
        6.  **Appendices (Optional):** Tools used, raw output, detailed logs.
    *   Clarity, accuracy, professionalism. Tailor language to the audience.
    *   <YouTube videoId_ HOW_TO_WRITE_A_GOOD_PENETRATION_TESTING_REPORT_TIPS_AND_TEMPLATE_by_The_Cyber_Mentor title="How to Write a Good Penetration Testing Report: Tips and Template by The Cyber Mentor" /> (Placeholder)

*   **Lesson 6.15: Continuous Learning in Cybersecurity and Ethical Hacking - Staying Updated**
    *   The threat landscape and technologies are constantly evolving.
    *   Resources for staying updated:
        *   Security news websites (The Hacker News, Bleeping Computer, Threatpost, Krebs on Security).
        *   Vendor security blogs (Microsoft, Cisco, Palo Alto Networks, CrowdStrike, etc.).
        *   CVE databases (NVD, MITRE).
        *   Security podcasts (Security Now, Darknet Diaries, Risky Business).
        *   Twitter (follow security researchers and organizations).
        *   Capture The Flag (CTF) competitions for hands-on practice.
        *   Home labs for experimentation.
        *   Industry certifications (Security+, CEH, OSCP, CISSP, etc. - for further career development).
        *   Online courses and training platforms.
    *   Importance of a passion for learning and curiosity.
    *   <YouTube videoId_ HOW_TO_STAY_UP_TO_DATE_IN_CYBERSECURITY_RESOURCES_AND_TIPS_by_Professor_Messer title="How to Stay Up-to-Date in Cybersecurity: Resources and Tips by Professor Messer" /> (Placeholder)

This completes the expansion for all modules of Course 7.
