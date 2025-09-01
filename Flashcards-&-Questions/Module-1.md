## 🗃️ Flashcards & Questions for module 1  
To reveal the answer, click on the question or the `>` arrow to the left side of the question.

-----

### Security Controls

<details>
  <summary>1. Name all the control categories</summary>
  - Technical, Managerial, Operational, and Physical
</details>


<details>
  <summary>2. What is a technical control?</summary>
  - Using software to control what functions can and cannot be used on a system. Firewalls can be used to block network traffic entering and leaving a system. Operating system controls can be used to prevent users from accessing functions and data
</details>


<details>
  <summary>3. What are managerial controls?</summary>
  - Implementing security designs and security policies that staff and users must be trained on and must adhere to as a standard operating procedure for keeping data safe.
</details>


<details>
  <summary>4. What are operational controls</summary>
  - Using people for control and security. Such as security guards, awareness programs, and posters informing staff how to keep data safe
</details>


<details>
  <summary>5. What are physical controls</summary>
  - These are physical security controls to prevent physical access such as fences, locks, badge readers, and bollards.
</details>


<details>
  <summary>6. What are the six control types?</summary>
  - Preventive, deterrent, detective, corrective, compensating, directive
</details>


<details>
  <summary>7. What are the six control types?</summary>
  - Preventive, deterrent, detective, corrective, compensating, directive
</details>


<details>
  <summary>8. What is preventive control?</summary>
  - Prevents access to a specific resource. For example, a firewall, security policies, locked doors, or guards checking ID to make sure they have access.
</details>


<details>
  <summary>9. Give an example of preventive controls for each control category</summary>
  
  - Technical: Firewall
  - Managerial: Security policy such as on-boarding policy
  - Operational: Guard shack checking ID's
  - Physical: Locked doors
</details>


<details>
  <summary>10. What are deterrent controls?</summary>
  - To deter and try prevent attackers from their attack. This can be done using warning signs and a threat of demotion if an employee accesses areas they are not supposed to.
</details>


<details>
  <summary>11. Give an example of deterrent controls for each control category</summary>
  
  - Technical: Splash screen (Warning Screen)
  - Managerial: Threat of demotion for accessing restricted areas.
  - Operational: Receptionist checking in everyone into the building.
  - Physical: Warning signs
</details>


<details>
  <summary>12. What are detective controls?</summary>
  - These controls are not likely to stop an attack or intrusion but they log and store information about what happened so that it can be investigated later.
</details>


<details>
  <summary>13. Give an example of detective controls for each control category</summary>
  
  - Technical: Collecting and reviewing system logs
  - Managerial: Review log in reports
  - Operational: Regular patrol of the property
  - Physical: Motion detectors
</details>


<details>
  <summary>14. What are corrective controls?</summary>
  - These controls are taken after an event has occurred to try reverse or minimise the effect to the system or business with minimal downtime.
</details>


<details>
  <summary>15. Give an example of corrective controls for each control category</summary>
  
  - Technical: Restoring from a backup
  - Managerial: Creating policies for reporting security issues.
  - Operational: Contacting law enforcement
  - Physical: Fire extinguishers.
</details>


<details>
  <summary>16. What are compensating controls?</summary>
  - Using temporary solutions to fix issues until you are able to fix the main issue permanently.
</details>


<details>
  <summary>17. Give an example of compensating controls for each control category</summary>
  
  - Technical: Firewall blocking until the app is patched
  - Managerial: Separation of duties
  - Operational: Simultaneous guard duties
  - Physical: Generator to keep systems running until mains power is restored
</details>


<details>
  <summary>18. What are directive controls?</summary>
  - This is where you give direct orders to people to try improve security. This is a very weak security control.
</details>


<details>
  <summary>19. Give an example of directive controls for each control category</summary>
  
  - Technical: Store sensitive files in a protected folder
  - Managerial: Create compliance policies and procedures
  - Operational: train users on proper security policies
  - Physical: A sign on a door saying "Authorised personnel only"
</details>


-----

### The CIA Triad

<details>
  <summary>1. What is the other name for the CIA triad?</summary>
  - AIC Triad.
</details>


<details>
  <summary>2. What does the C in CIA triad stand for and what does it mean?</summary>
  - Confidentiality. To prevent disclosure of information to unauthorised users or systems.
</details>


<details>
  <summary>3. What does the I in CIA triad stand for and what does it mean?</summary>
  - Integrity. Messages cannot be modified without detection.
</details>


<details>
  <summary>4. What does the A in CIA triad stand for and what does it mean?</summary>
  - Availability. To make sure our systems and networks are always up and running.
</details>


<details>
  <summary>5. Give 3 examples of how you can insure confidentiality:</summary>
  - Encrypting data before it is send over the network. Access Controls to restrict users access to specific resources. Two factor authentication when signing in to accounts.
</details>


<details>
  <summary>6. Give 4 examples of how you can insure integrity:</summary>
  - Hashing the data, using Digital Signatures, Using certificates, and non-repudiation.
</details>


<details>
  <summary>7. Give 3 examples of how you can insure Availability:</summary>
  - Building systems using redundancy, Fault tolerance (adding extra components incase of failure), and Patching systems doing updates and fixing security holes.
</details>


<details>
  <summary>8. What is non-repudiation?</summary>
  - The act of making sure someone cannot later deny an action or message after it is sent.
</details>


-----

### Non repudiation

<details>
  <summary>1. What is an example of non-repudiation?</summary>
  - signing a contract using private and public keys.
</details>


<details>
  <summary>2. What is proof of integrity?</summary>
  - It means we can verify that data has not been changed.
</details>


<details>
  <summary>3. What is one way we can insure data has not been changed?</summary>
  - Hashing the data.
</details>


<details>
  <summary>4. What is hashing?</summary>
  - Hashing takes data and runs it through an algorithm to get a hash value that will only be produced when the data is identical. This allows us to check if data has been changed.
</details>


<details>
  <summary>5. Are hash values different in length depending on the ammount of data passed to the algorithm?</summary>
  - No, hash values are typically the same length no matter how much data you pass to the algorithm.
</details>


<details>
  <summary>6. What are two other names for hashing?</summary>
  - Message digest and fingerprint.
</details>


<details>
  <summary>7. What is the difference between a public and private key?</summary>
  - A public key is kept secret and is used when hashing data you want to send to someone. The person receiving your message then uses your public key (Which can be shared with anyone) to decrypt your message to make sure nothing has been changed in the message and to confirm the message came from you.
</details>


-----

### The AAA framework

<details>
  <summary>1. What are the 3 parts of the AAA framework?</summary>
  - Authentication, Authorisation, and Accounting
</details>


<details>
  <summary>2. What is identification?</summary>
  - Identification is telling the system who you claim to be. Usually via a username.
</details>


<details>
  <summary>3. What is the first A of the AAA framework and what does it mean?</summary>
  - Authentication. Proves you are who you say you are by providing a password and other authentication factors.
</details>


<details>
  <summary>4. What is the second A in the AAA framework and what does it mean?</summary>
  - Authorisation. This is what you have access to based on who you are.
</details>


<details>
  <summary>5. What is the last A in the AAA framework and what does it mean?</summary>
  - Accounting. This is where the system logs everything from who logged in, what time they logged in, what they did, and when they logged out 
</details>


<details>
  <summary>6. How can a device be trusted onto a network without typing a password each time?</summary>
  - We can assign the device with a certificate that allows the device to be authenticated.
</details>


<details>
  <summary>7. Who must sign this certificate?</summary>
  - The certificate authority (CA).
</details>


-----

### The Gap Analysis

<details>
  <summary>1. What is a Gap Analysis?</summary>
  - The study of diffrence between where your security is now and where you want it to be.
</details>


<details>
  <summary>2. What is a baseline?</summary>
  - Internal goals set inside of the organisation on where your security should be.
</details>


<details>
  <summary>3. What are two things you can examine when setting a baseline?</summary>
  - Examine the employees and their current training level and the IT processes of the company.
</details>


<details>
  <summary>4. What do we need to do when creating a Gap Analysis?</summary>
  - We need to compare and evaluate existing system, identify weaknesses, and create a detailed analysis of broad security categories and break them into smaller segments.
</details>


<details>
  <summary>5. What do you do once you have finished analysing the Gap Analysis?</summary>
  - Create the final gap analysis report that details where weaknesses are and what we can do to get our security to where we want it to be.
</details>

-----

### Zero Trust

<details>
  <summary>1. What is zero trust?</summary>
  - Zero trust means that you must authenticate to use any resources on the network or system.
</details>


<details>
  <summary>2. How do we implement zero trust?</summary>
  - We first need to split the network into functional planes so that we can add and define rules and policies.
</details>


<details>
  <summary>3. What are the 2 planes of operation?</summary>
  - Data plane and control plane.
</details>


<details>
  <summary>4. What is the data plane?</summary>
  - The control plane is where we manage the actions of the data plane. Such as defining rules and policies on how packets and other data should be processed and forwarded.
</details>


<details>
  <summary>5. What is the control plane?</summary>
  - The control plane is where we manage the actions of the data plane. such as defining rules and policies on how packets and other data should be processed and forwarded.
</details>


<details>
  <summary>6. What is adaptive identity?</summary>
  - It is a system that allows us to check users are who they  say they are by checking the IP address, physical location, type of connection, and the relation to the organisation. 
</details>


<details>
  <summary>7. Give an example of using adaptive identity:</summary>
  - A user says they are in the US and is trying to login to a US account but using adaptive identity shows that they are actually in China. Proving the user is not who they say they are
</details>


<details>
  <summary>8. What is a threat scope reduction?</summary>
  - Reduces the amount of entry points to a network or physical building.
</details>


<details>
  <summary>9. What is a policy driven access control?</summary>
  - Examins the adaptive controls and a predefined set of rules to determine if the user is who they say they are.
</details>


<details>
  <summary>10. What are security zones?</summary>
  - Security zones are areas you define for example separate departments in a company. You can then set specific rules for each zone and define how they talk to each other.
</details>


<details>
  <summary>11. What is the policy enforcement point?</summary>
  - This is a gatekeeper that all the traffic must pass through and be subject to examination. The data will be passed to the policy decision point where the policy engine then decides whether to grant, deny, or revoke the request.
</details>


<details>
  <summary>12. What is the abbreviation for the policy enforcement point?</summary>
  - PEP.
</details>


<details>
  <summary>13. What does PDP stand for?</summary>
  - Policy Decision Point.
</details>


<details>
  <summary>14. What does the policy administrator do?</summary>
  - It sends back the decision from the policy engine to the PDP back to the PEP.
</details>

-----

### Physical Security 

<details>
  <summary>1. What are bollards and barricades?</summary>
  - These are used to prevent access or guide people into specific access point using barriers, cones, and even water features with a bridge that everyone must cross.
</details>


<details>
  <summary>2. What is Access Control Vastibule?</summary>
  - The act of restricting access to areas where other areas are open.
</details>


<details>
  <summary>3. Give an example where access control vestibule is used:</summary>
  - When you have multiple interal doors that are unlocked when the access door is locked. But once the access door is unlocked, the other lock to prevent immediate access.
</details>


<details>
  <summary>4. What are the benefits of having access control vestibule?</summary>
  - It allows you to have a one at a time system where each user must unlock each door to gain access. This allows you to have controlled areas.
</details>


<details>
  <summary>5. What is the main benefit of fences?</summary>
  - Prevent easy access to restricted areas. They can also provide privacy depending on what material and design you use.
</details>


<details>
  <summary>6. What does CCTV stand for?</summary>
  - Closed Circut Television.
</details>


<details>
  <summary>7. What is video surveillance used for?</summary>
  - For logging who did what in a specific area. Monitoring and alerting motion or object detection.
</details>


<details>
  <summary>8. Why do we use security guards?</summary>
  - Security guards are a great method of physical control as they can authenticate people and investigate incidents.
</details>


<details>
  <summary>9. Do security guards work alone?</summary>
  - No, we use multiple guards to prevent one person having access to all assets.
</details>


<details>
  <summary>10. Why is lighting a good security feature?</summary>
  - Attackers want to remain hidden from cameras and guards. Adding lighting removes areas where attackers can hide.
</details>


<details>
  <summary>11. What are the 4 types of motion detection?</summary>
  - Infrared sensors, pressure sensors, microwave sensors, and ultrasonic.
</details>


-----

### Deception and Disruption

<details>
  <summary>1. What is a honeypot?</summary>
  - A honeypot is a way to attract attackers to a fake system so that we can see what type of attackers and bots they are using.
</details>


<details>
  <summary>2. What is a bigger and more believable honeypot called?</summary>
  - A honey net. This consists of multiple fake servers, workstations, switches, routers, and firewalls.
</details>


<details>
  <summary>3. What is a honey file?</summary>
  - A honey file is a fake file that we label as something like "password.txt" to attract attackers. We can apply alerts to alert us when a user accesses this file.
</details>


<details>
  <summary>4. What is a honey token?</summary>
  - A honey token is a fake token or fake email address we setup to detect when an attacker tried to take our information.
</details>


-----

### Change Management

<details>
  <summary>1. What is change management?</summary>
  - The way we process updates and patches to systems to prevent downtime and security vulnerabilities in any enviroment
</details>


<details>
  <summary>2. What is a formal change control process?</summary>
  - This is the process we follow to make sure we have the least amount of risk and downtime.
</details>


<details>
  <summary>3. List the common processes:</summary>
  
  - Complete a request form
  - Document the reason for change
  - Identify the scope of the change
  - Schedule a date and time of the change
  - Analyse the risk of change
  - Get approval from the change control board
  - Get end-user acceptance and check for issues
</details>


<details>
  <summary>4. Who is impacted if the process goes wrong?</summary>
  - The stakeholders
</details>


<details>
  <summary>5. What type of risk do you have to analyse before making the change</summary>
  - Minor risks, Major risks, and risk of not changing.
</details>


<details>
  <summary>6. What can we use to test the change before pushing to production?</summary>
  - We can copy our systems to a sandbox enviroment and test the roll out and then test the backout plan.
</details>


<details>
  <summary>7. What is a backout plan?</summary>
  - A backout plan the the plan for reversing the upgrade using things like backups and reverting to previous software system versions.
</details>

-----

### Technical Change Management

<details>
  <summary>1. Who usually does the upgrades to a system?</summary>
  - A technician
</details>


<details>
  <summary>2. What is an allow list?</summary>
  - A list of software and applications that the user is able to run on their system. Everything else will not run.
</details>


<details>
  <summary>3. What is a deny list?</summary>
  - A list of software and applications that the user is unable to run on their system. Everything else will run fine.
</details>


<details>
  <summary>4. What software is commonly seen as a deny list?</summary>
  - Anti-virus software
</details>


<details>
  <summary>5. What is important about the scope when doing upgrades?</summary>
  - It tells you what systems need to be upgraded and how long you have to complete the task. It is important that you only complete the tasks taht have been approved during the time allocated.
</details>


<details>
  <summary>6. What is downtime?</summary>
  - The length of time the system will be unavailable for.
</details>


<details>
  <summary>7. What is a legacy application?</summary>
  - An older application that is no longer supported by the developer.
</details>


<details>
  <summary>8. What is classed as a dependancy system?</summary>
  - When a system relies on other systems. This means that when you upgrade one software, you may be required to upgrade the other.
</details>


<details>
  <summary>9. Why is it important to document changes?</summary>
  - To be able to track changes and track system version and configuration.
</details>


-----

### Public Key Infrastructure

<details>
  <summary>1. What does the public key infrastructure refer to?</summary>
  - The procedures, hardware, and software that creates, distributes, manages, stores, and revokes digital certificates. It also referes to the binding on the public keys to people or devices.
</details>


<details>
  <summary>2. What is symmetric encryption?</summary>
  - To use the same key to encrypt and decrypt data. Sometimes referred to as secret key algorithms.
</details>


<details>
  <summary>3. What is asymmetric encryption?</summary>
  - To use two diffrent keys to encrypt and decrypt data.
</details>


<details>
  <summary>4. What are the two keys used in asymmetric encryption?</summary>
  - The public key and the private key.
</details>


<details>
  <summary>5. What is a private key?</summary>
  - The private key is supposed to be kept a secret and is the only key that can decrypt data that is encrypted by the public key.
</details>


<details>
  <summary>6. What is a public key?</summary>
  - The public key is allowed to be known to the public and can be used to encrypt data to be sent to the owner of the private key.
</details>


<details>
  <summary>7. Explain how Bob would send Alice a message using asymmetric encryption.</summary>
  - Bob would encrypt his message using Alices public key. He will then send this encrypted data to Alice who would then decrypt the message using her private key.
</details>


-----

### Encrypting data

<details>
  <summary>1.What do we call data in storage?</summary>
  - Data at rest
</details>


<details>
  <summary>2. Name 4 devices where we can encrypt data at rest:</summary>
  - USB drive, SSD, Hard drive, and cloud storage
</details>


<details>
  <summary>3. What are the 4 types on encyption we can do to data at rest?</summary>
  - individual file encryption, full disk encryption, record-level encryption, or transparent encryption
</details>


<details>
  <summary>4. Where do you typically see record-level and transparent encryption?</summary>
  - A database
</details>


<details>
  <summary>5. What software can we use for full-disj encryption?</summary>
  - Windows = Bitlocker, Mac = FileVault
</details>


<details>
  <summary>6. What software can we use on windows to encrypt individual files?</summary>
  - EFS (encryption file system)
</details>


<details>
  <summary>7. How do we encrypt data in transport?</summary>
  - For a browser, we can use HTTPS. Or we can use a VPN (virtual private network) to transfer data from one network to another through a encrypted tunnel.
</details>


<details>
  <summary>8. Do alogrithms need to be kept secret?</summary>
  - No, only the keys.
</details>


<details>
  <summary>9. What can we do to make keys more secure?</summary>
  - Key stretching. This is where we make the keys longer by constantly running them through a hash function multiple times.
</details>


-----

### Key exchange

<details>
  <summary>1.What is out-of-band key exchange?</summary>
  - Exchanging keys off the internet. In person for example
</details>


<details>
  <summary>2. What is in-band exchange?</summary>
  - Exchanging keys over the internet
</details>


<details>
  <summary>3. Give an example of how to do in-band exchange in a secure way:</summary>
  - We can use asymmetric encryption to send a symmetric key to someone else.
</details>


<details>
  <summary>4. What is in-band exchange commonly used for?</summary>
  - Exchanging session keys with a server.
</details>


<details>
  <summary>5.What is key exchange algorithm?</summary>
  - This is where we take our private key and merge it with someone elses public key. Once the other person does the same with their private key and our public key, we can symmetric keys without any data going over the internet.
</details>


