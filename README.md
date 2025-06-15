# MoodSwingPredictor

Project for WIH3004 Trends In Data Science

## Setup & Run Instructions

### 1. Clone the Repository
```
git clone https://github.com/lqmannn4/MoodSwingPredictor.git
cd MoodSwingPredictor
```

### 2. Create and Activate a Virtual Environment (Recommended)
**On Windows (PowerShell):**
```
python -m venv .venv
.venv\Scripts\Activate.ps1
```
**On macOS/Linux:**
```
python3 -m venv .venv
source .venv/bin/activate
```

### 3. Install Dependencies
```
pip install -r requirements.txt
```

### 4. Run the App
```
python app.py
```

### 5. Open in Browser
- The app will display a local URL (e.g., http://127.0.0.1:8000/). Open it in your web browser.

---

## Notes
- **Do not track your `.venv` folder in git.** It is ignored via `.gitignore`.
- Large files like `afiqhensem.csv` and `mood_swings_model.pkl` are required for the app to work.
- If you encounter errors about package versions, ensure you are using the versions specified in `requirements.txt`.
- For Windows PowerShell, if you get a script execution error, run PowerShell as Administrator and execute:
  ```
  Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
  ```

## Repository Contents
- `app.py` - Main application code
- `requirements.txt` - Python dependencies
- `afiqhensem.csv` - Sample dataset
- `mood_swings_model.pkl` - Trained model
- `columns.pkl` - Model columns
- `.gitignore` - Git ignore rules
- `README.md` - This file
