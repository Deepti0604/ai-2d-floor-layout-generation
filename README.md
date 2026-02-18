🏗 AI-Based 2D Floor Layout Generation System
Research & Development Project using Vertex AI
📌 Project Overview

This project focuses on the research, evaluation, and development of an AI-powered system for automated 2D floor layout generation.

The system is designed to:

Read underlay architectural drawings

Understand user spatial requirements

Generate accurate and scalable 2D floor layouts

Operate through a Conversational AI Agent

The final solution leverages Google Cloud Vertex AI, custom ML training, and an integrated conversational workflow.

🎯 Objective

To design a scalable, cost-effective AI architecture capable of generating business-ready 2D floor layouts automatically.

🔬 Research & Tool Evaluation (50+ Tools Studied)

Extensive research was conducted on:

Testfit

Hypar

Planner5D

Maket.ai

Autodesk Forma

Revit

Archicad

Graph2Plan

Qbiq.ai

Laiout.co

DALL-E

Gemini

Claude

Replit AI

InteriorAI

and many more...

🔎 Shortlisted Tools

Qbiq.ai

Laiout.co

Limitation Identified:
High subscription cost → Not scalable for long-term deployment.

Full research summary available in /research/research-summary.md

🧠 Final Architecture (Custom AI + Vertex AI)

Due to limitations of existing platforms, a custom AI pipeline was developed using:

Python

OpenCV

Geometry-based spatial logic

Google Colab (training)

Vertex AI Agent

Cloud Storage Buckets

Replit integration

🏗 System Architecture

Workflow:

Underlay image upload

Cloud bucket storage

Dataset preparation

Colab-based model training

Vertex AI Agent creation

Conversational interaction

Layout generation

Output storage & retrieval

🤖 Conversational AI Agent

Built using Vertex AI

Integrated with Cloud Storage

Handles requirement interpretation

Generates structured layout output

Screenshot available in /screenshots/vertex-agent.png

🔄 End-to-End Workflow

Replit App → Service Account → Vertex AI Agent → Cloud Bucket → Generated Layout

🛠 Tech Stack
Layer	Technology
Programming	Python
Image Processing	OpenCV
AI Training	Google Colab
Cloud	Google Cloud Platform
ML Platform	Vertex AI
Agent Framework	Conversational AI Agent
Storage	Cloud Storage Bucket
Integration	Replit
Model Used	Gemini 2.5 Flash
📊 Current Status

✅ End-to-end pipeline functional
✅ Conversational AI Agent integrated
✅ Layout output generation working
⚠ Requires large-scale dataset for fine-tuning

🚀 Future Roadmap

Improve dataset size & quality

Fine-tune ML model for spatial precision

Implement constraint-based layout logic

Add real-time editing support

Develop web-based UI dashboard

Convert into SaaS architecture

Full roadmap in /docs/future-roadmap.md

🧠 Key Learnings

Spatial AI is highly complex

GPT models struggle with geometric precision

Custom ML + Cloud architecture is required

Vertex AI enables scalable conversational workflows

Data quality directly impacts layout accuracy

📌 Why This Project Matters

This project demonstrates:

Deep AI research capability

Real-world model evaluation

Cloud ML architecture design

End-to-end AI product thinking

R&D mindset for solving high-cost SaaS dependency problems

👩‍💻 Author

Deepti Rathore
BTech CSE | AI & Frontend Developer
