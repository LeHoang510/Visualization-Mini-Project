# Baby Names Visualization Mini-Project

Initial implementation for the Telecom Paris baby names mini-project.

This repository contains three notebook-based visualizations built from the French baby names dataset (`1900-2020`):

- `Visualization 1 - Baby Names Through Time.ipynb`
- `Visualization 2 - Regional Name Heatmap.ipynb`
- `Visualization 3 - Gender Dual Line Chart.ipynb`

The branch to use for grading is `main`.

## Repository Contents

- `Visualization 1 - Baby Names Through Time.ipynb`: popularity trends over time
- `Visualization 2 - Regional Name Heatmap.ipynb`: regional differences by department
- `Visualization 3 - Gender Dual Line Chart.ipynb`: differences between male and female usage for shared names
- `departements-version-simplifiee.geojson` and `departements-avec-outre-mer.geojson`: map data used for the regional visualization
- `visualization1.png`, `visualization2.png`, `visualization3.png`: exported screenshots

## How To Run

1. Clone the repository and move into it.
2. Install the Python dependencies with `uv`:

```bash
uv sync
```

3. Download the dataset used by the notebooks:

Then open any of the three notebooks listed above and run the cells from top to bottom.

## Dependencies

The project uses `uv` with a `pyproject.toml` configuration. Main libraries:

- `pandas`
- `altair`
- `geopandas`
- `notebook`
