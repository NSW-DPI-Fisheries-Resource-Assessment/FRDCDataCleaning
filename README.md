# FRDCDataCleaning
Data cleaning code FRDC project

# Convert Commonwealth data into the flat table
------
### Start with table LogSheetEvent and pull information from other tables:
* Pull TripNo and ShotNo infos from file "Cwth foreign squid fishing data - constructed shot-by-shot";
* Pull Species info from CAAB code database;



```python

```


```python
import os
from datetime import date
import numpy as np
import pandas as pd
```

## Load Commonwealth data


```python
data_dir = 'data_cw/' # Commonwealth data are stored in this folder
```


```python

```


```python
Species.columns
```




    Index(['CAAB', 'COMMON_NAME'], dtype='object')




