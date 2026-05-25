# AI-Based Waste Segregation Assistant with Area-wise Waste Analysis

A complete micro-framework Python Flask web application designed for Computer Science Projects (CSPs) on city smart sanitation and district waste analysis.

## Project Structure
```
AI-Waste-Segregation-CSP/
│
├── app.py                  # Core backend routing & APIs file
├── requirements.txt         # Project package requirements
├── waste_data.csv          # Municipal dataset file
├── README.md               # Quick execution handbook
│
├── templates/
│   ├── index.html          # Dashboard Landing view
│   ├── dashboard.html      # Regional charts and table logs
│   ├── ai_detect.html      # Image uploading segregation interface
│   └── about.html          # Project guidelines & documentation
│
└── static/
    └── css/
        └── style.css       # Layout styles
```

## How to Execuute locally
1. Ensure your system has **Python 3.8+** installed.
2. Initialize virtual environments (highly recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate       # On MacOS/Linux
   venv\Scripts\activate          # On Windows
   ```
3. Install package prerequisites:
   ```bash
   pip install -r requirements.txt
   ```
4. Fire up the development server:
   ```bash
   python app.py
   ```
5. Dive into the dashboard: open your browser and navigate to `http://127.0.0.1:5000`
