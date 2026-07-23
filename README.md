<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:000000,50:0A0A0A,100:9FEF00&height=240&section=header&text=HTB%20OPERATOR%20ARCHIVE&fontSize=46&fontColor=9FEF00&animation=fadeIn&fontAlignY=38&desc=Retired%20Hack%20The%20Box%20Writeups%20•%20Red%20Team%20Lab&descAlignY=58&descAlign=50"/>

<br>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=26&duration=2500&pause=1000&color=9FEF00&center=true&vCenter=true&width=1000&lines=%24+sudo+su+operator;%24+focus+%3D+enumeration+%7C+exploitation+%7C+privesc;%24+repository+%3D+retired+HTB+machines;%24+status+%3D+online+%26+actively+maintained"/>

<br><br>

<img src="https://img.shields.io/badge/Hack%20The%20Box-9FEF00?style=for-the-badge&logo=hackthebox&logoColor=black"/>
<img src="https://img.shields.io/badge/Red%20Team-FF003C?style=for-the-badge&logo=protonvpn&logoColor=white"/>
<img src="https://img.shields.io/badge/Offensive%20Security-00BFFF?style=for-the-badge&logo=kalilinux&logoColor=white"/>
<img src="https://img.shields.io/badge/Writeups-18-111827?style=for-the-badge&logo=readthedocs&logoColor=white"/>

</div>

---

## 🖥️ OPERATOR CONSOLE

<pre><code>┌──(operator㉿lab)-[~/htb/writeups]
└─$ mission-status

[✓] Enumeration methodology documented
[✓] Footholds reproduced in lab
[✓] Privilege escalation chains analyzed
[✓] Evidence sanitized for publication
[✓] Retired-machine compliance verified

SYSTEM STATUS : OPERATIONAL
VPN STATE     : CONNECTED
THREAT LEVEL  : LOW
</code></pre>

---

<div align="center">

# 📡 MISSION DASHBOARD

<img src="https://github-readme-activity-graph.vercel.app/graph?username=YOUR_USERNAME&theme=github-dark&bg_color=0D1117&color=9FEF00&line=00FF41&point=FFFFFF&hide_border=true" width="100%"/>

</div>

<br>

<div align="center">

| 🎯 Total | 🟢 Easy | 🟡 Medium | 🔴 Hard | ⚫ Insane |
| :------: | :-----: | :-------: | :-----: | :------: |
|  **18**  |  **7**  |   **9**   |  **2**  |   **0**  |

</div>

---

# 🎯 TARGET MATRIX

<div align="center">

| Machine       | OS                                                                         | Difficulty | Status                                                                      | Report                                                                                                                            |
| ------------- | -------------------------------------------------------------------------- | ---------- | --------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------- |
| **2Million**  | <img src="https://cdn.simpleicons.org/linux/9FEF00" width="16"/> Linux     | 🟢 Easy    | <img src="https://img.shields.io/badge/COMPLETE-00FF41?style=flat-square"/> | <a href="2Million/"><img src="https://img.shields.io/badge/OPEN-111827?style=flat-square&logo=readthedocs&logoColor=white"/></a>  |
| **DevHub**    | <img src="https://cdn.simpleicons.org/linux/9FEF00" width="16"/> Linux     | 🟡 Medium  | <img src="https://img.shields.io/badge/COMPLETE-00FF41?style=flat-square"/> | <a href="DevHub/"><img src="https://img.shields.io/badge/OPEN-111827?style=flat-square&logo=readthedocs&logoColor=white"/></a>    |
| **Enigma**    | <img src="https://cdn.simpleicons.org/linux/9FEF00" width="16"/> Linux     | 🟡 Medium  | <img src="https://img.shields.io/badge/COMPLETE-00FF41?style=flat-square"/> | <a href="Enigma/"><img src="https://img.shields.io/badge/OPEN-111827?style=flat-square&logo=readthedocs&logoColor=white"/></a>    |
| **PaperWork** | <img src="https://cdn.simpleicons.org/linux/9FEF00" width="16"/> Linux     | 🟡 Medium  | <img src="https://img.shields.io/badge/COMPLETE-00FF41?style=flat-square"/> | <a href="PaperWork/"><img src="https://img.shields.io/badge/OPEN-111827?style=flat-square&logo=readthedocs&logoColor=white"/></a> |
| **Connected** | <img src="https://cdn.simpleicons.org/windows/00BFFF" width="16"/> Windows | 🟡 Medium  | <img src="https://img.shields.io/badge/COMPLETE-00FF41?style=flat-square"/> | <a href="Connected/"><img src="https://img.shields.io/badge/OPEN-111827?style=flat-square&logo=readthedocs&logoColor=white"/></a> |
| **Bedside**   | <img src="https://cdn.simpleicons.org/linux/9FEF00" width="16"/> Linux     | 🟢 Easy    | <img src="https://img.shields.io/badge/COMPLETE-00FF41?style=flat-square"/> | <a href="Bedside/"><img src="https://img.shields.io/badge/OPEN-111827?style=flat-square&logo=readthedocs&logoColor=white"/></a>   |

</div>

---

# ⚔️ ATTACK CHAIN

<div align="center">

<table>
<tr>
<td align="center" width="180">

### 🔍 RECON

<img src="https://img.shields.io/badge/PORTS-2563EB?style=for-the-badge"/>

Nmap • Masscan • Fingerprinting

</td>
<td align="center" width="40"><h1>➜</h1></td>
<td align="center" width="180">

### 🧩 ENUMERATION

<img src="https://img.shields.io/badge/SURFACE-7C3AED?style=for-the-badge"/>

Users • Shares • Web • SMB

</td>
<td align="center" width="40"><h1>➜</h1></td>
<td align="center" width="180">

### 💥 EXPLOIT

<img src="https://img.shields.io/badge/FOOTHOLD-DC2626?style=for-the-badge"/>

RCE • Credentials • Sessions

</td>
<td align="center" width="40"><h1>➜</h1></td>
<td align="center" width="180">

### 👑 PRIVESC

<img src="https://img.shields.io/badge/ROOT-059669?style=for-the-badge"/>

Sudo • Kernel • AD Abuse

</td>
<td align="center" width="40"><h1>➜</h1></td>
<td align="center" width="180">

### 📝 REPORT

<img src="https://img.shields.io/badge/EVIDENCE-111827?style=for-the-badge"/>

Proof • Timeline • Reproduction

</td>
</tr>
</table>

</div>

---

# 🧠 LAB PRINCIPLES

<div align="center">

<table>
<tr>
<td align="center" width="300">

<img src="https://cdn.simpleicons.org/wireshark/9FEF00" width="42"/><br><br>

### Evidence First

Every claim is backed by observable output, packets, logs, screenshots, or reproducible commands.

</td>
<td align="center" width="300">

<img src="https://cdn.simpleicons.org/gnubash/9FEF00" width="42"/><br><br>

### Mechanism Over Tricks

Focus on authentication, execution flow, permissions, networking, and operating system behavior.

</td>
<td align="center" width="300">

<img src="https://cdn.simpleicons.org/git/9FEF00" width="42"/><br><br>

### Repeatable Process

Recon → Enumerate → Hypothesize → Test → Escalate → Document.

</td>
</tr>
</table>

</div>

---

# ⚠️ PUBLIC RELEASE NOTICE

> This repository contains **writeups for retired Hack The Box machines only** and is maintained as part of my **offensive security and red team training lab**.
>
> **No active machine solutions, VPN files, credentials, private keys, or challenge flags are included.**
>
> Content is shared strictly for **educational, defensive security research, and methodology documentation** purposes.

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:9FEF00,50:052E16,100:000000&height=140&section=footer"/>

<h3>⚡ EVIDENCE OVER ASSUMPTIONS</h3>

<pre><code>[ RECON ] → [ ENUMERATE ] → [ EXPLOIT ] → [ PRIVESC ] → [ DOCUMENT ]</code></pre>

<strong>One box • One methodology • Infinite lessons</strong>

<br><br>

<img src="https://komarev.com/ghpvc/?username=YOUR_USERNAME&color=9FEF00&style=for-the-badge"/>

</div>
