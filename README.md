# 🧮 Abacus Market – Analysis & Research of a Darknet Marketplace

> **Disclaimer**: This project is intended strictly for educational and research purposes. We do not endorse or promote any illegal activity. All information is gathered and analyzed from publicly available sources. Use responsibly.

---
[Abacus Market](https://abacustor.com/) - https://abacustor.com/ 

## 🌐 About the Project

**Abacus Market** is one of the most prominent darknet marketplaces in recent years. Known for its layered anonymity, support for multiple cryptocurrencies, and user-focused interface, it serves as a rich subject of study for cybersecurity researchers, OSINT analysts, and developers interested in anonymous ecosystems.

This repository provides a structured **framework for analyzing and simulating the architecture and behavior of Abacus Market** in a safe, offline environment. It’s designed for those seeking to understand how modern darknet marketplaces operate — from authentication systems and escrow mechanisms to vendor communications and UI/UX patterns.

Whether you're conducting research, simulating threat models, or simply exploring the technological underpinnings of these platforms, this project offers a comprehensive foundation.

---

## 🛠 Features

This project includes a range of capabilities for darknet marketplace research:

- 📊 **Marketplace structure analysis** — navigation, vendor profiles, product listings;
- 🔍 **User behavior simulation** — search, login, vendor messaging;
- 🔐 **PGP encryption workflows** — public key usage, order communication;
- 🧠 **Open-source intelligence (OSINT)** tools for darknet activity tracking;
- 🕵️ **Escrow & dispute system breakdowns** — based on real-world interactions;
- 🧪 Offline **interface replicas** for educational use (no live access);
- 🛠 Python-based **automation scripts** for metadata extraction;
- 🗓 Data collection and parsing from public .onion mirrors (via Tor);
- 📚 Knowledge base on darknet marketplace terminology and mechanisms.

---

## 💻 Technologies Used

| Stack | Tools |
|-------|-------|
| Language | Python 3.10+ |
| Web parsing | BeautifulSoup, Scrapy |
| Database | MongoDB / SQLite |
| API (optional) | FastAPI |
| Frontend (replica) | Flask + Jinja2 |
| Data analysis | Pandas, Matplotlib |
| Network | Tor + Stem library |
| DevOps | Docker, Docker Compose |

---

## ⚙️ Installation & Usage

> **Important**: This project is built to operate through the Tor network. Ensure Tor is installed and running locally before launching data gathering or interface components.

### 🐍 Local Setup

```bash
# Clone the repository
git clone https://github.com/yourusername/abacus-market-analysis.git
cd abacus-market-analysis

# Install dependencies
pip install -r requirements.txt

# Run a sample analyzer
python analyze_market.py
```

### 🐳 Docker-based Setup

```bash
docker-compose up --build
```

---

## 🧱 Repository Structure

```
abacus-market-analysis/
│
├── data/               # Dumps, public listings, screenshots
├── docs/               # Technical documentation, architectural notes
├── scripts/            # Scrapers, analyzers, simulation tools
├── ui/                 # Interface replica (Flask-based)
├── models/             # JSON schemas and structural data
├── tor_controller/     # Tor automation and monitoring
├── README.md           # You're here
```

---

## 🔬 Example Use Case

```python
from scripts.pgp_tools import extract_vendor_keys

# Load vendor data and extract PGP fingerprints
keys = extract_vendor_keys('data/vendors.json')
for key in keys:
    print(f"Vendor: {key['name']} – Fingerprint: {key['fingerprint']}")
```

---

## 📚 Educational Use Cases

This project is ideal for:

- Cybersecurity students and educators;
- Darknet threat intelligence analysts;
- OSINT practitioners studying anonymous ecosystems;
- Developers exploring P2P markets or escrow systems;
- Ethical hackers building darknet simulation environments.

---

## ⚖️ Legal & Ethical Notice

**This project is 100% educational.**

We do not provide access to live darknet services. The interface simulations and analysis are strictly offline and derived from publicly archived data. No illegal transactions or interactions are supported. Use responsibly, and only within the limits of your local law.

---

## 📜 License

This repository is released under the [MIT License](LICENSE). You are free to use, modify, and distribute it — so long as your usage is ethical and legal.

---

## 🤝 Contributing

We welcome contributions! Feel free to submit pull requests for:

- Improving code structure and logic;
- Translating documentation;
- Enhancing interface simulations;
- Adding new data extraction modules;
- Providing deeper insights into market structures.

Before contributing, please read `CONTRIBUTING.md` to understand the guidelines.

---

**Stay curious. Stay ethical. Study wisely.**

