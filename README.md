# 🤖 Autonomous AI Research Laboratory

<div align="center">

[![GitHub stars](https://img.shields.io/github/stars/vishakha2121/ai-research-lab-autonomous?style=for-the-badge&color=ffd700)](https://github.com/vishakha2121/ai-research-lab-autonomous/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/vishakha2121/ai-research-lab-autonomous?style=for-the-badge&color=ff69b4)](https://github.com/vishakha2121/ai-research-lab-autonomous/network)
[![GitHub issues](https://img.shields.io/github/issues/vishakha2121/ai-research-lab-autonomous?style=for-the-badge&color=red)](https://github.com/vishakha2121/ai-research-lab-autonomous/issues)
[![GitHub license](https://img.shields.io/github/license/vishakha2121/ai-research-lab-autonomous?style=for-the-badge&color=blue)](https://github.com/vishakha2121/ai-research-lab-autonomous/blob/main/LICENSE)
[![Python 3.9+](https://img.shields.io/badge/python-3.9+-blue?style=for-the-badge&logo=python)](https://www.python.org/downloads/)
[![React 18](https://img.shields.io/badge/react-18-blue?style=for-the-badge&logo=react)](https://reactjs.org/)
[![FastAPI](https://img.shields.io/badge/fastapi-0.104+-green?style=for-the-badge&logo=fastapi)](https://fastapi.tiangolo.com/)
[![CrewAI](https://img.shields.io/badge/crewai-0.20+-purple?style=for-the-badge)](https://crewai.io/)
[![Docker](https://img.shields.io/badge/docker-ready-blue?style=for-the-badge&logo=docker)](https://www.docker.com/)
[![Tailwind CSS](https://img.shields.io/badge/tailwind-3.3+-cyan?style=for-the-badge&logo=tailwindcss)](https://tailwindcss.com/)

</div>

---

## 🌟 **Project Overview**

An **intelligent multi-agent system** for automated scientific research that uses **Google Gemini AI** and **CrewAI** to autonomously generate ideas, run experiments, analyze results, and write technical reports.

> 🚀 *"The future of research is autonomous, collaborative, and intelligent - this project is your gateway to that future."*

---

## 🎯 **Core Features**

### 🤖 **Multi-Agent System**
| Agent | Function | Technology |
|-------|----------|------------|
| 🧠 **Idea Generator** | Generates novel research hypotheses using Gemini AI | CrewAI + Gemini |
| 🔬 **Experiment Runner** | Designs and executes experiments | Python Async |
| 📊 **Data Analyzer** | Analyzes results with statistical methods | Pandas + NumPy |
| 📝 **Report Writer** | Creates comprehensive technical reports | Markdown + PDF |
| 🎯 **Supervisor** | Orchestrates all agents and manages workflow | CrewAI |

### 🧠 **Intelligent Memory Systems**
- **Short-term Memory**: Real-time context and conversation history
- **Long-term Memory**: Vector database (ChromaDB) for persistent knowledge
- **Semantic Memory**: Knowledge graph for relationship mapping

### ⚡ **Real-Time Features**
- WebSocket live updates
- Interactive experiment monitoring
- Agent status tracking
- Live data visualization

---

## 📊 **System Architecture**

---

## 🛠️ **Tech Stack**

### **Backend**


---

## 📦 **Installation & Setup**

### **Prerequisites**
```bash
✅ Python 3.9 or higher
✅ Node.js 18 or higher
✅ PostgreSQL 14 or higher
✅ Docker & Docker Compose (optional)
✅ Gemini API Key (Get from Google AI Studio)
✅ Git

# Navigate to backend
cd backend

# Create virtual environment
python -m venv venv

# Activate virtual environment
# On Windows:
venv\Scripts\activate
# On Mac/Linux:
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt

# Copy environment variables
cp .env.example .env

# Edit .env file and add your Gemini API key
# GEMINI_API_KEY=your_api_key_here

# Navigate to frontend (from project root)
cd frontend

# Install dependencies
npm install

# Copy environment variables
cp .env.example .env 