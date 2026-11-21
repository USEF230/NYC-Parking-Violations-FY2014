# NYC Parking Violations — FY2014

An exploratory data analysis of approximately **7.45 million NYC parking violations** issued during fiscal year 2014. The project uses Python, pandas, Matplotlib, and Seaborn to uncover patterns by violation type, issuing agency, geography, and time.

## Project Files

| File | Description |
|---|---|
| [`youusef alasir .ipynb`](./youusef%20alasir%20.ipynb) | Main Jupyter/Google Colab analysis notebook |
| [`NYC_Parking_Violations_FY2014.pdf`](./NYC_Parking_Violations_FY2014.pdf) | Presentation summarizing the project and findings |
| [`.gitignore`](./.gitignore) | Files and directories excluded from Git |
| [`requirements.txt`](./requirements.txt) | Python dependencies for running the analysis |

## Analysis Objectives

- Explore the structure and quality of the 2014 parking-violation dataset
- Clean and transform date, location, and violation fields
- Identify the most frequent violation types
- Compare issuing-agency activity
- Examine geographic distribution across boroughs and areas
- Study temporal patterns across months, days, and times
- Present clear, reproducible conclusions and visualizations

## Tools and Libraries

- Python 3
- Jupyter Notebook / Google Colab
- pandas
- NumPy
- Matplotlib
- Seaborn

## Run the Notebook

### Option 1: Google Colab

1. Open [`youusef alasir .ipynb`](./youusef%20alasir%20.ipynb) on GitHub.
2. Select **Open in Colab** when available.
3. Upload or mount the source dataset if the notebook prompts for it.
4. Run the notebook cells from top to bottom.

### Option 2: Local Jupyter

```bash
git clone https://github.com/USEF230/NYC-Parking-Violations-FY2014.git
cd NYC-Parking-Violations-FY2014
python -m venv .venv

# Windows
.venv\Scripts\activate

# macOS / Linux
source .venv/bin/activate

pip install -r requirements.txt
jupyter notebook
```

Then open `youusef alasir .ipynb` from Jupyter.

## Dataset

The project analyzes approximately 7.45 million parking-violation records from NYC in FY2014.

> The raw dataset is not stored in this repository. Keep the original data file separate and do not publish it if redistribution is restricted by the source license.

## Presentation

A PDF presentation is available here: [`NYC_Parking_Violations_FY2014.pdf`](./NYC_Parking_Violations_FY2014.pdf).

## Reproducibility Notes

- Run cells in sequence because later analysis steps depend on cleaned and derived columns.
- Preserve the original filename and update the data-loading path if the dataset is moved.
- Keep generated plots with descriptive names if they are exported for reports.
- Results should be interpreted as historical descriptive analysis, not real-time operational predictions.

## Author

**Yousef Alasir**  
GitHub: [@USEF230](https://github.com/USEF230)
