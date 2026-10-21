# 🛍️ ShopMind AI (Multimodal E-Commerce Copilot)

An advanced multimodal e-commerce copilot designed to bridge visual search, intelligent recommendations, and context-aware product Q&A.

## 🚀 Key Features
* **Visual Search Integration:** Leverages **CLIP** to enable seamless image-to-product matching and visual discovery.
* **Hybrid Recommendation Engine:** Combines user preferences and product features to deliver accurate, tailored item suggestions.
* **RAG-Based Product Q&A:** Implements Retrieval-Augmented Generation to allow users to query product details dynamically.
* **High-Performance Backend:** Built using **FastAPI** paired with **Pandas** for efficient data processing and real-time inference.
* **Reliability Fallbacks:** Features automatic LLM fallback modes to guarantee continuous system uptime and a smooth user experience.

## 🛠️ Tech Stack
* **Language:** Python
* **Framework:** FastAPI
* **AI & Vision:** PyTorch, Hugging Face Transformers, CLIP, LangChain
* **Data Processing:** Pandas, NumPy

## ⚙️ Quick Start / Installation
1. Clone the repository:
   ```bash
   git clone [https://github.com/AnonymousPub/ShopMind-AI.git](https://github.com/AnonymousPub/ShopMind-AI.git)
   cd ShopMind-AI

Step 2: Set up a Virtual Environment 
Bash
python -m venv venv
source venv/bin/activate

Step 3: Install Dependencies
Bash
pip install -r requirements.txt

Step 4: Run the Application
Start the FastAPI backend server:
Bash
uvicorn app:app --reload
