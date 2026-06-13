# Accelerated Stability Study — KTP Associate Data Analysis Exercise

Analysis of an accelerated stability study comparing two prototype formulations (Lot A014 / Formulation A and Lot B025 / Formulation B) of the same product. Samples were stressed at elevated temperature and humidity for varying periods, then assayed for active content and two degradation products (Imp RRT 0.92 and Imp RRT 1.23).

The complete analysis and reasoning are in the single self-contained notebook **`KTP_stability_analysis.ipynb`**, which answers the six questions in the brief.

## Repository contents

| File | Purpose |
|------|---------|
| `KTP_stability_analysis.ipynb` | Self-contained notebook - analysis, plots, reasoning |
| `requirements.txt` | Python dependencies |

> Note: as per the exercise instructions, the dataset itself is **not** included in this repository. Place the supplied `KTP_task_datasets.xls` in the
> repository root before running.

## How to run

# Requirements: 1) Python 3.10 or later

```bash
# Step-1: clone and enter the repo
git clone <your-repo-url>.git
cd <repo>

# Step-2: create a virtual environment (recommended)
#Windows
python -m venv .venv
.venv\Scripts\activate

#macOS / Linux
python -m venv .venv
source .venv/bin/activate

# Step-3: install dependencies
pip install -r requirements.txt

# Step-4: add the supplied data file to the repo root
#    KTP_task_datasets.xls

# The project structure should look like:

repo/
 │
 ├── KTP_stability_analysis.ipynb
 ├── requirements.txt
 └── KTP_task_datasets.xls

# Step-5: launch and run the notebook top-to-bottom
jupyter notebook KTP_stability_analysis.ipynb
```
------------------------------------------------------
```
# If using VS-Code:
# Requirements: 1) Python 3.10 or later
#               2) Visual Studio Code with the Python and Jupyter extensions installed 

# Follow Steps 1–4 above, then continue with the instructions below:

# Step-5: open the project in VS Code

# Step-6: select the Python interpreter
  # press Ctrl+Shift+P (Windows/Linux) or Cmd+Shift+P (macOS)
  # search for Python: Select Interpreter
  # choose the interpreter from the .venv environment

# Step-7: run the notebook
  # open `KTP_stability_analysis.ipynb`
  # click "Run All" to execute the notebook from top to bottom
