#### 🎓 Professor Messer Study Notes

## Infrastructure considerations - CompTIA Security+ SY0-701 - 3.1

[Link to video](https://youtu.be/Ap3Z_0ZdqpQ?si=g0zToN6QgaBUX6Dh)

### Notes

Availability means that the site and its features are always available. We also want to make sure that they are only available to the right people.

Uptime is usually how people measure how available your services are.

Resilience is how quickly you can get your systems back online after they are taken offline. A typical measurement is Mean Time to Repair (MTTR)

Before the system comes back up, we need to find the root cause, replace any hardware thats broken, patch software, and sort any redundant systems.

Cost is a big consideration when looking at installing new software and devices and could be a limiting factor. The cost is not only in purchasing the technology, but setup, training, and maintaining the systems. 

Responsiveness is how fast you get a response from the system. This is really important for interactive features. Speed is an important metric. 

Scalability is how quick and easy we can increase or decrease capacity. Elasticity is the term we use for how quickly this can happen. 

An application consists of many different parts:
- Web server
- Database
- Caching server
- Firewall

When deploying the application, it’s important to look at the hardware resources, cloud budgets, and change controls. 

The process of automating deployment is known as Orchestration.

To minimise the risk of systems, more organisations will transfer the risk to a third-party. To do this, they will take out cybersecurity insurance which covers the cost of an attacks and downtime. This has been on the rise with ransomware. Some insurances may even cover you for the cost of loss of business. Some will also cover and protect against legal issues. 

Checking for patches and updates is usually the first thing we do after installation. 

Some embedded systems are unable to be patched due to the fact that some are not connected to the internet. If you are unable to patch a device, it is worth adding additional security measures.

It is important to monitor your power usage to make sure that your systems are always running. If you plan to scale your system, it’s important to check that your current power inlet can handle the amount of power needed. To check this, you can hire an electrician to check this for you.

It is also important to check if your system requires a UPS (Uninterruptible power supply) or a generator to keep your systems running during a power cut or broken cables. 

Compute power is the amount of computing power that your system has. This may be referred to in the cloud as the compute engine. It is important to check that you have enough compute power to run your applications and systems with heavy traffic. 
