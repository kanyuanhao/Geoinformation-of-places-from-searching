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
![Capture](https://user-images.githubusercontent.com/60058957/110760582-d45e1c80-8289-11eb-82bc-baa6b8737e05.PNG)
