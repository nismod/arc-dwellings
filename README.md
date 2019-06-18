
# Arc Analysis Dwelling Scenarios

This dataset covers projections for dwellings in the Arc area.

## Scenarios

### Baseline


### Scenario 0 - Unplanned


### Scenario 1 - New Cities

Here we take the overall growth trends from scenario 0 but more strongly clustered
employment to the LADs that either host or are closely connected to the 5 new cities in the
scenario, distributed as follows:

- Newtown 01 Cherwell (North of Bicester)
- Newtown 02 Aylesbury Vale (South of Winslow)
- Newtown 03 Central Bedfordshire (North of Cranfield)
- Newtown 04 Central Bedfordshire (East of Sandy)
- Newtown 05 South Cambridgeshire (North of Bassingbourn)

### Scenario 2 - Expansion



## Scenario processing

Data as provided by Adrian Hickford is processed into tidy CSV format suitable for input
to other models by the `convert-scenarios.ipynb` notebook.

Recommend using [`miniconda`](https://docs.conda.io/en/latest/miniconda.html) to install
Python, jupyter and pandas, xlrd to run the processing, and nbstripout to avoid saving notebook data
in git history.

- `data_as_provided`
  - `Scenario Baseline - Dwelling+Employment projections.xlsx`
  - `Scenario Expansion - Dwelling+Employment projections.xlsx`
  - `Scenario New Settlements - Dwelling+Employment projections.xlsx`
  - `Scenario Unplanned Development - Dwelling+Employment projections.xlsx`
  - `lad_nmcd_changes.csv` - derived from ONS Geography
- `data_processed`
  - `baseline.csv` - tidy version of `Scenario Baseline - Dwelling+Employment projections.xlsx`
  - `expansion.csv` - tidy version of `Scenario Expansion - Dwelling+Employment projections.xlsx`
  - `settlements.csv` - tidy version of `Scenario New Settlements - Dwelling+Employment projections.xlsx`
  - `unplanned.csv` - tidy version of `Scenario Unplanned Development - Dwelling+Employment projections.xlsx`

## Acknowledgements

Authors:
- Adrian Hickford
- Will Usher
- Tom Russell

Developed at the University of Southampton and the University of Oxford Environmental Change Institute, funded by the EPSRC via the Infrastructure Transitions Research Consortium Mistral project (EP/N017064/1).

