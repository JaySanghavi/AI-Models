# AI Models – Experimental AI Research Projects

## Overview

This repository contains a collection of experimental AI projects exploring cutting-edge multimodal AI models. The notebooks demonstrate practical applications of modern AI systems across **vision, language, speech, and video generation**.

The goal of this repository is to explore and experiment with advanced AI capabilities such as:

- Vision-language models
- Text-to-video generation
- Speech transcription and speaker diarization

All experiments are implemented in **Jupyter notebooks** to allow interactive exploration of the models.

---

# Repository Structure

```
AI-Models/
│
├── Image_Text_To_Text_Qwen_Qwen2_VL_2B_Instruct.ipynb
├── Text_2_Video_Linum_AI_linum_v2_720p.ipynb
├── VoiceTranscribeandDiarization_ASR_openai_whisper_large_v3.ipynb
└── README.md
```

---

# Notebook Descriptions

## 1. Image + Text → Text (Vision Language Model)

**Notebook:**  
`Image_Text_To_Text_Qwen_Qwen2_VL_2B_Instruct.ipynb`

This notebook demonstrates how a **vision-language model** can understand both images and text prompts.

Capabilities include:

- image captioning
- visual question answering
- multimodal reasoning
- image understanding using text prompts

The notebook uses the **Qwen2-VL multimodal model**, which allows combining visual inputs with natural language queries.

Example tasks:

- describe the content of an image
- answer questions about an image
- generate text explanations from visual inputs

---

## 2. Text → Video Generation

**Notebook:**  
`Text_2_Video_Linum_AI_linum_v2_720p.ipynb`

This notebook demonstrates **AI-based video generation from text prompts**.

The model converts a textual description into a generated video sequence.

Example workflow:

```
Text Prompt
      ↓
Video Generation Model
      ↓
Generated Video Output
```

Example prompts:

- "A futuristic city with flying cars"
- "An astronaut walking on Mars"

The notebook uses the **Linum AI video generation model** to create short AI-generated videos.

---

## 3. Speech Transcription + Speaker Diarization

**Notebook:**  
`VoiceTranscribeandDiarization_ASR_openai_whisper_large_v3.ipynb`

This notebook demonstrates **automatic speech recognition (ASR)** and **speaker diarization**.

Capabilities include:

- converting speech to text
- identifying multiple speakers in audio
- segmenting conversations by speaker
- generating transcripts from audio files

The notebook uses **OpenAI Whisper Large v3**, a state-of-the-art speech recognition model.

Example pipeline:

```
Audio Input
     ↓
Speech Recognition Model
     ↓
Text Transcription
     ↓
Speaker Diarization
```

Example applications:

- meeting transcription
- podcast transcription
- call center analytics
- audio content indexing

---

# Technologies Used

- Python
- Jupyter Notebook
- PyTorch
- Transformers
- OpenAI Whisper
- Vision-Language Models
- Video Generation Models

---

# Installation

Install the required dependencies:

```bash
pip install torch transformers accelerate diffusers librosa opencv-python
```

---

# Running the Notebooks

Clone the repository:

```bash
git clone https://github.com/JaySanghavi/AI-Models.git
cd AI-Models
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open and run the notebooks:

```
Image_Text_To_Text_Qwen_Qwen2_VL_2B_Instruct.ipynb
Text_2_Video_Linum_AI_linum_v2_720p.ipynb
VoiceTranscribeandDiarization_ASR_openai_whisper_large_v3.ipynb
```

Run the cells sequentially to reproduce the experiments.

---

# Applications

These AI models can be used in many real-world applications:

### Vision + Language
- image captioning
- visual search
- multimodal assistants

### Video Generation
- AI content creation
- media production
- storytelling and animation

### Speech Recognition
- meeting transcription
- voice assistants
- call center analytics
- podcast processing

---

# Future Improvements

Possible future extensions include:

- integrating multimodal pipelines
- building real-time AI applications
- deploying models using APIs
- combining video, speech, and vision models into unified systems

---

# Author

Jay Sanghavi  

GitHub: https://github.com/JaySanghavi