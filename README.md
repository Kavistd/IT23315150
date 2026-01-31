# IT3040 – IT Project Management  
## Assignment 1 – Automated Testing using Playwright

This repository contains the complete **Playwright automation testing project** developed for **IT3040 – IT Project Management (Semester 1, Assignment 1)**.

The purpose of this project is to design, document, and automate test cases for a web-based **Singlish to Sinhala translation system**, following the testing guidelines and submission requirements provided in the assignment brief.

---

## 📌 Assignment Scope

This project addresses **Option 1 – Singlish to Sinhala Converter Testing** using the Playwright automation framework.

The following assignment requirements are fully satisfied:

- ✅ Full **Playwright project repository** including all scripts and configuration files  
- ✅ Clear **README.md** with setup and execution instructions  
- ✅ Automated execution of test cases using Playwright  
- ✅ Public GitHub repository accessible for evaluation  
- ✅ Test cases documented separately using the **Appendix 2 Excel template**  
- ✅ Includes **Positive**, **Negative**, and **UI-related** test scenarios  

---

## 🧪 Application Under Test (AUT)

- **Application Name:** SwiftTranslator  
- **URL:** https://www.swifttranslator.com/  
- **Functionality Tested:**  
  Conversion of **Singlish text input** into **Sinhala language output**

---

## 🛠️ Technologies Used

- Node.js  
- Playwright Test Framework  
- JavaScript  
- Git & GitHub  

---

## 📂 Project Structure

IT23315150/
│
├── tests/
│ └── translator.spec.js # Automated Playwright test scripts
│
├── test-data/
│ └── testCases.json # Test inputs and expected outputs
│
├── playwright.config.js # Playwright configuration file
├── package.json # Project dependencies
├── README.md # Project documentation


---

## ⚙️ Prerequisites

Before running this project, ensure the following are installed on your system:

- **Node.js (LTS version recommended)**
- **Git**
- Stable internet connection (to access the live application)

---

## 📥 Installation Instructions

1. Clone the repository:
   ```bash
   git clone <YOUR_GITHUB_REPOSITORY_URL>

2. Navigate into the project directory:
   cd IT23315150

3. Install required dependencies:
   npm install

4. Install Playwright browsers:
   npx playwright install

▶️ Running the Test Suite

To execute all automated test cases:
   npx playwright test

To run tests in headed mode (browser visible):
   npx playwright test --headed



