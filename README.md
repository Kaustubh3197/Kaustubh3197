<h2 align="center">Hi, I'm Kaustubh Patil 👋</h2>
<p align="center"><b>Development Engineer · Automotive Systems & Robotics · Test Automation & CI/CD</b></p>

<p align="center">
  <a href="https://kaustubh3197.github.io"><img src="https://img.shields.io/badge/Portfolio-kaustubh3197.github.io-1f7a6c?style=flat-square" alt="Portfolio"></a>
  <a href="https://www.linkedin.com/in/kaustubh-prakash-patil"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
</p>

I build the software that lets vehicles **sense, communicate and act**, and the automation that proves it keeps working.
My work spans the whole path from a vehicle's sensors to the code that acts on them: embedded control, ROS perception
pipelines, and the in-vehicle middleware that connects them, backed by automated tests and CI/CD pipelines.

### 🔭 What I focus on
- **In-vehicle communication:** comparing and benchmarking middleware (DDS, SOME/IP, Zenoh) for ADAS and software-defined vehicles
- **Perception & V2X:** ROS pipelines that turn raw sensor data into standardised, filtered, visualised information
- **Quality & delivery:** browser test automation and CI/CD pipelines that test, package and deploy software on every change

---

### 📌 Featured projects

#### 🚗 Automotive & robotics

**[Middleware Comparison for ADAS / SDV](https://github.com/Kaustubh3197/middleware-comparison-thesis)** · *Master's thesis*<br>
Scored 8 in-vehicle protocols with a multi-criteria decision analysis, then benchmarked the top three (**OpenDDS, vSomeIP, Zenoh**) on the exact same simulated ADAS setup, so any difference in results comes from the middleware alone.<br>
`C++` `Python` `OpenDDS` `SOME/IP` `Zenoh`

**[V2X CPM Perception & Visualization Pipeline](https://github.com/Kaustubh3197/v2x-cpm-perception)**<br>
ROS pipeline that filters radar detections by confidence and distance, shows cars and pedestrians live in RViz, and converts them into **ETSI ITS Collective Perception Messages** (~130 custom message definitions).<br>
`ROS` `Python` `RViz` `ETSI ITS CPM`

**[Gesture-Control & Obstacle-Avoiding Car](https://github.com/Kaustubh3197/gesture-control-obstacle-avoiding-car)**<br>
Arduino car driven by a wireless accelerometer glove over RF433, plus an autonomous ultrasonic obstacle-avoidance mode, with fixes for gesture states the original design could never reach.<br>
`Arduino` `C++` `Embedded`

#### ✅ Test automation & CI/CD

**[E2E Test Automation Framework](https://github.com/Kaustubh3197/saucedemo-test-automation)** &nbsp;[![Tests](https://github.com/Kaustubh3197/saucedemo-test-automation/actions/workflows/tests.yml/badge.svg?branch=main)](https://github.com/Kaustubh3197/saucedemo-test-automation/actions/workflows/tests.yml)<br>
16 Playwright and 5 Selenium tests for an e-commerce site (login, cart, sorting, product pages, checkout and price checks), built with the **Page Object Model** and run by GitHub Actions on Chromium, Firefox and a mobile viewport.<br>
`Python` `Playwright` `Selenium` `pytest` `GitHub Actions`

**[Task Tracker: CI/CD Pipeline with Live Deployment](https://github.com/Kaustubh3197/task-tracker-cicd)** &nbsp;[![CI/CD](https://github.com/Kaustubh3197/task-tracker-cicd/actions/workflows/ci-cd.yml/badge.svg?branch=main)](https://github.com/Kaustubh3197/task-tracker-cicd/actions/workflows/ci-cd.yml) · **[Live demo →](https://task-tracker-kaustubh.onrender.com)**<br>
Flask app shipped by a gated six-stage pipeline (lint → tests on 3 Python versions → browser tests → Docker smoke test → publish → deploy) with a post-deploy version check. Includes a production incident drill: diagnosed from logs, rolled back, then reverted.<br>
`Python` `Flask` `Docker` `GitHub Actions` `Render`

---

### 🛠️ Toolbox

| Area | Tools |
|---|---|
| **Languages** | C++ · Python |
| **Automotive & robotics** | ROS · RViz · OpenDDS · SOME/IP (vSomeIP) · Eclipse Zenoh · ETSI ITS · Arduino |
| **Testing** | pytest · Playwright · Selenium · Page Object Model |
| **CI/CD & DevOps** | GitHub Actions · Docker · GitHub Container Registry · Render · Git |

---

<p align="center">💬 Open to conversations about <b>automotive software, embedded systems, robotics</b> and <b>test automation</b> roles.</p>
