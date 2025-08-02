# 🤖 AI Customer Support Agent

An **AI-powered customer support agent** built using **LangGraph, LangChain, and Gradio**, capable of:
- Automatically **categorizing customer queries** into **Technical, Billing, or General**
- **Analyzing sentiment** (Positive, Neutral, Negative)
- **Providing automated responses**
- **Escalating negative queries** to human agents

This project demonstrates **AI-driven customer support automation** and provides a **simple web interface** using **Gradio**.

---

## 📌 Features
- **Smart Categorization:** Automatically classifies queries into Technical, Billing, or General.
- **Sentiment Analysis:** Identifies if a query is Positive, Neutral, or Negative.
- **Dynamic Response Generation:** Provides helpful replies using **Groq LLaMA 3.3-70B**.
- **Escalation Handling:** Negative queries are flagged for human attention.
- **Web Deployment with Gradio:** Users can interact with the agent in a browser.

---

## 🛠️ Tech Stack
- **Python 3.10+**
- **LangChain & LangGraph**
- **Groq LLM (LLaMA 3.3-70B)**
- **Gradio for Web Interface**

---

## 🚀 Getting Started

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/username/ai-customer-support-agent.git
cd ai-customer-support-agent
pip install -r requirements.txt
python app.py
```

### Sample Interaction
```
Where can I find my receipt?
{
  "Category": "Billing",
  "Sentiment": "Neutral",
  "Response": "You can find your receipt in your account under 'Order History'."
}
```
### Project Structure
```
ai-customer-support-agent/
│
├── app.py              # Main Gradio application
├── requirements.txt    # Python dependencies
├── README.md           # Project documentation
└── sample_output.json  # Example interaction output
```
