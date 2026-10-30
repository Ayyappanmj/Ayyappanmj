<div align="center"> <img src="https://capsule-render.vercel.app/api?type=waving&color=0:7dd3fc,100:0ea5e9&height=220&section=header&text=Ayyappan%20M&fontSize=60&fontColor=ffffff&animation=twinkling&fontAlignY=35&desc=Full%20Stack%20Developer&descAlignY=55&descSize=22" width="100%"/> <a href="https://git.io/typing-svg"> <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&duration=3000&pause=800&color=7DD3FC&center=true&vCenter=true&width=700&lines=Full+Stack+Developer;React.js+%7C+Node.js+%7C+FastAPI+%7C+Flask;AI+%2F+ML+%7C+LLMs+%7C+RAG+%7C+AI+Agents;Voice+AI+%7C+Amazon+Bedrock+%7C+MCP;Data+Analytics+%7C+Power+BI+%7C+SQL;Building+Real-World+Projects+%F0%9F%9A%80" alt="Typing SVG" /> </a> <br/> <img src="https://komarev.com/ghpvc/?username=Ayyappanmj&label=Profile%20Views&color=7dd3fc&style=flat" alt="Profile Views"/> <img src="https://img.shields.io/github/followers/Ayyappanmj?label=Followers&style=flat&color=7dd3fc" alt="Followers"/> </div> <br/>
🧭 Who I Am
typescript
const ayyappan = {
  title: "Full Stack Developer",
  stack: {
    languages: ["Python", "Java", "C", "JavaScript", "TypeScript", "SQL", "HTML", "CSS"],
    web: ["React.js", "Next.js", "Node.js", "Express.js", "FastAPI", "Flask", "Tailwind CSS", "Django (Basics)", "REST APIs"],
    aiMl: ["Scikit-learn", "TensorFlow", "LLMs", "NLP", "RAG", "LangChain", "CrewAI", "Ollama", "FAISS", "MCP", "Computer Vision"],
    dataAnalytics: ["MS Excel", "Power BI", "DAX", "Advanced SQL", "Pandas", "NumPy", "Data Visualization"],
    databases: ["PostgreSQL", "MySQL", "MongoDB", "Redis", "SQLite", "DynamoDB", "Oracle Database"],
    cloudDevOps: ["AWS (Bedrock, IoT)", "Docker", "GitHub Actions (CI/CD)", "Render", "Vercel", "Supabase"],
    tools: ["Git", "GitHub", "Playwright", "Pytest", "VS Code", "Figma", "Canva"],
  },
  launchedProjects: [
    "nutrivoice-ai",
    "fastapi-api-gateway",
    "rag-document-assistant",
    "ipl-auction-strategy-optimizer",
    "autonomous-market-intelligence-agent",
    "self-healing-automation-agent",
    "bug-report-log-analyzer",
    "ai-production-incident-investigator",
    "fraud-detection-api",
    "predictive-maintenance-mlops",
    "ai-resume-analyzer",
    "ecommerce-churn-retention-analytics",
    "Enterprise-Ecommerce-SupplyChain-Optimization",
    "fullstack-realchat-app",
    "Smart-Attendance-System",
    "Sleep-detection-alarm",
    "developer-portfolio",
  ],
  softSkills: ["Communication", "Time Management", "Problem Solving", "Teamwork", "Adaptability"],
  status: "Building & shipping full-stack + AI-powered projects",
  openTo: ["Full Stack Development", "AI/ML Engineering", "Collaboration & Open Source"],
};
<br/>
⭐ Hackathon Project
🎙️ NutriVoice AI – Autonomous Voice Nutrition Assistant

AWS Builder Challenge & Alexa+ Track · Amazon Developer Hackathon

An autonomous, hands-free voice nutrition tracker that turns natural speech into structured food logs with sub-second parsing.

🎧 Ambient Voice Engine – continuous, zero-click background listener built on the Web Speech API with an armed two-stage state machine and "Alexa" wake-word execution
🧠 Bedrock Converse & Tool Calling – multi-turn entity extraction and tool dispatch via bedrock_runtime.converse, routing between Claude 3 Haiku (~380ms low-latency turns) and Claude 3.5 Sonnet (multi-ingredient parsing)
🔌 Deterministic MCP Server – Pydantic-validated tools over Model Context Protocol: log_food_entry, delete_last_meal (conversational rollback), and macro-budget recipe recommendations
🛡️ Disambiguation & Guardrails – stateful clarification for ambiguous foods (portion, crust, preparation) and health-safety interceptors that block extreme caloric deficits before DB commit
📊 Observability Dashboard – live Web Audio waveforms, macro adherence rings, and an inspection drawer showing latency, token usage, and raw JSON-RPC 2.0 payloads
📝 Engineering Friction Log – documented latency trade-offs, browser audio lifecycle issues, and Bedrock schema sync for the AWS Developer team

Python FastAPI Amazon Bedrock Claude 3.5 Sonnet / Haiku MCP React Vite Tailwind CSS Web Speech API SQLite / DynamoDB

🔗 Code

<br/>
🚀 Featured Projects
🌐 API Gateway & Rate Limiting Platform

Production-shaped API gateway with JWT auth (RBAC, refresh-token rotation), request routing/validation, and a React/TypeScript admin dashboard.

Redis-backed token bucket rate limiter using an atomic Lua script to prevent race conditions, with per-user / per-endpoint limits
Normalized 7-table PostgreSQL schema with Alembic migrations and aggregation endpoints for traffic trends, slowest endpoints, and error rates
85 pytest tests + GitHub Actions CI (lint, test, build, Docker verification)
Dockerized with Compose (Postgres, Redis, FastAPI, Nginx + React); deployed on Render, Vercel, Supabase, and Upstash

FastAPI PostgreSQL Redis React TypeScript Docker GitHub Actions

🔗 Live · Code

<br/>
📚 Production-Grade RAG Document Assistant

Document Q&A platform that answers questions from complex PDFs using grounded LLM generation.

Hybrid retrieval: FAISS semantic search + BM25 keyword search with metadata-aware chunking
Page-level source citations across multiple documents
Hallucination protection: context-only prompting, retrieval thresholds, citation coverage and groundedness checks, structured Pydantic outputs
Interactive Next.js dashboard

Python FastAPI Next.js FAISS BM25 LangChain Sentence Transformers Ollama Docker

🔗 Live · Code

<br/>
🏏 IPL Auction Strategy & Predictive Optimization System

End-to-end IPL analytics platform built on Cricsheet data for player analysis, performance prediction, and auction strategy.

Reproducible ETL pipeline for historical data and player-season aggregates
K-Means role clustering and chronologically validated performance prediction models
Budget-constrained squad optimization with configurable roles, costs, and constraints
Supabase PostgreSQL with advanced SQL analytics and storage safeguards under a 500 MB budget
Streamlit dashboard: team gap analysis, player scouting, auction simulation

Python Pandas Scikit-learn SciPy PostgreSQL SQLAlchemy Streamlit Plotly

🔗 Live · Code

<br/>
🤖 Autonomous Workflow Agent (Market Intelligence)

Multi-agent AI workflow that collects market news and passes it through specialized analysis agents.

News extraction, summarization, trend analysis, and structured report generation
Automated daily market briefing with modular agents and configurable workflows

Python LangChain / CrewAI LLMs NLP APIs Automation

🔗 Live · Code

<br/>
🛠️ Self-Healing Web Automation Agent

Browser automation agent that detects broken UI locators, inspects the live DOM, and generates replacement selectors to retry failed actions.

Deterministic candidate scoring using attributes, text, accessibility properties, DOM proximity, visibility, and uniqueness
Optional Ollama LLM reasoning for complex locator changes
Locator validation, confidence thresholds, retry controls, structured healing logs, and a Streamlit monitoring dashboard

Python Playwright Streamlit Ollama Pytest SQLite

🔗 Live · Code

<br/>
🐞 Bug Report & Log Analyzer Agent

AI incident analysis agent that parses large application logs, groups recurring errors, and performs evidence-based root-cause analysis with local LLM inference.

Source-code retrieval maps stack traces to files, functions, and verified snippets, separating observed evidence from AI hypotheses
Jira-compatible bug reports with structured Pydantic outputs, downloads, and deterministic fallback analysis

Python Streamlit Ollama Pydantic SQLite Pytest Docker

🔗 Live · Code

<br/>
🚨 AI Production Incident Investigator

Lightweight, CPU-friendly tool that analyzes production logs, detects error patterns, builds incident timelines, and recommends next investigation steps. No GPU, paid API, Docker, or database required.

Severity detection, likely failure areas, repeated error grouping, root-cause signals, confidence scoring
Covers: Database • Memory • Latency • Dependency • Authentication • Disk • Deployment • Network
Analysis only: never executes commands or modifies infrastructure

Python FastAPI Uvicorn HTML/CSS/JS Render

🔗 Live · Code

<br/>
🛡️ Real-Time Fraud Detection API
Anomaly detection model to flag potentially fraudulent financial transactions
FastAPI REST API for real-time scoring with structured validation
Dockerized, with a monitoring dashboard for prediction trends, anomalies, and API activity

Python Scikit-learn Pandas NumPy FastAPI Docker Streamlit

🔗 Live · Code

<br/>
⚙️ Predictive Maintenance System
ML pipeline on industrial sensor time-series data to predict equipment failures
Feature engineering, time-series analysis, model training and evaluation
Data-drift monitoring and automated retraining via GitHub Actions

Python Pandas NumPy Scikit-learn Time-Series GitHub Actions

🔗 Live · Code

<br/>
📄 AI Resume Analyzer
Parses uploaded resumes and extracts skills, education, and experience using NLP/LLMs
ATS-style scoring and job-description matching to highlight missing keywords and skill gaps
Returns structured feedback and improvement suggestions per resume section

Python NLP FastAPI React

🔗 Live · Code

<br/>
📈 E-Commerce Customer Churn & Retention Analytics
End-to-end pipeline on a synthetic 5,000-customer dataset: generation, cleaning, validation, feature engineering, SQLite loading
41 SQL queries (CTEs, window functions, cohorts, CLV) for churn, retention, revenue, and lifetime value
Insight: churn concentrated in the first 3 months (6.2%/month), on the Basic plan, and in the Affiliate channel
3-page Power BI dashboard with DAX measures and 33 automated tests

Python SQL (SQLite) Pandas Power BI pytest

🔗 Code

<br/>
📦 Enterprise E-Commerce Global Supply Chain & Margin Optimization
Data engineering and analytics pipeline over 500K+ transactional records from web, inventory, and shipping sources
MySQL data warehouse with CTEs, window functions, data-quality validation, and feature engineering for shipping delays, returns, retention, and profitability
Power BI executive dashboard with DAX measures, regional drill-downs, and KPIs for revenue, margins, fulfillment, and CLV

Python Pandas NumPy MySQL Power BI GCP/AWS

🔗 Code

<br/>
💬 Fullstack Real-Time Chat App

Real-time chat application with an interactive web interface, API communication, and database persistence.

React.js Tailwind CSS Node.js Express.js MongoDB

🔗 Live · Code

<br/>
🎓 Smart Attendance System

Automated attendance tracking using computer vision.

Python Computer Vision SQL

🔗 Code

<br/>
😴 Sleep Detection Alarm

Detects drowsiness and triggers an alarm.

Python Computer Vision

🔗 Code

<br/>
📁 Developer Portfolio

Personal portfolio showcasing projects, skills, and experience.

React.js Tailwind CSS Vercel

🔗 Live · Code

<br/>
📁 Doomscrolling

A project exploring and addressing doomscrolling behavior.

JavaScript Web

🔗 Code

<br/>
🛠️ Tech Stack

Languages

<img src="https://skillicons.dev/icons?i=py,java,c,js,ts,html,css" alt="languages"/>

Frontend

<img src="https://skillicons.dev/icons?i=react,nextjs,tailwind,vite,html,css" alt="frontend"/>

Backend / DevOps

<img src="https://skillicons.dev/icons?i=nodejs,express,fastapi,flask,django,docker,githubactions,git,github" alt="backend-devops"/>

Cloud

<img src="https://skillicons.dev/icons?i=aws,vercel" alt="cloud"/>

AI / Data

<img src="https://skillicons.dev/icons?i=tensorflow,sklearn,pandas,numpy,powerbi" alt="ai-data"/>

Databases

<img src="https://skillicons.dev/icons?i=mysql,postgres,mongodb,redis,sqlite,supabase,oracle" alt="databases"/>

Dev Tools

<img src="https://skillicons.dev/icons?i=vscode,figma" alt="dev-tools"/> <br/>
📊 GitHub Stats
<div align="center"> <img src="https://github-readme-stats.vercel.app/api?username=Ayyappanmj&show_icons=true&theme=nord&border_color=7dd3fc&title_color=7dd3fc&icon_color=7dd3fc&text_color=c9d1d9&bg_color=0d1117" alt="GitHub Stats" height="165"/> <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Ayyappanmj&layout=compact&theme=nord&border_color=7dd3fc&title_color=7dd3fc&text_color=c9d1d9&bg_color=0d1117" alt="Top Languages" height="165"/> <img src="https://streak-stats.demolab.com?user=Ayyappanmj&theme=nord&border=7dd3fc&ring=7dd3fc&fire=7dd3fc&currStreakLabel=7dd3fc" alt="GitHub Streak"/> </div>
🏆 Trophies
<div align="center"> <img src="https://github-profile-trophy.vercel.app/?username=Ayyappanmj&theme=nord&no-frame=true&no-bg=true&column=7&margin-w=8" alt="trophies"/> </div>
📈 Contribution Graph
<div align="center"> <img src="https://github-readme-activity-graph.vercel.app/graph?username=Ayyappanmj&theme=nord&color=7dd3fc&line=7dd3fc&point=ffffff&area=true&hide_border=true" alt="activity graph" width="100%"/> </div> <br/>
🤝 Connect With Me
<div align="center"> <a href="https://www.linkedin.com/in/ayyappan-m-104429214" target="_blank"> <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/> </a> <a href="mailto:ayyappanmadhuj@gmail.com"> <img src="https://img.shields.io/badge/Email-7dd3fc?style=for-the-badge&logo=gmail&logoColor=black" alt="Email"/> </a> <a href="https://developer-portfolio-6izs2uf8n-ayyappanmj2004.vercel.app/" target="_blank"> <img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio"/> </a> </div> <br/> <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0ea5e9,100:7dd3fc&height=150&section=footer&animation=twinkling" width="100%"/>
