
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

$LUMIX is a meme token on Solana that stands for real utility — not fluff. We build open tools like this to give our token purpose, visibility, and real world use.

---

## 🌍 Links

- Twitter: [https://twitter.com/LumixSol](https://twitter.com/LumixSol)  
- Website: Coming soon  

---

## 🚀 Getting Started

### Requirements

- Python 3.8+  
- OpenAI API key

## 🚀 Setup

Follow these instructions to get LUMIX Agent up and running on your local machine.

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Lumixsol/lumix-agent.git
   cd lumix-agent
   ```

2. **Install the required dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Set up environment variables:**
   - Copy the example environment variables file:
     ```bash
     cp .env.example .env
     ```
   - Open the `.env` file and add your OpenAI API key:
     ```bash
     OPENAI_API_KEY=your_openai_api_key_here
     ```

4. **Run the Flask app:**
   ```bash
   python web.py
   ```

Once the app is running, it will listen on `http://localhost:5000`.

---

## 💬 Example Usage

After running the agent, send a request like this to the `/ask` endpoint:

```bash
curl -X POST http://localhost:5000/ask -H "Content-Type: application/json" -d '{"message": "Tell me about Solana"}'
```

**Response:**

```json
{
  "reply": "Solana is a high-performance blockchain built for speed and low fees."
}
```

## 🧠 Stack

- Python 3  
- Flask  
- OpenAI GPT API  
- dotenv  

---

## 🔓 License

MIT License — free to use, modify, distribute, fork, and contribute.

---

Built by the $LUMIX community. No fluff. Just code.
