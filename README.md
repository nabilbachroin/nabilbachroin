<h1 align="center">Nabil Bachroin</h1>

<p align="center"><strong>Embedded Firmware Engineer</strong><br />
Wireless audio · Bluetooth LE · USB HID · DSP</p>

<p align="center">Taipei, Taiwan · Banyuwangi, Indonesia</p>

<p align="center">
  <a href="https://www.linkedin.com/in/nabilbachroin/"><img alt="LinkedIn" src="https://custom-icon-badges.demolab.com/badge/Nabil%20Bachroin-0A66C2?logo=linkedin-white&logoColor=white" /></a>
  <a href="https://www.instagram.com/nabilbachroin/"><img alt="Instagram" src="https://img.shields.io/badge/-nabilbachroin-bf3a96?style=flat&logo=instagram&logoColor=white" /></a>
  <a href="https://github.com/nabilbachroin"><img alt="GitHub" src="https://img.shields.io/badge/-nabilbachroin-0d1117?style=flat&logo=github" /></a>
  <a href="mailto:nabilbachroin@nabloom.id"><img alt="Email" src="https://img.shields.io/badge/-nabilbachroin@nabloom.id-c14438?style=flat&logo=maildotru&logoColor=white" /></a>
</p>

I build firmware for connected devices, with a focus on wireless input, audio codecs, and DSP optimization.
Outside embedded systems, I build web applications and automation for everyday needs, with a research background in computer vision and 3D reconstruction.

<p align="center"><a href="#selected-work">Selected Work</a> · <a href="#tech-stack">Tech Stack</a> · <a href="#activity">Activity</a></p>

## Selected Work

Professional work is described by technology. Personal projects and family websites remain unlinked.

<!-- PROJECTS:START -->
<p align="center">
  <picture>
    <source media="(max-width: 600px) and (prefers-color-scheme: dark)" srcset="./metrics/projects-emb-mobile-dark.svg?v=d6f138417ab9" />
    <source media="(max-width: 600px)" srcset="./metrics/projects-emb-mobile.svg?v=b7578629077d" />
    <source media="(prefers-color-scheme: dark)" srcset="./metrics/projects-emb-dark.svg?v=f71c6e56599a" />
    <img alt="Embedded &amp; Firmware" src="./metrics/projects-emb.svg?v=a366153cb858" width="880" />
  </picture>
</p>

<p align="center">
  <picture>
    <source media="(max-width: 600px) and (prefers-color-scheme: dark)" srcset="./metrics/projects-web-mobile-dark.svg?v=136213f1d99a" />
    <source media="(max-width: 600px)" srcset="./metrics/projects-web-mobile.svg?v=d3bf1e1ec3c7" />
    <source media="(prefers-color-scheme: dark)" srcset="./metrics/projects-web-dark.svg?v=a16db0e17878" />
    <img alt="Web &amp; Automation" src="./metrics/projects-web.svg?v=47a294c4e56c" width="880" />
  </picture>
</p>

<p align="center">
  <picture>
    <source media="(max-width: 600px) and (prefers-color-scheme: dark)" srcset="./metrics/projects-ml-mobile-dark.svg?v=79e1f4b4ae46" />
    <source media="(max-width: 600px)" srcset="./metrics/projects-ml-mobile.svg?v=8174ebb3c90b" />
    <source media="(prefers-color-scheme: dark)" srcset="./metrics/projects-ml-dark.svg?v=5ea88b2bf5c1" />
    <img alt="Machine Learning &amp; Research" src="./metrics/projects-ml.svg?v=530b9f8a8438" width="880" />
  </picture>
</p>

Repository commits include all authors on the default branch. Grouped projects sum their repository histories; counts are not a measure of individual output.
<details>
<summary>Project descriptions</summary>

#### Embedded & Firmware

| Project | Focus | Stack |
|---|---|---|
| Licensed game controller firmware | USB XInput, BLE HID, dual-mode pairing and USB audio on a single device | C, BLE, USB HID |
| Ultra-low-latency wireless HID & audio | The latency-critical path for wireless input and audio: radio scheduling, buffering and latency analysis | C, BLE, RTOS |
| Audio codec DSP development | Opus and LC3 codec development on a resource-constrained DSP core, optimised at the cycle level | C, Assembly, DSP |
| Wireless ESL / EPD display | Firmware for battery-powered electronic shelf labels driving e-paper panels over a wireless link | C, e-paper, BLE |

#### Web & Automation

| Project | Focus | Stack |
|---|---|---|
| Tempong Order Hub & n8n-warung | Order management for a small food business, wired to automated workflows for orders, notifications and reporting | FastAPI, Python, React, PostgreSQL, n8n |
| family-finance | Household budgeting and finance tracker | Fastify, TypeScript, Prisma, PostgreSQL |
| RTRS - Remote Timer Rental System | Session timers for a children's toy rental business that survive interruption and recover mid-session | React, TypeScript, Express, PostgreSQL, Docker |
| The Birth of Bilboo | Birth announcement site for my child, containerised and self-hosted | Laravel 11, PHP 8.3, Docker |
| Netflix-style wedding invitation | Our wedding invitation built as a streaming-service browse page, complete with title cards | Nuxt 3, Vue |

#### Machine Learning & Research

| Project | Focus | Stack |
|---|---|---|
| clusterCraft | A finite state machine for cluster coordination | Python |
| Baby cry classification | Classifies why an infant is crying - belly pain, hunger, discomfort, tiredness - from audio converted to spectrograms | Python, Jupyter |
| VE3DOR | NeRF-based 3D reconstruction experiments evaluated with IoU and Chamfer Distance | Python, Jupyter, nerfstudio |

</details>
<!-- PROJECTS:END -->

## Tech Stack

**Embedded, RTOS & Protocols**

![FreeRTOS](https://img.shields.io/badge/FreeRTOS-00979D?style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0ibm9uZSIgc3Ryb2tlPSIjZmZmIiBzdHJva2Utd2lkdGg9IjIuNCIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBkPSJNMTkuNSAxMy41QTggOCAwIDEgMSAxNiA1LjgiLz48cGF0aCBmaWxsPSIjZmZmIiBkPSJNMjEuNCAzLjJsLjYgNi4yLTYtMS41eiIvPjxjaXJjbGUgY3g9IjEyIiBjeT0iMTIiIHI9IjIuNiIgZmlsbD0iI2ZmZiIvPjwvc3ZnPg==&logoColor=white)
![Zephyr RTOS](https://img.shields.io/badge/Zephyr%20RTOS-009C82?style=for-the-badge&logo=linuxfoundation&logoColor=white)
![Keil MDK](https://img.shields.io/badge/Keil%20MDK-D9820D?style=for-the-badge&logo=arm&logoColor=white)
![Bluetooth LE](https://img.shields.io/badge/Bluetooth%20LE-0082FC?style=for-the-badge&logo=bluetooth&logoColor=white)
![USB HID / XInput](https://img.shields.io/badge/USB%20HID%20%2F%20XInput-2C5282?style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0ibm9uZSIgc3Ryb2tlPSIjZmZmIiBzdHJva2Utd2lkdGg9IjEuOSIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBkPSJNNSAxMmgxM00xMC41IDEybDMuNS00LjZNMTMuNSAxMmwtMy41IDQuNiIvPjxjaXJjbGUgY3g9IjQuNCIgY3k9IjEyIiByPSIyLjQiIGZpbGw9IiNmZmYiLz48cGF0aCBmaWxsPSIjZmZmIiBkPSJNMTcuNiA4LjloMy40djMuNGgtMy40eiIvPjxjaXJjbGUgY3g9IjkuNiIgY3k9IjE3LjQiIHI9IjIuMiIgZmlsbD0iI2ZmZiIvPjxwYXRoIGZpbGw9IiNmZmYiIGQ9Ik0xOC40IDkuMmw0LjQgMi44LTQuNCAyLjh6Ii8+PC9zdmc+&logoColor=white)
![Opus & LC3](https://img.shields.io/badge/Opus%20%26%20LC3-7B2CBF?style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PGcgZmlsbD0iI2ZmZiI+PHJlY3QgeD0iMi40IiB5PSI5IiB3aWR0aD0iMi44IiBoZWlnaHQ9IjYiIHJ4PSIxLjQiLz48cmVjdCB4PSI3LjIiIHk9IjQuNSIgd2lkdGg9IjIuOCIgaGVpZ2h0PSIxNSIgcng9IjEuNCIvPjxyZWN0IHg9IjEyIiB5PSI3IiB3aWR0aD0iMi44IiBoZWlnaHQ9IjEwIiByeD0iMS40Ii8+PHJlY3QgeD0iMTYuOCIgeT0iMi44IiB3aWR0aD0iMi44IiBoZWlnaHQ9IjE4LjQiIHJ4PSIxLjQiLz48L2c+PC9zdmc+&logoColor=white)
![DSP Optimisation](https://img.shields.io/badge/DSP%20Optimisation-9333EA?style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0ibm9uZSIgc3Ryb2tlPSIjZmZmIiBzdHJva2Utd2lkdGg9IjIiIHN0cm9rZS1saW5lY2FwPSJyb3VuZCIgZD0iTTEuNSAxMmMyLjYtNy40IDUuMi03LjQgNy44IDBzNS4yIDcuNCA3LjggMCAzLjktNC42IDUuNC0zLjQiLz48ZyBmaWxsPSIjZmZmIj48Y2lyY2xlIGN4PSI1LjQiIGN5PSI2LjQiIHI9IjEuNyIvPjxjaXJjbGUgY3g9IjEyLjkiIGN5PSIxNy42IiByPSIxLjciLz48Y2lyY2xlIGN4PSIyMC40IiBjeT0iOC45IiByPSIxLjciLz48L2c+PC9zdmc+&logoColor=white)

**Languages**

<p>
  <picture><source media="(prefers-color-scheme: dark)" srcset="./assets/icons/c-dark.svg" /><img src="./assets/icons/c-light.svg" alt="C" title="C" width="42" height="42" /></picture>
  <picture><source media="(prefers-color-scheme: dark)" srcset="./assets/icons/cpp-dark.svg" /><img src="./assets/icons/cpp-light.svg" alt="C++" title="C++" width="42" height="42" /></picture>
  <picture><source media="(prefers-color-scheme: dark)" srcset="./assets/icons/python-dark.svg" /><img src="./assets/icons/python-light.svg" alt="Python" title="Python" width="42" height="42" /></picture>
  <picture><source media="(prefers-color-scheme: dark)" srcset="./assets/icons/ts-dark.svg" /><img src="./assets/icons/ts-light.svg" alt="TypeScript" title="TypeScript" width="42" height="42" /></picture>
  <picture><source media="(prefers-color-scheme: dark)" srcset="./assets/icons/js-dark.svg" /><img src="./assets/icons/js-light.svg" alt="JavaScript" title="JavaScript" width="42" height="42" /></picture>
  <picture><source media="(prefers-color-scheme: dark)" srcset="./assets/icons/php-dark.svg" /><img src="./assets/icons/php-light.svg" alt="PHP" title="PHP" width="42" height="42" /></picture>
</p>

**Frameworks & Runtimes**

<p>
  <picture><source media="(prefers-color-scheme: dark)" srcset="./assets/icons/nodejs-dark.svg" /><img src="./assets/icons/nodejs-light.svg" alt="Node.js" title="Node.js" width="42" height="42" /></picture>
  <picture><source media="(prefers-color-scheme: dark)" srcset="./assets/icons/express-dark.svg" /><img src="./assets/icons/express-light.svg" alt="Express" title="Express" width="42" height="42" /></picture>
  <picture><source media="(prefers-color-scheme: dark)" srcset="./assets/icons/fastapi-dark.svg" /><img src="./assets/icons/fastapi-light.svg" alt="FastAPI" title="FastAPI" width="42" height="42" /></picture>
  <picture><source media="(prefers-color-scheme: dark)" srcset="./assets/icons/laravel-dark.svg" /><img src="./assets/icons/laravel-light.svg" alt="Laravel" title="Laravel" width="42" height="42" /></picture>
  <picture><source media="(prefers-color-scheme: dark)" srcset="./assets/icons/react-dark.svg" /><img src="./assets/icons/react-light.svg" alt="React" title="React" width="42" height="42" /></picture>
  <picture><source media="(prefers-color-scheme: dark)" srcset="./assets/icons/vue-dark.svg" /><img src="./assets/icons/vue-light.svg" alt="Vue" title="Vue" width="42" height="42" /></picture>
  <picture><source media="(prefers-color-scheme: dark)" srcset="./assets/icons/nuxtjs-dark.svg" /><img src="./assets/icons/nuxtjs-light.svg" alt="Nuxt" title="Nuxt" width="42" height="42" /></picture>
  <picture><source media="(prefers-color-scheme: dark)" srcset="./assets/icons/vite-dark.svg" /><img src="./assets/icons/vite-light.svg" alt="Vite" title="Vite" width="42" height="42" /></picture>
</p>

**Database & ORM**

<p>
  <picture><source media="(prefers-color-scheme: dark)" srcset="./assets/icons/postgres-dark.svg" /><img src="./assets/icons/postgres-light.svg" alt="PostgreSQL" title="PostgreSQL" width="42" height="42" /></picture>
  <picture><source media="(prefers-color-scheme: dark)" srcset="./assets/icons/prisma-dark.svg" /><img src="./assets/icons/prisma-light.svg" alt="Prisma" title="Prisma" width="42" height="42" /></picture>
</p>

**Tools**

<p>
  <picture><source media="(prefers-color-scheme: dark)" srcset="./assets/icons/git-dark.svg" /><img src="./assets/icons/git-light.svg" alt="Git" title="Git" width="42" height="42" /></picture>
  <picture><source media="(prefers-color-scheme: dark)" srcset="./assets/icons/github-dark.svg" /><img src="./assets/icons/github-light.svg" alt="GitHub" title="GitHub" width="42" height="42" /></picture>
  <picture><source media="(prefers-color-scheme: dark)" srcset="./assets/icons/gitlab-dark.svg" /><img src="./assets/icons/gitlab-light.svg" alt="GitLab" title="GitLab" width="42" height="42" /></picture>
  <picture><source media="(prefers-color-scheme: dark)" srcset="./assets/icons/vscode-dark.svg" /><img src="./assets/icons/vscode-light.svg" alt="VS Code" title="VS Code" width="42" height="42" /></picture>
  <picture><source media="(prefers-color-scheme: dark)" srcset="./assets/icons/docker-dark.svg" /><img src="./assets/icons/docker-light.svg" alt="Docker" title="Docker" width="42" height="42" /></picture>
  <picture><source media="(prefers-color-scheme: dark)" srcset="./assets/icons/postman-dark.svg" /><img src="./assets/icons/postman-light.svg" alt="Postman" title="Postman" width="42" height="42" /></picture>
  <picture><source media="(prefers-color-scheme: dark)" srcset="./assets/icons/linux-dark.svg" /><img src="./assets/icons/linux-light.svg" alt="Linux" title="Linux" width="42" height="42" /></picture>
  <picture><source media="(prefers-color-scheme: dark)" srcset="./assets/icons/bash-dark.svg" /><img src="./assets/icons/bash-light.svg" alt="Bash" title="Bash" width="42" height="42" /></picture>
  <picture><source media="(prefers-color-scheme: dark)" srcset="./assets/icons/cmake-dark.svg" /><img src="./assets/icons/cmake-light.svg" alt="CMake" title="CMake" width="42" height="42" /></picture>
</p>

## Activity

<!-- LANGUAGES:START -->
<p align="center">
  <picture>
    <source media="(max-width: 600px) and (prefers-color-scheme: dark)" srcset="./metrics/languages-mobile-dark.svg?v=bc93de03a5e5" />
    <source media="(max-width: 600px)" srcset="./metrics/languages-mobile.svg?v=c27d25c305f7" />
    <source media="(prefers-color-scheme: dark)" srcset="./metrics/languages-dark.svg?v=f17ce6a298d0" />
    <img alt="Repository language mix" src="./metrics/languages.svg?v=0c08f8cd3d9e" width="880" />
  </picture>
</p>
<!-- LANGUAGES:END -->

<details>
<summary>Contribution calendar and GitHub overview</summary>

<p align="center"><img alt="GitHub overview and isometric contribution calendar" src="./metrics/overview.svg" width="480" /></p>

</details>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/nabilbachroin/nabilbachroin/output/snake-dark.svg" />
    <img alt="Animated contribution graph" src="https://raw.githubusercontent.com/nabilbachroin/nabilbachroin/output/snake.svg" width="880" />
  </picture>
</p>

<sub>Project metrics refresh automatically. Skill icons by <a href="https://github.com/tandpfun/skill-icons">Skill Icons</a>.</sub>
