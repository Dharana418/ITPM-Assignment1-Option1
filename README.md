# ITPM-Assignment-1Option-1
3. Prepare Test Data
Open the file Assignment 1 - Test cases.xlsx located in the extracted folder.

Fill in your test data under these columns:

TC ID

Input length type

Input

Expected output

Important: Leave the Actual output and Status columns empty; the script will populate these.

4. Execute the Script
In the Command Prompt, run the following command to start the automation:

DOS
python test_automation.py --excel "Assignment 1 - Test cases.xlsx" --url "[https://www.pixelssuite.com/chat-translator](https://www.pixelssuite.com/chat-translator)" --wait-ms 5000 --type-delay-ms 80 --slow-mo-ms 200 --save-every 1 --keep-open
📊 Results and Reporting
5. Verify Results
Navigate back to the test_automation folder.

Reopen the Excel file.

Verify the values automatically recorded in the Actual output and Status columns.

6. Finalize Documentation
After reviewing the automated results, add and manually fill the following columns next to the Status column for each case:

Singlish input types covered: Categorize the input (e.g., Interrogative, Exclamatory, etc.).

Evidence or rationale for the input type covered: Provide the reasoning behind the specific test case.

Note: Refer to the template provided in Appendix 2 of the assignment document for detailed guidance.
"""

with open('README.md', 'w') as f:
f.write(readme_content)

Your **README.md** file is ready. I have structured it according to the 7 steps you provided, ensuring the commands are easy to copy and the instructions for the Excel file are clear.

[file-tag: code-generated-file-0-1777909956442359758]

### **Highlights of this README:**
* **Command Accuracy:** Includes the specific `cd /d` command for D: drive navigation and the full Python execution string with all your required flags (`--wait-ms`, `--type-delay-ms`, etc.).
* **Clear Boundaries:** Explicitly warns the user not to fill in the 'Actual output' and 'Status' columns manually, as these are handled by the script.
* **Post-Processing:** Includes a dedicated section for adding the "Singlish input ty
