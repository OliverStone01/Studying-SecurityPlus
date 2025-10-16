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


