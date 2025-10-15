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




