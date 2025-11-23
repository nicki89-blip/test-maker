# Translation Test Generator

A small browser-based tool that takes a text file of Slovene–English vocabulary pairs and generates randomized translation tests (multiple versions) ready for printing or saving as PDF.

The app runs entirely in the browser – no server or database needed.

---

## Features

- Upload **.txt** or **.rtf** files containing Q/A vocabulary pairs
- Automatically parses Slovene → English items:
  - `Q:` = Slovene (question)
  - `A:` = English (answer)
- Generates multiple randomized test versions (A, B, C, …)
- Four exercises per test:
  1. **Translate English → Slovene**
  2. **Translate Slovene → English**
  3. **Gap-fill** (English sentence with a blank, Slovene hint)
  4. **Correct the spelling** (auto-generated misspellings)
- Configurable:
  - Number of versions
  - Number of questions per exercise
  - Student name field label
  - Test title, school name, and exercise instructions (via config)
- Print-friendly layout (for physical copies or “Save as PDF”)

---

## File Format

The app expects a vocabulary file with pairs formatted like this:

```text
Q: ušesa
A: ears

Q: glava
A: head

Q: lase
A: hair
A: hair
