# 🎯 PromptForge – Professional Structured Prompt Generator

A lightweight Python tool that converts simple user input into **high-quality, structured, production-ready prompts** using an LLM API.

---

## 🚀 What This Project Does

PromptForge takes a vague idea like:

> "futuristic city at night"

and turns it into a **cinematic, structured, detailed prompt** suitable for:
- AI image generation (Midjourney, Stable Diffusion, etc.)
- Creative direction
- Content ideation

---

## ⚙️ How It Works

1. User enters a simple prompt  
2. System injects a **strict professional prompt-engineering template**  
3. Request is sent to an LLM via API  
4. Model returns a **fully structured creative prompt**

---

## 📂 Project Structure

```
PromptForge/
│
├── prompt_gen_bot.py   # Main script (only file)
└── README.md
```

---

## 🛠️ Requirements

Install dependencies:

```bash
pip install requests
```

---

## 🔑 Setup API Key

Replace this line in code:

```python
API_KEY = "sk-or-v1-...."
```

with your actual API key.

---

## ▶️ How to Run

```bash
python prompt_gen_bot.py
```

Then enter your input:

```
Enter Your Prompt Here....: futuristic car
```

---

## 📌 Output Format

The system generates **9 structured sections**:

1. Creative Intent & Overview  
2. Main Prompt  
3. Composition Guide  
4. Style Direction  
5. Color & Lighting  
6. Typography  
7. Technical Parameters  
8. Negative Prompt  
9. Short Ready-to-Paste Prompt  

---

## 💡 Example

### Input:
```
a warrior in desert
```

### Output:
- Cinematic description  
- Lighting + textures  
- Camera details  
- Color palette  
- Final optimized prompt  

---

## 🔥 Features

- ✅ Converts vague ideas into professional prompts  
- ✅ Strict structured output (no randomness)  
- ✅ No hallucinated brands or entities  
- ✅ Works with any LLM API (currently OpenRouter)  
- ✅ Simple, single-file implementation  

---

## ⚠️ Limitations (Reality Check)

- No UI → CLI only  
- No memory → each input is independent  
- Fully dependent on API response quality  
- No retry / error handling logic (basic only)  
- Not production-ready  

---

## 🔧 Improvements You SHOULD Make (if serious)

If you want this to be job-worthy, fix these:

- Add retry + timeout handling  
- Add streaming response  
- Convert into API (FastAPI)  
- Build simple UI (Streamlit)  
- Add prompt versioning  
- Add logging + analytics  

Right now → this is a **demo tool, not a product**

---

## 🧪 Use Cases

- AI image prompt generation  
- Creative writing support  
- Content ideation  
- Design direction  

---

## 🧠 Core Idea

This project is NOT AI magic.

It is:
- Prompt template engineering  
- + API call  
- + formatted output  

If you think this is “intelligence” → you're misunderstanding the system.

---

## 👨‍💻 Author

Karan Mistry  
AI / GenAI Learner

---
