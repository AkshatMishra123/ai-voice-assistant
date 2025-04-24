# AI Voice Assistant

An AI Voice Assistant built using Python that performs a variety of tasks via voice commands. It can interact with the user using speech recognition and text-to-speech technologies. The assistant is also designed to be extended with a dynamic UI using **Streamlit** in the future.

---

## Features

- **Speech Recognition**: Understands voice commands using the `speech_recognition` library.
- **Text-to-Speech**: Responds with natural-sounding voice using `pyttsx3`.
- **Web Searches**: Open websites like YouTube, Google, StackOverflow.
- **Wikipedia Search**: Search for information on Wikipedia and read out summaries.
- **Time Announcements**: Provides the current time.
- **System Control**: Opens software like Visual Studio Code.
- **Email Functionality**: Send emails via voice command (Gmail integration).

---

## Tech Stack

- **Programming Language**: Python
- **Libraries**:
  - `speech_recognition`: For voice input and recognition.
  - `pyttsx3`: For text-to-speech output.
  - `wikipedia`: For Wikipedia queries.
  - `webbrowser`: For opening websites.
  - `smtplib`: For email sending functionality.
  - **Streamlit** (upcoming): For building an interactive UI.

---

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/ai-voice-assistant.git
   cd ai-voice-assistant
