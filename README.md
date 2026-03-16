# 🚀 AI Vocational Content Automation Engine

A modular AI-powered automation system built in n8n for generating:

- 🎬 Vocational Training Video Scripts
- 🛠️ Hands-on Simulation Scripts
- 📘 Concept Explanations (LO-based)
- 📝 Assignments
- ❓ Assessments
- ☁️ Automated Google Drive Exports

This system transforms structured vocational inputs (Topic, Learning Outcomes, NSQF Level, Sector, Job Role) into fully formatted educational content.

---

# 🏗️ System Architecture

Webhook → Switch (Job Role Routing) → AI Generation → Formatting → Google Drive Export

Built using:
- n8n (Cloud)
- OpenAI GPT-4o Mini
- Gemini
- Claude
- Google Drive API
- Conditional Switch Routing
- Structured Prompt Engineering
- JSON-based content formatting

---

# 📂 Project 1: Video Script Generation

This workflow contains 4 major content modules:

## 1️⃣ Introduction Module
- Triggered via Webhook
- Routed using Switch (Job Role-based)
- GPT-4o Mini generates structured introduction
- Output saved directly to Google Drive

---

## 2️⃣ Concept Module (Advanced LO Processing)

Input:
- Topic
- Learning Outcomes (LOs)
- NSQF Level
- Sector

Processing Steps:
1. LO Segmentation Node:
   - Each Learning Outcome categorized into:
     - Easy Explanation
     - Medium Explanation
     - Deep Explanation

2. Script Generation Node:
   - Generates structured concept explanation
   - Ensures level-based depth alignment
3. Auto-save to Drive
This module ensures adaptive content depth based on LO complexity.

---

## 3️⃣ Text Module
- Prompt-driven structured script generation
- Custom formatting logic
- Controlled output structure

## 4️⃣ Assessment & Assignment Module
- Generates:
  - Assessments
  - Assignments
- Rule-based structured prompting
- Difficulty alignment with NSQF level
- Auto-export to Google Drive

---

   WORKFLOW 

   <img width="1137" height="616" alt="Screenshot 2026-03-12 114316" src="https://github.com/user-attachments/assets/9dd8e122-de7e-4fb0-ab60-5d1d81908591" />


# 📂 Project 2: Simulation Script Generation

Designed for hands-on practical experience training.

## Workflow Logic

### Step 1: Webhook Trigger
Receives:
- Topic
- Learning Outcomes
- Flow Idea
- Experience Type

-  Step 2:
                ┌──────────────────┐
                │    Webhook       │
                └────────┬─────────┘
                         │
                         ▼
                ┌──────────────────┐
                │  AI: Module &    │
                │  Step Generator  │
                └────────┬─────────┘
                         │
                         ▼
              (Re-enter Workflow)
                         │
                         ▼
                ┌──────────────────┐
                │   Switch Node    │
                │ (Module Routing) │
                └────────┬─────────┘
                         │
                         ▼
                ┌──────────────────┐
                │ AI: Script       │
                │ Expansion Layer  │
                └────────┬─────────┘
                         │
                         ▼
                ┌──────────────────┐
                │ Formatting Code  │
                └────────┬─────────┘
                         │
                         ▼
                Frontend / Drive Output

### Step 3: Module & Step Categorization
- Simulation broken into:
  - Modules
  - Steps
  - Practical Actions

### Step 4: Voiceover Script Generation
- Internal narration
- Instructional voiceovers
- Practical guidance scripting

### Step 5: Formatting Layer
- Code-based structured formatting
- Ensures consistent full-fledged script output

### Step 6: Final Export
- Google Drive file creation
- Organized folder placement

---
WORKFLOW

<img width="1695" height="717" alt="Screenshot 2026-03-12 114943" src="https://github.com/user-attachments/assets/071c1cde-1860-488e-be44-16faed435d53" />



📂 Project 3 — AI Translation Automation Tool

Overview

An AI-powered translation pipeline designed to automatically translate educational video and simulation scripts into multiple languages (Hindi, English, etc.) while preserving academic accuracy, formatting, and instructional quality.

The system combines multi-LLM orchestration with workflow automation to produce production-ready localized content instead of raw machine translations.

🎯 Problem

Educational storyboard scripts require:
Accurate academic terminology (NCERT-aligned)
Strict formatting preservation
Scene-by-scene consistency
Proper punctuation and readability
Manual review effort across hundreds of lines

Traditional translators or single LLM outputs often:
break structure,
change meaning,
lose tags,
or produce inconsistent tone.



****Workflow Architecture








🧠 Model Responsibilities
1️⃣ Gemini — Translation Engine
Performs context-aware translation
Maintains scene tags and structure
Applies academic tone
Supports curriculum-aligned terminology

2️⃣ OpenAI — Language Refinement
Fixes punctuation and sentence flow
Improves readability
Normalizes formatting
Ensures teacher-style narration

3️⃣ Gemini — Review & Validation
Final quality verification
Checks terminology consistency
Ensures educational correctness
Prevents structural corruption

🔧 Key Features

✅ Multi-LLM orchestration
✅ Automated Google Sheets integration
✅ Scene-level translation parsing
✅ Tag-preserving structured prompts
✅ Academic terminology enforcement
✅ Error-resilient parsing system
✅ Webhook-triggered automation
✅ Scalable for large storyboard datasets

🏗️ Tech Stack
Automation: n8n
LLMs: Gemini API, OpenAI API
Scripting: JavaScript (n8n Code Nodes)
Data Source: Google Sheets
Architecture: Prompt Engineering + Workflow Automation

🔄 Pipeline Logic
Fetch storyboard rows from Google Sheets
Auto-detect headers dynamically
Build structured tagged prompt
Translate using Gemini
Refine punctuation using OpenAI
Re-review translation via Gemini
Parse scene blocks automatically
Write translated output back to sheet


# 🛠️ Technical Stack

- n8n (Workflow Orchestration)
- OpenAI GPT-4o Mini
- Webhook-based input handling
- Switch-based conditional routing
- Google Drive API integration
- Structured Prompt Engineering
- Dynamic LO-based depth scaling

---

# 🔐 Security

- API Keys stored securely in n8n Credentials
- No secrets included in exported workflows
- Credentials must be reconnected upon import

---

# 🎯 Key Engineering Highlights

- Modular workflow architecture
- Multi-level content depth automation
- LO-based dynamic script expansion
- Conditional job-role routing
- Structured formatting enforcement
- Automated cloud document management


# 📈 Use Cases

- Vocational Training Automation
- EdTech Content Generation
- Scalable Curriculum Production
- Simulation-based Practical Training
- AI-assisted Instructional Design

---

# 👩‍💻 Author

Developed as part of an AI Automation Internship demonstrating:

- Workflow Architecture Design
- Prompt Engineering
- AI System Structuring
- Educational Content Automation
