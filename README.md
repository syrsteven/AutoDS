# AutoDS System
[![Start Using AutoDS](https://img.shields.io/badge/Try%20AutoDS-Start%20Now-blue)](http://47.115.222.218/)


Welcome to **AutoDS System** — an intelligent, autonomous research agent for digital medical studies.


## 🩺 Introduction

AutoDS is an **LLM-driven research agent** that autonomously conducts digital medical research. It dynamically designs experiments, analyzes data, and refines strategies — all within a **secure computational sandbox**.


## ✨ Key Features

- **Autonomous Decision-Making & Dynamic Strategy**
  - Powered by an LLM-based decision-making module.
  - Dynamically formulates experimental strategies and executes research operations in real time based on objectives and contextual state.

- **Heuristic Iterative Framework**
  - Follows a cyclical **decision → execution → feedback → optimization** process.
  - Breaks down complex medical research tasks into executable subtasks.
  - Continuously improves solutions through self-evaluation.

- **Versatile Research Capabilities**
  - Supports:
    - **Fixed-goal research** (predefined objectives).
    - **Open-goal exploration** (discovery-driven research).
  - Covers experiment design, data processing, mining, and generating interpretable analytical outputs.

- **Secure Sandbox Environment**
  - All operations run within a dedicated digital medicine sandbox.
  - Ensures robust data security and reproducibility.

- **Transparency & Explainability**
  - Stepwise, iterative design clearly deconstructs decision logic.
  - Enables human oversight and intervention when necessary.


## 🚀 User Guide

1. Click the **Start Using** button to enter the system.
2. Enter the task you want AutoDS to execute and click **Send**.
3. The system will intelligently analyze and decide the next steps.
4. Click **Next Step** to let AutoDS execute automatically, or enter your own suggestions.
5. In **File Explorer**, you can:
   - Select datasets used by AutoDS.
   - View all files in the workspace.


## ⚠️ Notes

- If the system is idle for **30 minutes**, it will automatically shut down.
- **Do not refresh the page** — this will erase your conversation.


## 🧠 Key Sections

AutoDS uses an internal structure for each cycle:

- **Thoughts**  
  The initial interpretation of a prompt or preliminary response to previous output.

- **Reasoning**  
  The justification behind each response.

- **Plan**  
  The execution steps toward achieving the goal.

- **Criticism**  
  Reflection on the current reasoning and decision-making.

- **Speak**  
  Information on the next action.


## 📂 Dataset Description

AutoDS ships with a sample dataset:

**Dataset:** `slit_lamp_dataset`  
**Size:** 3,064 slit-lamp photographs

**Classes:**

- **normal**
  - Images of healthy eyes without cataracts.
- **cataract**
  - Images of eyes affected by cataracts of varying severity and etiology.
- **post-surgery**
  - Post-operative images following cataract surgery.

> *Images are organized into folders, with filenames containing the corresponding label.*

