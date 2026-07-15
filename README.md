# The-Task-Automation-with-python-Scripts-
Code Alpha - Python Programming Internship - Task 3: Task Automation with python Scripts ( E-mail Organizer)

# CodeAlpha: Automated Email organizer (Interactive Utility)

## **Project Overview**
            This project is an interactive task automation script developed as part of the Python Programming Internship at CodeAlpha. The utility allows users to paste raw, unstructured text (such as chat logs, messy documents, or web scrapings) and instantly extract, clean, and de-duplicate all valid email addresses. It is 100% self-contained and runs safely in the console without needing system file permissions.

## **Key Concepts Used**
1. **Regular Expressions ('re' module):** Uses pattern-matching logic ('re.findall') to accurately isolate valid email formats while ignoring broken strings (like 'test@com').
2. **Dynamic Multi-Line Input:** Leverages an interactive 'while' loop that captures multi-line clipboard pastes until a terminate command ('DONE') is entered.
3. **Efficient Deduplication ('set'):** Converts the extracted matches into a Python set to instantly filter out duplicate entries, leaving only unique contacts.
4. **Input Sanitization:** Uses '.strip().upper()' to handle boundary spaces and case-insensitive commands smoothly.

## **Automation Mechanics & Flow**
1. **Interactive Paste Bin:** The terminal prompts the user to paste their raw text block.
2. **Dynamic Reading:** The script continually reads lines of text until the user types 'DONE' on a new line.
3. **Regex Scanning & Deduplication:** The script parses the compiled block, matches it against a robust RFC-compliant email pattern, and drops duplicates.
4. **Clean Output:** The extracted emails are printed as a neat, numbered directory, or a polite alert is triggered if no emails are found.

## **How to Run**
1. Copy the code from "Email organizer.py".
2. Paste it into any Python 3 environment (like OnlineGDB or VS Code or Goole colab).
3. Hit **Run**, paste your messy raw text directly into the terminal, type 'DONE' on a new line, and watch the automation magic happen!
