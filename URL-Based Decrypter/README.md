# URL-Based Decrypter

## Overview

This project is a Python utility that decodes an encrypted message provided through a published Google Docs URL. The program reads structured table data, converts the values into a two-dimensional character layout, and prints the decoded message to the console.

---

## How It Works

The general process is:

1. User inputs a published Google Docs URL.
2. Program opens and reads the document content.
3. Characters are extracted from table data.
4. Extracted values are inserted into a two-dimensional array.
5. The array is printed to reveal the hidden message.

---

## Skills Demonstrated

- Python programming
- URL-based data retrieval
- HTML/table parsing
- String processing
- Array/list manipulation
- Data reconstruction
- Console-based utility design

---

## Project Structure

```text
URL-Based Decrypter/
├── main.py
└── README.md
```

---

## How to Run

Run:

```bash
python main.py
```

Then enter a published Google Docs URL containing a properly formatted encrypted message.

---

## Example Input

```text
https://docs.google.com/document/d/e/2PACX-1vTER-wL5E8YC9pxDx43gk8eIds59GtUUk4nJo_ZWagbnrH0NFvMXIw6VWFLpf5tWTZIT9P9oLIoFJ6A/pub
```

---

## Future Improvements

- Add error handling for invalid URLs.
- Add validation for missing or malformed table data.
- Add support for file-based input.
- Add unit tests for parsing and reconstruction logic.
- Add clearer output formatting.

---

## Portfolio Relevance

This project demonstrates practical data parsing, transformation, and reconstruction logic in Python.
