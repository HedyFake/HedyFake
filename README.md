# HEDYFAKE — Cyber Security Portfolio

> **Cyber Security • Security Research • Tool Development • Automation • OSINT**

Selamat datang di portofolio keamanan siber saya. Repository ini berisi kumpulan proyek yang saya kembangkan untuk pembelajaran, riset keamanan, otomasi security testing, OSINT, digital forensics, dan security awareness.

## 🚀 Featured Projects

| Project | Fokus | Teknologi |
|---|---|---|
| [AISCAN](https://github.com/HedyFake/AISCAN) | Security scanning, AI analysis, reporting | Python, AI, Nuclei, Subfinder |
| [nucleiweb](https://github.com/HedyFake/nucleiweb) | Web interface & automation untuk Nuclei | PHP, Nuclei, Telegram |
| [TrackMe](https://github.com/HedyFake/TrackMe) | Geolocation & privacy research | JavaScript, PHP, ngrok |
| [CamHack](https://github.com/HedyFake/CamHack) | Webcam security-awareness research | PHP, Browser API, ngrok |
| [Photo](https://github.com/HedyFake/Photo) | OSINT & image metadata analysis | Python, EXIF, digital forensics |

## 🛡️ AISCAN

AISCAN merupakan framework security scanning yang menggabungkan automated reconnaissance, security checks, external security tools, AI-assisted analysis, triage, dan evidence-based reporting.

### Fitur utama

- Mass Scan
- Single Scan
- Scope/allowlist
- Subdomain discovery
- Security testing modules
- Secrets detection
- AI-assisted analysis
- HTML/Markdown reporting
- Evidence collection
- Finding triage
- External tool integration
- Windows path hardening
- Validation dan testing

### Security areas

- CORS
- XSS
- SQL Injection
- IDOR / authorization
- LFI
- SSRF
- CSRF
- Open Redirect
- Authentication & session security
- Security headers
- Content discovery
- Hidden parameters
- Sensitive information exposure
- Cryptography / transport security
- Business-logic related checks

> Digunakan untuk pembelajaran dan pengujian terhadap sistem yang memiliki izin.

## 🤖 nucleiweb

nucleiweb merupakan web interface/automation layer untuk menjalankan Nuclei secara lebih terstruktur.

Konsep utamanya:

```text
Target
  ↓
Web Interface
  ↓
Job / Workspace
  ↓
Nuclei Worker
  ↓
JSONL Results
  ↓
Parser & Grouping
  ↓
Report
  ↓
Telegram Notification
```

Fokus pengembangan:

- Background worker
- Target normalization
- JSONL processing
- Per-target reporting
- Group reporting
- Telegram notification
- Job workspace
- Result parsing
- Automated reporting

## 🌐 TrackMe

TrackMe adalah project security/privacy research yang mengeksplorasi bagaimana browser dapat menyediakan informasi melalui permission dan browser APIs.

Contoh data yang dapat menjadi objek penelitian:

- Geolocation
- Accuracy
- Altitude
- Speed
- Heading
- Platform
- CPU information
- Memory information
- Screen resolution
- Battery information
- User-Agent

Project ini diposisikan sebagai **authorized lab / security-awareness research** untuk memahami privacy exposure dan permission model browser.

## 📷 CamHack

CamHack merupakan security-awareness PoC untuk mempelajari keamanan akses webcam berbasis browser dan konsekuensi pemberian permission.

Materi pembelajaran mencakup:

- Browser camera permission
- Privacy awareness
- User consent
- Web server
- Public tunneling
- Data lifecycle
- Security-awareness testing

Project hanya digunakan pada lingkungan dan perangkat yang memang mendapatkan izin.

## 🖼️ Photo — OSINT & Digital Forensics

Photo berfokus pada analisis informasi yang terdapat pada file gambar.

Workflow:

```text
Image
 ↓
Metadata Extraction
 ↓
Technical Analysis
 ↓
OSINT Indicators
 ↓
Security / Privacy Review
 ↓
Report
```

Area analisis meliputi:

- EXIF metadata
- Camera information
- Image properties
- Potential location indicators
- File information
- Digital-forensics observations
- Security/privacy indicators

## 🧠 Security Research Methodology

Saya membangun project dengan pendekatan:

```text
RECON
  ↓
SCOPE
  ↓
DISCOVERY
  ↓
ANALYSIS
  ↓
VALIDATION
  ↓
EVIDENCE
  ↓
TRIAGE
  ↓
REPORT
  ↓
REMEDIATION
```

Prinsip yang digunakan:

- Scope-first
- Evidence-first
- Fail-closed
- Reproducible results
- Clear reporting
- Responsible disclosure
- Authorized testing

## ⚙️ Technology Stack

### Languages

- Python
- PHP
- JavaScript
- HTML
- CSS
- Shell

### Security Tools / Concepts

- Nuclei
- Subfinder
- CORS scanners
- XSS testing
- Web reconnaissance
- Secrets detection
- OSINT
- Digital forensics
- HTTP security analysis

### Automation

- Multi-threading
- Background workers
- JSONL pipelines
- Telegram automation
- HTML reporting
- AI-assisted triage

## 🧩 Project Evolution

```text
Simple Script
     ↓
Security Utility
     ↓
Automation
     ↓
Multi-tool Pipeline
     ↓
Reporting
     ↓
AI-assisted Analysis
     ↓
Security Research Framework
```

Tujuan saya bukan sekadar membuat tool yang dapat menjalankan command, tetapi membangun workflow yang:

**mengumpulkan data → menganalisis → memvalidasi → menyimpan evidence → menghasilkan laporan yang mudah dipahami.**

## 📊 Skill Matrix

| Area | Fokus |
|---|---|
| Web Security | Recon, testing, analysis |
| Automation | Python/PHP tooling |
| Reconnaissance | Domain/subdomain discovery |
| Vulnerability Research | Detection & validation |
| Reporting | HTML/Markdown |
| OSINT | Image & metadata analysis |
| Privacy | Browser permission research |
| Security Awareness | Webcam/geolocation PoC |
| AI | Assisted analysis & triage |
| DevOps-style Workflow | Workers, jobs, pipelines |

## 🧪 Responsible Security

Seluruh project keamanan dalam portofolio ini ditujukan untuk:

- Pendidikan
- Lab pribadi
- Security research
- CTF
- Authorized penetration testing
- Security awareness
- Defensive engineering

Jangan menjalankan scanning, collection, exploitation, atau pengujian terhadap sistem yang tidak dimiliki atau tidak memberikan izin.

## 🗺️ Repository Map

```text
HEDYFAKE
│
├── AISCAN
│   └── AI-assisted security scanner
│
├── nucleiweb
│   └── Nuclei automation & web interface
│
├── TrackMe
│   └── Geolocation/privacy research
│
├── CamHack
│   └── Webcam security-awareness PoC
│
└── Photo
    └── OSINT & image forensics
```

## 🔗 Repositories

- https://github.com/HedyFake/AISCAN
- https://github.com/HedyFake/nucleiweb
- https://github.com/HedyFake/TrackMe
- https://github.com/HedyFake/CamHack
- https://github.com/HedyFake/Photo

---

### 🧑‍💻 HEDYFAKE

**Cyber Security • Research • Automation • OSINT**

> Build. Break. Analyze. Learn. Secure.

⭐ Jika project ini bermanfaat untuk pembelajaran, silakan berikan star pada repository terkait.
