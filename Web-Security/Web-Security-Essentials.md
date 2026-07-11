# Lab Notes: TryHackMe - Web Security Essentials

**Date:** July 2026  
**Focus:** Web Infrastructure & Defensive Controls  

## 1. Core Concepts Learned
During this room, I focused on the three primary layers of a web application:
* **The Application Layer:** The front-end code, styling, and basic structures users interact with.
* **The Web Server Layer:** The engine listening for incoming requests and serving data back.
* **The Host Machine Layer:** The underlying operating system (usually Linux) hosting the web server.

## 2. Key Takeaways & Methodology
* **Log Analysis:** I learned about Access Logs. Security analysts use these to track every interaction with a server, identifying anomalous spikes in traffic or repeated unauthorized directory access attempts.
* **WAFs (Web Application Firewalls):** Learned how reverse proxies sit in front of backend infrastructure to block malicious requests before they ever hit the core code.

## 3. Practical Practice
I actively reviewed standard HTTP traffic layouts to separate normal web requests from potential automated brute-force attacks against target web servers.

