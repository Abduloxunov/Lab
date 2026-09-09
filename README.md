# Lab — air quality exploration

Coursework exploration of the Beijing Multi-Site Air Quality dataset (PRSA, 2013-03-01 to
2017-02-28): hourly readings of PM2.5, PM10, SO2, NO2, CO and O3 with co-located
meteorological variables, across twelve monitoring stations.

The twelve `PRSA_Data_*.csv` files are one station each — Aotizhongxin, Changping,
Dingling, Dongsi, Guanyuan, Gucheng, Huairou, Nongzhanguan, Shunyi, Tiantan, Wanliu and
Wanshouxigong. `sample.ipynb` loads and concatenates them for analysis.

Early work, kept for reference. My current machine learning work is in computer vision and
retrieval systems — see the pinned repositories.

## Data

Beijing Multi-Site Air-Quality Data Set, UCI Machine Learning Repository. Files are read
with `encoding='latin-1'`.

```python
import pandas as pd
df = pd.read_csv('PRSA_Data_Aotizhongxin_20130301-20170228.csv', encoding='latin-1')
```
