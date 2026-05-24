# Gemini AI CLI Chatbot

This is a terminal-based chatbot created with the help of a Gemini API key. It allows you to have real-time conversations with the AI directly from your python IDE Terminal, command prompt or powershell.

---

## Instructions & Requirements

### 1. Python Installation
You need to install the latest version of Python. Download it from the official Python website:
https://www.python.org

During installation on Windows, make sure to check the box that says "Add Python to PATH" so you can run Python commands from your command prompt.

### 2. Install the Google GenAI SDK
The chatbot requires the official Google Generative AI library. Open your python IDE terminal, command prompt or powershell and run:

```cmd
pip install google-generativeai

```

If you get an error saying "pip is not recognized", it means Python wasn't added to your system path during installation. You can fix that easily by typing:

```cmd
python -m pip install google-generativeai

```

### 3. Get a Gemini API Key

To create your API key, go to Google AI Studio:
https://aistudio.google.com

Log in with your Gmail ID, create a new API key, and copy it.

---

## Setup & Execution

1. Download the `main.py` file from this repository.
2. Open the downloaded `main.py` file and locate the placeholder text `"YOUR_API_KEY"`.
3. Replace `"YOUR_API_KEY"` with your actual Gemini API key without " " and save (Ctrl+S) before running it.

### Ways to Run / Execute the Script

#### Method 1: From the CLI (Command Prompt / PowerShell / Python IDE Terminal)

1. Open your command prompt, powershell, or IDE terminal.
2. Navigate to the folder where you downloaded `main.py` using the `cd` command:

```cmd
   cd path/to/your/folder

```

3. Run the script by typing:

```cmd
   python main.py

```

#### Method 2: From Python IDLE

1. Open the file in Python IDLE.
2. Click on the "Run" tab in the top menu.
3. Select "Run Module" (or simply press F5 on your keyboard).
