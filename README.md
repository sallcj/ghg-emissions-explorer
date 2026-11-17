# ghg-emissions-explorer

Exploratory data analysis and dashboard for visualization GHG emissions of major countries using the PRIMAP-hist dataset by Johannes Guetshow and coauthors. The Jupyter notebook `dashboard.ipynb` walks through the process of building the interactive dashboard and visualizations using Panel, HoloViews, and Bokeh and packages together the components to be served as a web app.

You can get the latest version of the PRIMAP-hist data (as of Sep 2026) on Zenodo at https://zenodo.org/records/22876287.

The final dashboard was deployed using Render. Check it out at https://ghg-explorer-svpx.onrender.com/dashboard.

For a video demo, see [here](https://drive.google.com/file/d/1SJ-qL7bD_WcyK7chmAH0QQTNFNkhKEm7/view?usp=sharing).

## Project Organization

```
├── LICENSE            <- MIT license
├── README.md          <- This file
├── requirements.txt   <- Python dependencies (install with `pip install -r requirements.txt`)
├── data               <- Folder with downloaded and intermediate data files
├── dashboard.ipynb    <- The Jupyter notebook that explains and builds the dashboard
├── .venv              <- Virtual environment
└── render.yaml        <- Configuration file used by Render
```

## Setup

```
python -m venv .venv
.venv\Scripts\activate        # Windows (macOS/Linux: source .venv/bin/activate)
pip install -r requirements.txt
```
