# 180 Days to Interview-Ready 🚀

An interactive **180-day interview preparation and skill-tracking dashboard** designed to help track progress across Data Science, Machine Learning, GenAI, AI Engineering, and Software Engineering topics.

## 🎯 Overview

This project provides a structured roadmap for becoming interview-ready through consistent daily practice.

The dashboard tracks:

- Overall preparation progress
- Daily study streak
- Topics completed
- Skill readiness by role
- Priority areas
- Daily learning history
- Badges and achievements
- Progress toward the 180-day goal

All progress is stored locally in the browser using `localStorage`.

## 🧠 Topics Covered

### Python & Coding
- Python fundamentals
- Data structures
- Advanced Python
- OOP
- NumPy
- Pandas
- Scikit-learn
- XGBoost
- LightGBM
- PySpark

### SQL
- SQL fundamentals
- Joins
- Subqueries
- CTEs
- Window functions
- Database design
- Query optimization
- Analytical SQL problems

### Mathematics & Statistics
- Linear Algebra
- Calculus
- Optimization
- Probability
- Statistics
- Hypothesis Testing
- A/B Testing
- Regression Statistics

### Machine Learning
- Supervised & unsupervised learning
- Regression
- Classification
- Ensemble methods
- Clustering
- Dimensionality reduction
- Feature engineering
- Hyperparameter tuning
- Time-series forecasting

### Model Evaluation & Explainability
- Classification metrics
- Regression metrics
- Cross-validation
- Business metric alignment
- SHAP
- LIME
- Feature importance

### Deep Learning
- Neural networks
- Backpropagation
- Optimization
- CNNs
- RNNs
- LSTMs
- GRUs
- Autoencoders
- Transfer learning
- PyTorch

### NLP & Transformers
- Tokenization
- TF-IDF
- Word embeddings
- Attention
- Self-attention
- Transformers
- BERT
- GPT
- Hugging Face

### Generative AI & LLMs
- LLM fundamentals
- Prompt engineering
- Structured outputs
- LLM safety
- Fine-tuning
- LoRA / QLoRA / PEFT
- Quantization
- Inference optimization
- Token-cost optimization

### RAG
- Document ingestion
- Chunking
- Embeddings
- Vector databases
- Semantic search
- Hybrid search
- Reranking
- Query rewriting
- Context compression
- Agentic RAG
- GraphRAG
- RAG evaluation

### Agentic AI
- LangChain
- LangGraph
- AI Agents
- ReAct
- Tool calling
- Multi-agent systems
- Agent loops
- State management
- Human-in-the-loop
- Agent evaluation

### MCP
- MCP architecture
- MCP clients and servers
- Tools
- Resources
- Prompts
- MCP vs APIs
- MCP vs function calling
- Enterprise MCP security

### AI Engineering & Production
- LLM evaluation
- AI observability
- AI governance
- Responsible AI
- MLOps
- MLflow
- Databricks
- Spark
- Data Engineering
- FastAPI
- Docker
- Cloud
- n8n
- Git & Software Engineering

### Interview Preparation
- DSA
- System Design
- AI System Design
- Product Thinking
- Business Thinking
- CV-based interview stories

## 📊 Role Readiness

The dashboard calculates preparation readiness for three career paths:

### Data Scientist
Focus areas include:

- Python
- SQL
- Mathematics
- Statistics
- EDA
- Machine Learning
- Model Evaluation
- Explainability
- Product & Business Thinking

### ML Engineer
Focus areas include:

- Python
- Machine Learning
- Deep Learning
- MLOps
- Databricks & Spark
- FastAPI
- Docker & Cloud
- Git
- System Design
- DSA

### GenAI Engineer
Focus areas include:

- NLP
- Transformers
- LLMs
- RAG
- Embeddings
- Vector Databases
- LangChain
- LangGraph
- AI Agents
- MCP
- LLM Evaluation
- AI Observability
- AI Governance
- FastAPI

## ✨ Features

### 180-Day Progress Tracker

A visual 180-day calendar shows:

- Completed days
- Current day
- Missed days
- Future days

### Daily Check-in

The user can check in each day and maintain a learning streak.

### Topic Tracking

Every topic contains multiple sections and individual concepts that can be marked as completed.

### Progress Analysis

The dashboard calculates:

- Items completed
- Items remaining
- Required daily pace
- Current streak
- Projected completion date
- Strongest skills
- Biggest skill gaps

### Skill Map

A radar-style visualization shows progress across:

- Foundations
- ML & DL
- GenAI
- Production
- Interview preparation

### Gamification

The project includes XP, levels, and achievement badges.

Levels progress from:

`Starter → Explorer → Builder → Practitioner → Specialist → Expert → Interview-ready → Offer-ready`

### Theme Support

The application supports light and dark themes.

### Local Persistence

Progress is automatically saved in the browser using `localStorage`, allowing the user to close and reopen the application without losing progress.

## 🛠️ Tech Stack

- HTML5
- CSS3
- JavaScript
- SVG
- Browser LocalStorage

No backend or database is required.

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone <your-repository-url>
cd <project-folder>
```

### 2. Open the application

Since the project is a standalone HTML application, simply open:

```text
index.html
```

in any modern web browser.

Alternatively, run it using a local development server:

```bash
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## 📁 Project Structure

```text
.
├── index.html
└── README.md
```

The application is intentionally lightweight and currently implemented as a single HTML file containing:

- HTML structure
- CSS styling
- JavaScript logic
- Learning roadmap
- Progress tracking
- Visualizations

## 💾 Data Storage

The application stores user progress locally in the browser.

The main storage key is:

```text
ck180
```

Stored information includes:

- Completed concepts
- Daily check-ins
- Study history
- Open sections
- Last selected topic

No external database is required.

## 🎨 Design

The interface uses:

- Responsive layout
- Gradient hero section
- Progress ring
- Interactive cards
- Skill radar
- Progress charts
- Achievement badges
- Light/dark theme
- Mobile-friendly layout

## 🔮 Future Improvements

Potential improvements include:

- Backend-based user accounts
- Cloud synchronization
- Authentication
- PostgreSQL/Firebase storage
- Daily reminders
- AI-powered study recommendations
- Interview question generation
- Personalized revision plans
- LeetCode integration
- GitHub integration
- Progress analytics
- Weekly reports
- AI interview simulator

## 📌 Goal

The ultimate goal of this project is simple:

> **Turn consistent daily preparation into interview readiness within 180 days.**

Every concept completed, every problem solved, and every day checked in moves the learner one step closer to the target role.

## 👨‍💻 Author

**Utsav Sarkar**

Built as a personal interview preparation and skill-tracking system.
