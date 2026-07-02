# 🚀 AI Viral Video Generator

**Local AI-powered** viral video idea & script generator with professional video production using **Kie AI + Veo 3.1**.

Local LLM ile yaratıcı fikir ve script üretip, Kie AI + Google Veo 3.1 ile yüksek kaliteli video oluşturan tam otomatik pipeline.

## ✨ Features

- **Fully local** idea & script generation (LM Studio)
- Strong creative output with viral hooks and storytelling
- Professional structured scripts optimized for YouTube Shorts, TikTok & Reels
- Integration with **Kie AI** and **Google Veo 3.1** for video generation
- End-to-end workflow (Idea → Script → Video Prompt → Final Video)
- Privacy-focused (chat/idea part stays completely local)

## 📸 Demo
Coming soon.

## 🛠 Tech Stack

- **n8n** (Self-hosted)
- **LM Studio** + Local LLM (I used qwen/qwen2.5-coder-14b)
- **Kie AI** + **Google Veo 3.1** (Video Generation)
- Latest n8n Agent Node (v3)

## 🙏 Credits

- **Template**: [Dr. Firas](https://n8n.io/creators/drfiras/) – Thank you for the amazing base template, i updated some nodes and make it compatible with local models. 

## 🚀 Quick Start

### Requirements
- LM Studio (Local Server running)
- n8n Self-hosted
- Access to Kie AI + Veo 3.1
- Minimum 16GB VRAM recommended

### Setup
1. **n8n**
 - Import the workflow JSON
 - Create **OpenAI Chat Model** credential:
   - Base URL: `http://localhost:1234/v1`
   - Model: `qwen/qwen2.5-coder-14b`
 - Configure Generate Video node and add your credentials.

2. Activate and test the workflow.

## 📝 Workflow Stages

1. Idea & Concept Generation (Local LLM)
2. Viral Script Writing (Local LLM)
3. Video Prompt Engineering (Local LLM)
4. Video Generation (Kie AI + Veo 3.1)

## 📁 Project Structure
├── workflow/
│   └── ai-viral-video-generator.json
├── demo/
│   └── demo.mp4
├── README.md
└── LICENSE
