# League of Legends Match Analysis

Data science notebooks analyzing League of Legends ranked solo match data.

## Notebooks

- **[Champion Analysis](notebooks/champion_analysis.ipynb)** - Analyze champion winrates, team compositions, and matchups for specific champions

## Setup

1. Install dependencies:
```bash
pip install -r requirements.txt
```

2. Place your match data in the `data/` directory:
   - `lol_matches.csv` - Processed match data
   - `lol_matches_raw.json` - Raw match data from Riot API

3. Open the notebooks in Jupyter:
```bash
jupyter notebook
```

## Data

The notebooks expect match data in CSV and JSON format. To generate this data, you'll need to:
1. Use the Riot Games API with your API key
2. Fetch match data using the data collection notebook
3. Process and save the data

## Requirements

- Python 3.8+
- pandas
- numpy
- matplotlib
- seaborn
- jupyter

See `requirements.txt` for full list.
