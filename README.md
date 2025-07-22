# Hack The Box Reporting using SysReptor
<h1 align="center">
    <a href="https://docs.sysreptor.com/"><img src="/assets/Banner-SysReptor-HTB.svg" width="100%" alt="SysReptor"></a>
</h1>

<p align="center">
<a href="https://github.com/syslifters/sysreptor/">
    <img src="https://img.shields.io/github/stars/Syslifters/sysreptor?color=yellow&style=flat-square">
</a>
<a href="https://github.com/syslifters/sysreptor/releases/latest">
    <img src="https://img.shields.io/github/v/release/syslifters/sysreptor?color=green&style=flat-square">
</a>
<a href="https://github.com/syslifters/sysreptor/releases/latest">
    <img src="https://img.shields.io/github/release-date/syslifters/sysreptor?color=blue&style=flat-square">
</a>
<a href="https://github.com/syslifters/sysreptor/releases/latest">
    <img src="https://img.shields.io/github/repo-size/syslifters/sysreptor?color=red&style=flat-square">
</a>
<a href="https://www.linkedin.com/company/syslifters/">
    <img src="https://img.shields.io/badge/-Linkedin-blue?style=flat-square&logo=linkedin">
</a>
<a href="https://twitter.com/intent/user?screen_name=sysreptor">
    <img src="https://img.shields.io/twitter/follow/sysreptor?style=social">
</a>
</p>

<h4 align="center">Pentest Reporting made easy: Design in HTML, Write in Markdown, Render to PDF. Self-hosted or Cloud.</h4>

---

## Hack The Box Reporting ([officially recommended](https://www.hackthebox.com/blog/certification-templates))
This is our [HTB](https://www.hackthebox.com/) reporting repository showcasing Hack The Box reports created with [SysReptor](https://github.com/Syslifters/sysreptor). Write your Hack The Box CPTS, CBBH, CDSA, CWEE or CAPE reports.  
Feedback is very welcome! ❤️

<h3 align="center">
    <a href="https://htb.sysreptor.com/htb/signup"><img src="/assets/Reptor_Schild_Signup.svg" width="15%" alt="Signup"></a>
</h3>
<h2 align="center">🚀 Sign up <a class="md-button" href="https://htb.sysreptor.com/htb/signup/">here</a> (it's free)</h2>

Already have an account? [Login here.](https://labs.sysre.pt)
<br>

### Prefer self-hosting (also free)?

1. [Install](https://docs.sysreptor.com/setup/installation/) SysReptor 
2. Import all HTB Designs and Reports:

```shell linenums="1"
cd sysreptor/deploy
curl -s "https://docs.sysreptor.com/assets/htb-designs.tar.gz" | docker compose exec --no-TTY app python3 manage.py importdemodata --type=design
curl -s "https://docs.sysreptor.com/assets/htb-demo-projects.tar.gz" | docker compose exec --no-TTY app python3 manage.py importdemodata --type=project
```

<h4>💡 Have a look at our <a class="md-button" href="https://docs.sysreptor.com/">documentation</a>.</h4>
<br>

PS: Are you missing a template, have feedback or any other questions?  
Let us know! Open an issue or [mail us](https://docs.sysreptor.com/contact-us/) and are happy to help you.

Happy Reporting! 🦖  


## Your Benefits
💲 Free  
📝 Write in markdown  
⚙️ Render to PDF  
🛡️ CPTS, CBBH, CDSA, CWEE, CAPE </br>
🚀 Fully customizable  
👌  No local software troubleshooting


## Your Hack The Box Report Within Minutes
![GIF](https://docs.sysreptor.com/images/cpts-reporting.gif)


## Hack The Box Report Template
<p float="left">
<a href="https://docs.sysreptor.com/assets/reports/HTB-CPTS-Report.pdf">
<img width="250" alt="HTB CPTS Report" src="https://docs.sysreptor.com/assets/reports/HTB-CPTS-Report-Preview.png" style="border:1px solid;">
</a>

<a href="https://docs.sysreptor.com/assets/reports/HTB-CBBH-Report.pdf">
<img width="250" alt="HTB CBBH Report" src="https://docs.sysreptor.com/assets/reports/HTB-CBBH-Report-Preview.png" style="border:1px solid;">
</a>

<a href="https://docs.sysreptor.com/assets/reports/HTB-CDSA-Report.pdf">
<img width="250" alt="HTB CDSA Report" src="https://docs.sysreptor.com/assets/reports/HTB-CDSA-Report-Preview.png" style="border:1px solid;">
</a>

<a href="https://docs.sysreptor.com/assets/reports/HTB-CWEE-Report.pdf">
<img width="250" alt="HTB CWEE Report" src="https://docs.sysreptor.com/assets/reports/HTB-CWEE-Report-Preview.png" style="border:1px solid;">
</a>

<a href="https://docs.sysreptor.com/assets/reports/HTB-CAPE-Report.pdf">
<img width="250" alt="HTB CAPE Report" src="https://docs.sysreptor.com/assets/reports/HTB-CAPE-Report-Preview.png" style="border:1px solid;">
</a>

<a href="https://docs.sysreptor.com/assets/reports/HTB-CJCA-Report.pdf">
<img width="250" alt="HTB CJCA Report" src="https://docs.sysreptor.com/assets/reports/HTB-CJCA-Report-Preview.png" style="border:1px solid;">
</a>
</p>

## Hack The Box Abbreviations

Exam acronym | Exam name                                         | Course details
-------------|---------------------------------------------------|-------------------
**CPTS**     | Certified Penetration Testing Specialist          | HTB Certified Penetration Testing Specialist (HTB CPTS) is a highly hands-on certification that assesses the candidates’ penetration testing skills. HTB Certified Penetration Testing Specialist certification holders will possess technical competency in the ethical hacking and penetration testing domains at an intermediate level. They will be able to spot security issues and identify avenues of exploitation that may not be immediately apparent from searching for CVEs or known exploit PoCs. They can also think outside the box, chain multiple vulnerabilities to showcase maximum impact, and actionably help organizations remediate vulnerabilities through commercial-grade pentesting reports.
**CBBH**     | Certified Bug Bounty Hunter                       | HTB Certified Bug Bounty Hunter (HTB CBBH) is a highly hands-on certification that assesses the candidates’ bug bounty hunting and web application pentesting skills. HTB Certified Bug Bounty Hunter certification holders will possess technical competency in the bug bounty hunting and web application penetration testing domains at an intermediate level. They will be able to spot security issues and identify avenues of exploitation that may not be immediately apparent from searching for CVEs or known exploit PoCs. They can also think outside the box, chain multiple vulnerabilities to showcase maximum impact, and actionably help developers remediate vulnerabilities through commercial-grade bug reports.
**CDSA**     | Certified Defensive Security Analyst              | HTB Certified Defensive Security Analyst (HTB CDSA) is a highly hands-on certification that assesses the candidates’ security analysis, SOC operations, and incident handling skills. HTB Certified Defensive Security Analyst (HTB CDSA) certification holders will possess technical competency in the security analysis, SOC operations, and incident handling domains at an intermediate level. They will be able to spot security incidents and identify avenues of detection that may not be immediately apparent from simply looking at the available data/evidence. They will also excel at thinking outside the box, correlating disparate pieces of data/evidence, and pivoting relentlessly to determine the maximum impact of an incident. Another skill they will bring is the creation of actionable security incident reports tailored for diverse audiences.
**CWEE**     | Certified Web Exploitation Expert              | HTB Certified Web Exploitation Expert (HTB CWEE) is a highly hands-on certification that assesses candidates' skills in identifying advanced and hard-to-find web vulnerabilities using both black box and white box techniques. HTB CWEE certification holders will possess technical competency in the web security, web penetration testing, and secure coding domains at an advanced level and be well-versed in the application debugging, source code review, and custom exploit development aspects of web security testing. They will also be able to professionally conduct web penetration tests against modern and highly secure web applications, as well as report vulnerabilities found in code or arising from logical errors.
**CAPE**     | Certified Active Directory Pentesting Expert              | HTB Certified Active Directory Pentesting Expert (HTB CAPE) is a highly hands-on certification assessing candidates' skills in identifying and exploiting advanced Active Directory (AD) vulnerabilities. HTB CAPE certification holders will possess technical competency in AD and Windows penetration testing, understanding complex attack paths, and employing advanced techniques to exploit them. HTB CAPE certification holders will demonstrate proficiency in executing sophisticated attacks abusing different authentication protocols such as Kerberos and NTLM and abusing misconfigurations within AD components and standard applications in AD environments such as Active Directory Certificate Services (ADCS), Windows Update Server Services (WSUS), Exchange, and Domain Trusts. Furthermore, they will be adept at leveraging specialized tools to exploit AD from Linux and Windows and utilizing Command and Control (C2) frameworks for post-exploitation operations. They will also be able to conduct internal penetration tests professionally against modern AD environments.
**CJCA**     | Certified Junior Cybersecurity Associate              | HTB Certified Junior Cybersecurity Associate (HTB CJCA) is a highly hands-on certification that assesses the candidates’ cybersecurity assessment skills. HTB Certified Junior Cybersecurity Associate holders demonstrate foundational technical competency across both offensive and defensive cybersecurity domains. They are equipped to identify common vulnerabilities, perform basic (post-)exploitation, and recognize potential security gaps. They are also capable of conducting SIEM-assisted security monitoring, analyzing network traffic and logs, and detecting intrusions. With hands-on experience in these areas and a hybrid skill set, they can assess and report on security issues in enterprise environments.

<h1 align="center">
    <a href="https://docs.sysreptor.com/"><img src="/assets/Tower_SysReptor.svg" width="100%" alt="SysReptor"></a>
</h1>
