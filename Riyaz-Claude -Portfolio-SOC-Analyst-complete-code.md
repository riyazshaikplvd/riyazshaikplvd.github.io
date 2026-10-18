# 🛡️ RIYAZ.CYBER WORLD

Animated single-file portfolio of **Riyaz Shaik** (aspiring SOC L1 / Cybersecurity Analyst).
Pure HTML + CSS + JavaScript, no frameworks, no build step. Open `index.html` in a browser or deploy it as-is (Vercel / GitHub Pages).

## Files
| File | Purpose |
|---|---|
| `index.html` | The complete portfolio (all images embedded) |
| `RIYAZ-SOC-L1.pdf` | Resume (also embedded in `index.html`) |
| `README.md` | This file |

## Sections
01 Professional Summary · 01.5 Live Profiles · 02 Core Skills · 03 Featured Projects · 03.5 Investigations · 04 Experience & Internships · 05 Education · 06 Certifications & Badges · 07 Connect

## Features
- Download CV buttons (top bar, hero, contact) use the resume embedded in `index.html`; `RIYAZ-SOC-L1.pdf` is kept beside it as a backup
- Welcome loader (laptop title, shield drawing, about 3.5 s)
- Animated `#techbg` background with 62 SOC and Blue-Team tool badges (floating, 5 s pulse, network lines)
- Investigations gallery: 19 evidence screenshots, equal-size cards, click to zoom
- Certifications grid with click-to-zoom certificate viewer
- Responsive layout, light/dark theme, reduced-motion support

## Investigations: evidence list
1. Splunk search, stats count by EventCode
2. Splunk dashboard, Log Sources Monitoring
3. Microsoft Sentinel, Data connectors
4. Azure Log Analytics, AuditLogs query
5. Wazuh dashboard, High and Critical alerts
6. Kali Linux, Nikto web server scan
7. Parrot OS, SSH service and remote login
8. Windows Event Viewer, Sysmon Operational log
9. VirusTotal, IP reputation check
10. Sysmon Event ID 1, Process Create
11. Linux SSH login log, failed attempts
12. DVWA, SQL Injection
13. DVWA, Command Injection
14. Ethical malware lab, Electron app deleting screenshots
15. Malware development notes, Electron app with VS Code, Node.js and Git setup
16. Malware training app in VS Code (Electron)
17. Firebase Realtime Database, commands and screenshots nodes
18. Automated SOC threat intelligence pipeline (n8n + Splunk + VirusTotal)
19. Deep Fake Source Identifier, project report cover

## Certifications (latest addition)
- Programming Hackathon 2022, Grand Finale: SVCET (Autonomous) with Computer Society of India, 20 Oct 2022 (placed after Python Full Stack Development)

## Editing tips
- Evidence images live in the `IM` object (keys `ev1` to `ev19`); captions are in the `EVC` array, in the same order.
- Certificates are in the `CRT` array; each entry is `[title, issuer, date, status, link, imageKey]`.
- Tool badges are inside `<div id="techbg">`.
