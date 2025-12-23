# n8n Operational Intelligence Modules ⚙️

**Automating the gap between Strategy and Execution.**

This repository contains "Core Modules"—foundational workflows designed to solve specific, high-value operational bottlenecks. These are streamlined versions of the robust **Pre-Strategy Engines** I build for enterprise clients.

## 📂 The Modules

### 1. The Strategic Research Dispatcher (`Strategic_Research_Dispatcher.json`)
**Problem:** The "Blank Page Phase." Analysts spend hours formatting basic research before strategy work begins.
**Solution:** An AI-driven agent that ingests a topic (e.g., "AI Compliance Trends"), determines the audience (Executive vs. Expert), and auto-dispatches a researched briefing via email.
**Tech Stack:**
* **n8n AI Agent:** Context-aware processing.
* **Dynamic Routing:** Adjusts complexity based on the target audience.
* **Output:** Formatted HTML Briefing.

### 2. The Revenue Protection Monitor (`Revenue_Protection_Monitor.json`)
**Problem:** Revenue leakage due to missed contract renewals or expiry dates.
**Solution:** A "Set and Forget" monitor that audits contract databases (Google Sheets/Airtable) and triggers high-priority alerts for impending expirations.
**Impact:** Prevents churn and protects recurring revenue (ARR).

---

## 🚀 How to Use
1. **Download:** Click the JSON file you need.
2. **Import:** Open your n8n instance → "Import from File."
3. **Configure:** Add your own credentials (Gmail, OpenAI/ Gemini, Google Sheets).

---

## 👨‍💻 About the Architect
**Abhishek Rai** | *Automation Architect & Strategy Engineer*
I engineer time. My focus is building "Agentic Loops"—systems that automate 80% of the manual drudgery in strategic planning and operations.

* **Connect on LinkedIn:** https://www.linkedin.com/in/abhishekrai2000/
* Open for consulting on complex workflow architecture.
