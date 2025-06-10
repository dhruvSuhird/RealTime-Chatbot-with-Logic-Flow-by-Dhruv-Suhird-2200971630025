# RealTime Chatbot with Logic Flow

A real-time chatbot web application built using Flask (Python), HTML, and CSS that supports:
- Emotion-aware conversation flow
- Activity suggestions (breathing exercise, creative prompt, mood journaling, mini workout, gratitude practice, music suggestion)
- Knowledge base queries (fact, quote, definition)
- Custom logic flow via a JSON-driven dialog engine

## Features

- **Real-time Chat Interface:** Send and receive messages instantly with a modern, responsive UI.
- **Emotion Recognition:** The bot responds empathetically to user emotions and triggers appropriate follow-ups.
- **Activities and Suggestions:** Offers a variety of activities for mental well-being and productivity.
- **Knowledge Base:** Provides fun facts, quotes, and definitions upon request.
- **Customizable Logic Flow:** Easily update triggers, follow-ups, and activities in `dialog_flow.json`.

## Technologies Used

- **Backend:** Python (Flask)
- **Frontend:** HTML, CSS, Bootstrap, JavaScript (vanilla)
- **Logic Engine:** JSON-based dialog flow

## Getting Started

### Prerequisites

- Python 3.x
- Flask (`pip install flask`)

### Installation

1. **Clone the repository:**
    ```bash
    git clone https://github.com/dhruvSuhird/RealTime-Chatbot-with-Logic-Flow-by-Dhruv-Suhird-2200971630025.git
    cd RealTime-Chatbot-with-Logic-Flow-by-Dhruv-Suhird-2200971630025
    ```

2. **Install dependencies:**
    ```bash
    pip install flask
    ```

3. **Run the application:**
    ```bash
    python app.py
    ```
    The app will run on `http://127.0.0.1:5000/`

4. **Open in your browser:**
    - Go to [http://127.0.0.1:5000/](http://127.0.0.1:5000/)

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

## Customizing the Chatbot

- **Modify logic or add activities:**  
  Edit `dialog_flow.json` to add new triggers, responses, activities, or knowledge entries.

- **Change the UI:**  
  Edit `templates/index.html` and `static/style.css` for look & feel.

## Example Activities & Queries

- "breathing exercise"
- "give me a quote"
- "tell me a fact"
- "definition of stress"
- "I'm feeling sad"
- "surprise me"
- "mini workout"

---

**Created by Dhruv Suhird**
