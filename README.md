# Systems and Site Reliability Engineer
An infrastructure-focused Software Engineer with **6+ years of professional experience** building highly reliable software. I specialize in the intersection of low-level execution, data integrity, service reliability and infrastructure lifecycle management.

## My Engineering Philosophy:
> - **Treat infrastructure as code.**
> - **Design data flows for strict determinism.**
> - **Architect software to be observable, highly available and secure.**
> - **Prove your systems have these qualities with complete and robust tests.**

This repository serves as an interactive technical appendix to my CV.
Instead of showcasing generic boilerplate applications, these projects isolate and solve complex, real-world challenges.

----

## 🏗️ Core Technologies

| Domain | Technologies & Tooling |
| :---- | :---- |
| **Languages** | ![C++](https://img.shields.io/badge/C%2B%2B-blue.svg?&logo=c%2B%2B&logoColor=white),  ![Go](https://img.shields.io/badge/Go-%2300ADD8.svg?&logo=go&logoColor=white),  ![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=fff), ![Bash](https://img.shields.io/badge/Bash-4EAA25?logo=gnubash&logoColor=fff) | 
| **Infrastructure & SRE** | ![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=fff),  ![Vault](https://img.shields.io/badge/Vault-FFCF25?logo=vault&logoColor=fff),  ![Alpine Linux](https://img.shields.io/badge/Alpine%20Linux-0D597F?logo=alpinelinux&logoColor=fff), ![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?logo=ubuntu&logoColor=white), ![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?logo=kubernetes&logoColor=white), ![Postgres](https://img.shields.io/badge/Postgres-%23316192.svg?logo=postgresql&logoColor=white), ![Redis](https://img.shields.io/badge/Redis-%23DD0031.svg?logo=redis&logoColor=white) |
| **Frameworks & Tools** | ![FastAPI](https://img.shields.io/badge/FastAPI-009485.svg?logo=fastapi&logoColor=white), ![LLVM](https://img.shields.io/badge/LLVM-black?logo=llvm&logoColor=white), ![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=fff), ![NumPy](https://img.shields.io/badge/NumPy-4DABCF?logo=numpy&logoColor=fff), ![Matplotlib](https://custom-icon-badges.demolab.com/badge/Matplotlib-71D291?logo=matplotlib&logoColor=fff), ![Pandas](https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=fff)  | 


----

## 🛠️ Current Projects

### [Remediation Watchdog [Work in Progress]](https://github.com/scholar-of-artifice/remediation-watchdog)

| Concept | Description |
| :---- | :---- |
| **Target** | ![SRE](https://img.shields.io/badge/SRE-B8F5BE?style=flat-square), ![Infrastructure](https://img.shields.io/badge/Infrastructure-CAF5B8?style=flat-square), ![Orchestration](https://img.shields.io/badge/Orchestration-E3F5B8?style=flat-square) |
| **Problem** | High-throughput data pipelines experience unpredictable spikes, consumer lag, and localized bottlenecks that traditionally require manual engineering intervention and paging. |
| **Solution** | Designing an automated "Control Plane" service running in local Kubernetes that monitors distributed SLIs (Kafka consumer lag, connection health) and executes closed-loop remediation scripts to auto-heal the cluster. |

### [Polyglot Security Foundations](https://github.com/scholar-of-artifice/polyglot-security-foundations)

| Concept | Description |
| :---- | :---- |
| **Target** | ![SRE](https://img.shields.io/badge/SRE-B8F5BE?style=flat-square), ![Infrastructure](https://img.shields.io/badge/Infrastructure-CAF5B8?style=flat-square), ![Security](https://img.shields.io/badge/Security-B8F5D3?style=flat-square) |
| **Problem** | Static or long-lived certificates create a security risk as well as operational overhead in distributed system architectures. |
| **Solution** | Orchestrated an automated, Zero-Trust network infrastructure leveraging HashiCorp Vault running in Sidecars to dynamically issue and manage identities. |

### [C++ Game Dice](https://github.com/scholar-of-artifice/game-dice-cpp)
| Concept | Description |
| :---- | :---- |
| **Target** |  ![Systems Engineering](https://img.shields.io/badge/Systems%20Engineering-BDE1F5?style=flat-square), ![HPC](https://img.shields.io/badge/HPC-BCF3F5?style=flat-square) |
| **Problem** | Standard runtime RNG utilities introduce mathematical bias and (typically) require heavy heap allocations. Some break execution determinism which is required for data pipelines and desirable for game design. |
| **Solution** | Engineered a header-only **0-heap allocation C++23 compile-time engine** for weighted distributions. Rigorously tested via extensive testing, benchmarking and profiling. Heavily inspected via static and dynamic analysis tools for quality and safety. |

----

## 📡 Collaboration

I am actively looking for dedicated Site Reliability Engineering and Data Infrastructure roles where I can apply my skills.

📩 Please refer to the direct contact details provided in my CV, or feel free to connect via GitHub discussions.

<!--
**scholar-of-artifice/scholar-of-artifice** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 
- 🌱 I’m currently learning ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
