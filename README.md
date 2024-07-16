# WHO Health Inequality Dataset Analysis

Create `original_data` folder in root and download the datasets to that folder

- https://www.who.int/data/sets/health-inequality-monitor-dataset#nut
- https://www.who.int/data/sets/health-inequality-monitor-dataset#ghe
- https://www.who.int/data/sets/health-inequality-monitor-dataset#rmnch

Then install all requirements

```
python -m venv venv
pip install -r requirements.txt
```

This is focused on health inequality data for women and newborn - data cleaning steps (powered by PySpark) are in `data_preprocessing.ipynb`.
Resulting files were used for creating visualisations, present in `who_health_data_viz.pbix`
