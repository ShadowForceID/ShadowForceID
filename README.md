<div align="center">

<img src="https://github.com/ShadowForceID.png" width="120" style="border-radius:50%" alt="ShadowForceID"/>

# ShadowForceID

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=18&pause=1000&color=36E29A&center=true&vCenter=true&width=600&lines=Security+Researcher+%F0%9F%94%90;Building+defensive+tools+from+Indonesia+%F0%9F%87%AE%F0%9F%87%A9;OSINT+%C2%B7+WhatsApp+Ops+%C2%B7+Web+Security" alt="Typing SVG" />

<br/>

![Profile Views](https://visitor-badge.laobi.icu/badge?page_id=ShadowForceID.ShadowForceID&left_color=0c1116&right_color=36e29a)
&nbsp;
[![Followers](https://img.shields.io/github/followers/ShadowForceID?style=flat-square&color=9b8cff&label=FOLLOWERS)](https://github.com/ShadowForceID?tab=followers)
&nbsp;
[![Stars](https://img.shields.io/github/stars/ShadowForceID?style=flat-square&color=e8b14a&affiliations=OWNER&label=TOTAL+STARS)](https://github.com/ShadowForceID)

</div>

---

## 👤 About

```yaml
handle   : ShadowForceID
org      : ShadowForce
location : Indonesia 🇮🇩
focus    : Defensive Security · OSINT · WhatsApp Ops · Web Recon
approach : Blue Team · Ethical · Authorized Use Only
```

Membangun alat keamanan yang berguna, etis, dan *actionable* — untuk pemilik aset yang ingin memahami eksposur mereka sendiri, bukan untuk menyerang siapapun.

---

## 🛠️ Projects

---

### 🔵 [SHADOWGRID](https://github.com/ShadowForceID/shadowgrid) — Platform Keamanan Digital

> *Kenali domain sebelum orang lain.*

**SHADOWGRID** adalah platform keamanan digital yang mengintegrasikan **domain reconnaissance** dan **web application testing** ke dalam satu antarmuka terpadu. Menghasilkan laporan terstruktur dengan integrity score, findings per severity, rekomendasi perbaikan, dan analisis AI mendalam.

```
🌐 Live  →  shadowgrid.shadowforce.id
⚠️  Authorized Use Only — hanya untuk domain yang Anda miliki
```

**22+ modul aktif:**

| Kategori | Tools |
|---|---|
| DNS & Mail | SPF · DMARC · DKIM · CAA · MX · NS |
| TLS/SSL | Handshake · Cipher Suite · SSLyze |
| HTTP Security | HSTS · CSP · X-Frame · Referrer-Policy |
| Network | Port Scan · NMAP TCP/UDP · Subdomain Enum |
| Web App | XSS · SQLi · Dir Bruteforce · Admin Finder · CORS |
| Vuln Scan | Nuclei · Nessus · OpenVAS · CVE Check · OWASP ZAP |
| Intelligence | JS Bundle Audit · GitHub Leak · ParamSpider · CMS Fingerprint |
| Export | HTML · TXT · JSON · PDF · ZIP Bundle |

[![Stars](https://img.shields.io/github/stars/ShadowForceID/shadowgrid?style=flat-square&color=36e29a&labelColor=0c1116)](https://github.com/ShadowForceID/shadowgrid/stargazers)
[![Forks](https://img.shields.io/github/forks/ShadowForceID/shadowgrid?style=flat-square&color=9b8cff&labelColor=0c1116)](https://github.com/ShadowForceID/shadowgrid/network/members)
[![Issues](https://img.shields.io/github/issues/ShadowForceID/shadowgrid?style=flat-square&color=e8b14a&labelColor=0c1116)](https://github.com/ShadowForceID/shadowgrid/issues)
[![Last Commit](https://img.shields.io/github/last-commit/ShadowForceID/shadowgrid?style=flat-square&color=36e29a&labelColor=0c1116)](https://github.com/ShadowForceID/shadowgrid/commits)

---

### 🟢 [KRONYX](https://github.com/ShadowForceID/kronyx) — Self-hosted Defensive OSINT Console

> *Assess the exposure of assets you own.*

**Kronyx** adalah konsol OSINT defensif ringan yang kamu jalankan sendiri — untuk memeriksa eksposur **email, domain, atau handle milikmu sendiri** di web publik. Kronyx menembakkan Google dork queries via API, merangkum hasilnya dengan LLM, dan menunjukkan apa yang perlu dibersihkan.

```
Stack  →  Python 3.8+ (stdlib only, no pip install)
Port   →  http://127.0.0.1:8787
Setup  →  python3 server.py  →  buka browser
```

**3 scan scope:**

| Scope | Menjawab pertanyaan |
|---|---|
| **Self Email** | Di mana emailku bocor? Paste sites, breach dumps, indexed files |
| **My Domain** | Attack surface domain apa yang terindeks publik? Auth pages, .env, subdomains |
| **My Footprint** | Di mana handleku muncul? Social, dev platforms, forum, agregator |

Setiap pemeriksaan menampilkan **query persis** yang dijalankan + audit log append-only untuk setiap scan.

[![Stars](https://img.shields.io/github/stars/ShadowForceID/kronyx?style=for-the-badge&logo=github&color=36e29a&labelColor=0c1116)](https://github.com/ShadowForceID/kronyx/stargazers)
[![Forks](https://img.shields.io/github/forks/ShadowForceID/kronyx?style=for-the-badge&logo=github&color=9b8cff&labelColor=0c1116)](https://github.com/ShadowForceID/kronyx/network/members)
[![Issues](https://img.shields.io/github/issues/ShadowForceID/kronyx?style=for-the-badge&logo=github&color=e8b14a&labelColor=0c1116)](https://github.com/ShadowForceID/kronyx/issues)
[![Last Commit](https://img.shields.io/github/last-commit/ShadowForceID/kronyx?style=for-the-badge&logo=git&color=9b8cff&labelColor=0c1116)](https://github.com/ShadowForceID/kronyx/commits)

---

### 🟣 [BytelOS](https://github.com/ShadowForceID/BytelOS) — WhatsApp Operations Center

> *Single-file ops dashboard untuk bot manajemen grup WhatsApp berbasis Baileys.*

**BytelOS** mengubah bot WhatsApp group-management menjadi browser-based control center. Bot menulis structured JSON logs; server Python kecil membacanya dan menyajikan dashboard live — tanpa database, tanpa Redis, tanpa Elasticsearch.

```
Stack   →  Baileys · Node.js 18+ · Flask · psutil
Port    →  http://localhost:8080
RAM     →  berjalan di 1 vCPU / 1 GB RAM
```

**Fitur utama:**

| Panel | Isi |
|---|---|
| **Live Feed** | Merged stream pesan, audit, error, system events (SOC-style) |
| **Group Monitor** | Pesan grup + nama pengirim + nama grup |
| **Audit Trail** | Join/leave/promote/demote/kick/command + admin pelaku |
| **VPS Monitor** | CPU · RAM · Disk · Network · Uptime via psutil |
| **Health Detection** | Bot ditandai OFFLINE jika heartbeat basi |

**Privacy modes:** `group` (default) · `metadata` · `full`  
**Bot commands:** `!ping` · `!menu` · `!tagall` · `!kick` · `!promote` · `!demote`

[![Stars](https://img.shields.io/github/stars/ShadowForceID/BytelOS?style=for-the-badge&color=ff2e88&labelColor=140a20)](https://github.com/ShadowForceID/BytelOS/stargazers)
[![Forks](https://img.shields.io/github/forks/ShadowForceID/BytelOS?style=for-the-badge&color=a855f7&labelColor=140a20)](https://github.com/ShadowForceID/BytelOS/network/members)
[![Issues](https://img.shields.io/github/issues/ShadowForceID/BytelOS?style=for-the-badge&color=fbbf24&labelColor=140a20)](https://github.com/ShadowForceID/BytelOS/issues)
[![Last Commit](https://img.shields.io/github/last-commit/ShadowForceID/BytelOS?style=flat-square&color=ec4899&labelColor=140a20)](https://github.com/ShadowForceID/BytelOS/commits)

---

## 📊 GitHub Stats

<div align="center">

<img height="160" src="https://github-readme-stats.vercel.app/api?username=ShadowForceID&show_icons=true&theme=tokyonight&bg_color=0d1117&title_color=36e29a&icon_color=36e29a&text_color=ffffff&border_color=36e29a&count_private=true" />
&nbsp;
<img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=ShadowForceID&layout=compact&theme=tokyonight&bg_color=0d1117&title_color=36e29a&text_color=ffffff&border_color=36e29a&langs_count=6" />

<br/><br/>

<img src="https://streak-stats.demolab.com?user=ShadowForceID&theme=dark&background=0D1117&ring=36E29A&fire=36E29A&currStreakLabel=36E29A&sideLabels=FFFFFF&dates=888888&border=36E29A" />

</div>

---

## 🧰 Tech Stack

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-121011?style=for-the-badge&logo=gnu-bash&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

</div>

---

## 📈 Contribution Graph

<div align="center">
<img src="https://github-readme-activity-graph.vercel.app/graph?username=ShadowForceID&bg_color=0d1117&color=36e29a&line=36e29a&point=ffffff&area=true&hide_border=true" />
</div>

---

## 🛠️ Skills

<div align="center">
<img src="https://skillicons.dev/icons?i=py,js,nodejs,flask,bash,linux,git,github&theme=dark" />
</div>

---

<div align="center">

**Semua alat di sini hanya untuk digunakan pada aset yang Anda miliki atau memiliki otorisasi eksplisit.**  
*Blue Team · Defensive · Ethical · Authorized Use Only*

<br/>

© 2026 **ShadowForce** · [shadowforce.id](https://shadowforce.id)

</div>
