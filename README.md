````markdown
<h1 align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=28&duration=2800&pause=1000&color=58A6FF&center=true&vCenter=true&random=false&width=900&lines=Ayush+Goel;Software+Engineering+%40+IIT+Kharagpur;Backend+Systems+%7C+System+Design;Algorithms+%7C+Applied+AI" alt="Typing SVG" />
</h1>

<p align="center">
  <a href="https://github.com/ayushgoel001">
    <img src="https://img.shields.io/badge/GitHub-ayushgoel001-1F6FEB?style=flat-square&logo=github&logoColor=white" alt="GitHub" />
  </a>
  <a href="https://www.linkedin.com/in/ayush-goel-4b6469297/">
    <img src="https://img.shields.io/badge/LinkedIn-Ayush_Goel-1F6FEB?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="https://codeforces.com/profile/ayushgoel02">
    <img src="https://img.shields.io/badge/Codeforces-Expert-1F6FEB?style=flat-square&logo=codeforces&logoColor=white" alt="Codeforces" />
  </a>
</p>

<p align="center">
  <strong>Software engineering first. Applied AI where it creates measurable value.</strong>
</p>

---

## About Me

```cpp
struct AyushGoel {
    std::string education =
        "B.Tech. (Hons.) @ IIT Kharagpur";

    std::vector<std::string> focus = {
        "Backend Systems",
        "System Design",
        "Algorithms",
        "Applied AI"
    };

    std::vector<std::string> languages = {
        "C++", "C", "Python", "SQL", "JavaScript"
    };

    std::string principle =
        "Build systems whose performance can be measured.";
};
```

I am a **B.Tech. (Hons.) undergraduate at IIT Kharagpur**, pursuing a Micro-specialization in **Artificial Intelligence and Applications**.

My primary interests are **software engineering, backend systems, algorithms, and system design**, complemented by hands-on work across **machine learning, computer vision, document intelligence, reinforcement learning, and robotics**.

I enjoy engineering systems where improvements can be quantified through **latency, throughput, reliability, scalability, accuracy, and algorithmic performance**.

---

## Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=cpp,c,python,js,html,nodejs,express,fastapi,postgres,redis,mongodb,docker,linux,git,githubactions,pytorch,sklearn,opencv&perline=9" alt="Tech Stack" />
</p>

<p align="center">
  <strong>Backend</strong><br>
  FastAPI · Node.js · Express.js · PostgreSQL · Redis · MongoDB · REST APIs
</p>

<p align="center">
  <strong>Machine Learning & Computer Vision</strong><br>
  PyTorch · scikit-learn · OpenCV · YOLO · MediaPipe · Stable-Baselines3 · NumPy · Pandas · SciPy
</p>

<p align="center">
  <strong>Engineering & Tooling</strong><br>
  Linux · Docker Compose · GitHub Actions · Git · pytest · Postman · Jupyter · Hugging Face
</p>

---

## Featured Engineering

<p align="center">
  <a href="https://github.com/ayushgoel001/ModelRoute">
    <img width="49%" src="https://github-readme-stats-sigma-five.vercel.app/api/pin/?username=ayushgoel001&repo=ModelRoute&theme=tokyonight&hide_border=true" alt="ModelRoute" />
  </a>
  <a href="https://github.com/ayushgoel001/proctorvision">
    <img width="49%" src="https://github-readme-stats-sigma-five.vercel.app/api/pin/?username=ayushgoel001&repo=proctorvision&theme=tokyonight&hide_border=true" alt="ProctorVision" />
  </a>
</p>

<p align="center">
  <a href="https://github.com/ayushgoel001/prm-astar-path-planning">
    <img width="49%" src="https://github-readme-stats-sigma-five.vercel.app/api/pin/?username=ayushgoel001&repo=prm-astar-path-planning&theme=tokyonight&hide_border=true" alt="PRM A-Star Path Planning" />
  </a>
</p>

### ModelRoute — Resilient Multi-Provider LLM API Gateway

`FastAPI` `Redis` `PostgreSQL` `Docker` `Async I/O`

- Designed **3 routing strategies** across OpenAI and Gemini adapters with bounded retries and automatic fallback
- Implemented Redis caching and **atomic Lua-based rate limiting**
- Reduced API **p50 latency by 86.7%**, from **81.2 ms to 10.8 ms**
- Reached **164 RPS with zero failures** across a **1,600-request benchmark**

### ProctorVision — Vision-Guided Proctoring Review Platform

`FastAPI` `YOLO` `MediaPipe` `Computer Vision` `CI`

- Designed a **5-rule AlertEngine** using duration, grace, and cooldown controls
- Improved processing throughput by **~19%**
- Reduced average frame latency from **279.4 ms to 234.9 ms**
- Validated the system with **79 automated tests** and GitHub Actions CI

### Deterministic PRM + A* Motion Planning

`SciPy` `NumPy` `KDTree` `A*` `OpenCV`

- Generated **502-node PRM graphs** with **2,233–5,312 collision-validated edges**
- Completed roadmap searches in **1.5–19.6 ms**
- Benchmarked PRM against goal-biased RRT over **60 matched-seed runs**
- Produced **21–23% shorter successful paths** across all three benchmark maps

---

## Experience

<details>
<summary>
  <strong>Wasserstoff — Software Development Engineer Intern</strong>
  &nbsp;·&nbsp; OCR CER ↓83% &nbsp;·&nbsp; 75× faster repeat extraction
</summary>

<br>

Built a FastAPI-based OCR and document-processing pipeline using **Tesseract, Docling, OpenCV, Docker, caching, and concurrent processing**.

- Reduced Character Error Rate from **0.481 to 0.080**
- Improved repeat extraction from **30.1 s to 0.4 s**
- Achieved **75× faster** repeated extraction through caching

</details>

<br>

<details>
<summary>
  <strong>University of Manchester & University of Liverpool — Undergraduate Research Intern</strong>
  &nbsp;·&nbsp; 29M+ predictions evaluated
</summary>

<br>

Developed data and evaluation pipelines for **subseasonal weather forecasting** using ERA5, ChaosBench, and ArchesWeather-S.

- Worked across **225 Zarr stores**
- Evaluated an **89.1M-parameter model**
- Trained only **0.23% of model parameters**
- Evaluated **29M+ predictions**

</details>

<br>

<details>
<summary>
  <strong>Chi SquareX Technologies — Machine Learning Developer Intern</strong>
  &nbsp;·&nbsp; 54.05% backtest return
</summary>

<br>

Built an OpenAI Gymnasium options-trading environment and trained **PPO/A2C agents** using Stable-Baselines3.

- **54.05% return**
- **48% win rate**
- **16% maximum drawdown**

</details>

<br>

<details>
<summary>
  <strong>Aerial Robotics Research Group — IIT Kharagpur</strong>
  &nbsp;·&nbsp; Autonomous systems & perception
</summary>

<br>

Worked across **ROS, Gazebo, MAVROS, drone simulation, computer vision, and autonomous-system tooling**, with a focus on algorithmic perception and simulated aerial navigation.

</details>

---

## Research

> ### Curvature-Weighted Gradient Diversity: A Noise Measure for Geometry-Adaptive SGD Schedules
>
> **Muhammad Hamza, Ayush Goel**  
> Preprint · **arXiv:2606.30455** · June 2026
>
> A geometry-aware approach to characterizing optimization noise for adaptive SGD scheduling.
>
> [Read on arXiv](https://arxiv.org/abs/2606.30455)

---

## Algorithms & Competitive Programming

| | Achievement |
|---|---|
| **Codeforces** | **Expert**, max rating **1638** |
| **Problem Solving** | **500+** problems across competitive programming platforms |
| **Codeforces Round 1110** | Global Rank **1,863** |
| **Optiver Quantitative Trade-a-thon 2026** | **Rank 22** |
| **Convolve 4.0 — Pan-IIT AI/ML Hackathon** | **All-India Rank 7** |

<p align="center">
  <a href="https://codeforces.com/profile/ayushgoel02">
    <img src="https://img.shields.io/badge/View_Codeforces_Profile-ayushgoel02-1F6FEB?style=for-the-badge&logo=codeforces&logoColor=white" alt="Codeforces Profile" />
  </a>
</p>

---

## Contribution Activity

<p align="center">
  <a href="https://github.com/ayushgoel001">
    <img
      width="100%"
      src="https://github-readme-activity-graph.vercel.app/graph?username=ayushgoel001&bg_color=1a1b27&color=70a5fd&line=70a5fd&point=bf91f3&area=true&hide_border=true&custom_title=Contribution%20Activity"
      alt="Ayush Goel's GitHub Contribution Activity"
    />
  </a>
</p>

---

## Current Focus

- Designing **scalable backend systems**, APIs, caching layers, asynchronous workflows, and reliability mechanisms
- Building depth in **system design, DBMS, operating systems, computer networks, OOP, and low-level design**
- Strengthening **data structures, algorithms, and competitive programming**
- Applying **machine learning and computer vision** where they create measurable engineering value

---

## Connect

<p align="center">
  <a href="https://github.com/ayushgoel001">
    <img src="https://img.shields.io/badge/GitHub-ayushgoel001-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
  <a href="https://www.linkedin.com/in/ayush-goel-4b6469297/">
    <img src="https://img.shields.io/badge/LinkedIn-Ayush_Goel-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="https://codeforces.com/profile/ayushgoel02">
    <img src="https://img.shields.io/badge/Codeforces-ayushgoel02-1F8ACB?style=for-the-badge&logo=codeforces&logoColor=white" alt="Codeforces" />
  </a>
</p>

<p align="center">
  <strong>Software engineering first. Applied AI where it creates measurable value.</strong>
</p>

<br>

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=58A6FF&height=100&section=footer" width="100%" alt="" />
</div>
````
