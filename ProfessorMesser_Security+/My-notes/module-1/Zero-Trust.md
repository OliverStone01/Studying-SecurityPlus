#### 🎓 Professor Messer Study Notes

## Zero Trust - CompTIA Security+ SY0-701 - 1.2

[Link to video](https://youtu.be/zC_Pndpg8-c?si=vmKh00Fkx8p-t9qY)

### Notes

Zero trust means that you have to authenticate your self every time you want to access any resources on a network or system.

This can mean that you need to use multifactor authentication, encryption when sending and storing data, system permissions, additional firewalls, monitoring, and analytics.

To implement Zero trust, we can split the network into functional planes. This means we can control each section of the network with different security features.

The first plane is the `Data plane`. This is where all network processing, forwarding, trunking, and encrypting takes place. Including processing frames, packets, and network data.

The second plane is the `Control plane`. This is where we manage the actions of the data plane, define policies, rules, determines how packets should be forwarded.

Adaptive identity is a way we can check information about users to find out who they are. This is a great way for implementing zero trust as we can prove that people are who they say they are by for example, if the user says they are in the US but the IP address is in China, we know something is not right.

Adaptive identity is able to check the physical location of the device, type of connection, IP address, and relation to the organisation.

Threat scope reduction is reducing the amount of entry points to a network or physical building.

Policy-driven access control examines the adaptive identity with a predefined set of rules to determine if the user is who they say they are.

Security zones are areas you set and can then control how each zone can talk to each other and what rules apply to different security zones.

Policy enforcement point (PEP) is a gatekeeper that all the traffic on the network must pass through and will be subject to examination. The PEP then passes this information to the `policy decision point` which is made up of the `policy engine` and the `policy administrator` which will then decide whether the request is denied or accepted. 

The policy engine evaluates each access decision based on policy and other sources of information. It will then either grant, deny, or revoke access. 

The policy administrator will then take the decision of the policy engine and pass it back to the PEP. 




