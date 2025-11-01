#### 🎓 Professor Messer Study Notes

##  Email Security - CompTIA Security+ SY0-701 - 4.5

[Link to video](https://youtu.be/v6ht9efsnRI?si=EHyDdB9K5-FlKZy3)

### Notes

The protocol used to transfer emails has very limited security. This means sometimes you receive emails from people who did not send that email. This is because attackers are able to spoof emails making it look like another person sent the email.

Fortunately, we can use a DNS server that can confirm whether an email was sent from a legitimate server.

Mail gateway is the gatekeeper that takes in mail you have received over the internet, it will check if the source is valid. If the source is valid, then the mail is placed into your inbox, else it is put into spam or deleted.

If the Mail gateway is on premises, then it should be placed into a screened subnet. 

SPF (Sender Policy Framework) is used to configure a server that will send mail on our behalf. This is commonly seen in a organisation. The policy is sent to the DNS server to confirm who is able to send mail on our behalf. 

These lists are added to your DNS server as a TXT record. Anyone on the internet can query your DNS server and see the data in the TXT record. 

You can add extra security to outgoing emails by using DKIM (Domain Keys Identified Mail). This is a public key signature that is sent between mail servers. You can find this in the headers. This verifies that an email was sent from your server.

The DKIM TXT record is added to the DNS server similarly to how the SPF TXT is added.

DMARC (Domain-based Message Authentication, reporting, and conformance) specifies what you want to happen when an email is not validated via SPF or DKIM. 

We can right a policy that tells all rejected mail to be sent to spam, accept it, or reject the email. 

You can also get a compliance report that will show how many emails were received and how many were rejected.

