# Blue Team Match Dashboard (Football Video Analytics)

This project turns a full match into a clean, decision-ready **Blue Team match dashboard**: event tagging → structured stats matrix → custom metrics + visuals → final dashboard deliverable.

The dashboard itself was designed in **Canva** and exported as PDF/PNG.

## What you’ll find in this repo

### 1) Blue Team Match Dashboard (final deliverable)

- `Karan Desai submission-Blue Team Match Dashboard.pdf` (best to view)
- `Karan Desai submission-Blue Team Match Dashboard.png`

### 2) Tagging Panel (how events were captured)

- `Tagging Panel In-Play Sports.png`

### 3) Stats Matrix (what the tagged events became)

- `Stats Matrix In-Play Sports.png`

### 4) Cleaned dataset (CSV)

- `Cleaned dataset Kanso Analytics Competition.csv`

### 5) Data visualization notebook (Python)

- `Data_Visualizations_for_Match_Comparision_Stats.ipynb`

## Workflow (explained)

- **Start with full match footage** and decide what you want to measure (possession patterns, ball-winning, restarts, delivery, shot quality, etc.)
- **Tag events in In-Play Sports** (label + annotate actions throughout the game)
- **Convert tags into a stats matrix** so each event becomes structured, countable data
- **Engineer custom metrics** (success rates, retention, efficiency comparisons, shot profile, etc.)
- **Visualize and summarize** the key differences between teams in Python
- **Deliver the dashboard** (final narrative + insights, designed in Canva)

## Quickstart

- **Read the dashboard**: open `Karan Desai submission-Blue Team Match Dashboard.pdf`
- **See the tagging + stats pipeline**: open `Tagging Panel In-Play Sports.png` and `Stats Matrix In-Play Sports.png`
- **Inspect the cleaned data**: open `Cleaned dataset Kanso Analytics Competition.csv`

## Run the notebook locally (optional)

The notebook uses Python with common data + plotting libraries.

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
jupyter notebook
```

Then open `Data_Visualizations_for_Match_Comparision_Stats.ipynb` and run all cells.  
It will save the visualization PNGs into the project folder.

## Notes / attribution

- **Dashboard design**: created in **Canva**, exported as PDF/PNG and included in this repository.
- **Tagging + stats matrix screenshots**: captured from In-Play Sports. If you are reusing this repository publicly, ensure you have the rights/permission to redistribute these screenshots.

