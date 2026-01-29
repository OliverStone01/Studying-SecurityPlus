#### 🎓 Professor Messer Study Notes

## Other Infrastructure Concepts - CompTIA Security+ SY0-701 - 3.1

[Link to video](https://youtu.be/HDiNPPrGhzE?si=f69rXO5ZuIDtR6zR)

### Notes

Cloud-based security is all centralised and is controlled by the third party cloud network provider. This means you do not need your own dedicated hardware and you won’t need to secure your own data centre.

On-premises on the other hand puts all the control and security in the hands of the organisation. This also means more costs.

The benefits to on-premises is that all the control is in your hands and you are able to manage every piece of security. 

The benefits of On-premises security is you have an in house IT Team that can be ready at any time to update systems and combat attacks.

The downside is that it takes time to upscale the system and manage the security.

Most organisations are physically decentralised as there are many locations, some cloud services, and different operating systems.

This can become difficult to manage and protect. 

What most security teams will do is create a centralised system that shows and allows them to manage all the systems from one place, receive alerts, and get all log files.

The downside to this approach is there is one point of failure and as the system scales, you may need more and more storage and system power to manage it all. 

Virtualisation allows us to build and tear down systems online. This works by having one device (infrastructure) powering all the systems and software (hypervisor) that splits up the system into multiple virtual systems.

Infrastructure = main device
Hypervisor = software managing the virtual devices on the main system.

Each system requires its own guest operating system and the applications you want to run on that system.

One inefficient issue with virtual machines is that each device requires its own operating system. Instead, organisations are moving to a container machine. 

Containers allow you to run different applications all on one device without the need of running multiple different virtual devices. 

The benefit is, each application is isolated from one another making it easy to remove and add other containers.

Containers are laid out with the main device (infrastructure) running the host operating system which runs the container software (a popular choice is docker) which runs the applications.

IOT = internet of things

These are devices connected to your internet that you may use in your everyday life. This includes: sensors (heating controls, lighting, motion sensor), smart devices (home automation, smart doorbell), wearable technology (smartwatch, smart ring), facility automation (temperature sensors, air quality sensors)

It’s important that you check the security with these devices and check default passwords as this can give access to your network.

Large machines are usually controlled with SCADA also known as an ICS.

SCADA = Supervisory Control and Data Acquisition System.

ICS = industry control system.

SCADA allows companies to monitor and modify all the large machines from one centralised system in real time. 

It’s important that SCADA systems are kept separate and secure because if an attacker gets in, they can take over the entire system.

A deterministic operating system is a system that can use all the processing power to focus on one task. For example, if you break hard in an electric car, the deterministic system solely focus on bringing you to a stop safely by working the breaks, the antilock system, etc.

These are also known as real time operating systems (RTOS). These systems are extremely sensitive to security vulnerabilities. 

Embedded system is where the hardware and software are build together as one device. This can be seen with traffic lights, digital watches, and medical imaging systems.

Redundancy means that you have multiple systems ready to take over if one goes down. This might mean that you still need to plug in the device and plug it in.

High availability (HA) means that the systems are always on and ready to go if something goes wrong.

Unlike redundancy where you may need to plug in the backup device, to achieve high availability, you may run two devices all the time and split the work load. If one device goes down the other device can take all the load.

High availability costs more than redundancy.


