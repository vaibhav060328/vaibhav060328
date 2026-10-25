<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=180&section=header&text=Vaibhav%20Joshi&fontSize=42&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=Software%20Developer%20%E2%80%A2%20Systems%20%E2%80%A2%20AI%2FML&descAlignY=58&descSize=16" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=18&pause=1200&color=58A6FF&center=true&vCenter=true&width=600&lines=Building+systems+that+are+correct+under+load;Backend+%E2%80%A2+Databases+%E2%80%A2+Distributed+Systems;Exploring+AI%2FML+and+cloud+infrastructure" />
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/vaibhav-joshi-6b8054302/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="https://github.com/vaibhav060328"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" /></a>
  <a href="https://leetcode.com/Vaibhav2820/"><img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" /></a>
</p>

---

## 🧑‍💻 About Me

I'm a Computer Science student who enjoys understanding how systems work underneath and turning ideas into working products. Most of my recent work sits where **backend engineering meets systems programming** — job queues, process isolation, geospatial queries — with a parallel track in **deep learning**.

```yaml
focus:      [backend engineering, databases, distributed systems]
exploring:  [AI/ML, LLMs & RAG, cloud infrastructure, DevOps]
practice:   regular DSA & algorithmic problem solving
```

---

## 🚀 Featured Projects

### ⚙️ [ProcExec — Database-backed Process Execution System](https://github.com/vaibhav060328/Database-backed-Process-Execution-System)

A job execution platform where uploaded programs are queued in PostgreSQL and run by a **C++ engine** in isolated OS processes, with output streamed live to a React dashboard.

- **Exactly-once job claiming** using `FOR UPDATE SKIP LOCKED` — verified with two concurrent dispatchers on 30 queued jobs: 30 claims, zero duplicates
- **Process isolation** with per-job memory caps and timeouts; workers run with no database credentials
- **Push-based live updates** via `LISTEN/NOTIFY` → Socket.io, with crash recovery for orphaned jobs

<p>
  <img src="https://img.shields.io/badge/C++17-00599C?style=flat-square&logo=cplusplus&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white" />
  <img src="https://img.shields.io/badge/Socket.io-010101?style=flat-square&logo=socketdotio&logoColor=white" />
  <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" />
</p>

---

### 🚑 [Emergency Vehicle Dispatch System](https://github.com/vaibhav060328/Emergency-vehicle-dispatch-system)

A dispatch platform that finds the nearest available emergency unit (ambulance, fire truck, police, rescue), logs the incident, and tracks the responder en route.

- **Proximity fleet scanning** with MongoDB `2dsphere` geospatial queries
- **Real road distance and ETA** from the OSRM routing API rather than straight-line distance
- **Incident lifecycle** — active-call dashboard, fleet registry with crew and equipment, and simulated en-route tracking that updates vehicle and incident status on arrival

<p>
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white" />
  <img src="https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white" />
  <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white" />
  <img src="https://img.shields.io/badge/OSRM-7EBC6F?style=flat-square&logo=openstreetmap&logoColor=white" />
</p>

---

### 🎙️ [AI vs Human Audio Detection](https://github.com/vaibhav060328/AI-vs-Human-audio-detection)

A deep learning classifier that distinguishes **human speech from AI-generated / TTS speech**, with a CLI and a Gradio web app for file or microphone input.

- **3-channel acoustic features** — Mel spectrogram, MFCC and spectral centroid stacked into a `128×128×3` input for a CNN
- **Feature caching pipeline** with parallel pre-extraction, cutting training step time from ~6s to under 0.01s
- **Diagnostic UI** showing the verdict with confidence, waveform and per-channel feature plots

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white" />
  <img src="https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=keras&logoColor=white" />
  <img src="https://img.shields.io/badge/librosa-4D4D4D?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Gradio-F97316?style=flat-square&logo=gradio&logoColor=white" />
</p>

---

## 🛠️ Tech Stack

| Area | Tools |
|:--|:--|
| **Languages** | <img src="https://skillicons.dev/icons?i=cpp,python,js,sql" /> |
| **Backend & Web** | <img src="https://skillicons.dev/icons?i=nodejs,express,react,tailwind,vite" /> |
| **Databases** | <img src="https://skillicons.dev/icons?i=postgres,mongodb,mysql" /> |
| **AI / ML** | <img src="https://skillicons.dev/icons?i=tensorflow" /> |
| **Cloud & DevOps** | <img src="https://skillicons.dev/icons?i=aws,docker,nginx,linux,git" /> |

---

## 📊 GitHub Activity

<p align="center">
  <img height="165" src="https://github-readme-stats.shion.dev/api?username=vaibhav060328&theme=dark&hide_border=true&include_all_commits=false&count_private=false" />
  <img height="165" src="https://streak-stats.demolab.com?user=vaibhav060328&theme=dark&hide_border=true" />
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/vaibhav060328/vaibhav060328/output/github-contribution-grid-snake.svg" />
</p>

---

## 🧠 Currently Learning

<p>
  <img src="https://img.shields.io/badge/Operating%20Systems-2d333b?style=flat-square" />
  <img src="https://img.shields.io/badge/Database%20Internals-2d333b?style=flat-square" />
  <img src="https://img.shields.io/badge/Distributed%20Systems-2d333b?style=flat-square" />
  <img src="https://img.shields.io/badge/System%20Design-2d333b?style=flat-square" />
  <img src="https://img.shields.io/badge/Cloud%20Architecture-2d333b?style=flat-square" />
  <img src="https://img.shields.io/badge/Machine%20Learning-2d333b?style=flat-square" />
</p>

## 📈 What I'm Working Toward

Building stronger foundations in **software engineering and systems** while continuing to explore **AI/ML and cloud technologies** — aiming for systems that are not just functional, but **scalable, maintainable and well engineered.**

---

<p align="center">
  <i>Build. Break. Understand. Rebuild better.</i>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,50:203a43,100:0f2027&height=100&section=footer" />
</p>
