# 🤖 Excuse Bot — AI-Powered Excuse Generator

## 📌 Objective
An intelligent excuse generator powered by a Large Language Model (LLM)
that creates believable, context-aware excuses with multilingual support,
voice output, and history tracking.

## ✨ Features
- 🧠 **LLM-powered** excuse generation using Zephyr-7B
- 🌐 **Multilingual** — generates excuses in English and Hindi
- 🎙️ **Voice output** — converts excuses to speech using gTTS
- 📧 **SMS & Email drafts** — ready-to-send templates
- 😢 **Apology mode** — emotional, guilt-tripping excuses
- 📊 **Ranking system** — scores excuses by clarity and empathy
- 🕐 **Time-based suggestions** — context-aware by time of day
- 📁 **History tracking** — logs all generated excuses to CSV

## 🛠️ Technologies Used
- Python
- HuggingFace Transformers (Zephyr-7B-Beta)
- MarianMT (English → Hindi translation)
- gTTS (Google Text-to-Speech)
- Pandas
- PyTorch
- Google Colab (T4 GPU)

## 🎭 Supported Scenarios
- Work · School · Social · Family

## ⚙️ Tone & Urgency Options
- **Tone:** Professional, Sincere, Casual
- **Urgency:** Low, Medium, High

## 🚀 How to Run
1. Open `majorproject_excusebot.ipynb` in Google Colab
2. Enable GPU runtime (T4)
3. Login to HuggingFace using `hf auth login`
4. Run all cells and try the demo at the bottom

## 💡 What I Learned
- How to use open-source LLMs via HuggingFace pipelines
- Text generation with prompt engineering
- Neural machine translation with MarianMT
- Text-to-speech integration with gTTS
- Building end-to-end NLP applications
