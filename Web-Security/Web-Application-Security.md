# Lab Notes: TryHackMe - Web Application Security

**Date:** July 2026  
**Focus:** Web Infrastructure and Access Vulnerabilities  

## 1. Core Concepts Learned
* **Web App Architecture**  
* **Vulnerability Type:** Insecure Direct Objects Reference-IDOR

**The login problem:** Sometimes soem websites don't limit the number of times you can login. A hacker can try thousands of passwords in a second until they hit the right one.

**HTTP:** If i type my password to login, anyone investigating the network can view it. HTTP is naked!

## 2. What I did:
* By changing one number on the URL(ID number) I was able to access sensitive personal data of other users without any authentication. THis is called IDOR which is a web vulnerability whic gives me access to details without checking who I am.
