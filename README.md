<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:020617,20:0F172A,40:111827,60:1E293B,80:064E3B,100:9FEF00&height=250&section=header&text=HTB%20WRITEUPS&fontSize=52&fontColor=9FEF00&animation=fadeIn&fontAlignY=36&desc=Retired%20Hack%20The%20Box%20Machines%20•%20Enumeration%20•%20Exploitation%20•%20Privilege%20Escalation&descAlignY=60&descSize=17"/>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=24&duration=2200&pause=700&color=9FEF00&center=true&vCenter=true&width=920&lines=%24+whoami+%E2%86%92+offensive-security-student;%24+focus+%E2%86%92+enumeration+%7C+exploitation+%7C+privilege-escalation;%24+repository+%E2%86%92+retired+HTB+writeups;%24+status+%E2%86%92+actively-maintained" alt="Typing SVG"/>

<br>

<img src="https://img.shields.io/badge/Hack%20The%20Box-9FEF00?style=for-the-badge&logo=hackthebox&logoColor=black"/>
<img src="https://img.shields.io/badge/Retired-Machines-111827?style=for-the-badge&logo=readthedocs&logoColor=9FEF00"/>
<img src="https://img.shields.io/badge/Red%20Team-Training-EF4444?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Status-ONLINE-00FF41?style=for-the-badge"/>

</div>

---

<table><tr><td width="58%" valign="top"><h3>🖥️ Operator Console</h3><pre><code>┌──(htb㉿operator)-[~/writeups]
└─$ ./status.sh

[+] Retired machines documented
[+] Enumeration findings verified
[+] Exploitation chains reproduced in lab
[+] Privilege escalation paths analyzed
[+] Evidence sanitized for public release
[+] GitHub rendering optimized

SYSTEM STATUS : OPERATIONAL </code></pre></td><td width="42%" valign="top"><h3>📡 Live Dashboard</h3><table><tr><td align="center"><img src="https://img.shields.io/badge/EASY-2-22C55E?style=for-the-badge"/></td></tr><tr><td align="center"><img src="https://img.shields.io/badge/MEDIUM-4-EAB308?style=for-the-badge"/></td></tr><tr><td align="center"><img src="https://img.shields.io/badge/HARD-0-EF4444?style=for-the-badge"/></td></tr><tr><td align="center"><img src="https://img.shields.io/badge/TOTAL-6-111827?style=for-the-badge"/></td></tr></table></td></tr></table>

---

<div align="center">

## 📚 MACHINE INDEX

<table><tr><th>Machine</th><th>OS</th><th>Difficulty</th><th>Status</th><th>Write-up</th></tr><tr><td><strong>2Million</strong></td><td><img src="https://cdn.simpleicons.org/linux/9FEF00" width="16"/> Linux</td><td><img src="https://img.shields.io/badge/EASY-22C55E?style=flat-square"/></td><td><img src="https://img.shields.io/badge/COMPLETE-16A34A?style=flat-square"/></td><td><a href="2Million/"><strong>OPEN</strong></a></td></tr><tr><td><strong>Bedside</strong></td><td><img src="https://cdn.simpleicons.org/linux/9FEF00" width="16"/> Linux</td><td><img src="https://img.shields.io/badge/EASY-22C55E?style=flat-square"/></td><td><img src="https://img.shields.io/badge/COMPLETE-16A34A?style=flat-square"/></td><td><a href="Bedside_HTB/"><strong>OPEN</strong></a></td></tr><tr><td><strong>Connected</strong></td><td><img src="https://cdn.simpleicons.org/linux/9FEF00" width="16"/> Linux</td><td><img src="https://img.shields.io/badge/MEDIUM-EAB308?style=flat-square"/></td><td><img src="https://img.shields.io/badge/COMPLETE-16A34A?style=flat-square"/></td><td><a href="Connected/"><strong>OPEN</strong></a></td></tr><tr><td><strong>DevHub</strong></td><td><img src="https://cdn.simpleicons.org/linux/9FEF00" width="16"/> Linux</td><td><img src="https://img.shields.io/badge/MEDIUM-EAB308?style=flat-square"/></td><td><img src="https://img.shields.io/badge/COMPLETE-16A34A?style=flat-square"/></td><td><a href="DevHub/"><strong>OPEN</strong></a></td></tr><tr><td><strong>Enigma</strong></td><td><img src="https://cdn.simpleicons.org/linux/9FEF00" width="16"/> Linux</td><td><img src="https://img.shields.io/badge/MEDIUM-EAB308?style=flat-square"/></td><td><img src="https://img.shields.io/badge/COMPLETE-16A34A?style=flat-square"/></td><td><a href="Enigma_HTB/"><strong>OPEN</strong></a></td></tr><tr><td><strong>PaperWork</strong></td><td><img src="https://cdn.simpleicons.org/linux/9FEF00" width="16"/> Linux</td><td><img src="https://img.shields.io/badge/MEDIUM-EAB308?style=flat-square"/></td><td><img src="https://img.shields.io/badge/COMPLETE-16A34A?style=flat-square"/></td><td><a href="PaperWork/"><strong>OPEN</strong></a></td></tr></table>

</div>

---

<div align="center">

## ⚔️ HTB WORKFLOW

<table><tr><td align="center" width="180"><img src="https://img.shields.io/badge/01-RECON-2563EB?style=for-the-badge"/><br><br><img src="https://cdn.simpleicons.org/nmap/2563EB" width="34"/><br><br><strong>Port Discovery</strong><br><sub>Nmap • Masscan • Service Fingerprinting</sub></td><td align="center" width="34"><h2>➜</h2></td><td align="center" width="180"><img src="https://img.shields.io/badge/02-ENUM-7C3AED?style=for-the-badge"/><br><br><img src="https://cdn.simpleicons.org/wireshark/7C3AED" width="34"/><br><br><strong>Surface Mapping</strong><br><sub>Users • SMB • Web • LDAP • RPC</sub></td><td align="center" width="34"><h2>➜</h2></td><td align="center" width="180"><img src="https://img.shields.io/badge/03-EXPLOIT-DC2626?style=for-the-badge"/><br><br><img src="https://cdn.simpleicons.org/metasploit/DC2626" width="34"/><br><br><strong>Initial Access</strong><br><sub>RCE • Credentials • Foothold</sub></td><td align="center" width="34"><h2>➜</h2></td><td align="center" width="180"><img src="https://img.shields.io/badge/04-PRIVESC-059669?style=for-the-badge"/><br><br><img src="https://cdn.simpleicons.org/linux/059669" width="34"/><br><br><strong>Root / SYSTEM</strong><br><sub>Sudo • Kernel • Misconfigurations</sub></td><td align="center" width="34"><h2>➜</h2></td><td align="center" width="180"><img src="https://img.shields.io/badge/05-REPORT-111827?style=for-the-badge"/><br><br><img src="https://cdn.simpleicons.org/readthedocs/9FEF00" width="34"/><br><br><strong>Evidence Archive</strong><br><sub>Screenshots • Proof • Reproduction</sub></td></tr></table>

</div>

---

<div align="center">

## 📂 LAB TOPOLOGY

</div>

<pre><code>.
├── 2Million/
│   ├── README.md
│   ├── screenshots/
│   └── notes.md
├── Bedside_HTB/
├── Connected/
├── DevHub/
├── Enigma_HTB/
├── PaperWork/
├── Challenges/
└── POC_Official/
</code></pre>

---

<div align="center">

## 🏆 DIFFICULTY DISTRIBUTION

<img src="https://quickchart.io/chart?c={type:'doughnut',data:{labels:['Easy','Medium','Hard'],datasets:[{data:[2,4,0],backgroundColor:['#22C55E','#EAB308','#EF4444'],borderColor:'#0D1117',borderWidth:4}]},options:{plugins:{legend:{labels:{color:'white'}}},cutout:'68%'}}" width="320"/>

</div>

---

## ⚠️ Public Release Notice

This repository contains **writeups for retired Hack The Box machines** and is maintained as part of my **offensive security and red team training**.

**Included**

* Reconnaissance methodology
* Enumeration findings
* Exploitation analysis
* Privilege escalation paths
* Evidence-based documentation

**Excluded**

* Active machine solutions
* VPN files
* Credentials
* Private keys
* Challenge flags
* Unreleased HTB content

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:111827,50:0F172A,100:065F46&height=4&section=footer"/>

<pre><code>[ recon ] → [ enumerate ] → [ exploit ] → [ privilege escalate ] → [ document ]</code></pre>

**⚡ One box at a time • Evidence over assumptions • Repeatable methodology**

<br>

<img src="https://komarev.com/ghpvc/?username=YOUR_USERNAME&color=9FEF00&style=for-the-badge"/>

<sub><code>root@github:~# exit</code></sub>

</div>
