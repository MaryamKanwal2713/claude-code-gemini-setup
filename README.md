# Claude Code + Google Gemini: Step-by-Step Setup Guide

This repository provides a simple, beginner-friendly guide to setting up Claude Code with Google Gemini.  
Follow each step carefully to get your environment ready for Spec-Driven Development.

---

## 📌 What is Claude Code with Google Gemini?

Claude Code combined with Google Gemini is a powerful AI coding setup that helps you:

- Understand detailed specifications  
- Generate accurate, maintainable code  
- Plan and implement complex projects with AI assistance  

This guide walks you through installation, initialization, and core workflows.

---

## ⚙️ Prerequisites

Make sure you have:

- Python 3.9 or newer installed  
- pip or uv tool installed  
- Access to an AI provider account with Claude + Google Gemini enabled  
- A terminal (PowerShell, Command Prompt, or Bash)  

---

## 📦 Installation Steps

### Step 1: Install Claude Code CLI

Install the tool globally so it is available anytime:

pip install claude-code-cli

Or install with uv tool:

uv tool install claude-code

---

### Step 2: Verify Installation

Run the following command to check if the CLI is installed correctly:

claude-code --version

You should see the version number, confirming the CLI is ready.

---

## 📂 Initialize Your Project

Create a new project folder and initialize with Claude + Gemini AI:

claude-code init my-project --ai google-gemini

Or initialize in the current directory:

claude-code init --here --ai google-gemini

---

## 🧭 Core Workflow

Once your project is initialized, use these commands in order:

### 1️⃣ Define project principles

claude-code constitution

### 2️⃣ Specify what you want to build

claude-code specify

### 3️⃣ Plan technical architecture

claude-code plan

### 4️⃣ Generate tasks

claude-code tasks

### 5️⃣ Implement features

claude-code implement

---

## ❗ Tips

- Restart your terminal if commands are not recognized  
- Prefer persistent installation for everyday work  
- Keep your specifications clear and non-technical at first  

---

## 🤝 Contributing

Feel free to fork this repo and submit pull requests with improvements or fixes.

---

Happy coding with Claude Code + Google Gemini! 🚀
