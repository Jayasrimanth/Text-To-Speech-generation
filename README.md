### README: Text-to-Speech Application with Cohere Integration

---

#### **Description**
This is a simple and interactive web application that combines text summarization (optional) and text-to-speech (TTS) conversion. The app uses:
- **Cohere API** for text summarization.
- **Google Text-to-Speech (gTTS)** for generating speech from text.
- **Streamlit** to create a user-friendly interface.

---

#### **Features**
1. **Text Input**: Users can input custom text via a text area.
2. **Summarization**: Use Cohere's summarization model to create concise versions of the input text (optional).
3. **Text-to-Speech**: Convert the input (or summarized) text into speech and play it directly in the browser.
4. **Simple UI**: A clean interface built with Streamlit for easy use.

---

#### **Requirements**
Ensure the following dependencies are installed:
- **Python 3.7+**
- Streamlit
- gTTS
- Cohere Python SDK (`cohere`)

You will also need:
- A valid Cohere API key. Register at [Cohere](https://cohere.com) to get an API key.

---

#### **Installation**
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/text-to-speech-app.git
   cd text-to-speech-app
   ```

2. Install the required Python packages:
   ```bash
   pip install streamlit gtts cohere
   ```

3. Add your **Cohere API key** to the script:
   Replace the placeholder in the code:
   ```python
   API_KEY = "your_api_key_here"
   ```

---

#### **Usage**
1. Run the application locally using Streamlit:
   ```bash
   streamlit run app.py
   ```

2. Open the app in your browser (usually `http://localhost:8501`).

3. Interact with the app:
   - Enter text in the text area.
   - Optionally summarize the text by clicking **Summarize Text with Cohere**.
   - Convert the text to speech by clicking **Convert Text to Speech**.
   - Listen to the generated speech directly on the app.

---

#### **File Structure**
- `app.py`: Main application file.

---

#### **Notes**
- Ensure you have an active internet connection since the app relies on external APIs.
- Replace `"output.mp3"` with a unique name for each TTS conversion if you need multiple files.

---

#### **License**
This project is licensed under the MIT License. Feel free to use, modify, and distribute.

---

**Developed with ❤️ using Python, Streamlit, and Cohere.**
