<div align="center">

🌐 [Português (BR)](README.pt_BR.md) | [Español](README.es.md)

<br/>

# 🎯 Soc Ops

### Social Bingo — built live with GitHub Copilot Agents

Break the ice at in-person events. Find people who match the prompts, mark your card, get five in a row — **bingo!**

<br/>

[![Live Demo](https://img.shields.io/badge/🎮_Live_Demo-4CAF50?style=for-the-badge)](https://copilot-dev-days.github.io/agent-lab-java/)
[![Lab Guide](https://img.shields.io/badge/📚_Lab_Guide-2196F3?style=for-the-badge)](workshop/GUIDE.md)
[![Java 21](https://img.shields.io/badge/Java-21-orange?style=for-the-badge&logo=openjdk)](https://adoptium.net/)
[![Spring Boot](https://img.shields.io/badge/Spring_Boot-3-6DB33F?style=for-the-badge&logo=springboot)](https://spring.io/projects/spring-boot)

</div>

---

## ✨ What is this?

**Soc Ops** is a hands-on **GitHub Copilot agent lab** wrapped inside a real Spring Boot web application. You'll use Copilot's coding agents to redesign the frontend, generate custom quiz content, and extend the game with new features — all in about an hour.

The game itself is a 5×5 social bingo board. Players mingle, find colleagues who match each square, and race to fill five in a row.

---

## 🗺️ Lab Guide

Work through the parts in order — each one builds on the last.

| Part | Title | What you'll do |
|:----:|-------|----------------|
| [**00**](workshop/00-overview.md) | Overview & Checklist | Get oriented and verify your setup |
| [**01**](workshop/01-setup.md) | Setup & Context Engineering | Bootstrap Copilot instructions for the project |
| [**02**](workshop/02-design.md) | Design-First Frontend | Redesign the UI with Plan Mode + cloud agents |
| [**03**](workshop/03-quiz-master.md) | Custom Quiz Master | Generate a themed quiz with a custom agent |
| [**04**](workshop/04-multi-agent.md) | Multi-Agent Development | Add a Scavenger Hunt mode via TDD agents |

> 📝 All guides live in [`workshop/`](workshop/) for offline reading.

---

## 🚀 Quick Start

**Prerequisites:** [Java 21 JDK](https://adoptium.net/) · [Maven 3.9+](https://maven.apache.org/) (or use the wrapper)

```bash
# Run locally
cd socops && ./mvnw spring-boot:run
# → open http://localhost:8080
```

```bash
# Build
cd socops && ./mvnw clean package

# Test
cd socops && ./mvnw test
```

> The app deploys automatically to GitHub Pages on every push to `main`.

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Backend | Java 21, Spring Boot 3 |
| Templates | Thymeleaf |
| Styles | Custom CSS utilities (`app.css`) |
| Build | Apache Maven (wrapper included) |
| CI/CD | GitHub Actions → GitHub Pages |

---

## 🤝 Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) · [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) · [SECURITY.md](SECURITY.md)
