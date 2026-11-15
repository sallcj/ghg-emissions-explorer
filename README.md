# ghg-emissions-explorer

Exploratory data analysis and dashboard for visualization GHG emissions of major countries using the PRIMAP-hist dataset by Johannes Guetshow and coauthors. You can get the latest version of the PRIMAP-hist data (as of Sep 2026) on Zenodo at https://zenodo.org/records/22876287.

The final dashboard was deployed as a web app using Render. See the dashboard at https://ghg-explorer-svpx.onrender.com/dashboard.

For a video walkthrough of the dashboard

## Project Organization

```
├── LICENSE            <- MIT license.
├── README.md          <- This file.
├── requirements.txt   <- Python dependencies. Install with `pip install -r requirements.txt`.
├── data               <- Downloaded and intermediate data files (not tracked by git).
└── notebooks          <- Jupyter notebooks for analysis and the dashboard.
```

## Setup

```
python -m venv .venv
.venv\Scripts\activate        # Windows (macOS/Linux: source .venv/bin/activate)
pip install -r requirements.txt
```
