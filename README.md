🚀 Singlish-to-Sinhala Automation Framework
⚡ Framework Core: Powered by Playwright for browser automation and Python 3.11/3.12.  

🛠️ Prerequisites:

Ensure Python 3.11 or 3.12 is installed on your system.  

Install Google Chrome (recommended) or use Playwright’s default Chromium.  

📂 Environment Setup:

Save the project ZIP to your D: drive and extract it to D:\test_automation.  

Open Command Prompt and navigate using: cd /d D:\test_automation.  

📦 One-Time Installation:

Upgrade pip: pip install -U pip.  

Install core libraries: pip install playwright openpyxl.  

Download browser binaries: playwright install.  

📝 Test Data Preparation:

Open "Assignment 1 - Test cases.xlsx" in the project folder.  

Enter data for TC ID, Input length type, Input, and Expected output.  

Crucial: Leave the Actual output and Status columns empty for the bot to fill.  

🤖 Execution Command:

Run the script with the following optimized parameters:
python test_automation.py --excel "Assignment 1 - Test cases.xlsx" --url "[https://www.pixelssuite.com/chat-translator](https://www.pixelssuite.com/chat-translator)" --wait-ms 5000 --type-delay-ms 80 --slow-mo-ms 200 --save-every 1 --keep-open  

📊 Post-Test Reporting:

Reopen the Excel file to verify the automated Actual output and Status results.  

Add two final columns: "Singlish input types covered" and "Evidence or rationale for the input type covered".  

Manually fill these based on the specific linguistic patterns tested in each case.
