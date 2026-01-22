<p align="center">
<img src="https://www.google.com/search?q=https://img.shields.io/badge/Turkcell-CodeNight-blue%3Fstyle%3Dfor-the-badge%26logo%3Dturkcell" alt="Turkcell CodeNight" />
<img src="https://www.google.com/search?q=https://img.shields.io/badge/Status-Active-success%3Fstyle%3Dfor-the-badge" alt="Status" />
<img src="https://www.google.com/search?q=https://img.shields.io/badge/License-Turkcell-orange%3Fstyle%3Dfor-the-badge" alt="License" />
</p>

<h1 align="center">🛡️ TrustShield</h1>

<p align="center">
<strong>Modern Fraud Detection and Risk Management Platform for Turkcell Ecosystem</strong>
<br />
<i>Comprehensive Security for Paycell • BiP • Superonline • TV+</i>
</p>

📸 Screenshots

🖥️ Main Dashboard

<p align="center">
<img src="docs/screenshots/dashboard.png" width="100%" alt="Main Dashboard View" />
</p>

🔍 Case Management & Audit Logs

<p align="center">
<img src="docs/screenshots/fraud_cases.png" width="48%" alt="Fraud Cases" />
<img src="docs/screenshots/decisions.png" width="48%" alt="Decision Logs" />
</p>

🎯 Project Overview

TrustShield is a high-performance security engine designed to detect and prevent fraudulent activities across Turkcell's digital services in real-time. By combining Rule-Based Risk Assessment with an intuitive Case Management System, it empowers security teams to mitigate risks before they escalate.

✨ Key Features

📊 Advanced Monitoring

Real-time Analytics: Instant tracking of events, open cases, and high-risk user profiles.

Dynamic Risk Scoring: Visual risk indicators (0-100) with color-coded severity levels.

Live Updates: High-performance data fetching with manual and auto-refresh options.

🛡️ Fraud & Risk Management

Smart Workflows: Complete lifecycle management from OPEN to CLOSED.

Custom Rule Engine: Full CRUD support for creating complex risk rules on the fly.

Action Triggers: Automated responses including FORCE_2FA, TEMPORARY_BLOCK, and ANOMALY_ALERT.

🏗️ Tech Stack

<table>
<thead>
<tr>
<th width="150">Layer</th>
<th width="300">Technology</th>
<th>Key Highlights</th>
</tr>
</thead>
<tbody>
<tr>
<td><b>Backend</b></td>
<td>
<img src="https://www.google.com/search?q=https://img.shields.io/badge/Spring_Boot-3.x-6DB33F%3Fstyle%3Dflat-square%26logo%3Dspring-boot%26logoColor%3Dwhite" />
<img src="https://www.google.com/search?q=https://img.shields.io/badge/Java-17%2B-ED8B00%3Fstyle%3Dflat-square%26logo%3Dopenjdk%26logoColor%3Dwhite" />
</td>
<td>Robust RESTful API with optimized JPA queries.</td>
</tr>
<tr>
<td><b>Frontend</b></td>
<td>
<img src="https://www.google.com/search?q=https://img.shields.io/badge/React-18-61DAFB%3Fstyle%3Dflat-square%26logo%3Dreact%26logoColor%3Dblack" />
<img src="https://www.google.com/search?q=https://img.shields.io/badge/Vite-5.x-646CFF%3Fstyle%3Dflat-square%26logo%3Dvite%26logoColor%3Dwhite" />
</td>
<td>Fast, component-based SPA using modern Context API.</td>
</tr>
<tr>
<td><b>Styling</b></td>
<td>
<img src="https://www.google.com/search?q=https://img.shields.io/badge/Tailwind_CSS-3.4-38B2AC%3Fstyle%3Dflat-square%26logo%3Dtailwind-css%26logoColor%3Dwhite" />
</td>
<td>Fully responsive UI with custom Turkcell color palette.</td>
</tr>
<tr>
<td><b>Infrastructure</b></td>
<td>
<img src="https://www.google.com/search?q=https://img.shields.io/badge/Docker-Enabled-2496ED%3Fstyle%3Dflat-square%26logo%3Ddocker%26logoColor%3Dwhite" />
</td>
<td>Containerized environment for seamless deployment.</td>
</tr>
<tr>
<td><b>Management</b></td>
<td>
<img src="https://www.google.com/search?q=https://img.shields.io/badge/Maven-Project-C71A36%3Fstyle%3Dflat-square%26logo%3Dapache-maven%26logoColor%3Dwhite" />
</td>
<td>Automated build and dependency management.</td>
</tr>
</tbody>
</table>

🚀 Installation & Deployment

🐳 Docker (Production Mode)

The easiest way to get TrustShield up and running is using Docker Compose:

docker-compose up --build


Frontend Access: http://localhost:5173

Backend API: http://localhost:8080

🛠️ Developer Setup

<details>
<summary><b>Backend Setup (Spring Boot)</b></summary>

cd backend
./mvnw clean install
./mvnw spring-boot:run


</details>

<details>
<summary><b>Frontend Setup (React + Vite)</b></summary>

cd frontend
npm install
npm run dev


</details>

📂 Project Directory Structure

.
├── 🐳 docker-compose.yml   # Multi-container orchestration
├── 📂 backend/             # Spring Boot Service (Java 17+)
├── 📂 frontend/            # React & Tailwind UI
└── 📂 docs/                # System Documentation
    └── 🖼️ screenshots/     # dashboard.png, fraud_cases.png, decisions.png


👥 Project Details

Etkinlik / Event: Turkcell CodeNight 2026 Hackathon

Geliştirme Süresi / Duration: ~3 Hours

Kapsam / Scope: End-to-end Fraud Management Solution

<p align="center">
<i>Protect your future, not just your data, with TrustShield.</i> 🛡️
<br />
<strong>© 2026 Turkcell CodeNight Project</strong>
</p>