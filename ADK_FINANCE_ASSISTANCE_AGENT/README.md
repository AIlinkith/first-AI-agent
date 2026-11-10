# ADK Finance Assistance Agent

A simple finance assistant built with Google's Agent Development Kit (ADK),
following the structure shown in the reference screenshot.

## Project structure

```text
ADK_FINANCE_ASSISTANCE_AGENT/
├── finance_assistance_agent/
│   ├── __init__.py
│   └── agent.py
├── .env
├── .env.example
├── README.md
└── requirements.txt
```

## Setup (Windows PowerShell)

1. Install Python 3.10 or newer.
2. Open this folder in VS Code.
3. Create and activate a virtual environment:

   ```powershell
   py -m venv .venv
   .\.venv\Scripts\Activate.ps1
   ```

4. Install dependencies:

   ```powershell
   python -m pip install --upgrade pip
   pip install -r requirements.txt
   ```

5. Open `.env` and replace `YOUR_GEMINI_API_KEY_HERE` with your own
   Gemini API key. Do not share or commit this file.

6. From the project root, run the ADK web interface:

   ```powershell
   adk web
   ```

   Then open the local URL printed in the terminal and select
   `finance_assistance_agent`.

## Notes

- The `.venv` directory is intentionally not included: it is generated
  locally during setup and can be very large and platform-specific.
- The `.env` file contains a placeholder, not a working API key.
- This assistant provides general financial education, not personalized
  investment, tax, or legal advice.
