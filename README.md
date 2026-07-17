<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="./assets/light.svg">
  <img src="./assets/dark.svg" width="100%" alt="Gabriel Varao — Software Engineering, Embedded Systems and Cybersecurity">
</picture>

<p align="center">
  <a href="https://github.com/GabrielVarao?tab=repositories">
    <img src="https://img.shields.io/badge/PORTFOLIO-Explore%20Projects-6D28D9?style=for-the-badge&logo=github&logoColor=white&labelColor=111827" alt="Portfolio">
  </a>
  <a href="mailto:gabrielvarao778@gmail.com">
    <img src="https://img.shields.io/badge/EMAIL-Contact%20Me-7C3AED?style=for-the-badge&logo=gmail&logoColor=white&labelColor=111827" alt="Email">
  </a>
  <a href="https://github.com/GabrielVarao">
    <img src="https://img.shields.io/badge/GITHUB-GabrielVarao-312E81?style=for-the-badge&logo=github&logoColor=white&labelColor=111827" alt="GitHub">
  </a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=GabrielVarao&label=PROFILE+VIEWS&color=6D28D9&style=for-the-badge" alt="Profile views">
  <img src="https://img.shields.io/github/followers/GabrielVarao?style=for-the-badge&logo=github&logoColor=white&label=FOLLOWERS&color=4F46E5&labelColor=111827" alt="GitHub followers">
  <img src="https://img.shields.io/github/stars/GabrielVarao?style=for-the-badge&logo=github&logoColor=white&label=STARS&color=7C3AED&labelColor=111827" alt="GitHub stars">
</p>

---

## About Me

I am an **Electronics Apprentice (EFZ) in Switzerland** with a strong focus on software engineering, embedded systems and cybersecurity.

I enjoy building systems where software interacts with real hardware, live data and operational workflows. My projects range from AVR firmware and real-time signal pipelines to monitoring dashboards, desktop engineering tools and embedded Linux deployments.

My engineering approach focuses on:

- clean and maintainable architecture
- practical testing and hardware validation
- real-time visualization and monitoring
- secure and reliable software design
- professional, product-focused interfaces

My long-term goal is to work professionally in cybersecurity and build technology that solves real technical problems.

### Open To

- Open-source collaboration
- Junior software engineering opportunities
- Cybersecurity and secure software projects
- Embedded systems and Linux development
- Applied AI, automation and real-time systems

---

## Tech Stack

### Languages

<p align="left">
  <img src="https://skillicons.dev/icons?i=c,rust,python,typescript,javascript,html,css&theme=dark" alt="Languages">
</p>

### Frontend

<p align="left">
  <img src="https://skillicons.dev/icons?i=react,vite,qt&theme=dark" alt="Frontend">
</p>

### Backend & Data

<p align="left">
  <img src="https://skillicons.dev/icons?i=nodejs,express,sqlite&theme=dark" alt="Backend">
</p>

<p>
  <img src="https://img.shields.io/badge/REST%20APIs-111827?style=flat-square&logo=postman&logoColor=A78BFA" alt="REST APIs">
  <img src="https://img.shields.io/badge/WebSockets-111827?style=flat-square&logo=socketdotio&logoColor=A78BFA" alt="WebSockets">
  <img src="https://img.shields.io/badge/ZeroMQ-111827?style=flat-square&logo=zeromq&logoColor=A78BFA" alt="ZeroMQ">
  <img src="https://img.shields.io/badge/Protocol%20Buffers-111827?style=flat-square&logo=google&logoColor=A78BFA" alt="Protocol Buffers">
</p>

### DevOps, Embedded & Tooling

<p align="left">
  <img src="https://skillicons.dev/icons?i=git,github,githubactions,docker,linux,ubuntu,bash,cmake,vscode,postman&theme=dark" alt="DevOps and tooling">
</p>

<p>
  <img src="https://img.shields.io/badge/Embedded%20Linux-111827?style=flat-square&logo=linux&logoColor=A78BFA" alt="Embedded Linux">
  <img src="https://img.shields.io/badge/Yocto-111827?style=flat-square&logo=linuxfoundation&logoColor=A78BFA" alt="Yocto">
  <img src="https://img.shields.io/badge/AVR%20%2F%20ATmega2560-111827?style=flat-square&logo=microchip&logoColor=A78BFA" alt="AVR">
  <img src="https://img.shields.io/badge/Matplotlib-111827?style=flat-square&logo=python&logoColor=A78BFA" alt="Matplotlib">
</p>

---

## AI / ML & Data Expertise

| Domain | Level | Details |
|---|:---:|---|
| Signal Processing | ![Intermediate](https://img.shields.io/badge/Intermediate-6D28D9?style=flat-square) | Signal generation, noise simulation, moving-average filtering and validation |
| Data Visualization | ![Intermediate](https://img.shields.io/badge/Intermediate-4F46E5?style=flat-square) | Live graphs, dashboards, histograms, heatmaps and operational displays |
| Machine Learning Foundations | ![Developing](https://img.shields.io/badge/Developing-7C3AED?style=flat-square) | Data preparation, model concepts, evaluation and Python workflows |
| Computer Vision | ![Exploring](https://img.shields.io/badge/Exploring-4338CA?style=flat-square) | OpenCV-oriented experimentation and local GPU-based tooling |
| AI Product Engineering | ![Developing](https://img.shields.io/badge/Developing-5B21B6?style=flat-square) | Integrating intelligent features into useful technical applications |

---

## Featured Projects

<details>
<summary><strong>Rust Signal Filter Lab</strong> — Real-time cross-language signal pipeline</summary>

<br>

A real-time measurement simulation in which Rust generates a signal, adds noise, applies a moving-average filter and streams typed samples to Python for live visualization.

| Category | Engineering Detail |
|---|---|
| **Stack** | Rust, Python, ZeroMQ, Protocol Buffers, Matplotlib |
| **Scale** | Continuous inter-process stream with clean, noisy and filtered samples |
| **Performance** | Compact binary serialization and responsive graph updates |
| **Security** | Explicit schema and controlled local communication |
| **Impact** | Demonstrates signal processing, distributed architecture and observability |
| **Repository** | [Open repository](https://github.com/GabrielVarao/sinus_signal_filter) |

The project separates data generation, filtering, serialization, transport and visualization into clear components. It provides a useful foundation for sensor simulations and industrial monitoring tools.

</details>

<details>
<summary><strong>4×4 Matrix Keypad Calculator</strong> — Hardware-validated AVR firmware</summary>

<br>

A firmware calculator for the ATmega2560 using a 4×4 matrix keypad as input and an HD44780-compatible LCD for output.

| Category | Engineering Detail |
|---|---|
| **Stack** | C, AVR, ATmega2560, Microchip Studio, LCD |
| **Scale** | Embedded single-board application with physical input and display |
| **Performance** | Deterministic finite-state-machine control |
| **Security** | Explicit state transitions and division-by-zero protection |
| **Impact** | Combines embedded input handling, arithmetic logic and hardware validation |
| **Repository** | [Open repository](https://github.com/GabrielVarao/Keyboard-Calculator) |

The project supports multi-digit numbers, floating-point calculations, result reuse, immediate display feedback and the four standard arithmetic operations.

</details>

<details>
<summary><strong>Stepper Motor Controller</strong> — Deterministic motion-control firmware</summary>

<br>

A structured AVR firmware project that controls stepper motor direction and speed using a finite state machine and an extended half-step sequence.

| Category | Engineering Detail |
|---|---|
| **Stack** | C, AVR, ATmega2560, Microchip Studio |
| **Scale** | Physical motor-control system operating from 20 to 300 steps per second |
| **Performance** | Eight-state half-step sequence for smoother motion |
| **Security** | Predictable state transitions and bounded speed control |
| **Impact** | Demonstrates motor control, firmware architecture and hardware validation |
| **Repository** | [Open repository](https://github.com/GabrielVarao/Schrittmotor) |

The implementation supports clockwise and anticlockwise rotation, dynamic speed adjustment and future extension with additional operating modes.

</details>

<details>
<summary><strong>Rust Sinus Console</strong> — Mathematical ASCII visualization</summary>

<br>

A compact Rust application that calculates a sine wave and renders it directly in the terminal as an ASCII graph.

| Category | Engineering Detail |
|---|---|
| **Stack** | Rust, Cargo, standard-library mathematics |
| **Scale** | Configurable terminal visualization |
| **Performance** | Lightweight calculation and direct console rendering |
| **Security** | No network access or privileged operations |
| **Impact** | Practical introduction to Rust, mathematics and visualization |
| **Repository** | [Open repository](https://github.com/GabrielVarao/sinus_console) |

The project maps calculated sine values to terminal rows and provides a simple foundation for more advanced signal-processing applications.

</details>

---

## Experience

### Electronics Apprentice (EFZ) · Zumbach Electronics AG

**Switzerland · Current**

Developing a broad engineering foundation across electronics, testing, calibration, service, embedded systems and software-oriented product development.

- Experience in assembly, testing, calibration and technical service
- Development of monitoring dashboards and engineering interfaces
- Work with REST APIs, React, Node.js and WebSockets
- Deployment and debugging on Linux-based embedded systems
- Investigation of Yocto and SD-card software update strategies
- Structured debugging across hardware, firmware, networking and application layers

<p>
  <img src="https://img.shields.io/badge/Embedded%20Systems-111827?style=flat-square&logo=microchip&logoColor=A78BFA" alt="Embedded Systems">
  <img src="https://img.shields.io/badge/Software%20Engineering-111827?style=flat-square&logo=github&logoColor=A78BFA" alt="Software Engineering">
  <img src="https://img.shields.io/badge/Test%20%26%20Calibration-111827?style=flat-square&logo=testinglibrary&logoColor=A78BFA" alt="Testing">
  <img src="https://img.shields.io/badge/Linux-111827?style=flat-square&logo=linux&logoColor=A78BFA" alt="Linux">
</p>

### Independent Software & Cybersecurity Development

**Ongoing**

- Building desktop applications with live engineering data
- Developing full-stack dashboards with API integrations
- Exploring ethical hacking, defensive security and secure development
- Creating Rust and Python applications for real-time systems
- Improving software architecture, testing and technical documentation

---

## Achievements

<div align="center">

| Recognition | Details |
|---|---|
| **Real-Time Systems Project** | Built a Rust-to-Python signal pipeline using ZeroMQ and Protocol Buffers |
| **Embedded Firmware Validation** | Tested calculator and motor-control firmware on ATmega2560 hardware |
| **Cross-Disciplinary Engineering** | Combined electronics, firmware, APIs, visualization and Linux |
| **Product-Focused Development** | Designed professional interfaces around real engineering workflows |
| **Technical Documentation** | Created structured setup, architecture and validation documentation |

</div>

---

## Learning Roadmap

### Cloud & Infrastructure

<p>
  <img src="https://img.shields.io/badge/AWS-Cloud%20Foundations-6D28D9?style=for-the-badge&logo=amazonwebservices&logoColor=white&labelColor=111827" alt="AWS">
  <img src="https://img.shields.io/badge/Docker-Containerization-4F46E5?style=for-the-badge&logo=docker&logoColor=white&labelColor=111827" alt="Docker">
</p>

### Networking & Cybersecurity

<p>
  <img src="https://img.shields.io/badge/Cisco-Networking%20Foundations-7C3AED?style=for-the-badge&logo=cisco&logoColor=white&labelColor=111827" alt="Cisco">
  <img src="https://img.shields.io/badge/Cybersecurity-Defensive%20Engineering-4338CA?style=for-the-badge&logo=hackthebox&logoColor=white&labelColor=111827" alt="Cybersecurity">
</p>

### AI & Software Engineering

<p>
  <img src="https://img.shields.io/badge/Machine%20Learning-Applied%20Foundations-5B21B6?style=for-the-badge&logo=python&logoColor=white&labelColor=111827" alt="Machine Learning">
  <img src="https://img.shields.io/badge/Rust-Systems%20Programming-312E81?style=for-the-badge&logo=rust&logoColor=white&labelColor=111827" alt="Rust">
</p>

---

## GitHub Analytics

<div align="center">
  <img height="180" src="https://github-readme-stats.vercel.app/api?username=GabrielVarao&show_icons=true&hide_border=true&include_all_commits=true&count_private=true&bg_color=0D1117&title_color=A78BFA&icon_color=8B5CF6&text_color=C4B5FD&ring_color=7C3AED" alt="GitHub stats">
  <img height="180" src="https://github-readme-stats.vercel.app/api/top-langs/?username=GabrielVarao&layout=compact&langs_count=8&hide_border=true&bg_color=0D1117&title_color=A78BFA&text_color=C4B5FD" alt="Most used languages">
</div>

<div align="center">
  <img width="92%" src="https://streak-stats.demolab.com?user=GabrielVarao&hide_border=true&background=0D1117&ring=7C3AED&fire=A78BFA&currStreakLabel=C4B5FD&sideLabels=C4B5FD&dates=818CF8&currStreakNum=F8FAFC&sideNums=F8FAFC" alt="GitHub contribution streak">
</div>

---

## GitHub Trophies

<div align="center">
  <img width="96%" src="https://github-profile-trophy.vercel.app/?username=GabrielVarao&theme=discord&no-frame=true&no-bg=true&margin-w=12&margin-h=12&column=7" alt="GitHub trophies">
</div>

---

## Contribution Activity

<div align="center">
  <img width="96%" src="https://github-readme-activity-graph.vercel.app/graph?username=GabrielVarao&bg_color=0D1117&color=A78BFA&line=7C3AED&point=60A5FA&area=true&hide_border=true&custom_title=Gabriel%20Varao%27s%20Contribution%20Activity" alt="Contribution graph">
</div>

---

## Contribution Snake

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/GabrielVarao/GabrielVarao/output/github-contribution-grid-snake-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/GabrielVarao/GabrielVarao/output/github-contribution-grid-snake.svg">
    <img width="96%" alt="GitHub contribution snake" src="https://raw.githubusercontent.com/GabrielVarao/GabrielVarao/output/github-contribution-grid-snake-dark.svg">
  </picture>
</div>

---

## Current Focus

```yaml
learning:
  - Applied machine learning and AI engineering
  - Secure software development and cybersecurity
  - Advanced Rust, Linux and embedded systems
  - Scalable backend and real-time architectures

building:
  - Engineering dashboards with live operational data
  - Embedded and desktop applications
  - Cross-language systems using Rust and Python
  - A professional portfolio of production-minded projects

exploring:
  - Computer vision and local AI tooling
  - Yocto-based embedded Linux
  - Safe software update strategies
  - Reverse engineering from an ethical perspective

open_to:
  - Open-source collaboration
  - Junior software engineering opportunities
  - Cybersecurity and embedded systems projects
  - Applied AI and developer-tooling projects
```

---

## Connect

<p align="center">
  <a href="mailto:gabrielvarao778@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-Contact%20Gabriel-6D28D9?style=for-the-badge&logo=gmail&logoColor=white&labelColor=111827" alt="Gmail">
  </a>
  <a href="https://github.com/GabrielVarao">
    <img src="https://img.shields.io/badge/GitHub-GabrielVarao-7C3AED?style=for-the-badge&logo=github&logoColor=white&labelColor=111827" alt="GitHub">
  </a>
  <a href="https://github.com/GabrielVarao?tab=repositories">
    <img src="https://img.shields.io/badge/Portfolio-Project%20Collection-4338CA?style=for-the-badge&logo=vercel&logoColor=white&labelColor=111827" alt="Portfolio">
  </a>
</p>

---

<p align="center">
  <strong>Engineering is where curiosity becomes a reliable system.</strong>
</p>

<p align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=140&section=footer&color=0:312E81,55:4C1D95,100:0D1117" alt="Footer">
</p>
