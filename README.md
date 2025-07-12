
# 🎙️ Gemini Voice-Enabled Q&A Chatbot

This project is a simple yet powerful **voice-controlled chatbot** powered by **Google's Gemini API**. It listens to your spoken queries, fetches intelligent responses from Gemini, and speaks the answers back to you.

## 🧠 Features

- 🎤 Converts voice to text using Google Speech Recognition
- 💬 Asks questions to the Gemini model (1.5 Flash)
- 🗣️ Reads answers aloud using Text-to-Speech
- 🔄 Supports continuous interaction in a loop
- 🛑 Exit with voice command: `exit`, `quit`, or `stop`


## 🛠️ Requirements

Install the required Python packages:

```bash
pip install google-generativeai
pip install SpeechRecognition pyttsx3 pyaudio
````

> 🔊 `pyaudio` may require system-level dependencies. On Ubuntu/Debian, run:
>
> ```bash
> sudo apt-get install portaudio19-dev
> ```

---

## 🔐 Setup

1. **Get a Gemini API Key**

   * Go to [Google AI Studio](https://makersuite.google.com/app)
   * Generate your API key from the [API key settings](https://aistudio.google.com/app/apikey)

2. **Replace in Code**
   Open the notebook and replace this line:

   ```python
   GOOGLE_API_KEY = "YOUR_GEMINI_API_KEY"
   ```

---

## 🚀 Running the Bot

Run the notebook `Gemini_QA_Chatbot.ipynb` in Jupyter or Google Colab.

Once started:

* The bot will prompt you to **speak**.
* It will send your query to Gemini and **read the response** back.
* Say `"exit"` or `"quit"` to end the session.

---

## 🧪 Example

```text
🗣️ You said: What is quantum computing?
🤖 Gemini: Quantum computing is a type of computation that harnesses the principles of quantum mechanics...
```

---

## 📁 File Structure

```
.
├── Gemini_QA_Chatbot.ipynb   # Main notebook
└── README.md                 # Project documentation
```

---

📚 Future Improvements

* GUI interface (e.g., Streamlit or Tkinter)
* Multilingual support
* Intent classification for broader tasks
* Integration with Alexa or Google Assistant hardware

---

📜 License

This project is open-source under the [MIT License](LICENSE).

---

## 🤝 Credits

Built using:

* [Google Generative AI (Gemini)](https://ai.google.dev/)
* [SpeechRecognition](https://pypi.org/project/SpeechRecognition/)
* [pyttsx3 TTS Engine](https://pypi.org/project/pyttsx3/)

---
