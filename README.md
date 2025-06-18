# 🗣️ Convey Voice Assistant Interface

This project provides the **voice interface** for the main [**Convey**](https://github.com/gokulkomath/convey) project — an AI assistant powered by Rasa. It enables natural voice conversations with Convey using speech recognition (via Whisper), and text-to-speech (via Piper).

> 🔗 **Main Convey Project**: [github.com/gokulkomath/convey](https://github.com/gokulkomath/convey)

---

## 🎯 Features

- 🎙️ Real-time microphone input with auto-stop on silence
- 🧠 Fast transcription using `faster-whisper`
- 📅 Built-in handling for time/date queries
- 🤖 Sends queries to a Rasa chatbot running locally
- 🔊 Speaks responses using Piper TTS

---

## 🧰 Requirements

### Python Dependencies

```bash
pip install sounddevice numpy scipy requests fuzzywuzzy faster-whisper


rasa run --enable-api

python convey_voice_interface.py
