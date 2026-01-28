#### 🎓 Professor Messer Study Notes

## DNS Attacks - CompTIA Security+ SY0-701 - 2.4

[Link to video](https://youtu.be/BoxeL5ybOXI?si=ZA6DQ6KJagGXZori)

### Notes

DNS = Domain Name Service

DNS servers allows us to use domain names and connects them to the IP address of that site. This allows us to brand and create easy to remember urls instead of needing to remember IP Addresses for every site.

DNS poisoning attacks are made so that when the user enters a domain, they are redirected to a different site.

DNS poisoning can be done by modifying the DNS server which is very difficult and not commonly seen.

Instead, attacker can modify the host file that is in the users device. The host file contains common sites the user visits. This way the device doesn’t have to query the DNS server every time you visit the site. 

Another method would be to preform a man in the middle attack with the request and return back a different address to the user.

Domain hijacking is where the attacker has access to the domain registration and changing the address that’s the domain links to.

URL hijacking can be done by registering domains that are spelt bad to catch users. They can make money by either selling this domain to the company or redirecting you to see an ad when you accidentally search the domain. 

The attacker could also create a phishing link that takes you to a similar site tricking the user to sign in with their real credentials.

These types are known as typo squatting/brandjacking.  

The attacker may also register the exact same url but with a different top level domain (.org for example).

