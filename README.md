# Kokoro TTS - Open-Weight Text-to-Speech Model 🎙️

![Kokoro TTS](https://huggingface.co/hexgrad/Kokoro-82M)

**Kokoro TTS** is an open-weight text-to-speech (TTS) model with **82 million parameters**, designed for high-quality voice synthesis across multiple languages. This repository provides a Gradio-based web demo for generating speech from text.

---

## 🚀 Features

- **Multiple Voices**: Choose from a variety of male and female voices in different accents.
- **GPU Acceleration**: Supports CUDA-enabled GPUs for faster inference.
- **Custom Pronunciation**: Modify pronunciation with markdown syntax.
- **Streaming Support**: Stream audio output in real time.
- **Multi-Language Compatibility**: Although this demo focuses on English, the model can be used with other languages.

---

## 📌 Installation

To run this project locally, install the dependencies:

```bash
pip install gradio torch kokoro misaki
