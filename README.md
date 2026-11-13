title:- AROGYA | KAVACH + FUEL++

# AROGYA KAVACH + FUEL++ |  # ✈️ HAL AROGYA - V1002 | 

### Hindustan Aeronautics Limited | Aircraft Health, Manual Intelligence, Kavach QR & DGCA Audit System

> **Offline | DGCA Compliant | SHA-256 Blockchain | QR Audit | Kannada / Hindi / Tamil Voice**
> **Built for HAL Aircraft Maintenance - ALH, Fuel System, Quality & Audit**

---

## 🎯 What Is HAL AROGYA?

HAL AROGYA is a **complete offline aircraft maintenance assistant** for HAL technicians.

One problem in HAL shop floor: Technician has 50-page PDF manual, but to find one procedure takes 20 minutes. Language problem for Kannada technicians. No proof for DGCA audit. Duplicate parts entering stores.

**HAL AROGYA solves all 4 in ONE dashboard:**

1. Live Aircraft Health Monitoring
2. Ask Question From Manual in Seconds + Voice Read in Kannada
3. Duplicate Part Detection with Kavach QR
4. Full DGCA Audit Proof with SHA + QR + PDF Report

**Result: 20 Minutes Work -> 20 Seconds. 50 Cr Aircraft + 2 Lives Saved.**

---

## ⭐ 6 TABS - Full Features

### 1. TAB 1 - LIVE HEALTH - Digital Twin
- Live Fuel Pressure Graph - GREEN / YELLOW / RED Zones
- KPI Cards: Live PSI, Health %, RUL, 50Cr Save
- Digital Twin 3D Display
- Auto Simulation: GREEN SAFE -> YELLOW WARNING -> RED CRITICAL
- Critical Alert: CRITICAL RED ALERT - Fuel Failure in 0 Hours! Replace FF-3012 NOW!
- Live Clock + File Count Header

### 2. TAB 2 - KAVACH QR - Anti-Duplicate / Blockchain
- Enter Part Number: FF-3012-5.2-ORIGINAL
- SHA-256 Hash Generation - First 16 Char Blockchain ID
- QR Code Generation - Unique for every part
- Result: ORIGINAL ✅ vs FRAUD DUPLICATE ❌
- Image Upload Scan Support
- Verified Count KPI + Audit Log Trail

### 3. TAB 3 - QUALITY CHECK - Resistivity Test
- Part No + Resistivity Input
- Standard: 5.2 ohm (4.8 - 6.0 PASS)
- Result: PASS ✅ ORIGINAL / FAIL ❌ FRAUD
- Certificate: CERT-HAL-<SHA>.pdf if PASS, REJECTED if FAIL
- QC QR Code with SHA

### 4. TAB 4 - HAL-GPT - HERO MODULE ⭐ - Main HR Module
- Upload Multiple PDF Manuals - Auto Indexed Offline
- 3-Level Search: EXACT PHRASE (100) + ALL WORDS (90) + SEMANTIC TF-IDF (1,2-gram)
- Shows: File Name | Page No | Para No | SHA Citation
- Yellow Highlight Overlay on Exact PDF Page - Auto Opens Page
- Procedure + Explanation Display
- Voice: English / Kannada / Hindi / Tamil
- deep-translator + gTTS + pyttsx3 Offline Fallback
- Kannada Letters Are READ, Not Numbers - Fixed Specially
- Real MP3 Player + Download MP3 Link
- Voice Input: Speak Question -> Auto Search
- Buttons: Read MP3 | Explain MP3 | Audit QR

### 5. TAB 5 - TAT INTEL - Turn Around Time
- Vendor, Part, TAT Days Input
- Delay Calculation: Delay = TAT - 10 Days
- SQLite History - Last 10 Records
- Live Audit Trail Display

### 6. TAB 6 - FOD + DGM MAIL - Safety Alert
- FOD Detection: Metal Chip / Bolt / Screw
- Result: Metal Chip - CRITICAL FOD / Bolt - FOD - Ground Aircraft / No FOD - Clean
- Action: STOP Work if CRITICAL
- DGM Mail: Real SMTP SSL Gmail Send
- Voice Command: Say Generate DGM Mail -> Auto Sends
- Subject: CRITICAL RED ALERT - Fuel Failure in 0 Hours! ALH Z-3012
- .eml File Generated Locally + Audit Trail

---

## 🏆 Why This Project Is Different?

| Normal Project | HAL AROGYA |
| :--- | :--- |
| Only Chatbot | 6 Full Modules in 1 Dashboard |
| Online Only | 100% Offline Search + Offline TTS Fallback |
| No Proof | SHA-256 + QR + Audit PDF for DGCA |
| English Only | Kannada / Hindi / Tamil / English Voice |
| No Real Action | Real Gmail to DGM + Real Audit PDF |
| Dummy Data | Real PDF Page Highlight + Real QR |

---

## 🛠️ Tech Stack
- Backend: Python, Flask
- PDF: PyMuPDF (fitz)
- AI Search: scikit-learn TF-IDF (1,2-gram) + Cosine Similarity
- Voice: gTTS, pyttsx3, deep-translator, Web Speech API
- QR / Blockchain: qrcode, hashlib SHA-256, base64
- Audit PDF: reportlab A4
- Database: SQLite - hal.db
- Frontend: HTML, CSS, JavaScript

---

## 🚀 How To Run - 2 Minutes

### Step 1 - Install
```bash
pip install -r requirements.txt

create .env file
GMAIL_USER=your_email@gmail.com
GMAIL_APP_PASSWORD=your_app_password_here
DGM_EMAIL=dgm_email@gmail.com

run
python app.py

browser
http://127.0.0.1:5000

project structure
HAL_FINAL/
  app.py
  requirements.txt
  README.md
  .env.example
  .gitignore
  templates/
    dashboard.html
    Note: uploads/, hal.db, .env, *.eml are local only. They are ignored by git.

    