<div align="center">

# Hi, I'm Akshat Gupta 👋

### *"I Don't Lose — I Win. That's My Job 👑"*

**Full Stack Developer · AI Systems Builder · India 🇮🇳**

*Computer Science @ Lovely Professional University*

[![Portfolio](https://img.shields.io/badge/Portfolio-Visit_Site-0A66C2?style=for-the-badge&logo=vercel&logoColor=white)](https://portfolioakshatgupta.netlify.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/akshat-gupta132)
[![GitHub](https://img.shields.io/badge/GitHub-Akshat--cyber--cloud-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Akshat-cyber-cloud)
[![LeetCode](https://img.shields.io/badge/LeetCode-400%2B_Solved-FFA116?style=for-the-badge&logo=leetcode&logoColor=white)](https://leetcode.com/u/aakshat11g/)

</div>

---

## About Me

I'm a third-year Computer Science student at Lovely Professional University (graduating 2027), building full-stack applications with a focus on AI and agentic systems. I'm currently looking for **internship opportunities** in Full Stack Development, SDE, and AI/LLM engineering roles.

I like building things that actually do work, not just answer questions — multi-agent systems, real-time collaborative tools, and apps with an AI layer that takes action instead of just responding. My two largest projects, **Gauntlet AI** and **CodeSpace**, both grew out of that: one benchmarks LLMs against each other, the other is a Kubernetes-backed coding sandbox with a built-in AI pair programmer.

- 3rd-year CS student at **Lovely Professional University**, Class of 2027
- Actively seeking **internships** in Full Stack / SDE / AI-GenAI roles
- Comfortable across the MERN stack, TypeScript, and LangChain/LangGraph-based AI tooling
- Top 15 at Sheryians Hackathon · 2nd Place at Hack N Hunt 2.0 (100+ teams)
- 400+ problems solved on LeetCode, with a strong DSA foundation
- Ship fast, iterate in public, and can walk through every design decision in my projects — including where AI tools helped and where I built things by hand

---

## Featured Projects

### Gauntlet AI — Multi-Agent Battle Platform *(Flagship)*

**Most AI demos show one model answering one question. Gauntlet AI asks which model is actually better — and proves it with data, not a gut feeling.**

- Two LLMs get the same prompt and respond independently; a third model judges both on accuracy, clarity, and reasoning — and has to explain the verdict, not just pick a winner
- Every match updates a persistent leaderboard, turning a one-off comparison into a running record of which models hold up across hundreds of prompts
- Built a replay system so results aren't a fluke — re-run the same prompt and check if the judge's call stays consistent
- The real engineering challenge: making the judging *trustworthy*. That meant forcing the judge to reason criteria-by-criteria before a verdict, and streaming all three responses over SSE so the UI never feels stalled on the slowest model

**Stack:** `React 19` · `Node.js` · `Express` · `LangGraph` · `Groq` · `MongoDB` · `Google OAuth`

**Live:** [gauntlet-ai-demo-link.com](https://web-dev-two-sigma.vercel.app/) · **Code:** [GitHub](https://github.com/Akshat-cyber-cloud/WebDev/tree/main/Project2)

---

### Clario — Multi-Agent Investment Research Terminal

**Ask Clario about a company and it doesn't hand you a canned summary — it dispatches four specialist agents to actually go find out.**

- Financial, News, SEC Risk, and Reputation agents run in parallel, then fan into a Decision Agent that synthesizes everything into a single 0–100 score plus a clear Invest / Hold / Pass verdict — reasoning included, not hidden
- Pulls live data per query from Finnhub, SEC EDGAR, and Tavily instead of relying on cached or stale numbers
- The hard part wasn't the pipeline — it was companies with *no clean data*: Indian stocks, private companies, anything without full SEC coverage
- Instead of showing a broken dashboard when financials come back empty, Clario detects the gap and falls back to a Sentiment & Data Status view built from whatever signal is available — deciding what to show when the ideal data doesn't exist was the real design problem

**Stack:** `React` · `Node.js` · `Express` · `LangGraph` · `Groq` · `Finnhub` · `SEC EDGAR` · `Tavily`

**Live:** [invest-agent-xi.vercel.app](https://invest-agent-xi.vercel.app) · **Code:** [GitHub](https://github.com/Akshat-cyber-cloud/Invest_Agent)

---

### CodeSpace — Collaborative Coding Sandbox

**A real-time coding environment where every session runs in its own isolated Kubernetes pod — one person's runaway process can't take down someone else's.**

- Code changes and terminal output stream live over SSE between collaborators
- A LangChain-orchestrated Mistral agent sits *inside* the editor as a real tool-calling assistant — it reads the current file, runs commands, and suggests fixes in context, not in a separate side chat
- NGINX Ingress routes traffic to the correct pod per session; Skaffold drives the dev-to-deploy loop so sandbox image changes don't mean a slow manual rebuild
- Less "add AI to an editor," more "design the infrastructure so AI-in-the-loop doesn't compromise isolation or speed"

**Stack:** `Kubernetes` · `LangChain` · `Mistral` · `Node.js` · `React`

**Live:** [codespace-demo-link.com](https://codespace-demo-link.com) · **Code:** [GitHub](https://github.com/Akshat-cyber-cloud/CodeSpace)

---

### Ember AI — AI Chatbot Platform

**Built around one belief: most chatbots stop at answering, when the actually useful version acts.**

- Mistral-powered conversational core with two things bolted onto it that most chatbots treat as separate features: live news retrieval and email drafting, both handled inline in the same conversation
- Combines retrieval and action in one interface instead of making the user hop between tools

**Stack:** `Node.js` · `Mistral API` · `REST APIs`

**Live:** [ember-ai-demo-link.com](https://webdev-6.onrender.com/) · **Code:** [GitHub](https://github.com/Akshat-cyber-cloud)

---

## Tech Stack

**Languages**

![Java](https://img.shields.io/badge/-Java-007396?style=flat-square&logo=openjdk&logoColor=white)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)

**Frontend**

![React](https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Redux](https://img.shields.io/badge/-Redux-764ABC?style=flat-square&logo=redux&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/-Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![HTML5](https://img.shields.io/badge/-HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/-CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)

**Backend**

![Node.js](https://img.shields.io/badge/-Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/-Express-000000?style=flat-square&logo=express&logoColor=white)
![MongoDB](https://img.shields.io/badge/-MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)

**AI & Systems**

![LangChain](https://img.shields.io/badge/-LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![OpenAI](https://img.shields.io/badge/-OpenAI_API-412991?style=flat-square&logo=openai&logoColor=white)

**DevOps & Tools**

![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/-Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Git](https://img.shields.io/badge/-Git-F05032?style=flat-square&logo=git&logoColor=white)
![Vercel](https://img.shields.io/badge/-Vercel-000000?style=flat-square&logo=vercel&logoColor=white)

---

## Currently Learning

```
Data Structures  → Web Deployment -> System Design  →  Advanced AI Systems  →  DevOps
```
---

## Contribution Snake

<div align="center">

<img alt="github contribution grid snake animation" src="https://raw.githubusercontent.com/Akshat-cyber-cloud/Akshat-cyber-cloud/output/github-contribution-grid-snake.gif" width="100%">

</div>

---

## What I'm Building Towards

- AI systems that **assist, automate, and act** — not just respond
- Chatbots and agents that go beyond conversation into **execution**
- Real-time applications with **intelligent decision layers**

> *The goal isn't to use AI. It's to build with it.*

---

<div align="center">

**"I build systems. Not just projects."**

![Visitor Count](https://komarev.com/ghpvc/?username=Akshat-cyber-cloud&color=7F77DD&style=flat-square&label=Profile+Views)

</div>
