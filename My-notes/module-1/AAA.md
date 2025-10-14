#### 🎓 Professor Messer Study Notes

## Authentication, Authorisation, and Accounting - CompTIA Security+ SY0-701 - 1.2

[Link to video](https://youtu.be/AhaZtj5P2a8?si=f-7jl7BdBd1FTsaf)

### Notes

Identification is telling the system who you claim to be. This is ususally done via your `username`.

Authentication is the act of proving who you say you are. This can be done via a `Password` and other authentication factors

Authorisation is what you have access to and this is based on your identification (who you are).

Accounting is the logging of who logged in, when they did so, what data was sent and received, and when they logged out.


An example of using triple AAA is logging in to a VPN for example. The user goes onto the internet using their device and browser. They then go the VPN's site and send login details to the VPN. The VPN itself doesnt store these details so it doesnt know whether you are a valid user or not. What the VPN service will then do is send your details to a AAA server on the VPN's main server which can verify if the details are correct. Once the details have been confirmed, a `credentials approved` signal is sent back to the VPN allwoing the user to login.


A device cannot type a password itself, so we must provide it with a signed certificate that proves its authentication. This certificate must be signed by a `Certificate Authority (CA)` and given to the device. 

To assing authorisation to specific systems, we can use an authorisation model that is placed between the user and the software and will only allow those that we have specified based on roles, organisation, attributes, etc.














