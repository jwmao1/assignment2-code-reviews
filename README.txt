CSE 242 Assignment 2 — local completed version

Files
  Assignment2.ipynb: completed answers, executed code, plots and numerical checks.
  Assignment2.html: readable export with embedded plots.
  Advertising.csv: original supplied dataset, unchanged.
  requirements.txt: exact main package versions used for this run.

Before submission
  Name and Student ID: Jiawei Mao, 2252678.
  Review all solutions.
  If you edit the notebook, run all cells and regenerate the HTML before zipping.
  No files have been submitted to Canvas or pushed to GitHub.

Reproduce (tested with Python 3.9.6 on macOS)
  Open a terminal in this folder, then run:
  python3 -m venv .venv
  source .venv/bin/activate
  python -m pip install -r requirements.txt
  python -m nbconvert --to notebook --execute --inplace Assignment2.ipynb
  python -m nbconvert --to html Assignment2.ipynb

An interactive notebook editor (Jupyter or VS Code) may also run the notebook.
Keep Advertising.csv in the notebook folder. Digits come bundled with sklearn.
The HTML export follows the assignment's permitted PDF-export fallback: this
machine has no Pandoc or XeLaTeX installation. HTML formulas may require an
Internet connection for the MathJax renderer; plots are embedded in the file.

Source repository: https://github.com/ucsc-cse-242/assignments
Source commit: 4a1ac214a08183c0323ceb2850819c57dba6268b
Source directory: Assignment2
