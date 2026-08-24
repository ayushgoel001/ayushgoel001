<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F2027,50:203A43,100:2C5364&height=180&section=header&text=Ayush%20Goel&fontSize=42&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=Software%20Engineering%20%7C%20Backend%20Systems%20%7C%20Applied%20AI&descAlignY=55&descSize=16" width="100%" />

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=500&size=18&duration=2500&pause=900&color=58A6FF&center=true&vCenter=true&width=720&lines=Software+Engineering+%40+IIT+Kharagpur;Backend+Systems+%7C+Algorithms+%7C+Applied+AI;Building+reliable%2C+measurable+and+scalable+systems" alt="Typing SVG" />

<br>

<a href="https://github.com/ayushgoel001">
  <img src="https://img.shields.io/badge/GitHub-ayushgoel001-181717?style=for-the-badge&logo=github&logoColor=white" />
</a>
<a href="https://codeforces.com/profile/ayushgoel02">
  <img src="https://img.shields.io/badge/Codeforces-Expert%20%7C%201638-1F8ACB?style=for-the-badge&logo=codeforces&logoColor=white" />
</a>

<br><br>

<img src="https://komarev.com/ghpvc/?username=ayushgoel001&label=Profile%20Views&color=0e75b6&style=flat-square" />
<img src="https://img.shields.io/github/followers/ayushgoel001?label=Followers&style=flat-square&color=0e75b6" />

</div>

---

## About

I'm **Ayush Goel**, a B.Tech. (Hons.) undergraduate at **IIT Kharagpur**, pursuing a Micro-specialization in **Artificial Intelligence and Applications**.

My primary interests lie in **software engineering, backend systems, algorithms, and system design**, complemented by hands-on experience across **machine learning, computer vision, reinforcement learning, document intelligence, and robotics**.

I enjoy building systems where the engineering can be **measured** — latency, throughput, reliability, accuracy, scalability, or algorithmic performance — rather than just demonstrated.

```text
Current direction

Software Engineering  ->  Backend Systems  ->  System Design
        |
        +-------------> Algorithms / Competitive Programming
        |
        +-------------> Applied ML / Computer Vision
```

---

## Engineering Snapshot

<div align="center">

<img src="https://img.shields.io/badge/API%20Throughput-164%20RPS-2ea44f?style=for-the-badge" />
<img src="https://img.shields.io/badge/p50%20Latency-86.7%25%20Lower-2ea44f?style=for-the-badge" />
<img src="https://img.shields.io/badge/OCR%20Caching-75%C3%97%20Faster-2ea44f?style=for-the-badge" />
<img src="https://img.shields.io/badge/Codeforces-Expert%201638-1F8ACB?style=for-the-badge" />

<br>

<img src="https://img.shields.io/badge/Problems%20Solved-500%2B-8250df?style=flat-square" />
<img src="https://img.shields.io/badge/Automated%20Tests-79%2B-8250df?style=flat-square" />
<img src="https://img.shields.io/badge/PRM%20Graph-502%20Nodes-8250df?style=flat-square" />
<img src="https://img.shields.io/badge/Forecast%20Evaluation-29M%2B%20Predictions-8250df?style=flat-square" />

</div>

---

## Featured Engineering

### [ModelRoute](https://github.com/ayushgoel001/ModelRoute)

#### Resilient Multi-Provider LLM API Gateway

`FastAPI` `Redis` `PostgreSQL` `Docker` `Async I/O` `Rate Limiting`

A resilient API gateway designed around **routing, caching, fault tolerance, rate limiting, and observability** across multiple LLM providers.

* Designed **3 routing strategies** across OpenAI and Gemini adapters with bounded retries and automatic fallback
* Implemented Redis caching and **atomic Lua-based rate limiting**
* Reduced API p50 latency by **86.7%**, from **81.2 ms to 10.8 ms**
* Benchmarked **1,600 requests** across four concurrency levels
* Reached **164 RPS with zero failures**

[View Repository](https://github.com/ayushgoel001/ModelRoute)

---

### [ProctorVision](https://github.com/ayushgoel001/proctorvision)

#### Vision-Guided Proctoring Review Platform

`FastAPI` `YOLO` `MediaPipe` `Computer Vision` `CI`

A computer-vision system that converts noisy frame-level detections into **persistent, reviewable behavioral alerts**.

* Designed a **5-rule AlertEngine** with duration, grace, and cooldown controls
* Improved processing throughput by **~19%**
* Reduced average frame latency from **279.4 ms to 234.9 ms**
* Built primary-candidate tracking using **IoU, center distance, and area similarity**
* Validated the system with **79 automated tests** and GitHub Actions CI

[View Repository](https://github.com/ayushgoel001/proctorvision)

---

### [Deterministic PRM + A* Motion Planning](https://github.com/ayushgoel001/prm-astar-path-planning)

#### Sampling-Based Motion Planning & Graph Search

`SciPy` `NumPy` `KDTree` `A*` `OpenCV`

A deterministic motion-planning system combining **Probabilistic Roadmaps, spatial search, collision validation, and A***.

* Generated **502-node PRM graphs** from 500 samples
* Constructed **2,233–5,312 collision-validated edges**
* Completed roadmap searches in **1.5–19.6 ms**
* Benchmarked PRM against goal-biased RRT over **60 matched-seed runs**
* Produced **21–23% shorter successful paths** across all three benchmark maps

[View Repository](https://github.com/ayushgoel001/prm-astar-path-planning)

---

## Experience

<table>
<tr>
<td width="50%" valign="top">

### Wasserstoff

**Software Development Engineer Intern**

Built a FastAPI-based OCR/document-processing pipeline using **Tesseract, Docling, OpenCV, Docker, caching, and concurrent processing**.

**Impact**

`CER 0.481 → 0.080`

`83% reduction`

`30.1 s → 0.4 s`

`75× faster repeat extraction`

</td>

<td width="50%" valign="top">

### University of Manchester & University of Liverpool

**Undergraduate Research Intern**

Developed data and evaluation pipelines for **subseasonal weather forecasting** using ERA5/ChaosBench and ArchesWeather-S.

**Scale**

`225 Zarr stores`

`89.1M parameter model`

`0.23% parameters trained`

`29M+ predictions evaluated`

</td>
</tr>

<tr>
<td width="50%" valign="top">

### Chi SquareX Technologies

**Machine Learning Developer Intern**

Built an OpenAI Gymnasium options-trading environment and trained **PPO/A2C agents** using Stable-Baselines3.

**Backtest**

`54.05% return`

`48% win rate`

`16% max drawdown`

</td>

<td width="50%" valign="top">

### Aerial Robotics Research Group — IIT Kharagpur

**Undergraduate Researcher**

Worked across **ROS, Gazebo, MAVROS, drone simulation, computer vision, and autonomous-system tooling**.

Focused on algorithmic perception and simulated aerial navigation.

</td>
</tr>
</table>

---

## Technical Toolkit

<div align="center">

<img src="https://skillicons.dev/icons?i=cpp,c,python,js,nodejs,express,fastapi,postgres,redis,mongodb,docker,git,github,linux,vscode&perline=8" />

</div>

### Languages

<p>
<img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white" />
<img src="https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black" />
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/SQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" />
</p>

### Backend & Databases

<p>
<img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
<img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" />
<img src="https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white" />
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
<img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" />
<img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white" />
</p>

### Machine Learning & Computer Vision

<p>
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" />
<img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white" />
<img src="https://img.shields.io/badge/YOLO-111F68?style=flat-square" />
<img src="https://img.shields.io/badge/MediaPipe-0097A7?style=flat-square" />
<img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white" />
<img src="https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white" />
<img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black" />
</p>

### Engineering & Tooling

<p>
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
<img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" />
<img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" />
<img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" />
<img src="https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white" />
<img src="https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white" />
</p>

---

## Algorithms & Competitive Programming

<div align="center">

<a href="https://codeforces.com/profile/ayushgoel02">
<img src="https://img.shields.io/badge/Codeforces-Expert-1F8ACB?style=for-the-badge&logo=codeforces&logoColor=white" />
</a>

<img src="https://img.shields.io/badge/Peak%20Rating-1638-1F8ACB?style=for-the-badge" />
<img src="https://img.shields.io/badge/Problems%20Solved-500%2B-8250DF?style=for-the-badge" />

</div>

<br>

* Global Rank **1,863** — Codeforces Round 1110
* Global Rank **2,320** — Codeforces Round 1111
* Global Rank **3,704** — Codeforces Round 1115
* **Rank 22** — Optiver Quantitative Trade-a-thon 2026
* **All-India Rank 7** — Convolve 4.0, Pan-IIT AI/ML Hackathon

---

## GitHub Activity

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=ayushgoel001&theme=github-compact&hide_border=true&area=true" width="96%" />

<br>

<img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=ayushgoel001&theme=github_dark" width="96%" />

</div>

---

## What I'm Working On

<details>
<summary><b>Software Engineering</b></summary>
<br>

Building depth in backend architecture, scalable APIs, databases, caching, asynchronous systems, reliability, and system design.

</details>

<details>
<summary><b>Algorithms & Core CS</b></summary>
<br>

Strengthening data structures and algorithms alongside operating systems, DBMS, computer networks, OOP, and low-level design.

</details>

<details>
<summary><b>Applied AI</b></summary>
<br>

Continuing practical work across computer vision, ML systems, model evaluation, document intelligence, and AI-backed software systems.

</details>

---

## Connect

<div align="center">

<a href="https://github.com/ayushgoel001">
<img src="https://img.shields.io/badge/GitHub-ayushgoel001-181717?style=for-the-badge&logo=github&logoColor=white" />
</a>

<a href="https://codeforces.com/profile/ayushgoel02">
<img src="https://img.shields.io/badge/Codeforces-ayushgoel02-1F8ACB?style=for-the-badge&logo=codeforces&logoColor=white" />
</a>

</div>

<br>

<div align="center">

**Software engineering first. Applied AI where it creates measurable value.**

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F2027,50:203A43,100:2C5364&height=110&section=footer" width="100%" />
