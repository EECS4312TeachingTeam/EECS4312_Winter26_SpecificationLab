# Meeting Slot Suggestion Lab Repository

This repository contains the starter code, templates, and tests for the **Requirements Specification and LLM‑Assisted Development** lab. Students will implement a meeting slot suggestion function, write specifications, and explore the impact of requirements completeness on AI‑assisted coding.

## Structure

- **solution.py** – Stub file where you implement `suggest_slots`. Do not rename this file.
- **public_tests.py** – Public tests you can run to check basic correctness. Use a test runner such as `pytest` to execute these tests.
- **hidden_tests.py** – Additional tests used by graders. **Do not open or modify this file.**
- **spec_templates/** – Contains Markdown templates for Group 2 (structured specification) and Group 3 (constraint‑complete specification).
- **prediction_sheet_template.md** – Template for recording your confidence and risk predictions before and after the change announcement.
- **traceability_template.md** – Template for documenting requirement coverage and explaining key design choices.
- **README.md** – This file.

## Running Tests

1. Install Python 3 if not already installed.
2. Implement your solution in `solution.py`.
3. Optionally create `student_tests.py` and write at least 10 test cases.
4. Run the public tests using:

```bash
pytest public_tests.py
```

5. Fix any failing tests before moving on. Remember that hidden tests will check additional requirements (e.g., buffer enforcement, day‑specific rules, invariants, tie‑breaking, and the Wednesday blackout window).

## Submitting Your Work

Submit the files listed in the lab handout: your specification (if required), updated `solution.py`, `student_tests.py`, filled prediction sheet, completed traceability matrix, and your LLM prompt transcript. Do not include the hidden tests in your submission.
