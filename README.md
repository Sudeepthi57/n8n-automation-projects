🚀 AI Vocational Content Automation Engine

An end-to-end AI-powered educational content generation platform built using n8n workflow orchestration and multiple Large Language Models to automate the creation, localization, and production of vocational training materials.

The system transforms structured curriculum inputs into fully production-ready educational assets, including scripts, simulations, translations, and voice narration.

🎯 Vision

Enable scalable creation of vocational education content by replacing manual instructional design workflows with AI-driven automation pipelines.

Instead of generating isolated AI outputs, this system builds a modular AI production engine capable of generating entire learning ecosystems automatically.

⚙️ Core Capabilities

The platform automatically generates:

🎬 Vocational Training Video Scripts

🛠️ Hands-on Simulation Scripts

📘 Learning Outcome (LO)-based Concept Explanations

📝 Assignments

❓ Assessments

🌍 Multilingual Translations

🎙️ AI Voice Narrations

☁️ Automated Google Drive Deliverables

🏗️ System Architecture
Webhook Input
      ↓
Job Role Routing (Switch Logic)
      ↓
AI Generation Layer (Multi-LLM)
      ↓
Formatting & Validation
      ↓
Translation / Audio Pipelines
      ↓
Google Drive Export
🧠 AI Stack

n8n — Workflow orchestration

OpenAI GPT-4o Mini — Structured content generation

Gemini — Translation & validation

Claude — reasoning & structured expansion

ElevenLabs — Voice synthesis

Google Drive API — automated storage

📂 Project 1 — Video Script Generation Engine

Automates creation of structured vocational training scripts aligned with curriculum standards.

🔹 Modules
1️⃣ Introduction Generator

Webhook-triggered workflow

Job-role based routing

Structured script generation

Direct export to Google Drive

2️⃣ Concept Module (LO-Based Intelligence)

Inputs:

Topic

Learning Outcomes

NSQF Level

Sector

Processing:

Learning Outcomes segmented into:

Easy explanation

Medium explanation

Deep explanation

Depth automatically aligned to NSQF level

Structured instructional narration generated

✅ Adaptive learning depth automation

3️⃣ Text Module

Controlled prompt templates

Structured formatting enforcement

Consistent instructional output

4️⃣ Assessment & Assignment Generator

Automatically creates:

Assessments

Assignments

Difficulty aligned with NSQF level

Auto-exported learning materials

⭐ Engineering Highlights

Dynamic LO interpretation

Curriculum-aware prompting

Modular workflow nodes

Automated document lifecycle

📂 Project 2 — Simulation Script Generation Engine

Generates hands-on training simulations for practical vocational learning.

⚙️ Workflow Logic
Webhook
   ↓
AI Module & Step Generator
   ↓
Switch Routing
   ↓
Script Expansion Layer
   ↓
Formatting Engine
   ↓
Drive / Frontend Output
🔧 Key Features

Automatic module decomposition

Step-by-step practical actions

Instructional narration generation

Voiceover-ready scripts

Structured formatting via code nodes

🧩 Output Includes

Simulation modules

Practical workflows

Instruction scripts

Voiceover narration

📂 Project 3 — AI Translation Automation Tool
🚀 Overview

A multi-LLM translation pipeline that converts educational scripts into multiple languages while preserving structure and academic accuracy.

⚙️ Translation Architecture
Google Sheets
      ↓
Prompt Builder
      ↓
Gemini — Translation
      ↓
OpenAI — Punctuation Refinement
      ↓
Gemini — Academic Review
      ↓
Structured Parser
      ↓
Google Sheets Output
🧠 Model Orchestration
Gemini — Translation

Context-aware translation

Tag preservation

Academic tone enforcement

OpenAI — Refinement

Grammar & punctuation correction

Readability improvement

Formatting normalization

Gemini — Validation

Terminology consistency

Educational correctness check

Structural verification

📈 Impact

~80–90% reduction in manual translation effort

Production-ready localized scripts

Consistent curriculum terminology

📂 Project 4 — AI Audio Generation Tool

Automatically converts storyboard scripts into natural voice narration using AI voice synthesis.

⚙️ Workflow
Storyboard Script
       ↓
Voice Selection Logic
       ↓
ElevenLabs API
       ↓
Audio Generation (.mp3)
       ↓
Drive Storage
🎙️ Supported Voice Personas

Kid Voice

Young Adult Voice

Male Voice

Female Voice

Elderly Narrator Voice

🔧 Features

Scene-wise audio generation

Character-based narration

API-driven automation

Scalable audio production

Plug-and-play with translation workflow

📈 Impact

Eliminated manual recording workflows

Reduced narration production time by ~90%

Enabled automated AI video pipelines

🛠️ Technical Stack

n8n (Workflow Orchestration)

OpenAI API

Gemini API

Claude

ElevenLabs API

JavaScript (n8n Code Nodes)

Google Sheets API

Google Drive API

Webhook Architecture

🔐 Security

API keys stored in n8n Credentials

No secrets included in repository

Credentials reconfigured after import

🎯 Engineering Highlights

✅ Modular AI workflow architecture
✅ Multi-LLM orchestration pipelines
✅ Learning Outcome–based adaptive generation
✅ Conditional job-role routing
✅ Structured AI output enforcement
✅ Automated cloud document management
✅ End-to-end AI content production system

📈 Use Cases

Vocational Training Automation

EdTech Content Production

Curriculum Scaling

Simulation-Based Learning

AI Instructional Design Systems

👩‍💻 Author

S. Sudeepthi
AI Automation Engineer (Intern)

Focused on building real-world AI systems combining:

Workflow Architecture

Prompt Engineering

LLM Orchestration

Educational AI Automation

⭐ What This Project Demonstrates

This is not a single AI script — it is a production-style AI automation platform integrating:

Generation

Validation

Translation

Voice synthesis

Cloud deployment workflows

Similar to internal AI tooling used in modern AI startup
