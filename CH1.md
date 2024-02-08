# Study Guide: Information Systems Security

## Chapter 1: Information Systems Security

### Learning Objective(s) and Key Concepts

**Learning Objective(s):**
- Explain information systems security and its effect on people and businesses.

**Key Concepts:**
- Information systems security concepts
- Confidentiality, integrity, and availability (C-I-A)
- The seven domains of an IT infrastructure
- The weakest link in the security of an IT infrastructure
- IT security policy framework and data classification standard

### Information Systems Security (1 of 3)

- **Internet:**
  - A worldwide network with approximately 5 billion users
  - Includes governments, businesses, and organizations
  - Links communication networks to one another

- **World Wide Web:**
  - A system defining how documents and resources relate across a network of computers

### Information Systems Security (2 of 3)

- **First American Financial Corporation, 2019:**
  - 885 million users had sensitive personal financial data leaked
  - Hackers extracted data, posing a risk of identity theft

- **FireEye, 2020:**
  - Penetration testing tools were stolen, posing a threat to companies

### Cyberspace: The New Frontier

### TCP/IP Communications Are in Cleartext

### Information Systems Security (3 of 3)

- **Internet of Things (IoT):**
  - Connects personal devices, home devices, and vehicles to the Internet
  - Increases the amount of data to steal
  - Emphasizes cybersecurity as a duty for governments and data security as a responsibility for organizations

### IoT

### Risks, Threats, and Vulnerabilities

- **Risk:**
  - The level of exposure to an event affecting an asset

- **Threat:**
  - Any action, natural or human-induced, that could damage an asset

- **Vulnerability:**
  - A weakness allowing a threat to be realized or affect an asset

### What Is Information Systems Security?

- **Information System:**
  - Hardware, operating system, and application software working together to collect, process, and store data

- **Security:**
  - Being free from danger or risk

- **Information Systems Security:**
  - Collection of activities protecting the information system and stored data

### What Are We Securing?

### Compliance Laws and Regulations Drive the Need for Information Systems Security

### Tenets of Information Security

- **Confidentiality:**
  - Only authorized users can view information

- **Integrity:**
  - Only authorized users can change information

- **Availability:**
  - Information is accessible by authorized users whenever they request it

### Confidentiality (1 of 2)

- **Confidential Information Includes:**
  - Private data of individuals
  - Intellectual property of businesses
  - National security for countries and governments

### Confidentiality (2 of 2)

- **Cryptography:**
  - Practice of hiding data from unauthorized users

- **Encryption:**
  - Process of transforming data from cleartext into ciphertext

- **Ciphertext:**
  - Scrambled data resulting from encrypting cleartext

### Encryption of Cleartext into Ciphertext

### Integrity

- Maintain valid and accurate information

### Availability

- In the context of information security
- The amount of time users can use a system, application, and data

### Availability Time Measurements

- Uptime
- Downtime
- Availability [A = (Total Uptime)/(Total Uptime + Total Downtime)]
- Mean time to failure (MTTF)
- Mean time to repair (MTTR)
- Mean time between failures (MTBF)
- Recovery point objective (RPO)
- Recovery time objective (RTO)

### Seven Domains of a Typical IT Infrastructure

### User Domain

- **Roles and Tasks:**
  - Users access systems, applications, and data based on defined access rights

- **Responsibilities:**
  - Employees are responsible for their use of IT assets

- **Accountability:**
  - Human resources department is accountable for implementing proper employee background checks

### Common Threats in the User Domain

- Unauthorized access
- Lack of user awareness
- User apathy toward policies
- Security policy violations
- User inserting CD/DVD/USB with personal files
- User downloading photos, music, or videos
- User destroying systems, applications, and data
- Disgruntled employee attacking organization or committing sabotage
- Employee romance gone bad
- Employee blackmail or extortion

### Workstation Domain

- **Roles and Tasks:**
  - Configure hardware, harden systems, and verify antivirus files

- **Responsibilities:**
  - Ensure integrity of user workstations and data

- **Accountability:**
  - Ensure Workstation Domain conforms to policy

### Common Threats in the Workstation Domain

- Unauthorized workstation access
- Unauthorized access to systems, applications, and data
- Desktop or laptop OS and software vulnerabilities
- Viruses, malicious code, and other malware
- User inserting CD/DVD/USB with personal files
- User downloading photos, music, or videos
- Security risk due to user violation of acceptable use policy (AUP)
- Bring Your Own Device (BYOD)

### LAN Domain

- **Roles and Tasks:**
  - Includes physical network components and logical configuration of services for users

- **Responsibilities:**
  - Maximize use and integrity of data within the LAN Domain

- **Accountability:**
  - Ensure LAN Domain conforms to policy

### Common Threats in the LAN Domain

- Unauthorized access to LAN
- Unauthorized access to systems, applications, and data
- LAN server OS software vulnerabilities
- LAN server app software vulnerabilities and patches
- Unauthorized access by rogue users on WLANs
- Compromised confidentiality of data on WLANs
- LAN servers with different hardware, OS, and software make them difficult to manage

### LAN-to-WAN Domain

- **Roles and Tasks:**
  - Includes physical pieces and logical design of security appliances; physical parts need to be managed for easy access to the service

- **Responsibilities:**
  - Physical components, logical elements, and applying defined security controls

- **Accountability:**
  - Ensure LAN-to-Wide Area Network (WAN) Domain security policies are used

### Common Threats in the LAN-to-WAN Domain

- Unauthorized network probing and port scanning
- Unauthorized access through LAN-to-WAN Domain
- DoS/DDoS attacks
- IP router, firewall, and network appliance OS vulnerability
- IP router, firewall, and network appliance config file errors or weaknesses
- Remote user download of sensitive data
- Download of unknown file type attachments from unknown sources
- Unknown email attachments and embedded URL links received by local users
- Lost productivity due to local users surfing the web

### WAN Domain

- **Roles and Tasks:**
  - Allow users the most access possible while ensuring what goes in and out is safe

- **Responsibilities:**
  - Physical components and logical elements

- **Accountability:**
  - Maintain, update, provide technical support, and ensure the company meets security policies

### Common Threats in the WAN Domain (Internet)

- Open, public, and

 accessible data
- Most Internet traffic sent as cleartext
- Vulnerable to eavesdropping, malicious attacks, DoS/DDoS attacks, TCP SYN flooding, and IP spoofing attacks
- Vulnerable to corruption of information/data
- Insecure TCP/IP applications
- Hackers, attackers, and perpetrators email Trojans, worms, and malicious software

### Common Threats in the WAN Domain (Connectivity)

- Commingling of WAN IP traffic on the same service provider router and infrastructure
- Maintaining high WAN service availability
- Maximizing WAN performance and throughput
- Using SNMP applications and protocols maliciously (ICMP, Telnet, SNMP, DNS, etc.)
- SNMP alarms and security monitoring 24/7/365

### Remote Access Domain

- **Roles and Tasks:**
  - Connect mobile users to IT systems through the public Internet

- **Responsibilities:**
  - Maintain, update, and troubleshoot hardware and logical remote access connection

- **Accountability:**
  - Ensure Remote Access Domain security plans are used

### Common Threats in the Remote Access Domain

- Brute-force user ID and password attacks
- Multiple logon retries and access control attacks
- Unauthorized remote access to IT systems, applications, and data
- Private or confidential data compromised remotely
- Data leakage violating data classification standards
- Mobile worker’s laptop is stolen
- Mobile worker token or other authentication stolen

### System/Application Domain

- **Roles and Tasks:**
  - Includes hardware, OS, applications, and data; secure mission-critical applications and intellectual property assets both physically and logically

- **Responsibilities:**
  - Server systems administration, database design and management, designing access rights, etc.

- **Accountability:**
  - Ensure System/Application Domain complies with security policies

### Common Threats in the System/Application Domain

- Unauthorized access to data centers, computer rooms, and wiring closets
- Downtime of servers for maintenance
- Server OS software vulnerabilities
- Insecure cloud computing virtual environments
- Susceptibility of client-server and web applications
- Unauthorized access to systems
- Data breach compromising private data
- Corrupt or lost data
- Loss of backed-up data as backup media are reused
- Recovery of critical business functions potentially too time-consuming
- Downtime of IT systems for an extended period after a disaster

### Weakest Link in the Security of an IT Infrastructure

- Humans are the weakest link in security
- Strategies for reducing risk:
  - Check background of job candidates carefully
  - Evaluate staff regularly
  - Rotate access to sensitive systems, applications, and data among staff positions
  - Test applications and software and review for quality
  - Regularly review security plans
  - Perform annual security control audits

### Ethics and the Internet

- Human behavior online is often less mature than in normal social settings
- Demand for systems security professionals is growing rapidly
- U.S. government and Internet Architecture Board (IAB) defined a policy regarding acceptable use of the Internet geared toward U.S. citizens
- Policy is not a law nor mandated
- Systems security professionals are responsible for doing what is right and stopping what is wrong

### IT Security Policy Framework

- **Policy:**
  - Short written statement defining a course of action applying to the entire organization

- **Standard:**
  - Detailed written definition of how software and hardware are to be used

- **Procedures:**
  - Written instructions for how to use policies and standards

- **Guidelines:**
  - Suggested course of action for using policy, standard, or procedure

### Hierarchical IT Security Policy Framework

### Foundational IT Security Policies

- Acceptable use policy (AUP)
- Security awareness policy
- Asset classification policy
- Asset protection policy
- Asset management policy
- Vulnerability assessment/management policy
- Threat assessment and monitoring policy

### Data Classification Standards (1 of 2)

- **Private Data:**
  - Data about people that must be kept private

- **Confidential:**
  - Information or data owned by the organization, for internal use only

- **Public Domain Data:**
  - Information or data shared with the public

### Data Classification Standards (2 of 2)

**U.S. Federal Government Data Classification Standards:**
- Top Secret
- Secret
- Confidential

### Summary

- Information systems security concepts
- Confidentiality, integrity, and availability (C-I-A)
- The seven domains of a typical IT infrastructure
- The weakest link in the security of an IT infrastructure
- IT security policy framework and data classification standards
