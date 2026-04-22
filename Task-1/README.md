# India House Price Prediction

This project contains a Jupyter notebook for training and evaluating a house price prediction workflow using an India housing sample dataset.

## Project Structure

- `India_House_Price_Prediction.ipynb` - Main notebook
- `datasets/` - Input data files
- `output_images/` - Saved plots and generated images
- `requirements.txt` - Python dependencies

## Prerequisites

- Python 3.10+ (recommended)
- Jupyter Notebook or VS Code with Jupyter extension

## Setup Instructions

1. Clone or download this project.
2. **If your dataset is provided as a ZIP file, extract the ZIP first** so the CSV files are available inside the `datasets/` folder.
3. (Optional but recommended) Create and activate a virtual environment.
4. Install dependencies.

### Windows (PowerShell)

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
pip install -r requirements.txt
```

### macOS / Linux

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

## Run the Notebook

1. Start Jupyter:

```bash
jupyter notebook
```

2. Open `India_House_Price_Prediction.ipynb`.
3. Run all cells in order.

## Notes

- Ensure required input files are present inside `datasets/` before running the notebook.
- Generated visuals can be stored in `output_images/`.
