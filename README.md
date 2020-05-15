# codepath_homework
# Project 8 - Pentesting Live Targets

Time spent: 3 hours spent in total

> Objective: Identify vulnerabilities in three different versions of the Globitek website: blue, green, and red.

The six possible exploits are:

* Username Enumeration
* Insecure Direct Object Reference (IDOR)
* SQL Injection (SQLi)
* Cross-Site Scripting (XSS)
* Cross-Site Request Forgery (CSRF)
* Session Hijacking/Fixation

Each color is vulnerable to only 2 of the 6 possible exploits. First discover which color has the specific vulnerability, then write a short description of how to exploit it, and finally demonstrate it using screenshots compiled into a GIF.

## Blue

Vulnerability #1: __________________

Description:

<img src="blue-vuln1.gif">

Vulnerability #2: __________________

Description:

<img src="blue-vuln2.gif">

## Green

Vulnerability #1: Username Enumeration 

Description:used the username and password "user" and foud that the green site looked different from the other two.
The error message was not in bold indicating that there is an issue with this particular site that is not in the other two.

<img src="green-vuln1.gif">


Vulnerability #2: performed an XSS attack by inserting <script>('XSS attack');</script>

Description:Using the feedback page I inserted the script <script>('XSS attack');</script> into both the your name and feeback boxes. After loging into an employee account through pperson and clicking on feedback, you can see multiple requests are sent using the one feedback form

<img src="green-vuln2.gif">
<img src="https://gph.is/g/Z2nR7RW" width="800">
## Red

Vulnerability #1: __________________

Description:

<img src="red-vuln1.gif">

Vulnerability #2: __________________

Description:

<img src="red-vuln2.gif">


## Notes

Describe any challenges encountered while doing the work
I spent a lot of time playing with the site and not getig anywhere.
