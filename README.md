<!--
✨ Hi, Tam-George! This README is designed to be eye-catching yet clean.
-->

<div align="center">

# 👋🏽 Hi, I'm **Tam-George Belema**

### Computer Science Student • Python Developer • Cybersecurity Enthusiast

<!-- Animated headline -->

<img src="https://readme-typing-svg.herokuapp.com?duration=3000&pause=500&center=true&vCenter=true&width=650&lines=Computer+Science+Student;Python+Developer;Blue+Team+%2F+Cybersecurity+Enthusiast;Always+learning%2C+always+building" alt="Animated headline"/>

<!-- Moving Python GIF -->

<img src="https://media.giphy.com/media/Ll22OhMLAlVDb8UQWe/giphy.gif" width="160" alt="Serious coder at laptop"/>

<!-- Cyber gif -->
<img src="https://media.giphy.com/media/LMt9638dO8dftAjtco/giphy.gif" width="160" alt="Hands typing on keyboard"/>
</div>
---

## 🧭 About Me

* 🎓 **Computer Science** undergraduate exploring software engineering and defensive security.
* 🐍 Writing clean, readable **Python** for scripts, automation, and backend experiments.
* 🛡️ Passionate about **Blue Team** topics: incident response, SIEM, monitoring, and threat detection.
* 📚 Currently diving into **data structures**, **networks**, and **secure coding**.
* 💡 I love breaking complex ideas into simple, teachable steps.

---

## 🧰 Tech Toolbox

<div align="center">

<!-- Python only with GIF -->

<img src="https://media.giphy.com/media/LMt9638dO8dftAjtco/giphy.gif" width="120" alt="Python moving gif"/>

</div>

---

## 🔭 What I'm Learning Now

* 🕵🏽‍♂️ **Network analysis** (pcap, Zeek logs, Suricata rules)
* 🧪 **Testing & CI** for Python projects (pytest + GitHub Actions)
* 🛠️ **Secure coding** patterns and threat modeling

---

## 📌 Featured Projects

### 1) **py-net-scout** — Packet Sniffer & Analyzer

Small Python toolkit to capture traffic, extract features, and export summaries.

* `Python`, `Scapy`, `Pandas`
* Features: live capture, protocol breakdown, CSV/JSON export

**Repo:** [github.com/Tam-George10/py-net-scout](https://github.com/Tam-George10/py-net-scout)

---

### 2) **logwatch-lite** — Simple Log Monitoring

CLI tool that tails logs, detects patterns/anomalies, and alerts to console.

* `Python`, `Regex`, `Rich`
* Features: colorized output, rules file, ignore lists

**Repo:** [github.com/Tam-George10/logwatch-lite](https://github.com/Tam-George10/logwatch-lite)

---

### 3) **ctf-scripts** — CTF Helpers

Handy Python scripts for encoding/decoding, hashing, and quick forensics.

* `Python`, `Click`
* Features: one-liners for base64/hex, file carving helpers

**Repo:** [github.com/Tam-George10/ctf-scripts](https://github.com/Tam-George10/ctf-scripts)

---

## ✍🏽 Snippet: My Python Style

```python
from dataclasses import dataclass
from typing import Iterable

@dataclass
class Event:
    ts: float
    src: str
    dst: str
    proto: str


def filter_by(events: Iterable[Event], **kwargs) -> list[Event]:
    return [e for e in events if all(getattr(e, k) == v for k, v in kwargs.items())]
```

---

## 📫 Connect with Me

* 📧 **Email:** [tgbeele@gmail.com](mailto:tgbeele@gmail.com)

---

## 🧩 Fun

<div align="center">

🎮 Currently playing: **CTF challenges & HackTheBox labs** 🕵🏽‍♂️
📚 Favorite book: *The Art of Invisibility* by Kevin Mitnick
💡 Fun fact: I automate boring stuff with Python—even renaming files and cleaning logs!

<!-- Snake contribution graph -->

<img src="https://raw.githubusercontent.com/Platane/snk/output/github-contribution-grid-snake.svg" alt="snake gif"/>

</div>

---

## 🏆 Certifications (Current & Future)

<div align="center">

<!-- Subtle animated GIFs for certs -->

  <img src="https://img.shields.io/badge/CompTIA-Network%2B-red?style=for-the-badge&logo=comptia" alt="CompTIA Network+ Badge"/>
  <img src="https://img.shields.io/badge/CompTIA-Security%2B-blue?style=for-the-badge&logo=comptia" alt="CompTIA Security+ Badge"/>



</div>

*Currently working toward Network+ and Security+ to strengthen my foundational knowledge in networking and security.*

### 🎯 Future Certifications

<div align="center">

<img src="https://img.shields.io/badge/CompTIA-CySA%2B-green?style=for-the-badge&logo=comptia" alt="CompTIA CySA+ Badge"/>
<img src="https://img.shields.io/badge/EC--Council-CEH-black?style=for-the-badge&logo=hackaday" alt="CEH Badge"/>
<img src="https://img.shields.io/badge/(ISC)²-CISSP-darkgreen?style=for-the-badge&logo=isc2" alt="CISSP Badge"/>


</div>

---

## 📝 Roadmap

* ✅ Build a **packet sniffer** in Python with Scapy
* ✅ Automate log parsing and anomaly detection with Regex + Python
* [ ] Build and publish a **SIEM mini-lab** with Docker Compose
* [ ] Write a blog post on **Suricata vs Zeek for beginners**
* [ ] Release a **FastAPI** backend template with auth & logging
* [ ] Contribute to an open-source **Blue Team security tool**
* [ ] Achieve **CompTIA Network+** certification
* [ ] Achieve **CompTIA Security+** certification
* [ ] Achieve **CompTIA CySA+** certification
* [ ] Achieve **CEH** certification
* [ ] Achieve **CISSP** certification

---

<div align="center">

**"Learn. Build. Secure."**

</div>

    

