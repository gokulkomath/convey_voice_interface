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
```

🚀 How to Run
To get the Convey Voice Assistant Interface up and running, follow these two simple steps:

1. Start the Rasa Chatbot
First, you need to launch your main Convey Rasa chatbot. Open your first terminal, navigate to your main Convey project directory, and run the Rasa server with the API enabled:

Bash

rasa run --enable-api
This command will start the Rasa chatbot, which will be ready to process requests from the voice interface.

2. Run the Voice Interface
Next, open a second terminal. Navigate to the directory where this convey_voice_interface.py file is located. Then, execute the Python script:

Bash

python convey_voice_interface.py
Once the script starts, it will begin listening for your voice through your microphone. You can then start speaking to interact naturally with your Convey AI assistant!
