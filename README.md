<div align="center">

```
 █████╗ ██████╗ ██████╗ ██╗   ██╗██╗     ██╗      █████╗ ██╗  ██╗
██╔══██╗██╔══██╗██╔══██╗██║   ██║██║     ██║     ██╔══██╗██║  ██║
███████║██████╔╝██║  ██║██║   ██║██║     ██║     ███████║███████║
██╔══██║██╔══██╗██║  ██║██║   ██║██║     ██║     ██╔══██║██╔══██║
██║  ██║██████╔╝██████╔╝╚██████╔╝███████╗███████╗██║  ██║██║  ██║
╚═╝  ╚═╝╚═════╝ ╚═════╝  ╚═════╝ ╚══════╝╚══════╝╚═╝  ╚═╝╚═╝  ╚═╝
```

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=22&duration=2400&pause=800&color=00FF41&center=true&vCenter=true&width=820&lines=%5B*%5D+intrusion+detected+...;%5B*%5D+decrypting+identity+...+01000001;%5B%2B%5D+ACCESS+GRANTED+%E2%80%94+welcome%2C+intruder.;%3E+Penetration+Tester+%2F%2F+Security+Engineer+%2F%2F+Dev" alt="breach sequence" />

</div>

<br/>

```c
┌──(abdullah㉿kali)-[~]
└─$ whoami && id
──────────────────────────────────────────────────────────────
  user      : Abdullah Nasir
  role      : Penetration Tester · Security Engineer
  groups    : offsec, red-team, full-stack, erp-next
  education : BS Software Engineering @ Bahria University
  uid=1337(abdullah)  ➜  I break systems so attackers can't.
──────────────────────────────────────────────────────────────
```

<br/>

## ⚑ &nbsp; `CAPTURE_THE_FLAG.chal`

```diff
- [!] You breached the perimeter. But can you read what's inside?
+ [*] Decode the payload below. Two layers guard the flag.
```

```bash
┌──(intruder㉿abdullah)-[/root/.secret]
└─$ cat flag.enc

  NjY2YzYxNjc3Yjc5MzA3NTVmNjI3MjMzMzQ2MzY4MzM2NDVmNzQ2ODMz
  NWY3MDMzNzIzMTZkMzM3NDMzNzI1ZjZjMzM3NDczNWY2MzMwNmU2ZTMz
  NjM3NDdk

  [?] layer 1 » the classic way to move bytes as safe text  (____64)
  [?] layer 2 » speaks only in pairs of 0-9 and a-f         (h_x)
  [$] reward  » DM me the plaintext on LinkedIn or X.
                first 3 to crack it get a shoutout. 🏴
```

<br/>

```c
┌──(abdullah㉿kali)-[~]
└─$ nmap -sV -A -p- abdullah.local
```

```yaml
Starting Nmap — Service & Skill Detection ...

PORT       STATE   SERVICE           VERSION
──────────────────────────────────────────────────────────────
443/tcp    open    web-pentesting    Web App Assessment · OWASP Top 10
80/tcp     open    api-security      Broken Auth · IDOR · Injection
8080/tcp   open    exploitation      PoC Dev · Responsible Disclosure
53/tcp     open    network-sec       Infra Hardening · Recon · Scanning
22/tcp     open    secure-dev        RBAC · Auth Flows · Secure Coding
3000/tcp   open    full-stack        React · Next.js · Node · MongoDB
9000/tcp   open    erp-systems       ERPNext · Deployment · Migration

Service detection: 7/7 ports open — 0 filtered. Scan complete.
```

<br/>

```c
┌──(abdullah㉿kali)-[~]
└─$ ls -la /opt/arsenal
```

<p align="center">
<img src="https://img.shields.io/badge/Burp_Suite-FF6633?style=for-the-badge&logo=burpsuite&logoColor=white" />
<img src="https://img.shields.io/badge/Metasploit-2596CD?style=for-the-badge&logo=metasploit&logoColor=white" />
<img src="https://img.shields.io/badge/Nmap-4682B4?style=for-the-badge&logoColor=white" />
<img src="https://img.shields.io/badge/Wireshark-1679A7?style=for-the-badge&logo=wireshark&logoColor=white" />
<img src="https://img.shields.io/badge/OWASP_ZAP-000000?style=for-the-badge&logo=owasp&logoColor=white" />
<br/>
<img src="https://skillicons.dev/icons?i=kali,linux,bash,react,nextjs,ts,nodejs,express,mongodb,git,github,postman&theme=dark" />
<br/>
<img src="https://img.shields.io/badge/ERPNext-0089FF?style=for-the-badge&logo=frappe&logoColor=white" />
</p>

<br/>

```c
┌──(abdullah㉿kali)-[~]
└─$ git log --oneline ~/projects
```

| Project | Stack | What it does |
| :--- | :--- | :--- |
| 🍽️ **Dastarkhan AI** | React · Node · MongoDB · AI | End-to-end AI-powered food delivery platform with recommendations & vendor dashboards |
| 📚 **LMS Tracker** | React · Chrome Extension · Node | Auto-syncs Bahria University LMS assignments so students never miss a deadline |
| 🎫 **EVENZA** | MERN · MVC + Repository | Multi-role event management platform with payment tracking |
| 🎓 **FYP Management System** | MERN · RBAC | 4-role project lifecycle platform with secure workflow & audit trail |

<br/>

```c
┌──(abdullah㉿kali)-[~]
└─$ ./snake --eat ~/.contributions
```

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/itsmalikabdullahnasir/itsmalikabdullahnasir/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/itsmalikabdullahnasir/itsmalikabdullahnasir/output/github-contribution-grid-snake.svg" />
  <img alt="snake eating the contribution graph" src="https://raw.githubusercontent.com/itsmalikabdullahnasir/itsmalikabdullahnasir/output/github-contribution-grid-snake.svg" />
</picture>

</div>

<br/>

```c
┌──(abdullah㉿kali)-[~]
└─$ ps aux | grep github
```

<div align="center">

<img src="https://img.shields.io/github/followers/itsmalikabdullahnasir?style=for-the-badge&logo=github&color=00FF41&labelColor=0d1117&logoColor=00FF41" />
<img src="https://komarev.com/ghpvc/?username=itsmalikabdullahnasir&label=PROFILE+VIEWS&color=00FF41&style=for-the-badge" />

<br/><br/>

<img height="155" src="https://github-readme-stats.vercel.app/api?username=itsmalikabdullahnasir&theme=dark&hide_border=true&include_all_commits=true&count_private=false&show_icons=true&title_color=00FF41&icon_color=00FF41&text_color=c9d1d9&bg_color=0d1117" />
<img height="155" src="https://github-readme-stats.vercel.app/api/top-langs/?username=itsmalikabdullahnasir&theme=dark&hide_border=true&include_all_commits=true&count_private=false&layout=compact&title_color=00FF41&text_color=c9d1d9&bg_color=0d1117" />

</div>

<br/>

```c
┌──(abdullah㉿kali)-[~]
└─$ cat ~/.certs | sort -r
```

- 🎯 **Foundations of Cybersecurity** — Google / Coursera · `95%`
- 🛠️ **Technical Support Fundamentals** — Google / Coursera · `99.2%`
- 📋 **Foundations of Project Management** — Google / Coursera · `95.9%`
- 🤖 **Google AI Essentials** — Google / Coursera
- ☁️ **Microsoft Learn** — 5 verified badges (Azure · Cloud & Developer Fundamentals)

<br/>

```c
┌──(abdullah㉿kali)-[~]
└─$ nc -lvnp 1337   # listening for your connection...
```

<p align="center">
<a href="https://linkedin.com/in/itsmalikabdullahnasir"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="https://g.dev/itsmalikabdullahnasir"><img src="https://img.shields.io/badge/Portfolio-00FF41?style=for-the-badge&logo=googlechrome&logoColor=black" /></a>
<a href="https://x.com/Abdullah_Nasir5"><img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white" /></a>
<a href="https://stackoverflow.com/users/23621453"><img src="https://img.shields.io/badge/Stack_Overflow-F58025?style=for-the-badge&logo=stackoverflow&logoColor=white" /></a>
<a href="mailto:malikabdullahnasir5@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" /></a>
</p>

<br/>

<div align="center">

<sub><code>root@abdullah:~# echo "find the flaw · prove the impact · report it · patch it" 🛡️</code></sub>

</div>
