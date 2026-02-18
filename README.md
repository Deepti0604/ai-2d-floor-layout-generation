# 🏗 AI-Based 2D Floor Layout Generation System

Research & Development Project using Google Cloud Vertex AI

## 📌 Project Overview

This project focuses on the research, evaluation, and development of an AI-powered system for automated 2D floor layout generation.

The system is designed to:

- Read underlay architectural drawings
- Understand user spatial requirements
- Generate accurate and scalable 2D floor layouts
- Operate through a Conversational AI Agent
- Deliver an end-to-end cloud-integrated workflow

The final solution leverages Google Cloud Vertex AI, custom ML training, geometry-based logic, and conversational AI orchestration.

## 🎯 Objective

To design a scalable, cost-effective AI architecture capable of generating business-ready 2D floor layouts automatically, while reducing dependency on high-cost SaaS tools.

## 🔬 Research & Tool Evaluation (50+ Tools Studied)

Extensive research was conducted across industry tools including:

Testfit, Hypar, Planner5D, Maket.ai, Autodesk Forma, Revit, Archicad, Graph2Plan, Qbiq.ai, Laiout.co, DALL-E, Gemini, Claude, Replit AI, InteriorAI, and many more...

## 🔎 Shortlisted Tools

After evaluation based on accuracy, customization, automation capability, and scalability, two tools were shortlisted:

- **Qbiq.ai**
- **Laiout.co**

### ⚠ Limitation Identified

High subscription cost → Not scalable for long-term deployment.

📄 Full research summary available in `/docs/research-summary.md`

## 🧠 Final Architecture (Custom AI + Vertex AI)

Due to the limitations of existing platforms, a custom AI pipeline was developed using:

- Python
- OpenCV
- Geometry-based spatial logic
- Google Colab (model training)
- Vertex AI Conversational Agent
- Google Cloud Storage Buckets
- Replit integration

## 🏗 System Architecture

### Workflow:

1. Underlay image upload
2. Cloud bucket storage
3. Dataset preparation
4. Colab-based model training
5. Vertex AI Agent creation
6. Conversational interaction
7. Layout generation
8. Output storage & retrieval

## 🤖 Conversational AI Agent

- Built using Vertex AI
- Integrated with Google Cloud Storage
- Handles requirement interpretation
- Generates structured layout output
- Connected securely using Service Accounts
- Integrated with Replit application

📸 Screenshot available in `/screenshots/vertex-agent.png`

## 🔄 End-to-End Workflow

Replit App → Service Account → Vertex AI Agent → Cloud Bucket → Generated Layout Output


## 🛠 Tech Stack

| Layer | Technology |
|-------|-----------|
| Programming | Python |
| Image Processing | OpenCV |
| AI Training | Google Colab |
| Cloud | Google Cloud Platform |
| ML Platform | Vertex AI |
| Agent Framework | Conversational AI Agent |
| Storage | Cloud Storage Bucket |
| Integration | Replit |
| Model Used | Gemini 2.5 Flash |

## 📊 Current Status

- ✅ End-to-end pipeline functional
- ✅ Conversational AI Agent integrated
- ✅ Layout output generation working
- ⚠ Requires large-scale dataset for fine-tuning

## 🚀 Future Roadmap

- Expand dataset size & improve quality
- Fine-tune ML model for spatial precision
- Implement constraint-based layout logic
- Add real-time layout editing support
- Develop web-based UI dashboard
- Convert system into SaaS-ready architecture

📄 Full roadmap available in `/docs/future-roadmap.md`

## 🧠 Key Learnings

- Spatial AI is highly complex
- GPT-based models struggle with geometric precision
- Custom ML + Cloud architecture is essential
- Vertex AI enables scalable conversational workflows
- Data quality directly impacts layout accuracy

## 📌 Why This Project Matters

This project demonstrates:

- Deep AI research capability
- Real-world model evaluation
- Cloud ML architecture design
- End-to-end AI product thinking
- R&D mindset for solving high-cost SaaS dependency challenges

## 👩‍💻 Author

**Deepti Rathore**
BTech CSE | AI & Frontend Developer

## License

This project is open source and available under the MIT License.

