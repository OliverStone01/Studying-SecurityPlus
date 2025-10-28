# Security+ SY0-701 Practice Exam #1  
**Total Questions:** 90  
**Format:** Multiple choice  
**Instructions:** Choose the *best* answer (A–D).  

---

**Domain 1 – Threats, Attacks, and Vulnerabilities**  

1. Which of the following best describes a phishing attack?  
A. Injecting malicious code into a database query  
B. Sending deceptive emails to trick users into revealing credentials  
C. Exploiting buffer memory to execute arbitrary code  
D. Monitoring network packets for unencrypted passwords  

2. An attacker intercepts and alters communications between two parties. What attack is this?  
A. Brute-force attack  
B. Man-in-the-middle  
C. Denial of Service  
D. Phishing  

3. Which malware hides its presence by modifying system files and masking processes?  
A. Logic bomb  
B. Rootkit  
C. Trojan horse  
D. Worm  

4. A hacker sends thousands of SYN packets to overwhelm a server. This is an example of:  
A. Replay attack  
B. SYN flood  
C. Session hijacking  
D. ARP poisoning  

5. Which type of vulnerability arises from poor input sanitization in web forms?  
A. SQL injection  
B. Phishing  
C. Dictionary attack  
D. DoS attack  

6. Which of the following describes ransomware?  
A. Steals credentials by keylogging  
B. Encrypts user data and demands payment  
C. Hijacks browser sessions  
D. Deletes data upon execution  

7. What is the purpose of a honeypot?  
A. Protect endpoints from malware  
B. Deceive attackers to study their behavior  
C. Encrypt sensitive files  
D. Prevent SQL injection  

8. An attacker uses DNS queries to exfiltrate data. What is this called?  
A. Cross-site scripting  
B. DNS tunneling  
C. Spoofing  
D. Data breach  

9. Which attack attempts every possible password combination?  
A. Dictionary  
B. Brute force  
C. Password spraying  
D. Rainbow table  

10. Which vulnerability scanner output shows “CVE-2024-1111” entries?  
A. Compliance checklist  
B. Common Vulnerabilities and Exposures ID  
C. Port number reference  
D. Encryption algorithm index  

11. What technique involves an attacker supplying unexpected input to a program to overwrite memory?  
A. SQL injection  
B. Buffer overflow  
C. Cross-site request forgery  
D. Directory traversal  

12. Which social-engineering attack specifically targets high-level executives?  
A. Vishing  
B. Whaling  
C. Tailgating  
D. Baiting  

13. An attacker sends a flood of traffic to a web service to exhaust resources. This is a:  
A. Man-in-the-middle attack  
B. Denial-of-service attack  
C. DNS tunneling  
D. Privilege escalation attempt  

14. Which attack tricks a user into executing a malicious link via voice communication?  
A. Phishing  
B. Smishing  
C. Vishing  
D. Watering hole  

15. What is the primary goal of reconnaissance in the attack lifecycle?  
A. Exploit vulnerabilities to gain admin rights  
B. Gather information to plan later stages of an attack  
C. Encrypt data for ransom  
D. Clean up traces of intrusion  

16. Which of the following is an example of credential stuffing?  
A. Trying commonly used passwords across many accounts  
B. Using stolen username/password pairs from other breaches to log in  
C. Phishing users for passwords via fake sites  
D. Brute-forcing a single account with many guesses  

17. A malicious script on one website executes in another user’s browser because content wasn’t escaped. This is:  
A. Cross-site scripting (XSS)  
B. Cross-site request forgery (CSRF)  
C. SQL injection  
D. Local file inclusion  

18. Attackers modify DNS records to redirect users to malicious sites. This is called:  
A. DNS spoofing/poisoning  
B. ARP poisoning  
C. URL filtering  
D. Subdomain takeover  

19. Which technique allows attackers to maintain persistent access by altering registry keys or services?  
A. Lateral movement  
B. Privilege escalation  
C. Persistence mechanisms  
D. Data exfiltration  

20. What type of malware replicates itself across systems without user interaction?  
A. Trojan  
B. Worm  
C. Ransomware  
D. Rootkit

---
 
**Domain 2 – Architecture & Design (21–28)**

21. Which network design concept limits the impact of a compromise by separating environments?  
A. Segmentation  
B. Redundancy  
C. Availability zone  
D. Load balancing

22. A DMZ primarily provides which benefit?  
A. Database backup  
B. Isolation of public-facing servers from internal networks  
C. File encryption  
D. Secure wireless access

23. Which of the following is a defense-in-depth approach?  
A. Using multiple security controls at different layers  
B. Relying on a single firewall for protection  
C. Disabling logging to improve performance  
D. Granting all users admin rights on endpoints

24. What is the primary goal of zero trust architecture?  
A. Trust devices on the internal network by default  
B. Never trust and always verify user and device identity for each request  
C. Replace encryption with segmentation  
D. Permit access once on VPN regardless of device posture

25. Which control is BEST for preventing unauthorized physical access to a server room?  
A. Role-based access control (RBAC)  
B. Physical access control (badges, biometrics)  
C. Network ACLs  
D. Application allow listing

26. Which design principle improves availability by distributing load across multiple servers?  
A. Fault injection  
B. Load balancing  
C. Encryption  
D. Access control

27. Which architecture reduces the blast radius by isolating critical services?  
A. Flat network design  
B. Microsegmentation  
C. Single VLAN for all services  
D. Shared hosting

28. Which of the following is an example of secure by design?  
A. Adding authentication after deployment  
B. Embedding security early in the software development lifecycle (SDLC)  
C. Disabling encryption to reduce latency  
D. Sharing admin passwords among developers

**Domain 3 – Implementation (29–40)**

29. Which protocol provides secure remote management of network devices?  
A. Telnet  
B. SSH  
C. FTP  
D. HTTP

30. To securely store passwords, which approach is recommended?  
A. Encrypt passwords with reversible symmetric keys  
B. Store passwords in plaintext in the database  
C. Hash passwords with a strong algorithm and unique salt  
D. Use Base64 encoding for stored passwords

31. Which technology allows centralized authentication and single sign-on across many services?  
A. Kerberos or SAML-based SSO  
B. RADIUS only for wireless  
C. Local accounts on each server  
D. FTP-based authentication

32. Which control helps ensure software running on endpoints is known and approved?  
A. Application allow listing  
B. Firewall rule tightening  
C. DNS sinkholing  
D. Public key infrastructure

33. Which encryption model uses the same key for encryption and decryption?  
A. Asymmetric encryption  
B. Symmetric encryption  
C. Public key cryptography  
D. Hashing

34. Which is the BEST method to secure web application session tokens?  
A. Store tokens in localStorage without expiration  
B. Use secure, HTTP-only cookies with appropriate expiration and rotation  
C. Embed tokens in URLs for convenience  
D. Use plain text cookies across subdomains

35. What does MFA stand for and why is it used?  
A. Mandatory File Access — to restrict file reads  
B. Multi-Factor Authentication — to require two or more forms of identity proof  
C. Managed Firewall Access — to centrally manage firewalls  
D. Mutual File Authorization — to share files securely

36. Which email authentication protocol helps detect forged sender addresses by verifying sending servers?  
A. S/MIME  
B. SPF  
C. TLS  
D. POP3

37. Which control is MOST effective at preventing exploitation of known OS vulnerabilities across many endpoints?  
A. Regular patch management  
B. Application obfuscation  
C. Hiding ports with NAT  
D. Disabling logging

38. Which technique protects against interception of credentials by ensuring one-time codes change constantly?  
A. Static passwords  
B. Time-based one-time passwords (TOTP)  
C. Reused session cookies  
D. Storing credentials in plain text

39. For enterprise Wi-Fi, which combination provides centralized authentication with the strongest enterprise controls?  
A. WPA2-Personal with a shared PSK  
B. WEP with hidden SSID  
C. WPA2-Enterprise with 802.1X (RADIUS)  
D. Open Wi-Fi with VPN required

40. Which service type provides authentication and authorization for devices seeking access to network resources (e.g., NAC enforcement)?  
A. DHCP server only  
B. Network access control (NAC) with posture checks  
C. DNS resolver  
D. SMTP relay

---

