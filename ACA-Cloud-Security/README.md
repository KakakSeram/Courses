# Alibaba Cloud Exam - ACA Cloud Security

## Single Answer

1. Which of the following issue would not happen if ECS server is under attack by hackers?

	A. sensitive data leak  
	B. service running on that server is not available  
	C. physical server damage  
	D. compromise the reputation of service provider on that server

	**Answer : C**

2. In a regular server maintenance operation, the purpose of installing a patch on the operating system is?
	
	A. to Improve server resource usage  
	B. to improve system usability  
	C. to enhance system functionality  
	D. to avoid existing system vulnerabilities being used by some hackers
	
	**Answer : D**

3. Which of the following statements are NOT true about Server Guard's remote logon detection functionality?
	
	A. It needs to setup common logon location in 'Server Guard' configuration  
	B. It can detect the attacking tool used by attacker  
	C. It can detect the remote logon used source IP address  
	D. It can send warning message to 'Server Guard' user

	**Answer : B**

4. If your company's official website is tampered, the consequence of such an attack could NOT be:

	A. Website is used for some illegal attempts  
	B. Public image or reputation of your company is damaged  
	C. Business is impacted  
	D. Physical server is damaged 
	
	**Answer : D**

5. Which of the following shell commands can be used to check disk usage in a Linux OS ECS?

	A. df -h  
	B. echo $path  
	C. free -m  
	D. ps -e -o
	
	**Answer : A**

6. Which of the following benefits cannot be provided by 'Server Guard'?

	A. Lower the risk of sensitive data leak  
	B. Improve the usage of system resource  
	C. Lower the cost of security protection  
	D. Get instant alerts after attacks are detected 
	
	**Answer : B**

7. If your company has a lot of employees who would try to simultaneously access an ECS server protected by Server Guard using your company's intranet, Server Guard may mistakenly identify those access requests as attacks. Which of the following methods is the best way to solve this problem?

	A. Set a highly complex administrator password  
	B. Change the rule of the security group to unblock all company internal IPs  
	C. Add those IPs which need to access the ECS server into the Server Guard logon whitelist  
	D. Ask employees to access that ECS server not very frequently
	
	**Answer : C**

8. When 'Server Guard' detects remote logon behavior, what information will be shown on the 'Server Guard' console?

	A. Illegal Logon!  
	B. Migrated Already!  
	C. Logon Successfully!  
	D. Remote Logon Detected!
	
	**Answer : D**

9. Which of the following statements is the possible reason that might lead to system vulnerabilities?

	A. Software logic flaw or mistakes made during the software development cycle  
	B. Hardware devices are not up to date  
	C. System administrator didn't follow the operation manual exactly  
	D. The proprietary software that is safer than open source one should be installed
	
	**Answer : A**

10. Which command in Redhat Linux shell can be used to check if some specific string is included in a bunch of text files? 

	A. watch  
	B. find  
	C. grep  
	D. cat
	
	**Answer : C**

11. Which service in RedHat Linux OS can be used to build network firewall functionality?

	A. iptables  
	B. ipfirewall  
	C. linuxfw  
	D. netstat
	
	**Answer : A**

12. Which command in Redhat Linux shell can be used to check disk usage?

	A. ls  
	B. df  
	C. diskUsage  
	D. diskSpace
	
	**Answer : B**

13. Which of the following protocols can be considered as an 'application' layer protocol in the ISO/OSI 7 layer model?

	A. TCP  
	B. UDP  
	C. IP  
	D. SMTP
	
	**Answer : D**

14. Which of the following HTTP status codes reflects that the requested page does not exist?

	A. 403  
	B. 404  
	C. 201  
	D. 304
	
	**Answer : B**

15. What status transition flow will a TCP client go through in order to proactively establish a connection and disconnect it?

	A. SYNC_SENT -> ESTABLISHED -> FIN_WAIT1 -> FIN_WAIT2 -> TIME_WAIT  
	B. SYNC_SENT -> ESTABLISHED -> FIN_WAIT1 -> FIN_WAIT2 -> CLOSE_WAIT  
	C. SYNC_RCVD -> ESTABLISHED -> CLOSE_WAIT -> TIME_WAIT -> LAST_ACK  
	D. SYNC_SENT -> SYNC_RCVD -> ESTABLISHED -> FIN_WAIT1 -> FIN_WAIT2
	
	**Answer : A**

16. Which of the following protocols is dedicated to resolving IP and MAC addresses?

	A. TCP  
	B. ARP  
	C. DNS  
	D. ICMP
	
	**Answer : B**

17. In Windows OS, what command can be used to open the registry table and edit it?

	A. gpedit  
	B. regedit  
	C. gedit  
	D. zedit
	
	**Answer : B**

18. Which web server is the default one in Windows OS?

	A. HTTPD  
	B. IIS  
	C. Web Daemon  
	D. Apache
	
	**Answer : B**

19. Which command in Windows OS can be used to open a terminal?

	A. painter.exe  
	B. cmd.exe  
	C. batch.exe  
	D. term.exe

	**Answer : B**

20. In Windows OS, you can turn off a service through:

	A. Control Panel -> Management Tool -> Stop the running service  
	B. Control Panel -> Windows Update -> Stop  
	C. Create new firewall rule to stop service  
	D. Delete administrator role and related accounts 
	
	**Answer : A**

21. Which of the following functions is NOT provided by Server Guard vulnerability detection?

	A. Trojan detection  
	B. Weak password detection  
	C. Sensitive data encryption  
	D. Linux system vulnerability scanning
	
	**Answer : C**

22. On which layer of the ISO/OSI 7 layer networking model does a CC attack happen?

	A. Presentation Layer  
	B. Session Layer  
	C. Data Link Layer  
	D. Application Layer
	
	**Answer : D**

23. Which of the following functions does not belong to what WAF can provide?

	A. DB encryption  
	B. SQL injection detection  
	C. XSS attack detection  
	D. Unauthorized resource access blocking
	
	**Answer : A**

24. From which of the following attacks will WAF not provide protection?

	A. SYN Flood  
	B. Web Server vulnerability attack  
	C. Core files unauthorized access  
	D. HTTP flood
	
	**Answer : A**

25. Which of the following security vulnerabilities is not a "Server Side" security issue?

	A. SQL injection  
	B. System Command Execution vulnerability  
	C. CSRF (cross-site request forgery) vulnerability  
	D. File uploading vulnerability
	
	**Answer : C**

26. CC attacks can cause serious damages. Which of the following statements about CC attacks is not correct?
	
	A. CC attacks will simulate real user requests  
	B. Will consume massive server-side resources  
	C. CC attacks are done on the network layer  
	D. The requests generated by CC attacks are hard to distinguish from normal requests
	
	**Answer : C**

27. Which of the following steps is not a valid step for using anti-DDoS pro?

	A. Configure to be protected domain name  
	B. Add new DNS record  
	C. Change source IP  
	D. If original server is using its own firewall, then need to add Anti-DDoS pro IP to its whitelist  
	E. Bind real customer identity to anti-DDoS pro IP
	
	**Answer : E**

28. After WAF was purchased, users need to add one DNS record to map their domain name to WAF provided IP. What is the type of that DNS record?

	A. A Record  
	B. CNAME Record  
	C. TXT Record  
	D. MX Record
	
	**Answer : A**

29. Which of the following options could NOT be the reason that causes website tampering?

	A. Share password between different users  
	B. Botnet attack  
	C. System vulnerability is not fixed in time  
	D. Wrong security configuration
	
	**Answer : A**

30. Which of the following statements about WAF is NOT true?

	A. WAF only protects traffic coming in and won't protect traffic going out  
	B. DNS will resolve the original domain name to the WAF cluster  
	C. After scrubbing, traffic will be re-injected to the original server  
	D. Server response traffic will be scrubbed also
	
	**Answer : A**

31. What is the correct action sequence of WAF protection strategy: (1) CC detection (2) Web application attack detection (3) Access control

	A. 213  
	B. 312  
	C. 132  
	D. 231
	
	**Answer : B**

32. Which of the following products won't be a DDoS attack target?

	A. Offline backup tape devices  
	B. Enterprise major website  
	C. Router device  
	D. Online banking system
	
	**Answer : A**

33. Which of the following 4 functions can be achieved through ECS security group configuration?

	A. Allow specific IP to remote access ECS server  
	B. Make ECS server able to defend 15Gb/s DDOS attack  
	C. Fix XSS vulnerability  
	D. Assign customized IP address to ECS
	
	**Answer : A**

34. Which of the following statements is NOT true about EIP and NAT gateway?

	A. NAT gateway can support multiple servers inside VPC to access public internet through one public IP  
	B. EIP can be bound to different ECS servers at the same time  
	C. Different EIPs can't share bandwidth  
	D. NAT gateway can support shared bandwidth between several IPs
	
	**Answer : B**

35. What design flaw of TCP/IP protocol does SYN flood attack use?

	A. UDP stateless connection  
	B. DNS 3 times handshake  
	C. TCP 3 times handshake  
	D. HTTP plain text transmission
	
	**Answer : C**

36. If a user is using anti-DDoS Pro service, but the original server has a rule to limit access to client IPs, which of the following actions is the most proper one to take?

	A. Enable CDN and change anti-DDoS pro IP to CDN address  
	B. Add anti-DDoS pro IP into the customer firewall whitelist  
	C. Disable the original server firewall  
	D. Enable SLB for the original server
	
	**Answer : B**

37. From which of the following attacks can anti-DDoS Pro NOT defend its users?

	A. XSS attack  
	B. TCP flood  
	C. UDP flood  
	D. ICMP flood
	
	**Answer : A**

38. Which of the following items can't be set in ECS security group configuration?

	A. OS type  
	B. Network interface  
	C. Authorization policy  
	D. Authorization object
	
	**Answer : A**

39. Apart from technical approaches, the proper data security management rules can be applied in daily operations to lower the risk of information leakage. Which of the following risks can be mitigated by setting a strong data security management policy for the company's employees?

	A. Information is sniffed during network transition  
	B. Under HTTP flood attack  
	C. Sensitive information is taken away by a former employee  
	D. Email phishing
	
	**Answer : C**

40. Which of the following statements is NOT true about anti-DDoS basics and anti-DDoS Pro?

	A. Both can defend against DDoS attacks  
	B. Anti-DDoS Pro is free to charge  
	C. Anti-DDoS Pro has more capabilities to defend against DDoS attacks  
	D. Anti-DDoS Pro can protect both inside and outside Alibaba Cloud servers
	
	**Answer : B**


## Multiple Answer

1. In order to stop the service provided through a particular port in Windows OS, which of the following methods can be used to achieve this objective? (The number of correct answers: 3)

	A. Adjust firewall rule  
	B. Adjust local security policy  
	C. Update OS patch  
	D. Stop the service itself  
	E. Stop all guest role access

	**Answer : A, B & D?**

2. When we talk about "security vulnerability" of ECS server, we are referring to: (the number of correct answers: 3)

	A. OS vulnerability  
	B. Hardware fault  
	C. Application vulnerability  
	D. Hypervisor vulnerability  
	E. Data Center Serviceability
	
	**Answer : A, C & D?**

3. Which of the following statements about the possible reasons that cause web server vulnerabilities are true? (The number of correct answers: 2)
	
	A. Bugs generated during common component development  
	B. Hardware configuration is not up to date  
	C. Software used or OS itself contain some logic flaw  
	D. End user didn't follow the user manual
	
	**Answer : A & C?**

4. Which of the following statements about IPv6 and IPv4 are true? (The number of correct answers: 2)

	A. IPv6 has a bigger route table size  
	B. IPv6 address length upper limit is 128 bits  
	C. IPv6 has a more simplified header  
	D. No network switch device is needed when using IPv6 protocol to transfer data
	
	**Answer : B & C?**

5. Inside cloud, hypervisor vulnerability could cause the following possible consequences: (the number of correct answers: 3)

	A. One client host can access another client's data  
	B. User service become unavailable  
	C. Hacker can access host server directly  
	D. Incorrect client resource usage calculating
	
	**Answer : A, B & C?**

6. Which of the following statements about VLAN are NOT true? (The number of correct answers: 3)

	A. Users in different VLANs can connect each other directly without pre-configuration  
	B. Different VLANs mean different physical locations of switches  
	C. VLAN configuration can be done through an TCP/IP router device  
	D. VLAN can enhance network security and data isolation
	
	**Answer : B, C & D?**

7. Which of the following elements are included in a TCP/IP-based route table? (The number of correct answers: 3)

	A. Network Destination  
	B. Netmask  
	C. MAC Address  
	D. Gateway IP  
	E. Port

	**Answer : A, B & D?**

8. Which of the following keys in HTTP headers are related to cache control? (The number of correct answers: 3)
	  
	A. Cache-Control  
	B. Date  
	C. Age  
	D. Expires  
	E. Host
	
	**Answer : A, D & E?**

9. Which of the following logs can be accessed through ECS logs provided by Alibaba Cloud? (The number of correct answers: 2)

	A. OS system log  
	B. Application log  
	C. Hypervisor log  
	D. Cloud platform log
	
	**Answer : A & B**

10. Which of the following statements are true about the difference between HTTP and HTTPS? (The number of correct answers: 2)

	A. HTTP must use port 80 and HTTPS must use port 443 to provide service  
	B. HTTPS is more secure than HTTP regarding the way they transfer data  
	C. Data transferred through HTTPS is under encryption  
	D. You must buy a commercial CA before you set up your own web server with HTTPS service
	
	**Answer : B & C**

11. Which of the following protection rules are provided by WAF to better protect from CC attack? (The number of correct answers: 2)

	A. Loose  
	B. Strict  
	C. Normal  
	D. Emergency
	
	**Answer : A & B**

12. Which of the following scenarios are suitable to use CC emergency mode protection? (The number of correct answers: 2)

	A. Web page  
	B. HTML 5 page  
	C. API  
	D. Native APPs 
	
	**Answer : A & B**

13. What modes will Alibaba Cloud WAF provide to defend SQL injection? (The number of correct answers: 2)

	A. Normal Mode  
	B. Protection Mode  
	C. Warning Mode  
	D. Restriction Mode
	
	**Answer : B & C**

14. After configuring WAF, from the management console, it shows service abnormal. What could be the reasons? (The number of correct answers: 2)

	A. CNAME setting is not correct  
	B. No any traffic on given domain name  
	C. No CC rules defined  
	D. Is protecting a server not inside Alibaba Cloud
	
	**Answer : A & C**

15. The Alibaba Cloud WAF protection strategy provides the following: (The number of correct answers: 3)

	A. Loose  
	B. Strict  
	C. Normal  
	D. Regular  
	E. Early Warning
	
	**Answer : A, B & C**

16. What are the advantages of anti-DDoS Pro compared to anti-DDoS Basic service? (The number of correct answers: 3)

	A. Stronger defending attacks capability  
	B. Elastic protection bandwidth  
	C. No upper limit to the attack traffic need to be handled  
	D. Can do anti-fraud protection  
	E. Can protect IDC outside Alibaba Cloud
	
	**Answer : A, B & E**

17. Which of the following risks are considered as common network security risks? (The number of correct answers: 2)

	A. Massive traffic flood attack  
	B. Software version is not up to date  
	C. Data under transferring is being sniffed  
	D. Physical Fiber Channel Cable is broken
	
	**Answer : B & C**

18. Which of the following scenarios should be handled by anti-DDoS service? (The number of correct answers: 3)

	A. Server is under syn flood attack, and is not reachable  
	B. Online game service which is suffering with too many empty connections and slow connections  
	C. DNS server is under udp flood attack and got no response anymore  
	D. Website is under SQL Injection attack  
	E. Website is under XSS attacks
	
	**Answer : A, B & C**

19. Which of the following statements about ECS, VPC, and security groups are NOT true? (The number of correct answers: 2)

	A. Rule setting for security group supports both in and out direction configuration  
	B. Default security group rule is safe enough, please don't change it too much  
	C. By default, ECS in different security group can communicate with each other  
	D. One ECS can be configured into several different security groups
	
	**Answer : B & C**

20. Which of the following services may be under anti-DDoS attack? (The number of correct answers: 3)

	A. Servers in VPC only configured with private network  
	B. Any device internet reachable  
	C. Government website  
	D. Public DNS service
	
	**Answer : B, C & D**