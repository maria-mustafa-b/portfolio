<div align="center">
  <img src="favicon.svg" width="86" alt="Maria Mustafa monogram" />

  # Maria Mustafa — Cybersecurity Portfolio

  **Offensive Security · Penetration Testing · Secure Engineering · Dubai, UAE**

  A responsive personal portfolio showcasing my cybersecurity experience, infrastructure work, research, hackathon achievements, and selected technical projects.

  <br />

  [![Live Portfolio](https://img.shields.io/badge/Live_Portfolio-Open_Site-00C7B7?style=for-the-badge&logo=netlify&logoColor=white)](https://maria-mustafa-portfolio.netlify.app)
  [![LinkedIn](https://img.shields.io/badge/LinkedIn-Maria_Mustafa-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/maria-mustafa-baranwala)

  <br />

  ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
  ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
  ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=111)
  ![Netlify](https://img.shields.io/badge/Deployed_on-Netlify-00C7B7?style=flat-square&logo=netlify&logoColor=white)

</div>

---

## Live portfolio

**Production:** [maria-mustafa-portfolio.netlify.app](https://maria-mustafa-portfolio.netlify.app)

The site is deployed as a static production build on Netlify with HTTPS enabled on the public `netlify.app` URL.

## About this project

This portfolio presents my work as a cybersecurity student and aspiring penetration tester in a format that goes beyond a traditional resume. It focuses on practical security work, infrastructure experience, technical projects, research, and achievements while keeping the interface fast, accessible, and intentionally minimal.

The visual direction uses a dark security-focused design without relying on a heavy framework or template. The entire front end is implemented with semantic HTML, custom CSS, and lightweight JavaScript.

## Featured work

### Q-SCOUT — Network Discovery & Cryptographic Posture Scanner

Q-SCOUT is my Python-based defensive reconnaissance and cryptographic assessment project. It supports IPv4 addresses, hostnames, CIDR ranges, and file-based target input, then performs safe discovery and TLS inspection with deterministic reporting.

**Highlights:** bounded concurrent discovery, port and banner observation, reverse DNS, local-L2 MAC discovery, TLS certificate and cipher analysis, cryptographic classification, JSON/CSV reporting, Pytest validation, and controlled Linux-based testing.

[View Q-SCOUT repository →](https://github.com/maria-mustafa-b/q-scout)

### Airwings Hotel Search — Internal Automation Tool

An internal hotel-rate search application built around an admin-controlled browser automation workflow. The project combines a FastAPI backend, Playwright automation, structured hotel search, result extraction, and Linux service deployment while keeping authenticated provider access separated from the client-facing interface.

**Stack:** Python · FastAPI · Playwright · Linux · Uvicorn · systemd

> This is a private internal project, so implementation details that could expose credentials or business-sensitive information are intentionally not published.

## Portfolio highlights

- Cybersecurity internship experience covering authorized reconnaissance, vulnerability assessment, web security testing, Linux administration, and Docker infrastructure.
- 50+ PortSwigger Web Security Academy labs completed across major web-security vulnerability classes.
- Lead research author on an AI accessibility paper published in Springer Nature conference proceedings for ISDIA 2026.
- 1st Place — ASUS Bounty Challenge / StudySync AI.
- 2nd Place — Zayed University Innovation Hackathon / Visi-Tech.
- Sustainability Award — Green Power Challenge.

## Tech stack

| Area | Technologies |
| --- | --- |
| Front end | HTML5, CSS3, JavaScript |
| Design | Responsive CSS, custom components, CSS variables, motion/reveal effects |
| Hosting | Netlify |
| Version control | Git, GitHub |
| Featured security stack | Python, Burp Suite, Nmap, Metasploit, Wireshark, Kali Linux |
| Infrastructure | Linux, Docker, Nginx, Prometheus, Grafana, Loki, Gitea, Mailcow |

## Repository structure

```text
portfolio/
├── .gitignore
├── favicon.svg
├── index.html
├── netlify.toml
├── README.md
├── robots.txt
├── script.js
├── sitemap.xml
└── styles.css
```

## Run locally

No framework, package manager, or build step is required.

```bash
git clone https://github.com/maria-mustafa-b/portfolio.git
cd portfolio
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

You can also open `index.html` directly in a browser, although serving it locally is closer to the deployed environment.

## Deployment

The production site is hosted on **Netlify**.

For a Git-connected Netlify workflow:

1. Import this GitHub repository into Netlify.
2. Use the repository root as the publish directory.
3. No build command is required because the site is static.
4. Netlify publishes the production deployment and provides HTTPS automatically on the `netlify.app` subdomain.

The included `netlify.toml` defines the publish directory and security-focused HTTP response headers.

## Design goals

- Professional enough for internship and recruiter review.
- Security-focused without using an exaggerated “hacker” aesthetic.
- Clear project hierarchy with Q-SCOUT as the primary technical showcase.
- Fast loading and zero front-end framework dependencies.
- Responsive across desktop and mobile layouts.
- Accessible navigation, semantic sections, and reduced unnecessary motion/content.

## Contact

**Maria Mustafa** — Dubai, UAE  
Cybersecurity student · Aspiring Penetration Tester

[LinkedIn](https://www.linkedin.com/in/maria-mustafa-baranwala) · [GitHub](https://github.com/maria-mustafa-b) · [Live Portfolio](https://maria-mustafa-portfolio.netlify.app)

---

<div align="center">
  <sub>Personal cybersecurity portfolio · Maintained by Maria Mustafa</sub>
</div>
