# *San Francisco Housing*
---
We will research and analyze the San Francisco housing prices and rental prices for a proptech company looking to offer an instant, one-click service for people to buy properties and then rent them.  We will collect the data and put the data into visualizations, including aggregation, interactive visualizations, and geospatial analysis to find properties in the San Francisco market that are viable investment opportunities.  

Using the Plotly and the Mapbox API, we will create interactive visualizations for the following

---
## Technologies:

The Jupyter file utilizes python 3.7 along with the following libraries and dependencies:

os

pandas

plotly

hvplot

pathlib

dotenv

MAPBOX_API_ACCESS_TOKEN


```python
    import os
    import pandas as pd
    import plotly.express as px
    import hvplot.pandas
    from pathlib import Path
    from dotenv import load_dotenv
```

Please create your own .env file with your unique mapbox API access token in order for the mapbox API calls to work.



---

## Contributors

kevin-mau

---

## License

MIT