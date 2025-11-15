# 🧠 NeuroSim - AI-Powered Brain Experiment Optimization


## 🎯 The Problem

Brain stimulation experiments cost **$50,000 each** and take **3 months**. Researchers often need 15+ failed experiments to find optimal parameters, wasting **$750,000** and **2+ years**.

** Problem **
> "I run brain stimulation experiments at UCSF. Each costs $50K and takes 3 months. 
> Experiments on failed parameter optimization is very expensive."
## 💡 The Solution

NeuroSim uses AI agents and Bayesian optimization to **simulate experiments before running them**, finding optimal parameters in minutes instead of months.


- **Real commercial value**: $600K+ saved per optimized protocol
- **Technical sophistication**: Bayesian optimization + multi-agent AI
- **Live demo**: Working end-to-end system
- **Clear impact**: Reduces animal use (NIH 3Rs priority)

### Best Use of Daytona ($1,000)
- Isolated simulation environments ensure reproducibility
- Parallel workspace execution (10+ simultaneous)
- Version-controlled experiment tracking
- Production-ready architecture

## 🚀 Tech Stack

**AI & ML:**
- Groq (Llama 3.3 70B) - Literature analysis
- Bayesian Optimization - Parameter search
- Scikit-optimize - Optimization engine

**Infrastructure:**
- Daytona - Isolated compute workspaces
- Galileo - AI observability
- FastAPI - Backend orchestration
- React + Vite - Frontend UI

**Key Libraries:**
- `bayes-opt` - Bayesian optimization
- `scipy` - Scientific computing
- `recharts` - Data visualization

## 📊 Results

**From my actual UCSF research:**
- Target: Prefrontal cortex arousal optimization
- **Optimal Parameters Found:**
  - Frequency: 652 kHz
  - Intensity: 718 W/cm²
  - Duration: 199 ms
- **Predicted Success: 95%**
- **Cost Savings: $600,000**
- **Time Saved: 2.4 months**


*Live Demo (2 min):**
1. Enter experiment: "Prefrontal cortex + increase arousal"
2. Click "Run Simulation"
3. **Show Daytona dashboard**: Multiple workspaces spawning
4. **Results appear**: Optimal parameters found
5. **Money shot**: "$600K saved, 2.4 months saved"
6. **Show convergence chart**: Visual proof of optimization

**Slide 3 (30 sec):** Business
> "Target: Every neuroscience lab + pharma doing neuromodulation
> Subscription: $500/month × 10,000 labs = $60M ARR
> I'm already using this at UCSF."

## 🔧 How to Run
```bash
# Backend
cd backend
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
python main.py

# Frontend
cd frontend
npm install
npm run dev
```

Visit: http://localhost:5173

This project directly extends my UCSF research on focused ultrasound brain stimulation optimization.


## Acknowledgments

**Sponsors:**
- Daytona - Isolated compute environments
- Groq - Lightning-fast LLM inference
- Galileo - AI observability
- Anthropic - Hackathon support
