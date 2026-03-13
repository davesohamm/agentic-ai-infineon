
╔══════════════════════════════════════════════════════════════════════════════╗
║                             AGENTIC BUG HUNTER                               ║
║                                                                              ║
║                    AI-Powered Bug Detection for C++ Programs                 ║
╚══════════════════════════════════════════════════════════════════════════════╝


────────────────────────────────────────────────────────────────────────────────
OVERVIEW
────────────────────────────────────────────────────────────────────────────────

Agentic Bug Hunter is an AI-driven tool designed to automatically detect bugs
in C++ source code. The system leverages modern AI APIs to analyze code,
identify potential issues, and produce structured results for further analysis.

Detected bugs are stored in a CSV file for easy review and processing.



────────────────────────────────────────────────────────────────────────────────
PROJECT STRUCTURE
────────────────────────────────────────────────────────────────────────────────

Agentic-Bug-Hunter/
│
├── run.py
├── requirements.txt
├── .env
│
└── output/
    └── output.csv

All detected bugs will be saved inside:

output/output.csv



────────────────────────────────────────────────────────────────────────────────
SETUP AND EXECUTION
────────────────────────────────────────────────────────────────────────────────

Follow the steps below to run the project.



━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
STEP 1 — CREATE VIRTUAL ENVIRONMENT
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

python -m venv venv



━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
STEP 2 — ACTIVATE VIRTUAL ENVIRONMENT
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

Windows

venv\Scripts\activate

Mac / Linux

source venv/bin/activate



━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
STEP 3 — INSTALL DEPENDENCIES
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

pip install -r requirements.txt



━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
STEP 4 — ADD API KEYS
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

Open the `.env` file and add your API keys:

HUGGINGFACE_API_KEY=paste_your_key_here  
GROQ_API_KEY=paste_your_key_here



━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
STEP 5 — RUN THE PROGRAM
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

python run.py



────────────────────────────────────────────────────────────────────────────────
OUTPUT
────────────────────────────────────────────────────────────────────────────────

After execution, the detected bugs will be stored in:

output/output.csv

The CSV file contains structured information about the detected issues.



────────────────────────────────────────────────────────────────────────────────
TEAM
────────────────────────────────────────────────────────────────────────────────

Soham   ── Bug Detector Agent
Vedant  ── Bug Explainer Agent
Jenil   ── Database  
Diti    ── APIs 



────────────────────────────────────────────────────────────────────────────────
END
────────────────────────────────────────────────────────────────────────────────
```
