# Meeting Minutes Generator 🎙️📝

An automated tool to **transcribe audio recordings and generate structured meeting minutes** using AI.  
This project takes audio files and produces professional meeting minutes including summaries, discussion points, takeaways, and action items.

---

## Description

**English:**

Meeting Minutes Generator is a practical AI-powered tool that automates the creation of meeting minutes from audio recordings. It combines automatic speech recognition (ASR) with large language models (LLMs) to transcribe audio and generate well-structured, professional documentation. The tool supports both open-source models (Whisper + Llama) and commercial APIs (OpenAI), giving users flexibility based on their needs and resources. Perfect for any type of meeting, interview, or recorded discussion that needs documentation.

**Français:**

Meeting Minutes Generator est un outil pratique alimenté par l'IA qui automatise la création de comptes rendus de réunions à partir d'enregistrements audio. Il combine la reconnaissance vocale automatique (ASR) avec des modèles de langage (LLM) pour transcrire l'audio et générer une documentation structurée et professionnelle. L'outil prend en charge à la fois les modèles open source (Whisper + Llama) et les API commerciales (OpenAI), offrant aux utilisateurs une flexibilité selon leurs besoins et ressources. Parfait pour tout type de réunion, d'interview ou de discussion enregistrée nécessitant une documentation.

---

## Features

- **Dual Transcription Options:**
  - Open-source: Whisper via Hugging Face Transformers
  - Commercial: OpenAI Whisper API
- **Automated Minutes Generation** using LLMs (Llama or GPT)
- **Structured Output** including:
  - Meeting summary with attendees, location, and date
  - Key discussion points
  - Takeaways
  - Action items with assigned owners
- **Flexible Input** - works with any audio format (MP3, WAV, etc.)
- **GPU Acceleration** support for faster processing
- **Markdown Formatting** for clean, shareable outputs

---

### Prerequisites

- Python 3.8+
- GPU with CUDA support (recommended) or Google Colab
- Hugging Face account and token
- OpenAI API key (optional, for commercial transcription)
