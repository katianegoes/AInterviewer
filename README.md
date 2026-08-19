# AInterviewer

AInterviewer is an AI-powered mock interview app built with Streamlit. It tailors interview questions to a candidate's experience, skills, target role, and company, then provides a score and personalized feedback.

## Features

- Collects candidate background and target role details
- Conducts a five-question interview using OpenAI
- Adapts questions to the candidate's experience level and position
- Provides an overall score, strengths, improvement areas, and a practical recommendation

## Requirements

- Python 3.11 or newer
- An OpenAI API key

## Setup

1. Clone the repository and open the project directory.

2. Create and activate a virtual environment:

   ```bash
   python3 -m venv .venv
   source .venv/bin/activate
   ```

3. Install the dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Create `.streamlit/secrets.toml` and add your OpenAI API key:

   ```toml
   OPEN_AI_KEY = "your-openai-api-key"
   ```

   Keep this file private and do not commit it to GitHub.

## Run the app

```bash
streamlit run app.py
```

Then open the local URL displayed by Streamlit in your browser.

## Tech stack

- Python
- Streamlit
- OpenAI API
- streamlit-js-eval
