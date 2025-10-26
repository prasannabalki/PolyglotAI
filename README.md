
**அகர முதல எழுத்தெல்லாம் ஆதி பகவன் முதற்றே உலகு.**  
*"As the letter 'A' is the first of all letters, so the eternal God is first in the world." — Thirukkural 1:1*

---

## 🌍 Overview

**Indic-LLM** is an open-source initiative to build a **multimodal and multilingual Large Language Model**, starting from **Tamil** and extending to other **Indic** and **global languages**.  
It combines **text, speech, and visual intelligence** to create a unified ecosystem that understands cultural nuance, linguistic variety, and multimodal information.

Unlike generic multilingual models, **Indic-LLM** emphasizes *cultural, linguistic, and phonetic precision* — beginning with Tamil (தமிழ்) and expanding to related Indian and foreign languages for cross-lingual communication and global inclusivity.

---

### 🧠 Supported Languages

| Category | Language | Script | Use Case / Purpose |
|-----------|-----------|---------|--------------------|
| 🇮🇳 **Indic Languages** | **Tamil (ta)** | தமிழ் | Core LLM training, OCR digitization, and speech interfaces |
| 🇮🇳  | **Hindi (hi)** | देवनागरी | National communication, e-governance, and education |
| 🇮🇳  | **Malayalam (ml)** | മലയാളം | Literature, media transcription, and accessibility |
| 🇮🇳  | **Kannada (kn)** | ಕನ್ನಡ | Academic, administrative, and regional dialogue |
| 🇮🇳  | **Telugu (te)** | తెలుగు | Healthcare, conversational AI, and subtitles |
| 🌏 **Foreign Languages** | **Japanese (ja)** | 日本語 | Technical documentation, translation, and educational use |
| 🇩🇪  | **German (de)** | Deutsch | Industrial and medical domain reasoning |
| 🇫🇷  | **French (fr)** | Français | Academic and policy communication |
| 🇪🇸  | **Spanish (es)** | Español | Cultural, conversational, and tourism-based applications |

---

### 🧩 Multimodal Capabilities

| Modality | Function | Description |
|-----------|-----------|-------------|
| 📝 **Text** | Tokenizer + LLM | Shared multilingual tokenizer and fine-tuned LLM with CT → SFT → DPO pipeline for fluency, translation, and politeness across languages. |
| 🔊 **Speech** | ASR + TTS | Whisper and Coqui TTS/VITS pipelines for Indic and global accents, supporting native pronunciation and cross-lingual voice interaction. |
| 🖼️ **OCR** | Image → Text | Tesseract + OpenCV with traineddata for Tamil, Devanagari, Malayalam, Kannada, Telugu, and Latin scripts — enabling universal document understanding. |
| 📚 **RAG** | Knowledge Retrieval | FAISS + multilingual Sentence-Transformers to ground model responses with factual data from Indic and global knowledge bases. |
| ⚙️ **Serving** | API + Interface | FastAPI + vLLM backend with a Gradio UI for interactive text, speech, and document queries. |

---

### 🔍 Why This Matters

India’s linguistic diversity — over **20+ official languages and 100+ dialects** — lacks open, high-quality AI models that respect script, accent, and context.  
**Indic-LLM** provides a foundation for:

- **Education & Accessibility:** Voice-based multilingual tutors and regional translation tools.  
- **Healthcare & Governance:** Real-time multilingual assistants for hospitals and public services.  
- **Cultural Preservation:** OCR and AI-based restoration of ancient texts and manuscripts.  
- **Research & Innovation:** Open-source datasets, tokenizers, and fine-tuning frameworks for multilingual LLMs.  
- **Global Communication:** Seamless Tamil–Japanese, Hindi–German, or Telugu–French translation and dialogue.

---

### 🧬 Key Innovations

- **Unified Indic + Foreign Tokenizer:** Hybrid SentencePiece vocabulary across 9 scripts.  
- **Cross-Lingual Pretraining:** Transfers knowledge between Tamil, Hindi, and Japanese corpora.  
- **SFT + DPO Alignment:** Politeness and tone adapted to each language’s culture.  
- **Multilingual ASR & TTS:** Native-sounding speech models for major Indic and foreign tongues.  
- **Multiscript OCR Pipeline:** Universal recognition across Indic and Latin-based scripts.  
- **FAISS-Based RAG:** Multilingual factual retrieval from Indic + Wikipedia sources.  
- **FastAPI + vLLM Serving:** Optimized for real-time, scalable inference across languages.

---

### 🌐 Vision

To create a **cross-cultural AI ecosystem** that:
- Understands the **semantics and tone** of Tamil and other Indic languages.  
- Enables **real-time translation** and **cross-language question answering**.  
- Unites **Indic and global linguistic ecosystems** under one multimodal LLM family.  
- Promotes **AI inclusivity** and **digital equality** across scripts, dialects, and borders.

---

### 🕉️ Impact

| Domain | Benefit |
|---------|----------|
| **Education** | Cross-lingual AI tutors in Tamil, Hindi, and global languages |
| **Healthcare** | Speech translation between regional and international doctors |
| **Governance** | Multilingual assistants for citizen communication |
| **Culture** | Digitization of literature and temples’ archival data |
| **Tourism & Diplomacy** | Tamil–Japanese–French AI interpreters for global collaboration |

---

### ✨ Summary

Together, these components form a **unified Indic–Global Multimodal AI Platform** that can **read, listen, translate, and respond** across:
> **Tamil · Hindi · Malayalam · Kannada · Telugu · Japanese · German · French · Spanish**

Bridging civilizations through the power of multilingual AI 🇮🇳🤝🌏
