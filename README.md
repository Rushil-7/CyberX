# CyberX
🔐 Welcome to CyberX! Explore cybersecurity, ethical hacking, and digital defense. Learn, solve challenges, and showcase your skills. Think ethically, hack responsibly, and secure the digital world! 
# 🛡️ my-ctf-solutions

> Writeups and notes from my **Cyber Induction CTF** challenges: what I tried, what worked, and what I learned.

This repository is my personal learning log and portfolio for beginner-level cybersecurity. Every writeup is based on work I actually did during the event, using only the challenge files and systems provided by the organizers.

---

## 📌 Objectives

- Document my approach to each challenge in a clear, repeatable way
- Reinforce what I learn by explaining it in my own words
- Build a habit of taking notes, saving evidence (commands and screenshots), and reflecting
- Practice ethical, authorized security work only
- Create a portfolio that shows my progress over time

---

## ⚖️ Ethics & Rules

All work in this repository follows these principles:

- ✅ I only test systems and files that the CTF organizers **explicitly provided and authorized**.
- ✅ I follow the event's rules (scope, allowed tools, no attacking the platform or other participants).
- ✅ I do not share content that the event forbids publishing. If the rules say to keep flags or solutions private, I redact them or wait until the event allows sharing.
- ❌ I never use these techniques against real people, personal accounts, or systems I don't have permission to test.

---

## 🗂️ Repository Structure

```text
my-ctf-solutions/
├── README.md                 # You are here
├── writeup-template.md       # Reusable template for every challenge
├── tools-and-commands.md     # Cheat sheet of useful commands, explained
├── resources.md              # Learning resources
├── .gitignore                # Files Git should not track
├── assets/
│   └── screenshots/          # Shared images (optional)
└── challenges/
    ├── linux/
    ├── web-exploitation/
    ├── cryptography/
    ├── forensics/
    ├── steganography/
    └── osint/
```

Each category folder has its own `README.md`. Each challenge gets its own subfolder:

```text
challenges/<category>/<challenge-name>/
├── README.md          # The writeup (copied from writeup-template.md)
└── screenshots/       # Evidence images for this challenge
```

---

## 🧰 Tools

> Keep only the tools **you actually used** and delete the rest.

| Category | Common tools |
|----------|--------------|
| Linux | `ssh`, `ls`, `cat`, `grep`, `find`, `chmod` |
| Web Exploitation | Browser DevTools, `curl`, Burp Suite |
| Cryptography | CyberChef, `base64`, `openssl`, Python |
| Forensics | `file`, `strings`, `exiftool`, `binwalk`, Wireshark |
| Steganography | `exiftool`, `steghide`, `zsteg`, `binwalk` |
| OSINT | Search operators, reverse image search, Wayback Machine, `whois` |

See [`tools-and-commands.md`](tools-and-commands.md) for explanations and examples.

---

## 🎓 Skills Learned

> Tick (`[x]`) only the skills you genuinely practiced, and add your own.

**Linux**
- [ ] Navigating the file system and reading files from the command line
- [ ] Searching with `grep` and `find`
- [ ] Understanding file permissions
- [ ] Connecting to remote machines with SSH

**Web Exploitation**
- [ ] Inspecting pages with browser DevTools
- [ ] Sending HTTP requests with `curl`
- [ ] Understanding cookies, headers, and basic input handling

**Cryptography**
- [ ] Recognizing common encodings (Base64, hex, ROT13)
- [ ] Understanding the difference between encoding, encryption, and hashing
- [ ] Using CyberChef to decode data

**Forensics**
- [ ] Identifying file types and reading metadata
- [ ] Extracting readable strings and embedded files
- [ ] Inspecting network captures

**Steganography**
- [ ] Checking images for hidden data and metadata
- [ ] Using extraction tools on provided media files

**OSINT**
- [ ] Using search operators effectively
- [ ] Verifying information using multiple public sources
- [ ] Working only within the challenge's defined scope

**General**
- [ ] Writing clear, reproducible documentation
- [ ] Using Git and GitHub

---

## 📑 Challenge Index

Update this table each time you add a writeup. Use the *Status* column to track progress: ✅ Solved, 🟡 Partially solved, ❌ Unsolved.

| # | Challenge | Category | Difficulty | Points | Status | Writeup |
|---|-----------|----------|------------|--------|--------|---------|
| – | _No writeups added yet_ | – | – | – | – | – |

<!-- Example row format (copy, edit, and remove this comment):
| 1 | Challenge Name | Linux | Easy | 100 | ✅ | [Link](challenges/linux/challenge-name/README.md) |
-->

### By category

- [Linux](challenges/linux/README.md)
- [Web Exploitation](challenges/web-exploitation/README.md)
- [Cryptography](challenges/cryptography/README.md)
- [Forensics](challenges/forensics/README.md)
- [Steganography](challenges/steganography/README.md)
- [OSINT](challenges/osint/README.md)

---

## ✍️ How to Add a New Writeup

```bash
# 1. Create a folder for the challenge (example: a Linux challenge)
mkdir -p challenges/linux/my-challenge-name/screenshots

# 2. Copy the template into it
cp writeup-template.md challenges/linux/my-challenge-name/README.md

# 3. Fill it in using your own notes, commands, and screenshots
# 4. Add a row to the Challenge Index above and in the category README
```

---

## 📚 More

- [Tools & Commands cheat sheet](tools-and-commands.md)
- [Learning resources](resources.md)

---

## 👤 About

**Name:** RUSHIL
**Event:** Cyber Induction CTF
**GitHub:** [@Rushil-07](https://github.com/your-username)

_This repository is for educational purposes only._
