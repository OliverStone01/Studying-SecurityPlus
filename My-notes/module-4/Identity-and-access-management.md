#### 🎓 Professor Messer Study Notes

##  Identity and Access Management - CompTIA Security+ SY0-701 - 4.6

[Link to video](https://youtu.be/ZoOyyqhptik?si=TLQXuBB-7Gt9HFRL)

### Notes

IAM (Identity and Access Management) ensures the right people get the right access at the right time. It begins when a user is onboarded and ends when their account is deactivated.

At its core, IAM defines Access control: Who can access what. This is done by creating accounts, assigning permissions, and later updating and removing.

Provisioning and deprovisioning are the foundation

Least privilege means users should only get the permissions necessary for their job.

IAM also relies on Identity proofing which means we must confirm that a user is who they claim to be. This can be done via passwords, security questions, government documents, or automated checks like credit history. Once authenticated, system can decide whether to grant access.

Single Sign-On (SSO) allows you to log in once, then use resources across the network without re-entering credentials repeatedly.

LPAD (Lightweight Directory Access Protocol) Manages large directories of users and resources.

SAML (Security Assertion Markup Language) Lets organisations reply on third party authentication databases (Not mobile friendly)

OAuth is designed for modern mobile environments. It is an authentication framework, often paired with OpenID for authentication.

Federation allows you to log in to one service using credentials from another, like signing into a website with your google account or apple account.

Organisations choose which systems to use based on interoperability. For instance, if a VPN supports LDAP and your company already has Active Directory.
