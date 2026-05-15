# Create a Standard ML Project Structure

Bring the new ML project at `/root/code/fraud-detection/` in line with the team's standard directory structure conventions.

---

## Steps

### 1. VS Code UI

I didn't use the terminal since the VS Code UI was available.
Open the `fraud-detection` folder in VS Code.

### 2. Create folders

Go to the `data` folder. Create `raw` and `processed` folders.
Go to the root folder. Create `tests` and `configs` folders.

### 3. Rename folders

Go to the `src` folder. 
Rename `feature` to `features`.
Rename `util` to `utils`.

### 4. Check __init__.py

Check for `__init__.py` files in the subfolders of `src`. Confirmed they are there.

### 5. Update requirements.txt

Open `requirements.txt`.
Change `sklearn` to `scikit-learn`.
Add missing `mlflow`.

### 6. Update README.md

Open `README.md`.
Replace `# Fraud-` with `# fraud-detection`.

---
