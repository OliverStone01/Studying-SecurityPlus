#### 🎓 Professor Messer Study Notes

## Cross-site scripting - CompTIA Security+ SY0-701 - 2.3

[Link to video](https://youtu.be/PKgw0CLZIhE?si=zmsqs4Dr5XZqVTbs)

### Notes

XSS = Cross site scripting

Cross-site scripting gets its name because of a flaw that allowed you to share information from one site to another site.

This is one of the most common web app vulnerabilities seen.

Cross-site scripting attacks mostly use JavaScript.

An example of this attack is an attacker sends a link containing a malicious script to a victim. Once the link is clicked, the user is taken to a legitimate site but when the site loads, the cookies and other data loaded by the site is sent to the attacker.

Non-persistent (reflected) XSS attack is when an attacker can inject and run javascript on a site.

Persistent (stored) XSS attack is when the attacker makes a post on social media that contains malicious code so that when users visit the post, the malicious code is run.

To protect against XSS, be careful when clicking untrusted links and never blindly click on your email inbox. You can also limit the javascript in your browser. Make sure to keep your browser and applications updated.

As a developer, you need to make sure you are validating inputs to remove scripts.








