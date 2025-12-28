# CSI 115 - Computer and Programming Concept

## Overview
This repository curates the teaching materials for CSI 115, an introductory programming course delivered in Python. It combines lecture slide decks, interactive Jupyter notebooks, and recommended textbooks so students can review concepts, practice live in notebooks, and reference longer-form explanations outside class.

## Repository Structure
- Lecture Slides (LaTex and PPTX)/
  - Before Mid/: PowerPoint decks (N4Less01.ppt through N4Less30.pps) covering pre-midterm lectures.
  - After Mid/ PDFs/: Exported slide PDFs for Lectures 1-3 (post-midterm sequence).
  - After Mid/ Source/: Zip archives containing the LaTeX source for the post-midterm slide decks.
- Notebooks/: Six lecture notebooks that walk through core Python topics with runnable code and exercises.
- Text Books/: Course reference texts (Eric Matthes's *Python Crash Course* and Allen Downey's *Think Python*).

## Lecture Slide Highlights
### Before Midterm
The N4Less series of PowerPoint slide decks delivers foundational programming topics. Although the files are binary and not previewable here, they cover introductory problem solving, Python syntax, and computing concepts aligned with the early notebook material.

### After Midterm
For Lectures 1-6 (post-midterm numbering), both PDF exports and LaTeX sources are provided. These resources make it easy to review slides quickly or regenerate them from LaTeX if updates are required.

## Interactive Notebooks
Each notebook blends short readings with executable examples and hands-on exercises.

| Notebook | Focus | Key Activities |
| --- | --- | --- |
| Lecture_1.ipynb | Getting started with Python | Print statements, prime number loop, personalization exercise. |
| Lecture_2.ipynb | Variables, data types, and expressions | Naming rules, string methods, whitespace control, numeric operations, constants. |
| Lecture_3.ipynb | Conditionals | Boolean logic, relational operators, chained and nested conditionals, control-flow best practices. |
| Lecture_4.ipynb | Iteration | Variable updates, for and while loops, break patterns, infinite loop warnings, Newton's method for square roots. |
| Lecture_5.ipynb | Functions | Calling built-ins, defining functions, parameters vs. arguments, scope, fruitful vs. void functions, applied examples. |
| Lecture_6.ipynb | Data structures and arrays | Lists (slicing, methods, map/filter/reduce), tuples, dictionaries, histogram example, NumPy arrays and dimensions. |

Each notebook encourages experimentation; most code cells include prompts to modify variables or extend functionality to reinforce concepts.

## Reference Textbooks
- Eric Matthes, *Python Crash Course: A Hands-On, Project-Based Introduction to Programming* (PDF).
- Allen B. Downey, *Think Python, 2nd Edition* (PDF).

Both texts deepen coverage of the notebook topics and offer additional exercises.

## Getting Started
1. Install Python 3.9 or later and JupyterLab (or use VS Code with the Python and Jupyter extensions).
2. Clone the repository and open the Notebooks/ folder.
3. Launch the notebooks in Jupyter and execute cells sequentially. Use Restart and Run All frequently to ensure a clean kernel state.
4. Review slide decks alongside the matching notebook for each lecture to reinforce concepts.
5. Consult the textbooks for extended explanations, especially when preparing assignments or exams.

## Suggested Learning Path
1. Work through Lecture_1.ipynb to confirm Python is running locally.
2. Pair each notebook with the corresponding slide deck (Before Mid or After Mid) for the same lecture number.
3. Attempt the guided exercises and extend them with your own variations.
4. Use the histogram and NumPy sections in Lecture_6.ipynb as gateways to data analysis libraries.

## Maintenance Notes
- The LaTeX source archives under Lecture Slides (LaTex and PPTX)/After Mid/Source/ can be unpacked and recompiled with standard LaTeX toolchains (TeX Live or MiKTeX) to regenerate PDFs.
- PowerPoint files are provided as-is; update them in Microsoft PowerPoint or LibreOffice Impress.
- No automated tests or CI configuration are present. If you add scripts or assignments, consider organizing them in a dedicated folder and documenting execution steps here.

## Contributions and Licensing
No explicit license is included; assume all materials are course-confidential unless the authors provide permission for redistribution. If you expand the repository (e.g., add lab assignments or sample solutions), document authorship and licensing notes within those additions.
