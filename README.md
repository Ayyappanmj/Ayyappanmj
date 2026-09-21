<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:7dd3fc,100:0ea5e9&height=220&section=header&text=Ayyappan%20M&fontSize=60&fontColor=ffffff&animation=twinkling&fontAlignY=35&desc=Full%20Stack%20Developer&descAlignY=55&descSize=22" width="100%"/>

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&duration=3000&pause=800&color=7DD3FC&center=true&vCenter=true&width=650&lines=Full+Stack+Developer;React.js+%7C+Node.js+%7C+Flask+Developer;AI+%2F+ML+%7C+LLMs+%7C+RAG+Enthusiast;Data+Analytics+%7C+Power+BI+%7C+SQL;Building+Real-World+Projects+%F0%9F%9A%80" alt="Typing SVG" />
</a>

<br/>

<img src="https://komarev.com/ghpvc/?username=Ayyappanmj&label=Profile%20Views&color=7dd3fc&style=flat" alt="Profile Views"/>
<img src="https://img.shields.io/github/followers/Ayyappanmj?label=Followers&style=flat&color=7dd3fc" alt="Followers"/>

</div>

<br/>

## 🧭 Who I Am

```typescript
const ayyappan = {
  title: "Full Stack Developer",
  stack: {
    languages: ["Python", "Java", "C", "JavaScript", "SQL", "HTML", "CSS"],
    web: ["React.js", "Node.js", "Express.js", "Tailwind CSS", "Flask", "Django (Basics)", "REST APIs"],
    aiMl: ["Linear Regression", "Scikit-learn", "TensorFlow", "LLMs", "NLP", "RAG Frameworks", "Computer Vision"],
    dataAnalytics: ["MS Excel", "Power BI", "Advanced SQL", "Database Design", "Data Visualization"],
    databases: ["MySQL", "PostgreSQL", "Oracle Database", "MongoDB"],
    cloudIot: ["AWS (IoT with AWS)", "Cloud Fundamentals"],
    tools: ["Git", "GitHub", "Docker", "VS Code", "Figma", "Canva"],
  },
  launchedProjects: [
    "developer-portfolio",
    "doomscrolling-",
    "Smart-Attendance-System",
    "Sleep-detection-alarm",
    "fullstack-realchat-app",
  ],
  softSkills: ["Communication", "Time Management", "Problem Solving", "Teamwork", "Adaptability"],
  status: "Building & shipping full-stack + AI-powered projects",
  openTo: ["Full Stack Development", "AI/ML Projects", "Collaboration & Open Source"],
};
```

<br/>

## 🚀 Featured Projects

# 🚨 AI Production Incident Investigator

An AI-assisted production incident investigation platform that analyzes application logs, identifies error patterns, builds incident timelines, detects likely failure areas, and provides structured investigation recommendations.

Designed to be **free, lightweight, and suitable for low-spec laptops**, the project works without a GPU, paid AI API, Docker, or an external database.

---

## 🌐 Live Demo

🚀 **Try the deployed application:**

### [🔗 AI Production Incident Investigator — Live Demo](https://ai-production-incident-investigator.onrender.com)

> The application is deployed on Render and can be accessed directly from a web browser.

### 🔗 Project Links

* 🌐 **Live Demo:** [ai-production-incident-investigator.onrender.com](https://ai-production-incident-investigator.onrender.com)
* 💻 **GitHub Repository:** [github.com/Ayyappanmj/ai-production-incident-investigator](https://github.com/Ayyappanmj/ai-production-incident-investigator)

---

## 📌 Project Overview

Production incidents can generate hundreds or thousands of log entries. During an incident, engineers need to quickly understand:

* What went wrong?
* When did the problem start?
* What errors occurred repeatedly?
* Which system component is most likely involved?
* What should be investigated next?

The **AI Production Incident Investigator** provides an automated first-pass investigation of production logs.

It analyzes supplied logs and produces a structured incident investigation containing:

* 🔴 Incident severity
* 🔎 Likely failure area
* 📊 Error and warning counts
* 🔁 Repeated error patterns
* 🕒 Incident timeline
* 🧩 Root-cause signals
* 📌 Supporting evidence
* 🛠️ Recommended investigation steps
* 📈 Confidence score
* ⚠️ Analysis limitations

The application is designed as an **incident investigation assistant**, not an autonomous production-management system.

---

# ✨ Features

## 🔍 1. Production Log Analysis

Users can either:

* Paste logs directly into the application
* Upload `.log` files
* Upload `.txt` files

The analyzer processes the supplied log content and identifies important incident signals.

---

## 🚨 2. Incident Severity Detection

The system evaluates the number and type of detected events and provides a simple severity classification.

Example:

```text
SEV-1 / HIGH
SEV-2 / MEDIUM
SEV-3 / LOW
NO INCIDENT SIGNAL
```

Severity is based on the supplied logs and should not be treated as an official organizational incident classification.

---

## 🧠 3. Likely Failure Area Detection

The analyzer looks for patterns associated with common production problems.

Supported areas include:

```text
Database
Memory
Latency
Dependency
Authentication
Disk / Storage
Deployment
Network
```

Example:

```text
ERROR database connection refused
ERROR database connection refused
CRITICAL database connection refused
```

The system can identify **database** as a strong incident signal.

---

## 🔁 4. Repeated Error Detection

Repeated errors are normalized and grouped together.

For example:

```text
ERROR request failed id=1001
ERROR request failed id=1002
ERROR request failed id=1003
```

can be grouped as a recurring error pattern.

This makes high-frequency failures easier to investigate.

---

## 🕒 5. Incident Timeline

Important events are extracted into a timeline.

The dashboard displays:

```text
INFO
 ↓
WARN
 ↓
ERROR
 ↓
ERROR
 ↓
CRITICAL
```

This helps engineers understand the sequence of events surrounding the incident.

---

## 🎯 6. First Major Error

The application identifies the first detected:

```text
ERROR
CRITICAL
FATAL
```

event.

This provides a useful starting point for manual investigation.

---

## 📊 7. Confidence Score

The system calculates a lightweight confidence indicator based on the distribution of detected incident signals.

Example:

```text
Likely Area: Database
Confidence: 72%
```

The confidence value represents the strength of the detected pattern, **not the probability that the identified issue is definitely the root cause**.

---

## 🛠️ 8. Investigation Recommendations

Based on detected signals, the application suggests investigation steps.

For example, for a database-related incident:

```text
Check database connection pool saturation.

Check database CPU, connections, locks,
and slow queries.

Compare the incident start time with
recent schema/query changes.
```

---

## ⚠️ 9. Investigation Limitations

The system explicitly communicates that log-based signals are not proof of root cause.

For real incidents, engineers should correlate:

```text
Logs
 +
Metrics
 +
Traces
 +
Deployments
 +
Infrastructure Events
 +
Service Dependencies
```

---

# 🏗️ Architecture

```text
                    ┌─────────────────────────┐
                    │       Web Browser       │
                    │                         │
                    │  HTML + CSS + JavaScript│
                    └────────────┬────────────┘
                                 │
                                 ▼
                    ┌─────────────────────────┐
                    │        FastAPI          │
                    │       REST API          │
                    └────────────┬────────────┘
                                 │
                                 ▼
                    ┌─────────────────────────┐
                    │    Incident Analyzer    │
                    ├─────────────────────────┤
                    │                         │
                    │  Log Parser             │
                    │  Error Detection        │
                    │  Error Grouping         │
                    │  Severity Analysis      │
                    │  Signal Detection       │
                    │  Timeline Builder       │
                    │  Evidence Extraction    │
                    │  Recommendations        │
                    │  Confidence Calculation │
                    │                         │
                    └────────────┬────────────┘
                                 │
                                 ▼
                    ┌─────────────────────────┐
                    │ Investigation Dashboard │
                    │                         │
                    │ Severity                │
                    │ Root-Cause Signals      │
                    │ Errors                  │
                    │ Timeline                │
                    │ Recommendations         │
                    └─────────────────────────┘
```

---

# 🛠️ Technology Stack

| Layer                | Technology                    |
| -------------------- | ----------------------------- |
| Programming Language | Python                        |
| Backend              | FastAPI                       |
| ASGI Server          | Uvicorn                       |
| Frontend             | HTML5                         |
| Styling              | CSS3                          |
| Frontend Logic       | JavaScript                    |
| Log Analysis         | Python                        |
| API                  | REST                          |
| Database             | Not required                  |
| AI Model             | Not required for base version |
| GPU                  | Not required                  |
| Cloud API            | Not required                  |
| Deployment           | Render                        |
| Source Control       | Git + GitHub                  |

---

# 📁 Project Structure

```text
ai-production-incident-investigator/
│
├── app/
│   ├── __init__.py
│   │
│   ├── main.py
│   │
│   ├── analyzer.py
│   │
│   └── static/
│       ├── index.html
│       ├── app.js
│       ├── style.css
│       └── sample.log
│
├── PROJECT_BUILD_PROMPT.md
├── README.md
├── requirements.txt
├── run.py
└── .gitignore
```

---

# ⚙️ How It Works

The investigation pipeline follows these steps:

```text
1. User provides production logs
              ↓
2. Logs are parsed
              ↓
3. Log levels are identified
              ↓
4. Errors and warnings are extracted
              ↓
5. Similar errors are grouped
              ↓
6. Incident signals are detected
              ↓
7. Severity is calculated
              ↓
8. Timeline is generated
              ↓
9. Investigation recommendations are generated
              ↓
10. Results are displayed in the dashboard
```

---

# 💻 Run Locally

## Requirements

You need:

* Windows / Linux / macOS
* Python 3.10+
* Internet connection for initial dependency installation

No GPU is required.

---

## 1. Clone the Repository

```bash
git clone https://github.com/Ayyappanmj/ai-production-incident-investigator.git
```

---

## 2. Enter the Project

```bash
cd ai-production-incident-investigator
```

---

## 3. Create a Virtual Environment

### Windows

```bash
python -m venv .venv
```

### Linux / macOS

```bash
python3 -m venv .venv
```

---

## 4. Activate the Virtual Environment

### Windows

```bash
.venv\Scripts\activate
```

### Linux / macOS

```bash
source .venv/bin/activate
```

---

## 5. Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 6. Start the Application

```bash
python run.py
```

You should see the FastAPI/Uvicorn server start.

---

## 7. Open the Application

Open:

```text
http://127.0.0.1:8000
```

---

# 🧪 Testing the Application

The project includes a sample incident log:

```text
app/static/sample.log
```

You can test the application by clicking:

```text
Load Sample
       ↓
Investigate Incident
```

The dashboard should display the detected incident information.

---

# 📝 Example Input

You can also paste:

```text
2026-09-21 10:00:01 INFO api Starting application
2026-09-21 10:01:05 INFO api Traffic increased
2026-09-21 10:02:10 WARN api Database connection pool 95%
2026-09-21 10:02:15 ERROR api database connection refused
2026-09-21 10:02:16 ERROR api database connection refused
2026-09-21 10:02:17 ERROR api database connection refused
2026-09-21 10:02:20 ERROR api request timeout /orders
2026-09-21 10:02:21 ERROR api request timeout /orders
2026-09-21 10:02:30 CRITICAL api database connection refused
```

Click:

```text
Investigate Incident
```

The application should identify database-related signals and display the incident timeline.

---

# 📊 Example Output

A typical investigation can contain:

```text
Severity
SEV-1 / HIGH

Likely Area
Database

Confidence
High signal confidence

Error Count
6+
```

Along with:

```text
Likely Root-Cause Signals
──────────────────────────
Database
Latency
Dependency
```

And recommended investigation steps.

---

# 🌐 Deployment

The current application is deployed using **Render**.

### Live Application

🚀 **[Open AI Production Incident Investigator](https://ai-production-incident-investigator.onrender.com)**

---

## Render Configuration

Build command:

```bash
pip install -r requirements.txt
```

Start command:

```bash
uvicorn app.main:app --host 0.0.0.0 --port $PORT
```

The application does not require:

* GPU
* Docker
* Kubernetes
* External database
* Paid AI API

for the current version.

---

# 🔐 Security Considerations

Production logs can contain sensitive information.

**Do not upload real production logs containing:**

```text
API Keys
Passwords
Access Tokens
Session Cookies
Database Credentials
Personal Information
Customer Data
Private Infrastructure Information
```

Use anonymized logs when demonstrating the project publicly.

The application is designed as an analysis tool and does not automatically:

```text
❌ Restart services
❌ Execute shell commands
❌ Execute SQL
❌ Delete files
❌ Modify infrastructure
❌ Perform production rollback
```

---

# ⚠️ Limitations

The current version is a lightweight incident-analysis system.

It does **not** have complete observability across:

```text
Application Logs
Infrastructure Metrics
Distributed Traces
Cloud Events
Deployment Systems
Service Meshes
```

Therefore, the detected "likely area" should be treated as an **investigation signal**, not a confirmed root cause.

---

# 🚀 Future Roadmap

## Phase 1 — Current

* [x] Log upload
* [x] Log parsing
* [x] Error detection
* [x] Warning detection
* [x] Severity analysis
* [x] Error grouping
* [x] Timeline generation
* [x] Root-cause signals
* [x] Investigation recommendations
* [x] Web dashboard
* [x] Free deployment

---

## Phase 2 — AI Enhancement

* [ ] Local LLM integration
* [ ] Natural-language incident summaries
* [ ] RAG-based incident knowledge base
* [ ] Historical incident comparison
* [ ] Intelligent root-cause reasoning
* [ ] Automated incident report generation

---

## Phase 3 — Observability

* [ ] OpenTelemetry integration
* [ ] Prometheus metrics
* [ ] Distributed trace analysis
* [ ] Service dependency mapping
* [ ] Deployment event correlation
* [ ] Infrastructure event correlation

---

## Phase 4 — Enterprise Features

* [ ] User authentication
* [ ] Role-based access control
* [ ] Incident history
* [ ] SQLite/PostgreSQL support
* [ ] Team collaboration
* [ ] Slack integration
* [ ] Microsoft Teams integration
* [ ] Email notifications
* [ ] PDF incident reports
* [ ] Incident management dashboard

---

# 🤖 AI Roadmap

The current version intentionally uses a lightweight analysis engine so that it can run on low-spec hardware.

A future version can add a local LLM architecture:

```text
Production Logs
       ↓
Log Parser
       ↓
Error Clustering
       ↓
Incident Context
       ↓
Local LLM
       ↓
RAG Knowledge Base
       ↓
Root-Cause Analysis
       ↓
Incident Report
```

Possible future local AI technologies include:

```text
Ollama
Local LLMs
Embeddings
Vector Database
RAG
```

These are optional and are not required for the current application.

---

# 🎯 Skills Demonstrated

This project demonstrates practical experience with:

* Python
* FastAPI
* REST API development
* JavaScript
* HTML/CSS
* Log processing
* Pattern recognition
* Error classification
* Incident investigation
* SRE concepts
* DevOps concepts
* Production troubleshooting
* Git
* GitHub
* Cloud deployment
* API architecture
* Full-stack development
* AI-assisted software design

---

# 📚 Learning Objectives

This project was built to explore how software can assist engineers during production incidents.

Key concepts demonstrated:

### Site Reliability Engineering

```text
Incident Detection
      ↓
Investigation
      ↓
Evidence Collection
      ↓
Root-Cause Investigation
      ↓
Remediation
      ↓
Post-Incident Analysis
```

### Observability

```text
Logs
Metrics
Traces
   ↓
Observability
```

### Incident Investigation

```text
What happened?
       ↓
When did it happen?
       ↓
What changed?
       ↓
Which component is affected?
       ↓
What evidence supports the hypothesis?
       ↓
What should be investigated next?
```

---

# 📈 Project Status

```text
Status: Active Development

Version: 1.0

Deployment: Live

Backend: FastAPI

Frontend: HTML/CSS/JavaScript

Hosting: Render

GPU Required: No

Paid API Required: No
```

---

# 👨‍💻 Author

## Ayyappan M

**Information Technology Graduate | Full Stack Developer**

### Connect

* 💻 GitHub: [Ayyappanmj](https://github.com/Ayyappanmj)
* 🚀 Live Project: [AI Production Incident Investigator](https://ai-production-incident-investigator.onrender.com)

---

# ⭐ Support

If you find this project useful or interesting, consider giving the repository a ⭐ on GitHub.

---

## 📄 License

This project can be adapted and extended for educational, portfolio, and development purposes. Add a specific open-source license to the repository if you want to define formal reuse and distribution terms.



### 📁 Developer Portfolio
Personal developer portfolio built to showcase projects, skills, and experience.

<img src="https://github-readme-stats.vercel.app/api/pin/?username=Ayyappanmj&repo=developer-portfolio&theme=nord&border_color=7dd3fc&title_color=7dd3fc&text_color=c9d1d9&bg_color=0d1117" alt="developer-portfolio"/>

| Layer      | Technology                  |
|------------|------------------------------|
| Frontend   | React.js, Tailwind CSS       |
| Deployment | Vercel                       |

🔗 [Live](https://developer-portfolio-6izs2uf8n-ayyappanmj2004.vercel.app/) · [Code](https://github.com/Ayyappanmj/developer-portfolio)

<br/>

### 📁 Doomscrolling
A project exploring and addressing the pattern of doomscrolling behavior.

<img src="https://github-readme-stats.vercel.app/api/pin/?username=Ayyappanmj&repo=doomscrolling-&theme=nord&border_color=7dd3fc&title_color=7dd3fc&text_color=c9d1d9&bg_color=0d1117" alt="doomscrolling"/>

| Layer      | Technology                  |
|------------|------------------------------|
| Stack      | JavaScript / Web             |

🔗 [Code](https://github.com/Ayyappanmj/doomscrolling-)

<br/>

### 📁 Smart Attendance System
An automated attendance tracking system.

<img src="https://github-readme-stats.vercel.app/api/pin/?username=Ayyappanmj&repo=Smart-Attendance-System&theme=nord&border_color=7dd3fc&title_color=7dd3fc&text_color=c9d1d9&bg_color=0d1117" alt="Smart-Attendance-System"/>

| Layer      | Technology                  |
|------------|------------------------------|
| Core       | Python, Computer Vision      |
| Database   | SQL                          |

🔗 [Code](https://github.com/Ayyappanmj/Smart-Attendance-System)

<br/>

### 📁 Sleep Detection Alarm
A system that detects drowsiness/sleep and triggers an alarm.

<img src="https://github-readme-stats.vercel.app/api/pin/?username=Ayyappanmj&repo=Sleep-detection-alarm&theme=nord&border_color=7dd3fc&title_color=7dd3fc&text_color=c9d1d9&bg_color=0d1117" alt="Sleep-detection-alarm"/>

| Layer      | Technology                  |
|------------|------------------------------|
| Core       | Python, Computer Vision      |

🔗 [Code](https://github.com/Ayyappanmj/Sleep-detection-alarm)

<br/>

### 📁 Fullstack Real Chat App
A full-stack real-time chat application.

<img src="https://github-readme-stats.vercel.app/api/pin/?username=Ayyappanmj&repo=fullstack-realchat-app&theme=nord&border_color=7dd3fc&title_color=7dd3fc&text_color=c9d1d9&bg_color=0d1117" alt="fullstack-realchat-app"/>

| Layer      | Technology                        |
|------------|-------------------------------------|
| Frontend   | React.js, Tailwind CSS              |
| Backend    | Node.js, Express.js                 |
| Database   | MongoDB                             |

🔗 [Code](https://github.com/Ayyappanmj/fullstack-realchat-app)

<br/>

## 🛠️ Tech Stack

**Languages**

<img src="https://skillicons.dev/icons?i=py,java,c,js,html,css" alt="languages"/>

**Frontend**

<img src="https://skillicons.dev/icons?i=react,tailwind,html,css" alt="frontend"/>

**Backend / Infra**

<img src="https://skillicons.dev/icons?i=nodejs,express,flask,django,docker,git,github" alt="backend-infra"/>

**Cloud**

<img src="https://skillicons.dev/icons?i=aws" alt="cloud"/>

**AI / Databases**

<img src="https://skillicons.dev/icons?i=tensorflow,pandas,mysql,postgres,mongodb,oracle" alt="ai-db"/>

**Dev Tools**

<img src="https://skillicons.dev/icons?i=vscode,figma" alt="dev-tools"/>

<br/>

## 📊 GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=Ayyappanmj&show_icons=true&theme=nord&border_color=7dd3fc&title_color=7dd3fc&icon_color=7dd3fc&text_color=c9d1d9&bg_color=0d1117" alt="GitHub Stats" height="165"/>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Ayyappanmj&layout=compact&theme=nord&border_color=7dd3fc&title_color=7dd3fc&text_color=c9d1d9&bg_color=0d1117" alt="Top Languages" height="165"/>

<img src="https://streak-stats.demolab.com?user=Ayyappanmj&theme=nord&border=7dd3fc&ring=7dd3fc&fire=7dd3fc&currStreakLabel=7dd3fc" alt="GitHub Streak"/>

</div>

### 🏆 Trophies

<div align="center">
<img src="https://github-profile-trophy.vercel.app/?username=Ayyappanmj&theme=nord&no-frame=true&no-bg=true&column=7&margin-w=8" alt="trophies"/>
</div>

### 📈 Contribution Graph

<div align="center">
<img src="https://github-readme-activity-graph.vercel.app/graph?username=Ayyappanmj&theme=nord&color=7dd3fc&line=7dd3fc&point=ffffff&area=true&hide_border=true" alt="activity graph" width="100%"/>
</div>

<br/>

## 🤝 Connect With Me

<div align="center">

<a href="https://www.linkedin.com/in/ayyappan-m-104429214" target="_blank">
  <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
</a>
<a href="mailto:ayyappanmadhuj@gmail.com">
  <img src="https://img.shields.io/badge/Email-7dd3fc?style=for-the-badge&logo=gmail&logoColor=black" alt="Email"/>
</a>
<a href="https://developer-portfolio-6izs2uf8n-ayyappanmj2004.vercel.app/" target="_blank">
  <img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio"/>
</a>

</div>

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0ea5e9,100:7dd3fc&height=150&section=footer&animation=twinkling" width="100%"/>
