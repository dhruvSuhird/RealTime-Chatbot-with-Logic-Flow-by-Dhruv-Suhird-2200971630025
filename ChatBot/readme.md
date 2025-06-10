# RealTime Chatbot with Logic Flow

A real-time, emotion-aware chatbot web application built using Flask (Python), HTML, and CSS. The chatbot uses a logic flow powered by a JSON configuration to provide empathetic responses, suggest activities, and answer knowledge-based queries in real time.

---

## Features

- **Emotion Recognition:** Responds empathetically to user emotions and triggers appropriate follow-ups.
- **Activity Suggestions:** Offers well-being activities like breathing exercises, creative prompts, gratitude practice, and more.
- **Knowledge Base:** Shares facts, quotes, and definitions upon request.
- **Customizable Logic Flow:** Easily update triggers, follow-ups, and activities in `dialog_flow.json`.
- **Real-time Chat Interface:** Modern, responsive UI.

---

## Dataset Used

- The chatbot's knowledge base, dialog triggers, and response flows are defined in [`dialog_flow.json`](dialog_flow.json).
    - **Dialog triggers:** Map user phrases to emotional states and responses.
    - **Activities:** List of well-being and productivity activities.
    - **Knowledge base:** Includes facts, quotes, and definitions for quick retrieval.

This dataset is hand-crafted for demo and educational purposes and can be extended for richer conversations.

---

## Approach Summary

- **Logic Flow:** The chatbot does not use machine learning; instead, it maps user input to triggers, follow-ups, and knowledge using pattern matching and keywords defined in a JSON file.
- **Flexible Parsing:** The backend parses user commands for activity/knowledge requests (e.g., "give me a quote", "definition of stress") and intelligently matches them to the appropriate response.
- **Emotion Icons:** Each response is associated with an emotion, displayed as an emoji in the chat UI.
- **Frontend-Backend Communication:** Uses AJAX (fetch) for real-time, seamless chat experience.

---

## Dependencies

- **Python >= 3.7**
- **Flask**
- (Frontend) **Bootstrap 5** (via CDN)

### Install dependencies:
```bash
pip install flask
```

---

## Getting Started

1. **Clone the repository:**
    ```bash
    git clone https://github.com/dhruvSuhird/RealTime-Chatbot-with-Logic-Flow-by-Dhruv-Suhird-2200971630025.git
    cd RealTime-Chatbot-with-Logic-Flow-by-Dhruv-Suhird-2200971630025
    ```

2. **Run the application:**
    ```bash
    python app.py
    ```
    The app will run at [http://127.0.0.1:5000/](http://127.0.0.1:5000/)

3. **Open in your browser:**
    - Go to [http://127.0.0.1:5000/](http://127.0.0.1:5000/)

---

## File Structure

```
.
├── app.py                # Flask backend with logic flow
├── dialog_flow.json      # JSON-based logic, triggers, activities, and knowledge base
├── templates/
│   └── index.html        # Main chat UI
├── static/
│   └── style.css         # Custom styles
└── README.md
```

---

## Example Activities & Queries

- `breathing exercise`
- `give me a quote`
- `tell me a fact`
- `definition of stress`
- `I'm feeling sad`
- `surprise me`
- `mini workout`

---

**Created by Dhruv Suhird**
