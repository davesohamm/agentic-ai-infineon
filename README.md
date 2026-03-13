# Agentic Bug Hunter

AI-powered system for detecting bugs in **C++ code** using modern language models.

The program analyzes source code, identifies potential bugs, and stores structured results for further inspection.

---

## Overview

Agentic Bug Hunter is designed to automate the process of finding bugs in C++ programs using AI models.

The system analyzes code and generates bug reports which are saved in a structured format for easy analysis.

Output is stored as a CSV file.

---

## Project Structure

```
Agentic-Bug-Hunter/
│
├── run.py
├── requirements.txt
├── .env
│
└── output/
    └── output.csv
```

Detected bugs will be saved in:

```
output/output.csv
```

---

## Setup Instructions

### 1. Create a Virtual Environment

```bash
python -m venv venv
```

### 2. Activate the Virtual Environment

**Windows**

```bash
venv\Scripts\activate
```

**Mac / Linux**

```bash
source venv/bin/activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Add API Keys

Open the `.env` file and add your API keys:

```
HUGGINGFACE_API_KEY=paste_your_key_here
GROQ_API_KEY=paste_your_key_here
```

### 5. Run the Program

```bash
python run.py
```

---

## Output

After execution, results will be saved in:

```
output/output.csv
```

The CSV file contains detected bugs and related information.

---

## Team

| Member | Role |
|------|------|
| Soham | Bug Detector Agent|
| Vedant | Bug Explainer Agent |
| Jenil | Database |
| Diti | APIs handling |

---
