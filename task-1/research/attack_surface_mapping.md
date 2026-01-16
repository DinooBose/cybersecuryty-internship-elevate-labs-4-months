## Types of Attackers

 |Attacker Type       |	Motivation              | Skill Level | Typical Targets                          |
 |--------------------|-------------------------|-------------|------------------------------------------|
 |Script Kiddies      |	Curiosity, fun          |	Low         |	Easy targets, known vulnerabilities      |
 |Insiders            | Revenge, financial gain |	Medium-High	| Company data, intellectual property      |
 |Hacktivists         | Political/social agenda |	Medium    	| Government sites, corporate websites     |
 |Nation-State Actors	| Espionage, warfare      |	Very High   |	Critical infrastructure, military secrets|
 |Organized Crime     |	Financial profit	      | High      	| Banking systems, customer data           |
 |Competitors         |	Business advantage	    | Medium-High	| Trade secrets, R&D data                  |


## Attack Surface Analysis

  Attack surface refers to all possible points where an unauthorized user can try to enter or extract data from a system.

Common Attack Surfaces:

    1. Web Applications     : SQL injection, XSS vulnerabilities

    2. Mobile Apps          : Insecure data storage, weak encryption

    3. APIs                 : Broken authentication, excessive data exposure

    4. Networks             : Unsecured ports, misconfigured firewalls

    5. Cloud Infrastructure : Misconfigured storage buckets, weak IAM policies

    6. Human Element        : Phishing, social engineering

    7. Physical Access      : Unsecured devices, stolen hardware

## Daily Application Mapping to Attack Surfaces
|Application |	Primary Attack Surface |	Potential Attacks|
|------------|------------------------|------------------|
|Email (Gmail)	| Web interface, SMTP/IMAP protocols |	Phishing, credential theft, malware attachments|
|WhatsApp	|Mobile app, end-to-end encryption	| Social engineering, fake messages, backup interception|
|Banking Apps	| Mobile/Web app, APIs	| Man-in-the-middle, session hijacking, credential stuffing|
|E-commerce Sites	| Web app, payment gateway |	Card skimming, account takeover, API abuse|

## Data Flow & Attack Points
User → [Browser/App] → [Load Balancer] → [Web Server] → [Application Server] → [Database]

Attack Points:
1. User Device: Malware, keyloggers
2. Network Transmission: Packet sniffing, MITM attacks
3. Load Balancer: DDoS attacks
4. Web Server: Server misconfigurations, outdated software
5. Application Server: Business logic flaws, insecure APIs
6. Database: SQL injection, unauthorized data access
7. Human User: Social engineering, credential sharing
