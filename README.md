
# 🤖 LUMIX Agent

LUMIX Agent is a simple, open-source AI tool powered by $LUMIX on Solana. It helps users interact with AI through a lightweight Flask API. No hype — just clean and useful code backed by the community.

---

## 🔧 Features

- OpenAI-powered AI assistant  
- One endpoint: `/ask`  
- Lightweight Flask app  
- Easy to run locally or on a VPS  
- Built to support the $LUMIX ecosystem  

---

## 💰 What’s $LUMIX?

$LUMIX is a meme token on Solana that stands for real utility — not fluff. We build open tools like this to give our token purpose, visibility, and real-world use.

---

## 🌍 Links

- Twitter: [https://twitter.com/LumixSol](https://twitter.com/LumixSol)  
- Website: Coming soon  
- Pump.fun: [https://pump.fun/LUMIX](https://pump.fun/LUMIX)

---

## 🚀 Getting Started

### Requirements

- Python 3.8+  
- OpenAI API key

### Setup

```bash
git clone https://github.com/YOUR_USERNAME/lumix-agent.git
cd lumix-agent
pip install -r requirements.txt
cp .env.example .env
# Add your OpenAI key to the .env file
python web.py
```

---

## 💬 Example Usage

Once it’s running, send a request like this:

```bash
curl -X POST http://localhost:5000/ask -H "Content-Type: application/json" -d '{"message": "Tell me about Solana"}'
```

```json
{
  "reply": "Solana is a high-performance blockchain built for speed and low fees."
}
```

---

## 🧠 Stack

- Python 3  
- Flask  
- OpenAI GPT API  
- dotenv  

---

## 🔓 License

MIT — free to use, fork, and contribute.

---

Built by the $LUMIX community. No fluff. Just code.
