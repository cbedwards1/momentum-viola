# Momentum Voilà Sandbox

This folder contains a Jupyter notebook that can be run as a student-facing
Voilà application.

## Files

- `momentum_voila_sandbox.ipynb` — interactive notebook/application
- `requirements.txt` — Python package requirements

## Local setup

From a terminal in the same folder:

```bash
python -m venv .venv
```

Activate the environment:

**Windows PowerShell**

```powershell
.venv\Scripts\Activate.ps1
```

**macOS or Linux**

```bash
source .venv/bin/activate
```

Install the packages:

```bash
python -m pip install -r requirements.txt
```

Open and test the notebook:

```bash
jupyter lab momentum_voila_sandbox.ipynb
```

Launch the student-facing application:

```bash
voila momentum_voila_sandbox.ipynb
```

Voilà will print a local address in the terminal. Open that address in a
browser. The notebook code will be hidden and the widgets will remain
interactive.

## Instructional note

The app does not permanently save student predictions or explanations.
Students should submit their required evidence through Padlet, an LMS, or a
laboratory notebook.
