<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=22&pause=1200&color=2EA043&center=true&vCenter=true&width=640&lines=Hi%2C+I'm+Rodgers+%F0%9F%91%8B;Visiting+Professor+%40+Tongmyong+University%2C+Busan;Networks+%E2%80%A2+Cryptography+%E2%80%A2+Blockchain;Teaching+machines+to+talk+securely+%F0%9F%94%90" alt="Typing intro" />

<p>
  <a href="https://www.linkedin.com/in/rodgers-agil-jato-msc-767628213"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:rodgersochieng6@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <a href="https://www.tu.ac.kr"><img src="https://img.shields.io/badge/Tongmyong_University-003876?style=for-the-badge&logo=googlescholar&logoColor=white" /></a>
</p>

</div>

---

### `$ whoami`

I teach and build at the intersection of **networks, cybersecurity, cryptography, blockchain and AI**.
Currently a **Visiting Professor** in the Department of AI & Computer Engineering at Tongmyong University (Busan, Korea), an Assistant Lecturer at Africa International University (Nairobi, Kenya), and a **PhD candidate in IT Convergence & Applied Engineering**.
Before academia I spent years keeping real networks alive — LAN/WAN, VPNs, firewalls, cloud migrations.

---

### ⛓️ My career, as a blockchain

> Every block stores the hash of the one before it. Change my history and the chain breaks. *(The hashes are real SHA-256 — verify them below.)*

```yaml
block: 0                      # genesis
period:    2017 – 2020
data:      BSc IT, First Class Honours · Africa International University
prev_hash: 0000000000000000
hash:      d2a15c98598a405f
```
```yaml
block: 1
period:    2018 – 2022
data:      Networking Consultant, Charleon Solutions · IT Officer, Nation Media Group
prev_hash: d2a15c98598a405f
hash:      ff1f07bc6e024774
```
```yaml
block: 2
period:    2022 – 2025
data:      MSc IT, Distinction, Strathmore · GTA → Assistant Lecturer, AIU · IT Consultant, Doshi Group
prev_hash: ff1f07bc6e024774
hash:      317ef79110139351
```
```yaml
block: 3                      # head of chain
period:    2026 – now
data:      Visiting Professor, AI & Computer Engineering · Tongmyong University, Busan
prev_hash: 317ef79110139351
hash:      ec15491b987beb64  ✅ chain valid
```
```yaml
# ⏳ mempool — pending transaction
tx:        PhD, IT Convergence & Applied Engineering
status:    in progress · awaiting confirmation 🎓
```

<details>
<summary>🔍 Verify the chain yourself</summary>

```python
import hashlib

blocks = [
    ("0", "2017-2020", "BSc IT, First Class Honours | Africa International University"),
    ("1", "2018-2022", "Networking Consultant, Charleon Solutions | IT Officer, Nation Media Group"),
    ("2", "2022-2025", "MSc IT, Distinction, Strathmore | GTA then Assistant Lecturer, AIU | IT Consultant, Doshi Group"),
    ("3", "2026-now",  "Visiting Professor, AI & Computer Engineering | Tongmyong University, Busan"),
]

prev = "0" * 64
for idx, period, data in blocks:
    h = hashlib.sha256(f"{idx}|{period}|{data}|{prev}".encode()).hexdigest()
    print(f"block {idx}: prev={prev[:16]}  hash={h[:16]}")
    prev = h
```

</details>

---

### 🔬 What I work on

| Area | Focus |
|---|---|
| 🌐 **Networks** | Routing & switching, network architectures, troubleshooting, network automation with Python |
| 🔐 **Cryptography** | Foundational algorithms, data integrity, enterprise encryption, post-quantum signatures |
| ⛓️ **Blockchain** | Decentralised systems, smart contracts, blockchain in AI-driven environments |
| 🤖 **AI** | AI agents, AI workflow, agent security, AI applications — and everything else AI |
| 🛡️ **Security** | Network security infrastructure, IT governance, compliance (ISO, ODPC) |
| 💻 **Development** | Software engineering, Python & TypeScript applications, APIs, workflow automation |
| 🌱 **Open-Source Development** | Community contributions, open tooling, public teaching & research repositories |
| 🐧 **Linux** | System administration, shell scripting, server hardening, networking & security tooling |
| 🖥️ **Infrastructure & Homelab** | Virtualization, self-hosted services, containerization, isolated network & security testbeds |
| 🎓 **Education** | Curriculum design, mentorship systems, SDG 4 |

---

### 🧪 Labs & projects

| Project | Stack | Role |
|---|---|---|
| [Blockchain & ML Framework for Detecting Cloned and Refilled Alcohol](https://github.com/rodgersprofessor/Blockchain-and-ML-Framework-for-Detecting-Cloned-and-Refilled-Alcohol) | HTML · MIT | Main |
| [Beyond Efficiency: A Socio-Technical Framework and Exploratory Evidence for Community-Aware AI Data Center Siting in South Korea](https://github.com/torjoymorshad/beyond-efficiency-siting) | Python | Contributor |
| [Portable AI-Based Driver Drowsiness and Distraction Detection System](https://github.com/karkidipak/Portable-AI-Based-Driver-Drowsiness-and-Distraction-Detection-System) | Python · OpenCV | Supervisor |
| [AI-Based Mouse and Keyboard](https://github.com/alal23120126-cell/Twenty3) | Python · OpenCV | Supervisor |
| [Real-Time Weapon Detection System (YOLO)](https://github.com/torjoymorshad/weapon-detection-yolo) | Python · YOLO | Supervisor |
| [Speed Camera Detection System](https://github.com/visionX77/Speed-Camera-detection) | Python · OpenCV | Supervisor |
| [AI/ML campus maintenance system for reporting, classifying, prioritizing, and managing university facility](https://github.com/taimurahman740-art/Team-INNOVEXA) | *Stack* | Supervisor |
| [Your Erasmus Guide](https://github.com/rodgersprofessor/your-erasmus-guide) | TypeScript | Main |
| 🔒 `blockchainlive` | Python | Main |
| 🔒 `blockdemo` | Python | Main |
<sub>🔒 = private for now · teaching repos are opened up as courses go public</sub>

---

### 🧭 Currently exploring

Repos I've forked to study and experiment with:

- **Decentralised storage:** [kubo](https://github.com/rodgersprofessor/kubo), [helia](https://github.com/rodgersprofessor/helia) (IPFS)
- **Content provenance:** [c2pa-rs](https://github.com/rodgersprofessor/c2pa-rs), [watermarks-remover](https://github.com/rodgersprofessor/watermarks-remover)
- **Post-quantum crypto:** [mldsa-esp32](https://github.com/rodgersprofessor/mldsa-esp32) (ML-DSA / FIPS 204 on ESP32)
- **Web3:** [wagmi](https://github.com/rodgersprofessor/wagmi), [Block-Certify](https://github.com/rodgersprofessor/Block-Certify)
- **AI agents & simulation:** [agent-office](https://github.com/rodgersprofessor/agent-office), [mesa](https://github.com/rodgersprofessor/mesa), [n8n](https://github.com/rodgersprofessor/n8n)
- **Quantum:** [qiskitdocumentation](https://github.com/rodgersprofessor/qiskitdocumentation)

---

### 🛠️ Toolbox

<p>
  <img src="https://img.shields.io/badge/Cisco-1BA0D7?style=flat-square&logo=cisco&logoColor=white" />
  <img src="https://img.shields.io/badge/Huawei-FF0000?style=flat-square&logo=huawei&logoColor=white" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white" />
  <img src="https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white" />
  <img src="https://img.shields.io/badge/Microsoft_365-D83B01?style=flat-square&logo=microsoft&logoColor=white" />
  <img src="https://img.shields.io/badge/Solidity-363636?style=flat-square&logo=solidity&logoColor=white" />
</p>

**Certifications:** CCNA · Huawei HCIA Cloud Computing · Cybersecurity & Forensics (Brno University) · Microsoft 365 Security Administration · Design-Led Strategy (University of Sydney)

---

### 🎓 For my students

If you're in one of my classes — **Network Architectures, Cryptography, or Blockchain** — lab materials will live in the repos above. Open an issue if something breaks; that counts as participation. 😉

---

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=rodgersprofessor&show_icons=true&hide_border=true&theme=github_dark" height="150" />

<sub>🇰🇪 Nairobi → 🇰🇷 Busan · Speaks English, Kiswahili, Dholuo</sub>

</div>
