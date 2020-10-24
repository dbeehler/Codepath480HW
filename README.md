# Project 8 - Pentesting Live Targets

Time spent: **3** hours spent in total

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

Vulnerability #1: SQL Injection (SQLi)

Description: You are able to manipulate the website URL into the SQL sleep function

<img src="blue-vuln1.gif">

Vulnerability #2: Session Hijacking/Fixation

Description: Log into one browser and use the hacktool to grab the sessionID. You are then able to use a different browser, change the ID, and are instantly logged in

<img src="blue-vuln2.gif">

## Green

Vulnerability #1: Username Enumeration

Description: Known users are bolded, and unknown are not

<img src="green-vuln1.gif">

Vulnerability #2: Cross-Site Scripting (XSS)

Description: You are able to input XSS through the contact form

<img src="green-vuln2.gif">


## Red

Vulnerability #1: Insecure Direct Object Reference (IDOR)

Description: You are allowed to see "hidden" users by changing the ID in the url

<img src="red-vuln1.gif">

Vulnerability #2: Cross-Site Request Forgery (CSRF)

Description: You are allowed to still submit changes even when the CSRF_Token is changed

<img src="red-vuln2.gif">


## Notes

Describe any challenges encountered while doing the work

