# Geoinformation of places from searching

Get the geoinformation of one place just by typing the name of the place.

## Libraries requirements

**GeoPy, NumPy, pandas**
```python
from geopy.geocoders import Nominatim
import numpy as np
import pandas as pd
```

## Example

```python
ucl = Place('UCL')
ucl.nation
```
>'United Kingdom'
