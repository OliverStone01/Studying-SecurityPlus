#### 🎓 Professor Messer Study Notes

##  Application Security - CompTIA Security+ SY0-701 - 4.1

[Link to video](https://youtu.be/fFvXy3WkLpA?si=S6Dk94T7BC4fWiQM)

### Notes

When apps are created, there is a fine balance between having enough time/getting the application out there and making sure the application is secure.

To make an application as secure as possible, we need to run as many tests as possible. This is usually done during QA (Quality Assurance) which checks the app’s functionality and its security.

Input validation is the method of check the data that a user has imputed into the application. We do this to prevent users from inputting any malicious code or injections as these will be thrown out by the system. 

Fuzzing might be tested which automatically tests these inputs for you and will make sure the application performs as it should and does not crash.

Secure cookies are similar to normal cookies although they can only be transferred over HTTPS with encryption. 

Cookies are not very secure which is why the devs do not put any of your personal information to keep track of your session. That said, if an attack got your cookies they might be able to jump into your session gaining access to your account.

One method for developers to test how secure their applications are, they run it through SAST (Static Application Security Testing).

SAST identifies security flaws by analysing the code.

Code signing is the process of checking the integrity of the code you have installed. Most organisations and developers will create a hash of the code and post that online. You can then download the application, run the hashing algorithm and see if they match. If they do, your software is legit. 

Sandboxing is a way of testing software. The software inside of the sandbox will only have access to the data allocated to that sandbox.

Developers build their applications in a sandbox environment so that it doesn’t affect the production application.

Most developers will make build in security monitoring. This means they can track real time information and view blocked attacks like SQL injection attempts. This will create a log that can then be audited and viewed by the developers.

You may also have anomaly detection which detects any unusual file transfers and a big fluctuation in client access.

