# EXP 07: READ AND EXTRACT FROM PDF

### AIM

The objective is to read the full text content from a sample PDF file and save that content into a new `.txt` file for further processing or review.

---

### PROCEDURE

The workflow uses activities from the `UiPath.PDF.Activities` package:

1.  **Install Package:** The `UiPath.PDF.Activities` package is installed to enable PDF manipulation.
2.  **Read PDF Text:** The **Read PDF Text** activity is used with the relative path `"Sample.pdf"`. The extracted content is stored in the String variable `pdfText`.
3.  **Write Text File:** The **Write Text File** (Classic) activity is used to output the `pdfText` content to the relative path `"Output.txt"`.
4.  **Best Practice:** All file paths are kept relative to the project root directory (`"Sample.pdf"`, `"Output.txt"`) to ensure project portability and avoid absolute path warnings.

---

### OUTPUT

The automation creates one output file in the project folder:

* **File Name:** `ExtractedRPA.txt`
* **Contents:** The raw, extracted text from `RPA qp.pdf`.
<img width="1919" height="1019" alt="image" src="https://github.com/user-attachments/assets/3b55b918-b295-4d41-986d-7aeb16a6e852" />

files attached.

---

### RESULT

The automation successfully processes the PDF file and saves all readable text to a designated text file completed successfully.
