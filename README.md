🤖 Smart Chat Assistant:

A sleek, responsive, and voice-enabled web-based chat assistant powered by a large language model (LLM) API. This project integrates modern UI design, dark mode toggle, voice input, local storage for chat history, and real-time typing indicators — delivering an intuitive chat experience straight from your browser.

🚀 Features:

- ✅ Real-time chat with LLM API
- 🎤 Voice input using Web Speech API
- 💬 Chat history stored in `localStorage`
- 🌗 Dark mode toggle
- 🧹 One-click chat clear button
- 🕐 Timestamps for messages
- 🔊 Speech output for bot replies

📁 Project Structure:

📦 Smart-Chat-Assistant/
├── index.html           # Main HTML page
├── style.css            # All UI styling (light & dark mode)
├── main.js              # App logic, API integration, voice I/O, theme, storage
├── api.txt              # Legacy bot code (now integrated)
└── settings.json        # VS Code live server settings

📸 Demo

- Type or speak a message and receive intelligent responses in real time.  
- ✨ Enjoy the UI with toggled themes and smooth animations.

![screenshot-placeholder](https://via.placeholder.com/800x400?text=Chat+UI+Preview)

🔐 API Info:

This project uses the following LLM API:
https://backend.buildpicoapps.com/aero/run/llm-api?pk=YOUR_API_KEY
You must obtain your own API key and replace it in `main.js`.

⚙️ Voice Recognition Support:

Voice input works on most modern browsers (Chrome recommended).
Ensure microphone permissions are allowed.

📦 Dependencies

- [Google Fonts Material Icons](https://fonts.google.com/icons)
- [Web Speech API](https://developer.mozilla.org/en-US/docs/Web/API/Web_Speech_API) (for voice recognition/output)

📌 Notes:

- Chat history is stored locally in the browser and can be cleared using the delete button.
- Type `/clear` to wipe messages from memory.
- No backend or database required — 100% frontend.



> Created by devangjain999 — Feel free to fork and enhance!
