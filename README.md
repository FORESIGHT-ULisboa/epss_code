# EPSS 2026/27 · Part 1 · Water balance and long-term simulation of a reservoir

## Group

| Name | Student number |
|---|---|
| | |
| | |
| | |
| | |

## How to run

```
conda env create -f environment.yml      # once
conda activate epss
python -m ipykernel install --user --name epss --display-name "Python (epss)"   # once
pytest                                   # tests
```

The parts you must write are marked `# TODO` and raise `NotImplementedError` with a description of the
task; the comments below each `TODO` say what goes in and what comes out. The notebooks keep the outputs of
a complete solution, so you can see what is intended: your results should look alike.

Open the notebooks in `notebooks/` in order (01 → 06) with the **epss** kernel and run them top to bottom.
Notebook 01 downloads ERA5-Land data (needs a CDS account and `~/.cdsapirc`); if
`data/raw/era5land_monthly.nc` already exists, the download is skipped.

| Folder | Content |
|---|---|
| `src/epss/` | `climate`, `pet`, `soil`, `eflows`, `reservoir`, `metrics` |
| `notebooks/` | 01 download · 02 climate · 03 PET · 04 Thornthwaite–Mather · 05 reservoir · 06 design |
| `tests/` | `pytest` tests, incl. a reference case in `data/reference/` |
| `data/` | `case.json`, `catchment.kml`, `hv_curve.csv`, `raw/` ERA5-Land files |

## Answers (section 3.7)

*To be completed.*

## AI declaration

Tools used and what for:
