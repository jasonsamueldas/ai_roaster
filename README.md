# Roastify Me

Welcome to **Roastify Me** — a playful and sassy Streamlit web app that dishes out roasts or compliments based on your mood or text input. Whether you're feeling fabulous or need a little love, this app’s got your vibe covered!

---

## Features

- **Roast or Compliment Mode**: Flip between sass and sweetness.
- **Mood Slider**: Adjust your mood to change the tone.
- **Mirror Mode**: Roasts you using your exact words!
- **TTS (Text-to-Speech)**: Hear your roast or compliment aloud.
- **Random Surprise**: Get a surprise roast/compliment.
- **GIF Reactions**: Get spicy with random reaction GIFs.
- **History Log**: Keeps track of all your sassy moments.

---

## Installation

### Prerequisites

- Python 3.8+
- `pip` (Python package manager)

### Clone & Run

```bash
git clone https://github.com/yourusername/roastify-me.git
cd roastify-me
pip install -r requirements.txt
streamlit run app.py
```

---

## How It Works

- **Sentiment Analysis** using `TextBlob` detects tone from user input.
- Roasts are chosen from a curated roast bank (positive, neutral, or negative).
- Compliments are served sweet using a similar logic (defined in `compliment_engine.py`).
- Mood can be overridden with a slider for more control.

---

## Project Structure

```
roastify-me
├── app.py                  # Streamlit app
├── roast_engine.py         # Roast logic based on sentiment
├── compliment_engine.py    # Compliment generator
├── roast_bank.py           # Lists of roasts
├── compliment_bank.py      # Lists of compliments
├── roast_log.txt           # User input/output logs
├── requirements.txt        # Dependencies
└── README.md               # You are here!
```

---

## Requirements

```txt
streamlit
textblob
gTTS
```
