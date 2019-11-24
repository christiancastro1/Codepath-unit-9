# Project 8 - Pentesting Live Targets

Time spent: **X** hours spent in total

> Objective: Identify vulnerabilities in three different versions of the Globitek website: blue, green, and red.

The six possible exploits are:
* Username Enumeration
* Insecure Direct Object Reference (IDOR)
* SQL Injection (SQLi)
* Cross-Site Scripting (XSS)
* Cross-Site Request Forgery (CSRF)
* Session Hijacking/Fixation

Each version of the site has been given two of the six vulnerabilities. (In other words, all six of the exploits should be assignable to one of the sites.)

## Blue

Vulnerability #1: SQL Injection
<img src="http://g.recordit.co/yIUxwHGOUq.gif" width="800">

Vulnerability #2: Session Hijacking/Fixation

<img src="http://g.recordit.co/k2nUicQltX.gif" width="800">


The browser on the left is safari(attacker), as you can see he is not logged in. On the right is the target who will sign in. We will get the session id of user thats signed in and copy it. Then the attacker will change his session id which will allow him to sign in.
## Green

Vulnerability #1: XSS
<img src="http://g.recordit.co/kMTGBM3Ro6.gif" width="800">

Vulnerability #2: User enumeration
<img src="http://g.recordit.co/kzHqU6Dw6e.gif" width="800">

If both password and username are wrong "Login unsuccessful" appears in regular text but, if user name is correct but password wrong "Login Unsuccessful" appears in bold letting the attacker know that his close.


## Red

Vulnerability #1: CSRF
<img src="http://g.recordit.co/KFsvNVifIQ.gif" width="800">

Vulnerability #2: IDOR
<img src="http://g.recordit.co/NdIDJsZO5m.gif" width="800">


## Notes
Eveything was explained very well, no problems at all
