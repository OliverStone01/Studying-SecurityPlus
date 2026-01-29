#### 🎓 Professor Messer Study Notes

##  Resiliency - CompTIA Security+ SY0-701 - 3.4

[Link to video](https://youtu.be/sb0dRaQbuBA?si=6tMYC11UROnJB2vO)

### Notes

To have high availability, you must have high resilience to attacks and other challenges that may cause your system to go down.

To have high availability, your system must be ready to take over in case something goes down.  This means you will need more systems running that is being used and you will also see higher energy costs to run these systems.

Another method for high availability is to use server clustering. This is where you combine two or more servers to act as a back up in case the other fails. This also means you can have quick scalability and can be turned on during configuration.

The servers will use a shared database server so that they do not all need to read and write data all the time.

Load balancing is used to split the load across the servers to prevent a single server being overloaded with requests.

You can add and remove devices to the load balancer as you go. They will also do this automatically if one of the servers fails.

Site resiliency is having a second site that is up to date with all the data and is ready to go in case anything happens to the original site.

This is usually in a completely different part of the world to protect against natural disasters or power outages. 

A hot site is an exact replica of your data centre where we keep everything up to date including software updates and backups of your data. This allows us to swap over immediately if we needed to in case the first site went down.

A cold site is an empty building with no hardware which means you would need to bring all your data and hardware to the site before you can be operational again. 

A warm site is an in-between a Hot site and a Cold site where some equipment may be there and in place but there are missing components that you need to plug in before you can be operational again.

Geographic dispersion is used to make sure that the backup site would not be impacted if a natural disaster stuck the main site. 

Platform diversity is used to prevent your entire infrastructure being at risk due to one vulnerability effecting the operating system. Instead, by using different operating systems in different parts of your organisation, you prevent all systems being down. 

We can do a similar thing with cloud systems by using different cloud services for different parts of the organisation can prevent the entire organisation being shut down due to one service going down. 

COOP (Continuity of operations planning) means that you have a paper back up method that doesn’t require technology to complete tasks and keep the organisation running. 
