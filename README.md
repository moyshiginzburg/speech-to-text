# ✍️ Speech-to-Text

[**🌐 Click here to access the app**](https://moyshiginzburg.github.io/speech-to-text/)

An advanced speech-to-text system, enabling real-time dictation and audio file transcription via the browser, with an emphasis on the Hebrew language.
The application runs directly without installation and is completely secure - your API keys are saved locally on your browser only.

## ✨ Main Features

- **Continuous Real-Time Dictation:** Simply click the microphone and start speaking.
- **File Transcription (Upload):** Support for uploading audio and video files (MP3, WAV, M4A, OGG, etc.) for automatic transcription.
- **Support for A Variety of Leading Transcription Engines:**
  - ⚡ **ElevenLabs** (Scribe v2 Realtime) - Next-generation speech recognition, extremely fast and accurate (Requires API Key).
  - 🎯 **Deepgram** (Nova-3) - A fast and accurate real-time alternative (Requires API Key).
  - 🔍 **Google Web Speech API** - Free, works only in the Chrome browser.
  - 🇮🇱 **ivrit.ai** (Whisper) - Transcription based on a Whisper model trained specifically for Hebrew (Files only, requires Token in HuggingFace).
  - 🤖 **OpenAI** (Whisper-1) - Reliable multilingual voice recognition from OpenAI (Files only).
  - ☁️ **Azure Speech-to-Text** - Microsoft Azure speech recognition service, high accuracy and multi-language support (Files only, requires API Key + Azure Region).
  - ✨ **Gemini** (Google AI) - Transcription using Google's Gemini language model, including punctuation and line breaks (Files only, requires API Key).
  - 🆓 **Local Whisper** (Transformers.js) - Runs the Whisper-Tiny model directly in the browser without any API Key and completely free. The model (~77MB) is downloaded once and cached. Suitable for uploading files, with processing speed limitations (Files only).
- **Elegant and Practical User Interface:** A convenient editing window, statistics tracking tools (word count, character count, dictation time), and easy editing options.
- **Quick Copy and Download:** One click to copy the text or download it as a text file to your computer.

## 🚀 How to Get Started?

1. Go to the [**App Hosted on GitHub Pages**](https://moyshiginzburg.github.io/speech-to-text/).
2. Select the transcription engine you want to work with.
3. If necessary (ElevenLabs / Deepgram / OpenAI / ivrit.ai / Azure / Gemini), enter your API key. The key is stored securely in the browser environment and is only available for your requests to the relevant servers.
4. Click the microphone button 🎙️ to start real-time dictation, or alternatively drag a file to the designated area 📁.
5. Enjoy accurate and simple voice typing effortlessly!

## 🛠️ Technologies and Structure
The application is lightweight, with no heavy third-party dependencies, built entirely using:
- **Vanilla Web Technologies:** Written in HTML5, modern CSS (including variables, Flexbox), and clean JavaScript without external libraries (Zero dependencies).
- **Web Audio API & WebSockets:** Capturing audio at the bit level through the microphone and transmitting it directly for transcription via live streaming with WebSockets for optimal performance (ElevenLabs and Deepgram).
- **Responsive Design:** A clean, meticulously designed responsive experience with full support for mobile and wide screens.

---
*This project was created to provide a high-quality, accessible, and fast solution for all needs regarding voice typing and audio transcription to Hebrew and other languages.*
