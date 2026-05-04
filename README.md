# Transliteration Accuracy Testing – Assignment 1 (Option 1)

## 👤 Student Information

* **Name:** Chathuranga B A W
* **Registration Number:** IT23838352
* **Module:** IT3040 – IT Project Management (Semester 1)
* **Assignment:** Transliteration Accuracy Testing (Option 1)

---

## 📌 Project Overview

This project presents an automated testing solution designed to evaluate the **Sinhala transliteration accuracy** of the web application:

🔗 [https://www.pixelssuite.com/chat-translator](https://www.pixelssuite.com/chat-translator)

The focus of this assignment is to identify **negative scenarios**—cases where the system produces incorrect, unexpected, or failed outputs when converting Singlish text into Sinhala.

A total of **50 negative test cases** have been carefully designed and executed, covering all **24 Singlish input types** specified in the assignment guidelines.

---

## 🚀 Key Features

* ✅ Automated testing using **Playwright**
* ✅ Structured test case management via **Excel**
* ✅ Automatic capturing of:

  * Actual Output
  * Test Status (Pass/Fail)
* ✅ Coverage of all **24 Singlish input categories**
* ✅ Includes multiple input lengths:

  * Short (S)
  * Medium (M)
  * Long (L)

---

## 📂 Project Structure

```
IT23838352/
├── IT23838352_Assignment_1_Test_Cases.xlsx
├── test_automation/
│   ├── test_automation.py
│   └── (supporting files)
└── GitHub_Link.txt
```

---

## ⚙️ Prerequisites

Ensure the following are installed on your system:

* Python **3.11** or **3.12**
* Google Chrome Browser

---

## 🛠️ Installation Guide

1. Open Command Prompt
2. Navigate to the automation folder:

```cmd
cd /d D:\test_automation
```

3. Install required dependencies:

```cmd
pip install playwright openpyxl
playwright install
```

---

## ▶️ Running the Automation

Execute the following command:

```cmd
python test_automation.py --excel "Assignment 1 - Test cases.xlsx" --url "https://www.pixelssuite.com/chat-translator" --wait-ms 5000 --type-delay-ms 80 --slow-mo-ms 200
```

### 🔍 Parameters Explained

* `--excel` → Path to the Excel test case file
* `--url` → Target web application URL
* `--wait-ms` → Wait time for page loading
* `--type-delay-ms` → Delay between keystrokes
* `--slow-mo-ms` → Slows down execution for visibility

---

## 📊 Test Case Summary

* **Total Test Cases:** 50
* **Type:** Negative Test Cases (Neg_xxxx)
* **Coverage:** All 24 Singlish input types
* **Distribution:** Minimum 2 test cases per input type

---

## 📁 Submission Contents

* ✔ Completed Excel file with:

  * Actual Output
  * Test Status
  * Analysis (Columns G & H)
* ✔ Fully functional Playwright automation project
* ✔ Public GitHub repository link

---

## 🎯 Conclusion

This project demonstrates a systematic approach to identifying weaknesses in Sinhala transliteration systems using automation. By focusing on negative scenarios, it highlights areas where the system fails to meet expected behavior, providing valuable insights for improvement.

---

## 📬 Contact

For any clarification or inquiries, please feel free to reach out.

---

⭐ *Thank you for reviewing this project!*
