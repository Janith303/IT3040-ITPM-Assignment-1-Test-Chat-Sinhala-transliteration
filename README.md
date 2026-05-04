# IT23191310 – IT3040 Assignment 1

##  Project Title
Automated Testing for Singlish to Sinhala Transliteration System

##  Repository


---

##  Project Structure

test_automation/

- test_automation.py           → Playwright automation script  
- Assigment 1- Test cases.xlsx → Excel file with test cases & results  
- requirements.txt             → Python dependencies  
- README.md                    → Project documentation  
---

##  Technologies Used

- Python  
- Playwright (UI Automation)  
- OpenPyXL (Excel handling)

---

##  How to Run the Project

1. Open terminal inside project folder    

2. Install dependencies  
   pip install -U pip
   pip install playwright openpyxl  
   playwright install  

3. Run the automation script  
   python test_automation.py --excel "test_automation/Assignment 1 - Test cases.xlsx" --url "https://www.pixelssuite.com/chat-translator" --wait-ms 5000 --type-delay-ms 80 --slow-mo-ms 200 --save-every 1 --keep-open  

---

##  Output

- Results are automatically written to the Excel file  
- Columns updated:
  - Actual output  
  - Status (PASS / FAIL)  

---

##  Test Case Details

- Total Test Cases: 50+  
- Test Type: Negative Testing  

### Covered Scenarios:
- Mixed language inputs (Singlish + English)  
- Spelling variations  
- Emojis & symbols  
- Real-world scenarios (banking, travel, apps)  
- System-related messages (errors, logs)  
- Numeric and date inputs  

---

##  Important Notes

- This system uses strict comparison  
- Even small differences in Sinhala output (spacing, formatting, spelling) will result in FAIL  
- Some failures are expected due to:
  - Transliteration inconsistencies  
  - Mixed language complexity  
  - UI timing delays  

---

##  Student Information

- Student ID: IT23191310
- Module: IT3040  
- Assignment: Assignment 1 (Option 1)  

---

##  Final Status

✔ Automation script working  
✔ Excel-based validation completed  
✔ Test coverage includes multiple edge cases  

---

##  Submission Notes

- All required files are included  
- Project is fully runnable using requirements.txt  

---
