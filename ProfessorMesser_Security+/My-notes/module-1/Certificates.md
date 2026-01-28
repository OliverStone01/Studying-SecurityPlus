#### 🎓 Professor Messer Study Notes

## Certificates - CompTIA Security+ SY0-701 - 1.4

[Link to video](https://youtu.be/cLa94BZH_9s?si=xKCjX1TuSwUNDDbT)

### Notes

A digital certificate contains a public key and a digital signature. It is essentially a digital ID.

A digital signature adds trust that the user is who they say they are. We also use Certificate Authorities for additional trust and Web of trust.

When a Certificate authority signs a certificate, it means that it can be trusted.

A Web of trust means that if your friend trust a person and you trust your friend then we can trust that other person.

You can create your own certificates using built in tools in the operating system or we can use a third party option. 

When you visit a website and see the lock in the URL bar, you can click on this and it will reveal the sites digital certificate. Most sites use a standard format known as X.509.

Certificate details:
- Serial number
- Version
- Signature Algorithm
- Issuer
- Name of the cert holder
- Public key
- Extensions


Trust is everything in security. When visiting a new site for example, how do we trust that its safe? We can use software, hardware (HSM), security enclave, certificate authorities as the root of trust.

For example, when visiting a site for the first time, we can check that sites digital certificate to see if it has been signed by a trusted third party like a Certificate Authority that you trust. This means that if you trust the Certificate Authority, then you can trust the site.

Third-party certificate authorities are build-in to your browser. 

We can revoke certificates using a CRL (Certificate Revocation List). This list is managed on the Certificate authority. 

Another method is using OCSP stapling (Online Certificate status protocol). This status is stapled to the SSL/TLS handshake.











