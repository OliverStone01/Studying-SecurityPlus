### 🗃️ Flashcards & Questions for module 4
To reveal the answer, click on the question or the `>` arrow to the left side of the question.

-----

### Access Controls

<details>
  <summary>What is access control?</summary>
  Access control is about controlling and enforcing policies that allow or deny access to data.
</details>

<details>
  <summary>Can access controls be placed on an individual or on a group?</summary>
  Both.
</details>

<details>
  <summary>What is the best type of access control?</summary>
  Least privilege.
</details>

<details>
  <summary>What’s is mandatory access control (MAC)?</summary>
  Every resource is assigned a label of severity. Then each user is assigned a level of severity that they are able to access.
</details>

<details>
  <summary>What is discretionary access control (DAC)?</summary>
  The owner of the data decides who gets access and at what level.
</details>

<details>
  <summary>What is role based access control (RBAC)?</summary>
  Access based on your job role.
</details>

<details>
  <summary>What is rule based access control?</summary>
  Permissions are enforced by rules set by administrators.
</details>

<details>
  <summary>What is attribute-based access control (ABAC)?</summary>
  This is a next generation access control that considers attributes such as IP address, time of day, request action, and relationship to the data.
</details>

<details>
  <summary>What does access control insure?</summary>
  That after authentication, users only have access to the data they need.
</details>


-----

### Analysing Vulnerabilities

<details>
  <summary>What is a false positive?</summary>
  Information given about a vulnerability but after investing, the error does not exist. Given a positive but it turned out to be false.
</details>

<details>
  <summary>What is a false negative?</summary>
  A false negative means there is a vulnerability but your detection systems didn’t detect it.
</details>

<details>
  <summary>What is a CVE score?</summary>
  A score on how severe a vulnerability is.
</details>

<details>
  <summary>What does CVE stand for?</summary>
  Common vulnerabilities and exposures.
</details>

<details>
  <summary>What is the range of a CVE score?</summary>
  0–10 (10 being the most severe).
</details>

<details>
  <summary>How do vulnerability scanners work?</summary>
  They scan your system looking for signatures of malware.
</details>

<details>
  <summary>Why is it important to keep your vulnerability scanners up to date?</summary>
  To make sure that the malware signatures are up to date with the latest versions.
</details>

<details>
  <summary>What is an exposure factor?</summary>
  The quantification of how risky the vulnerability is to the network and system.
</details>

<details>
  <summary>How is an exposure factor represented?</summary>
  As a percentage.
</details>

<details>
  <summary>If a vulnerability will affect the functionality of a system 50% of the time, what is the exposure factor?</summary>
  50%.
</details>

<details>
  <summary>What exposure factor does a buffer overflow attack have?</summary>
  100%.
</details>

<details>
  <summary>How do we decide which device to patch first?</summary>
  How many users are using the device and how much revenue is the device bringing in.
</details>

<details>
  <summary>What is risk tolerance?</summary>
  Prioritising which device/system should be patched first.
</details>


-----

### Application Security

<details>
  <summary>What is quality assurance (QA)?</summary>
  These are tests that check the app’s functionality and its security.
</details>

<details>
  <summary>What is input validation?</summary>
  Checking the input for malicious code or injections before processing the input in the application.
</details>

<details>
  <summary>What is fuzzing?</summary>
  Fuzzing is an automation tool that tests the application for input validation and to make sure the application preforms as it should.
</details>

<details>
  <summary>What are secure cookies?</summary>
  These cookies are very similar to standard cookies but they can only be transferred over HTTPS with encryption.
</details>

<details>
  <summary>What would happen if an attacker managed to get access of your cookies?</summary>
  They could try a session jacking attack where they could log into your account without any information.
</details>

<details>
  <summary>What is a method developers use to test the security of their application?</summary>
  Running their code through a SAST.
</details>

<details>
  <summary>What is a SAST?</summary>
  Static application security testing.
</details>

<details>
  <summary>What does a SAST do?</summary>
  SAST’s analyse code and identifies security flaws.
</details>

<details>
  <summary>What is code signing?</summary>
  This is when developers hash their code so that when others install the code they can check for integrity by hashing the code them selves and checking they get the same value.
</details>

<details>
  <summary>What is sandboxing?</summary>
  Testing software in a safe environment where the software only has access to the data in the sandbox.
</details>

<details>
  <summary>What is anomaly detection?</summary>
  This detects anything unusual happening on the network. For example, large amounts of file transfers in the middle of the night.
</details>


-----

### Asset Manager

<details>
  <summary>What is classification?</summary>
  The process of determining what type of asset something is. (Software/hardware)
</details>

<details>
  <summary>What is media sanitisation?</summary>
  The process of wiping data from a device before either passing it on to another user or throwing it away.
</details>

<details>
  <summary>What is a simple method for making sure a device cannot be used again?</summary>
  Physical damage.
</details>

<details>
  <summary>What is degaussing?</summary>
  Using electromagnetic fields that erase all data on a drive.
</details>

<details>
  <summary>What is data retention?</summary>
  Keeping data backed up.
</details>


-----

### Digital Forensics

<details>
  <summary>What is digital forensics?</summary>
  The process of collecting, preserving, and analysing data.
</details>

<details>
  <summary>What is the key to good digital forensics?</summary>
  Following best practices.
</details>

<details>
  <summary>What is an industry guideline used in digital forensics?</summary>
  RFC 3227 provides industry guidelines for evidence collection and archiving.
</details>

<details>
  <summary>What is a legal hold?</summary>
  Instructions from a lawyer or court on preserving specific electronically stored information (ESI).
</details>

<details>
  <summary>Why is it important that we log who has had access to data and that we hash data?</summary>
  To make sure the data hasn’t been tampered with.
</details>

<details>
  <summary>What does all data need when being dealt with by digital forensics?</summary>
  Documentation and a chain of custody.
</details>

<details>
  <summary>Do analysts use the original data to conduct their investigation?</summary>
  No, they create and use a copy of the original data which must be preserved.
</details>

<details>
  <summary>What is E-discovery?</summary>
  It’s about the collection of data.
</details>


-----

### Email Security

<details>
  <summary>What is the purpose of a DNS server in email security?</summary>
  We can use a DNS server to confirm whether an email was sent from a legitimate server or not.
</details>

<details>
  <summary>What is a mail gateway?</summary>
  The gatekeeper that takes in mail you have received over the internet. It checks if the sources are valid.
</details>

<details>
  <summary>Where should you put a mail gateway if it’s kept on premises?</summary>
  On a screened subnet.
</details>

<details>
  <summary>What is a SPF (Sender Policy Framework)?</summary>
  This is used to configure a server that will send mail on your behalf. Commonly seen in an organisation.
</details>

<details>
  <summary>Where are SPF’s added?</summary>
  To your DNS server as a TXT record.
</details>

<details>
  <summary>How can you add extra security to outgoing emails?</summary>
  Using DKIM (Domain keys identified mail).
</details>

<details>
  <summary>What is a DKIM?</summary>
  This is a public key signature sent between mail servers.
</details>

<details>
  <summary>What is DMARC (Domain-based message authentication, reporting, and conformance)?</summary>
  Specifies what you want to happen when an email is not validated via SPF or DKIM.
</details>


-----

### Endpoint Security

<details>
  <summary>What is endpoint security?</summary>
  The security of the device that users rely on every day.
</details>

<details>
  <summary>Where should you place a firewall?</summary>
  At the edge of the network where the internal system meets the outside internet.
</details>

<details>
  <summary>What is a posture assessment?</summary>
  Checks to ensure devices are properly secured before they are allowed full access to the network.
</details>

<details>
  <summary>What happens if a device fails a posture assessment?</summary>
  It may be quarantined.
</details>

<details>
  <summary>What is a persistent agent?</summary>
  It is installed on a device and continuously monitors the system.
</details>

<details>
  <summary>What is a dissolvable agent?</summary>
  It runs temporarily during login and removes itself after.
</details>

<details>
  <summary>Why is traditional anti-malware not as effective today?</summary>
  Because millions of new malware variants are created daily.
</details>

<details>
  <summary>What is a EDR (Endpoint Detection and Response)?</summary>
  This is an advanced anti-virus that extends beyond signatures and checks user behaviour, process monitoring, and machine learning to identify threats. EDR’s also provide root-cause analysis.
</details>

<details>
  <summary>What is XDR (Extended Detection and Response)?</summary>
  An XDR pulls in data from multiple systems, including endpoints, networks, and user activity.
</details>

<details>
  <summary>What is the goal of an EDR and XDR?</summary>
  To detect malicious activity quickly and stop it in real time to prevent it becoming a larger problem.
</details>


-----

### Firewalls

<details>
  <summary>What does a firewall do when it is setup inline with your network?</summary>
  Decides whether to allow or deny traffic depending on rules we set.
</details>

<details>
  <summary>What are the two methods used to filter traffic?</summary>
  Port or application.
</details>

<details>
  <summary>What are the two types of firewalls?</summary>
  Traditional and NGFW (Next-generation firewalls).
</details>

<details>
  <summary>What can you do to turn a firewall into a VPN endpoint firewall?</summary>
  Encrypt the traffic.
</details>

<details>
  <summary>What other device can a firewall be configured to be?</summary>
  A router / layer 3 device.
</details>

<details>
  <summary>What layer does a next generation firewall operate on?</summary>
  Layer 7.
</details>

<details>
  <summary>What is another common name for a next generation firewall?</summary>
  Application gateways.
</details>

<details>
  <summary>Explain why next generation firewalls work on level 7.</summary>
  Because this is the application layer, we can decide whether to block or allow traffic from specific applications.
</details>

<details>
  <summary>How do traditional firewalls decide what data to allow or deny?</summary>
  We set rules on what ports the data is using to get from point A to point B.
</details>

<details>
  <summary>What is an implicit deny rule?</summary>
  If the firewall cannot find a rule set based on the data then it will automatically deny the data.
</details>

<details>
  <summary>What is another name for a rule list?</summary>
  ACL (Access Control List).
</details>

<details>
  <summary>Where will most people put a firewall?</summary>
  Between their network and the internet.
</details>

<details>
  <summary>What is a screened subnet?</summary>
  A screened subnet is a separate network from our internal network and contains devices that need to be accessed by the internet. The firewall then works as a router routing to either the screened subnet or to the internal network.
</details>

<details>
  <summary>Why is it a good idea to have a screened subnet?</summary>
  Because if an attacker manages to get access to the screened subnet, they do not have access to our internal network.
</details>

<details>
  <summary>What does IPS stand for?</summary>
  Intrusion Prevention System.
</details>

<details>
  <summary>What does an IPS do?</summary>
  It recognises injections and malicious software signatures and blocks the attack.
</details>

<details>
  <summary>What device is usually linked with an IPS?</summary>
  Next generation firewalls.
</details>


-----

### Hardening Targets

<details>
  <summary>What can you follow for hardening devices and software?</summary>
  Most manufactures will provide a hardening guide to follow.
</details>

<details>
  <summary>What tool are you likely to use if you manage mobile devices in your organisation?</summary>
  MDM (Mobile Device Manager).
</details>

<details>
  <summary>What method is used by manufactories to fix vulnerabilities?</summary>
  Patches in the form of updates.
</details>

<details>
  <summary>Other than updates, what else can you do to harden devices?</summary>
  Remove unnecessary applications and change default passwords.
</details>

<details>
  <summary>What can you do to harden cloud infrastructures?</summary>
  Secure the admin device and account, and make sure all other parts of the system follow the principle of least privilege.
</details>

<details>
  <summary>What does EDR stand for?</summary>
  Endpoint Detection and Response.
</details>

<details>
  <summary>What does an EDR do?</summary>
  These will monitor for threats and respond accordingly.
</details>

<details>
  <summary>What else should you setup when working with cloud infrastructures?</summary>
  C2C (Cloud to Cloud) backup.
</details>

<details>
  <summary>Name 3 methods of hardening a server:</summary>
  Updates, firewalls, and minimum password requirements.
</details>

<details>
  <summary>What should you setup to monitor servers?</summary>
  Anti-virus/anti-malware.
</details>

<details>
  <summary>Why are embedded systems more difficult to harden?</summary>
  Because they have their own purpose-built operating system.
</details>


-----

### Identity and Access Management (IAM)

<details>
  <summary>What does IAM stand for?</summary>
  Identity and Access Management.
</details>

<details>
  <summary>What does an IAM do?</summary>
  It ensures the right people get the access at the right time.
</details>

<details>
  <summary>What is least privilege?</summary>
  Least privilege means users should only get the permissions necessary for their job.
</details>

<details>
  <summary>How can we prove that a person is who they are claiming to be?</summary>
  Passwords, security questions, government documents, or automated checks like credit history.
</details>

<details>
  <summary>What does SSO stand for?</summary>
  Single Sign-On.
</details>

<details>
  <summary>What does an SSO do?</summary>
  An SSO allows you to log in once, then use resources across the network without needing to re-enter credentials.
</details>

<details>
  <summary>What does LDAP stand for?</summary>
  Lightweight Directory Access Protocol.
</details>

<details>
  <summary>What does an LDAP do?</summary>
  Manages large directories of users and resources.
</details>

<details>
  <summary>What does SAML stand for?</summary>
  Security Assertion Markup Language.
</details>

<details>
  <summary>What does a SAML do?</summary>
  Lets organisations rely on third-party authentication databases.
</details>

<details>
  <summary>What is OAuth?</summary>
  OAuth is an authentication framework often paired with OpenID for authentication.
</details>

<details>
  <summary>What is federation?</summary>
  Federation allows you to log in to one service using credentials for another service — for example, signing in using your Google or Apple account.
</details>

<details>
  <summary>How does an organisation choose which system to use?</summary>
  Interoperability.
</details>


-----

### Incident Planning

<details>
  <summary>What is a readiness test?</summary>
  This tests how well the response plan is documented and how skilled teams are at executing it.
</details>

<details>
  <summary>What systems must be used for readiness tests?</summary>
  Non-production systems.
</details>

<details>
  <summary>What must each team do after a test?</summary>
  Hold a review session to evaluate performance.
</details>

<details>
  <summary>What are the two types of tests an organisation can do?</summary>
  Tabletop exercises and simulations.
</details>

<details>
  <summary>What is a tabletop exercise?</summary>
  Where teams gather around a table and walk through a hypothetical incident step by step.
</details>

<details>
  <summary>What is a simulation exercise?</summary>
  These are fake attacks that mimic real attacks. They are used to uncover weaknesses in security departments.
</details>

<details>
  <summary>What are two things commonly revealed when doing a simulated attack?</summary>
  How well technical systems like spam filters and anti-phishing protections are working, and how well employees can spot and avoid traps.
</details>

<details>
  <summary>What is threat hunting?</summary>
  Actively looking for vulnerabilities before attackers find them.
</details>


-----

### Incident Response

<details>
  <summary>What is NIST?</summary>
  NIST (National Institute of Standards and Technology) share clear frameworks and standards that should be used to stay secure when using technology.
</details>

<details>
  <summary>NIST released a framework in a publication called The Computer Security Incident Handling Guide 800-61 revision 2. What are the phases of the lifecycle in this framework?</summary>
  Preparation, Detecting and Analysis, Containment, Eradication, Recovery, and Post-incident Activities.
</details>

<details>
  <summary>What are some ways you can prepare for responding to an incident?</summary>
  Keep communication lists updated, maintain an incident go bag (laptops, forensic software, removable media, and imaging tools), have documentation ready (network diagrams, file hashes, and baseline configurations), and store clean OS images and applications installed.
</details>

<details>
  <summary>What can you use to help spot changes in systems?</summary>
  Logs, alerts, and monitoring tools.
</details>

<details>
  <summary>What should you do if you confirm an attack has occurred?</summary>
  Act fast, isolate the malware by using sandboxing or by taking the system offline.
</details>

<details>
  <summary>What is recovery?</summary>
  The act of restoring from clean sources after an attack. This involves wiping the system, reinstalling the OS, restoring from backups, disabling compromised accounts, and patching vulnerabilities.
</details>

<details>
  <summary>What is reflection?</summary>
  Meeting with the relevant teams to find out what happened, what was the timeline, how well the system held up, if there were missed indicators, and what must be changed for next time.
</details>

<details>
  <summary>When should training happen?</summary>
  Before the incident, not during. It’s important everyone knows their roles and the processes they must follow in a response situation.
</details>


-----

### Log Data

<details>
  <summary>What is log data?</summary>
  Logs are lots of information about how a device or software is performing. This can be traffic flow information and exploit attempts.
</details>

<details>
  <summary>What would logs of a firewall contain?</summary>
  Every connection with the source and destination IP address, ports in use, and whether the traffic was allowed or blocked.
</details>

<details>
  <summary>What would application logs contain?</summary>
  These logs track system events, process activity, password changes, and authentication details.
</details>

<details>
  <summary>What data would be stored on endpoint logs?</summary>
  Login attempts, system processes, directory services, and account lockouts.
</details>

<details>
  <summary>What data would be stored on operating system logs?</summary>
  Brute force attempts, changes to critical system files, and unusual service activity.
</details>

<details>
  <summary>Which logs usually give you the first indication of an attack?</summary>
  Operating system logs.
</details>

<details>
  <summary>What is metadata?</summary>
  Metadata is hidden information inside documents, emails, pictures, and web traffic.
</details>

<details>
  <summary>Why do we do vulnerability scans?</summary>
  To check for unpatched or misconfigured systems.
</details>

<details>
  <summary>What can we use to centralise and automate the log collection from all these devices on the network?</summary>
  A SIEM.
</details>

<details>
  <summary>What can you use to see the deepest level of visibility when it comes to network traffic?</summary>
  Packet capture tools like Wireshark that allow us to see each frame and every header.
</details>


-----

### Monitoring Data

<details>
  <summary>What does FIM stand for?</summary>
  File integrity monitoring.
</details>

<details>
  <summary>What does a FIM do?</summary>
  Monitors core files on a device to see if they are suddenly modified.
</details>

<details>
  <summary>What FIM is used on Windows?</summary>
  SFC (System File Checker).
</details>

<details>
  <summary>What does SFC do?</summary>
  Scans critical system files, verifies their integrity, and replaces any files that have been altered.
</details>

<details>
  <summary>What FIM tool is used on Linux?</summary>
  Tripwire.
</details>

<details>
  <summary>What does a host-based intrusion prevention system do?</summary>
  Gives visibility into local file changes as well as block known attacks.
</details>

<details>
  <summary>What does DLP stand for?</summary>
  Data loss prevention.
</details>

<details>
  <summary>What does a DLP system do?</summary>
  These systems are designed to stop sensitive data from leaking out.
</details>

<details>
  <summary>What are the different types of DLPs?</summary>
  Network-based DLPs, Endpoint/Host-based DLPs, Cloud-based DLPs, and Email-based DLPs.
</details>

<details>
  <summary>What is one of the biggest channels for data loss?</summary>
  Email.
</details>

<details>
  <summary>What do network-based DLPs do?</summary>
  Inspect traffic in real time.
</details>

<details>
  <summary>What do endpoint/host-based DLPs do?</summary>
  They run on an individual system, often blocking risky transfers such as a USB drive.
</details>

<details>
  <summary>What do cloud-based DLPs do?</summary>
  They monitor and block sensitive uploads into SaaS platforms and cloud storage.
</details>

<details>
  <summary>What do email-based DLPs do?</summary>
  They scan outgoing messages for sensitive information.
</details>


-----

### Multi-Factor Authentication

<details>
  <summary>What is multi-factor authentication?</summary>
  When you sign in using one factor like a username and password, then you are asked for a second factor like a code sent to your phone or a fingerprint.
</details>

<details>
  <summary>What are the four factors?</summary>
  Something you know, something you have, something you are, and somewhere you are.
</details>

<details>
  <summary>Give an example of something you know?</summary>
  Password, a pin, or an unlock pattern. Memorised secrets only you should know.
</details>

<details>
  <summary>Give an example of something you have?</summary>
  A smart card, a USB security key, or a hardware token that displays random codes. This also includes receiving SMS login codes.
</details>

<details>
  <summary>Give an example of something you are?</summary>
  Biometrics like a fingerprint or face scan.
</details>

<details>
  <summary>Give an example of somewhere you are?</summary>
  Your physical location via GPS or IP address.
</details>

-----

### Operating System Security

<details>
  <summary>What is Active Directory?</summary>
  This is a database that contains all the different components of your network (printers, computers, etc.)
</details>

<details>
  <summary>What can you do from the Active Directory?</summary>
  Manage authentication and determine which users can access what resources.
</details>

<details>
  <summary>What is a group policy?</summary>
  This is where you create groups of users and then create policies and apply them to these groups.
</details>

<details>
  <summary>What system can you use to manage group policies?</summary>
  Group policy management editor.
</details>

<details>
  <summary>With Linux, what is a DAC?</summary>
  Discretionary access control.
</details>

<details>
  <summary>If you are using Linux in an organisation, what might you want to setup?</summary>
  Mandatory access control system which allows you to control the device and assign policies as a central administrator.
</details>

<details>
  <summary>What must you convert your Linux system into to activate DAC?</summary>
  SELinux (Security enhanced Linux).
</details>

<details>
  <summary>What does SELinux allow you to do?</summary>
  Allows admin to set least privilege.
</details>


-----

### Password Security

<details>
  <summary>What is the goal when making a password?</summary>
  Make it hard to guess.
</details>

<details>
  <summary>What are we trying to protect against when making passwords?</summary>
  Brute-force and password spraying attacks.
</details>

<details>
  <summary>What is the measurement of strength when making passwords?</summary>
  Entropy, which is how unpredictable the password is.
</details>

<details>
  <summary>How do you increase entropy?</summary>
  Avoid obvious words or single terms, mix uppercase, lowercase, numbers, and special characters.
</details>

<details>
  <summary>What is the minimum password length you should have?</summary>
  8.
</details>

<details>
  <summary>What is the best practice when setting passwords?</summary>
  Use a unique password for every account.
</details>

<details>
  <summary>Why should you use a unique password for each account?</summary>
  Because if one of those accounts is compromised, all your other accounts are safe.
</details>

<details>
  <summary>What is a password manager?</summary>
  Stores all your credentials in one encrypted database.
</details>

<details>
  <summary>What other features do some password managers have?</summary>
  Generate random, strong passwords automatically. Check if your passwords are weak or compromised.
</details>

<details>
  <summary>What does JIT permissions stand for?</summary>
  Just in time permissions.
</details>

<details>
  <summary>What are JIT permissions?</summary>
  Temporary credentials from a secure password vault. These credentials are short-lived and are based on primary credentials.
</details>


-----

### Penetration Testing

<details>
  <summary>What is a penetration test?</summary>
  Where we perform attacks on our systems to check for weaknesses.
</details>

<details>
  <summary>What must be agreed upon before any testing is done?</summary>
  Rules of engagement.
</details>

<details>
  <summary>What is the rules of engagement?</summary>
  These rules outline what testers can and cannot do during the test. This is called the scope.
</details>

<details>
  <summary>What are the four main types of penetration testing?</summary>
  Physical, internal, external, and digital.
</details>

<details>
  <summary>What might be the first thing an attacker does when successfully breaking into a system?</summary>
  Create a backdoor in case the vulnerability is patched.
</details>

<details>
  <summary>What is a bug bounty program?</summary>
  A rewards program that rewards testers when finding vulnerabilities in sites that offer a responsible disclosure program.
</details>


------

### Scripting and automation

<details>
  <summary>What is scripting all about?</summary>
  Automation.
</details>

<details>
  <summary>What are benefits of scripting?</summary>
  Speed and accuracy freeing IT staff to focus on more interesting work.
</details>

<details>
  <summary>What are common automations created?</summary>
  Patching, Configurations, Scaling, Monitoring, Onboarding/Off-boarding, Guardrails, Security group monitoring, Help desk integration, Access controls, DevOps, and APIs.
</details>

<details>
  <summary>List 5 downsides to scripts:</summary>
  Complexity, Costs, Single point of failure, Technical debt, and Ongoing support.
</details>


-----

### Secure Baseline

<details>
  <summary>What is a security baseline?</summary>
  The minimum best practices for each application and device.
</details>

<details>
  <summary>When should you meet this baseline?</summary>
  Before the application or device is deployed.
</details>

<details>
  <summary>Give an example of what could be a baseline?</summary>
  Adding a firewall to a device or network.
</details>

<details>
  <summary>What must you do if a baseline is not met?</summary>
  Put a plan in place to recorrect it immediately.
</details>

<details>
  <summary>Who normally sets what the baseline is for a device?</summary>
  The manufacturer.
</details>

<details>
  <summary>What may you need to do if new vulnerabilities are found?</summary>
  You may need to go back and add to the baseline.
</details>

<details>
  <summary>What do you do if two manufacturers have opposing baselines?</summary>
  You may have to decide which baseline is better.
</details>


------

### Securing Wireless and Mobile

<details>
  <summary>What is a site survey?</summary>
  A site survey will help you understand how your network is running and performing. It identifies the access points and will help find ways to tweak and improve your network.
</details>

<details>
  <summary>What is a heat map?</summary>
  A heat map is a visual representation of a site survey and will display signal strengths of connection.
</details>

<details>
  <summary>What do other wireless survey tools allow you to do?</summary>
  Check signal coverage, check for potential interference, use built-in tools, and spectrum analyser.
</details>

<details>
  <summary>What do we use for securing wireless networks?</summary>
  We use MDM (Mobile Device Management).
</details>

<details>
  <summary>What are the two types of mobile devices in an organisation?</summary>
  Company owned and BYOD (Bring your own device).
</details>

<details>
  <summary>What does a MDM do?</summary>
  This tool allows technicians to manage the devices at a centralised location.
</details>

<details>
  <summary>What does BYOD stand for?</summary>
  Bring your own device.
</details>

<details>
  <summary>What does BYOT stand for?</summary>
  Bring your own technology.
</details>

<details>
  <summary>What does COPE stand for?</summary>
  Corporate owned, personally enabled.
</details>

<details>
  <summary>What does CYOD stand for?</summary>
  Choose your own device.
</details>

<details>
  <summary>Who owns the device in a CYOD situation?</summary>
  The organisation.
</details>

<details>
  <summary>What is each point of a cellular network known as?</summary>
  A cell.
</details>

<details>
  <summary>What are the three common security concerns with mobile devices?</summary>
  Traffic monitoring, location tracking, and worldwide access to mobile devices.
</details>

<details>
  <summary>What is Bluetooth?</summary>
  A high-speed communication over short distances.
</details>

<details>
  <summary>What is another name for Bluetooth?</summary>
  PAN (Personal Area Network).
</details>


------

### Security Monitoring

<details>
  <summary>What can you monitor to find out if someone is trying to log into an account?</summary>
  Authentication logs.
</details>

<details>
  <summary>What tool can we use to check logs in a centralised location?</summary>
  We can use a SIEM (Security Information and Event Manager) tool.
</details>

<details>
  <summary>What do organisations preform to check for vulnerabilities?</summary>
  Active scanning.
</details>

<details>
  <summary>Why should you create reports on patches and vulnerabilities?</summary>
  To help determine the next actions to take.
</details>

<details>
  <summary>What are these reports called?</summary>
  Actionable reports.
</details>

<details>
  <summary>According to a IBM report in 2022, how long does it take for an organisation to identify a breach?</summary>
  9 months.
</details>

<details>
  <summary>What is alerting?</summary>
  A notification of a security event.
</details>

<details>
  <summary>What should you do when an alert is triggered?</summary>
  Quarantine the system to prevent the attack spreading to other devices on the network.
</details>

<details>
  <summary>What should you tune your alerting system to prevent?</summary>
  To prevent false positives and false negatives.
</details>


-----

### Security Protocols

<details>
  <summary>What is a way to protect data being sent over a wireless or wired connection?</summary>
  Encrypt the data.
</details>

<details>
  <summary>List 4 protocols that are not encrypted:</summary>
  Telnet, FTP, SMTP, IMAP.
</details>

<details>
  <summary>How can you confirm whether data is encrypted?</summary>
  By capturing the packets and looking at the data.
</details>

<details>
  <summary>What is the secure version of Telnet?</summary>
  SSH.
</details>

<details>
  <summary>What is the secure version of HTTP?</summary>
  HTTPS.
</details>

<details>
  <summary>What is the secure version of IMAP?</summary>
  IMAPS.
</details>

<details>
  <summary>What is the secure version of FTP?</summary>
  SFTP.
</details>

<details>
  <summary>What does a VPN create?</summary>
  An encrypted tunnel for you to pass data between two points.
</details>


-----

### Security Tools

<details>
  <summary>What issue may you have if you are running different types of security devices?</summary>
  They may identify the same vulnerability but they might all have a different name for it.
</details>

<details>
  <summary>What does SCAP stand for?</summary>
  Security Content Automation Protocol.
</details>

<details>
  <summary>What does NIST stand for?</summary>
  National Institution of Standards and Technology.
</details>

<details>
  <summary>What does SCAP do?</summary>
  Converts all these different notifications into one language and allows the system to highlight them as one vulnerability.
</details>

<details>
  <summary>What does SCAP allow you to do?</summary>
  Allows you to completely automate ongoing monitoring, notifications, alerting, and remediation of noncompliant systems.
</details>

<details>
  <summary>What is a benchmark?</summary>
  A benchmark is the bare minimum of security.
</details>

<details>
  <summary>Where can you find benchmarks?</summary>
  On the CIS (Center of Internet Security) website.
</details>

<details>
  <summary>What are agents used for?</summary>
  To see if a device is compliant.
</details>

<details>
  <summary>What do agents do?</summary>
  They monitor for real-time notifications.
</details>

<details>
  <summary>What does it mean if a system is agentless?</summary>
  It runs without a formal install. It performs the check, then disappears.
</details>

<details>
  <summary>What does SIEM stand for?</summary>
  Security Information and Event Management.
</details>

<details>
  <summary>What are SIEMs used for?</summary>
  To log security events and information.
</details>

<details>
  <summary>What does DLP stand for?</summary>
  Data Loss Prevention.
</details>

<details>
  <summary>What does DLP do?</summary>
  It finds and blocks sensitive data on your network.
</details>

<details>
  <summary>What does SNMP stand for?</summary>
  Simple Network Management Protocol.
</details>

<details>
  <summary>What does MIB stand for?</summary>
  Management Information Base.
</details>

<details>
  <summary>What is NetFlow?</summary>
  NetFlow is a standard for monitoring traffic flows and looking at statistics related to application usage.
</details>


-----

### Threat Intelligence

<details>
  <summary>What does OSINT stand for?</summary>
  Open Source Intelligence.
</details>

<details>
  <summary>What is OSINT?</summary>
  Open source information that can tell you more about an attack.
</details>

<details>
  <summary>What is commercial data?</summary>
  Data that has been released by an organisation.
</details>

<details>
  <summary>What is a threat intelligence service?</summary>
  A third party that does your threat intelligence for a fee.
</details>

<details>
  <summary>What will a threat intelligence service do?</summary>
  They will highlight the areas that need amending or patching.
</details>

<details>
  <summary>What does CTA stand for?</summary>
  Cyber Threat Alliance.
</details>


-----

### Vulnerability Scanning

<details>
  <summary>What is a vulnerability scan?</summary>
  A vulnerability scan checks if a system is susceptible to specific vulnerabilities. The scanner will also do a port scan to check for any open ports.
</details>

<details>
  <summary>Does a vulnerability scan attack the system?</summary>
  No, that would be a penetration test.
</details>


-----

### Web Filtering

<details>
  <summary>What is a content filter?</summary>
  These are used to block content like a parent control.
</details>

<details>
  <summary>What does URL stand for?</summary>
  Uniform Resource Locator.
</details>

<details>
  <summary>How do content filters work?</summary>
  They scan the URL and compare it with URLs on the block and allow list.
</details>

<details>
  <summary>What is a block list?</summary>
  A list of sites that a user cannot access.
</details>

<details>
  <summary>What is an allow list?</summary>
  A list of sites a user can access. Everything else will be blocked.
</details>

<details>
  <summary>How do you block all of a type of website?</summary>
  You can create group categories that contain specific information.
</details>

<details>
  <summary>What device would you use to set up URL filtering?</summary>
  NGFW (Next Generation Firewall).
</details>

<details>
  <summary>What is an agent-based firewall?</summary>
  A firewall on the user's device.
</details>

<details>
  <summary>What is the benefit of an agent-based firewall?</summary>
  The user can travel anywhere and still be protected.
</details>

<details>
  <summary>What is a proxy?</summary>
  A proxy sits between the user and the external network, making the requests for the user.
</details>

<details>
  <summary>What is a proxy cache?</summary>
  This is where the proxy stores results from queries so that repeated requests don’t need to go out to the external network again.
</details>

<details>
  <summary>What can you control with a proxy?</summary>
  The flow of traffic — you can control which devices are allowed to access the Internet.
</details>

<details>
  <summary>What is an explicit proxy?</summary>
  When you have to manually tell the device to use the proxy.
</details>

<details>
  <summary>What is a transparent proxy?</summary>
  A proxy that the end user doesn’t realise they are using.
</details>

<details>
  <summary>What is a forwarding proxy?</summary>
  A proxy that forwards requests to the external network on behalf of the user.
</details>

<details>
  <summary>What is another name for a forward proxy?</summary>
  An internal proxy.
</details>

<details>
  <summary>What other tools do proxies have?</summary>
  URL filtering and the ability to block malware.
</details>

<details>
  <summary>What are the ranges of risk?</summary>
  Trustworthy, low risk, medium risk, suspicious, and high risk.
</details>

<details>
  <summary>What is a reputation filter?</summary>
  This means the content filter will look at the reputation of a site before allowing access.
</details>

<details>
  <summary>What is DNS filtering?</summary>
  When the DNS service blocks URLs that are known to be bad or contain malware.
</details>


-----

### Wireless Security Settings

<details>
  <summary>What are the two main concerns with wireless devices?</summary>
  Sending data over the network and making sure only authorised users have access to the device.
</details>

<details>
  <summary>What can we do to solve these concerns?</summary>
  Encrypt the data travelling over the network and make sure the correct authentication methods are set up.
</details>

<details>
  <summary>What does MIC stand for?</summary>
  Message Integrity Check.
</details>

<details>
  <summary>What does PSK stand for?</summary>
  Pre-Shared Key.
</details>

<details>
  <summary>What encryption tool is no longer recommended with wireless connections?</summary>
  WPA2.
</details>

<details>
  <summary>What is the latest encryption tool used for wireless connections?</summary>
  WPA3.
</details>

<details>
  <summary>What does GCMP stand for?</summary>
  Galois/Counter Mode Protocol.
</details>

<details>
  <summary>What makes WPA3 more secure?</summary>
  WPA3 includes data confidentiality with AES protocol, message integrity checking with GCMP, mutual authentication, and it creates a shared session key without sending the key over the network.
</details>

<details>
  <summary>What does SAE stand for?</summary>
  Simultaneous Authentication of Equals.
</details>

<details>
  <summary>What key exchange does SAE derive from?</summary>
  Diffie-Hellman.
</details>

<details>
  <summary>What is the name for this handshake?</summary>
  The Dragonfly Handshake.
</details>

<details>
  <summary>What type of key is a WiFi password?</summary>
  PSK (Pre-Shared Key).
</details>

<details>
  <summary>What is a more secure version of a WiFi password that an organisation might use?</summary>
  802.1X, which is a centralised authentication method that may require a username, password, and another type of authentication.
</details>

<details>
  <summary>What would a home setup most likely look like?</summary>
  WPA3-Personal / WPA3-PSK.
</details>

<details>
  <summary>What would an organisation setup look like?</summary>
  WPA3-Enterprise / WPA3-802.1X.
</details>

<details>
  <summary>What is the centralised server known as?</summary>
  The AAA Framework.
</details>

<details>
  <summary>How does the AAA Framework work?</summary>
  It starts with identifying the user via a username, then Authentication (password), Authorisation (what resources are allowed), and Accounting (logging who logged in and what was done).
</details>

<details>
  <summary>What is one of the most popular authentication protocols?</summary>
  RADIUS (Remote Authentication Dial-In User Service).
</details>
