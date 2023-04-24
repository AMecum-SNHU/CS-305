# CS-305

Artemis Financial creates financial plans for their clients.  We were hired to create a web application for them that is secure, as there would be personal and financial data being passed.

I don’t know if there was anything in particular that I would describe as me doing “particularly well”.  I successfully created a certificate, ran the checksum, and created the vulnerability report, but these are more or less just a result of following instructions that were provided in previous modules.  Regardless, secure coding is important to protect sensitive information, such as personal and financial information.  For the company, it protects their reputation and draws in more business.  Nobody wants to hand their personal information to someone if it won’t be kept safe.

The dependency check tool is very helpful, as it automatic, saving a lot of time and effort that would have been spent on manual checks.

The main security addition was the self-signed certificate, allowing HTTPS to be used.  I also added a hash function to encode the data.

Unit testing and manually reviewing the code ensure the code is functional.  As for ensuring it’s secure, it is necessary to re-run the dependency check after patching vulnerabilities.  This makes sure no new ones are added and, if they are, what else needs to be patched.

I used the Internet to research algorithms and additional references to what we were taught in previous modules.

I would actually rather not show this assignment to future employers.  It’s something I would prefer to practice more so I could have something better to show.
