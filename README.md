# Geoinformation of places from searching

Get the geoinformation of one place just by typing the name of the place.

## Libraries requirements

**GeoPy, NumPy, pandas**
```python
from geopy.geocoders import Nominatim
import numpy as np
import pandas as pd
import folium
```

## Example

```python
ucl = Place('UCL')
ucl.nation
```
>'United Kingdom'

## Three samples

Two for universities, and one for world known buildings.
I also plot those locations at the map
![Capture_1](https://user-images.githubusercontent.com/60058957/110811691-da6fef80-82c1-11eb-8535-72b0a3a6ec18.PNG)

