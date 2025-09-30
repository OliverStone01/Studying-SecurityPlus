#### 🎓 Professor Messer Study Notes

##  Security-policies - CompTIA Security+ SY0-701 - 5.1

[Link to video](https://youtu.be/5kY9kvzeWjA?si=b6j7LpM8Asdpmh01)

### Notes

The main goal of a security administrator is to maintain the CIA triad:
- Confidentiality
- Integrity
- Availability

To achieve this, we reply of rules and policies that everyone must follow.

Security policies are broad and some are very detailed. Either way, it should tell us what we should do and why we need to do it. The enforcement of these policies and rules comes through technical security controls. 

Most organisations keep a master list of security protocols. This isn’t optional, In many cases it’s a mandatory set of rules that maintain uptime, availability, and overall security.

These documents contain:
- What happens if a virus is found of a workstation
- What if someone tries to connect remotely
- What if a vulnerability is exploited

There is also a roles and responsibility section which has the contact information for the person to call if there is a problem. It’s important to note that policies only matter if they are enforced.

The Acceptable Use Policy (AUP) applies to everyone and it defines what employees can and cannot do with company technology. Not only does it set expectations, but it also protects the organisation legally if someone breaks the rules.

Business continuity policies is the manual way of continuing business without technology. This might be processing payments manually and calling the credit card company for approval instead of using a card payment network.

Business continuity requires lots of planning and regular testing to make sure everything works.

Disaster recovery is an extreme version of business continuity. A disaster recovery plan covers how you would recover to a recovery site if the main site has been destroyed in a natural disaster. This might require a new site, data centre, and possibly an appliance rebuild.

You also need an Incident response policy that outlines exactly what to do when malware is executed, a phishing attack occurs, or a denial of service attack takes systems offline. 

These policies guide the incident response team, it security managers, compliance officers, technical staff, and end users. For deeper structure, organisations often follow the NIST framework special publication 800-61 which lays out the response lifecycle:
- Preparation
- Detection and analysis
- Containment
- Eradication and recovery
- Post incident review

Policies also extend into the software development lifecycles (SDLC). This is the structured process for building applications. This includes:
- Requirements and development
- Testing
- Deployment
- Maintenance

Two common approaches are waterfall (linear) and agile (iterative which is much faster).

Every update that is done on a system must go throughChange management. This is a structured process which ensures updates do not disrupt business operations and must always include a fallback plan for if something goes wrong.

