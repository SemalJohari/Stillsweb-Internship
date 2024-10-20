### Stillsweb Internship

These are two Python notebooks containing implementation of Python code using two APIs - Sentinel Hub (sentinel_hub.ipynb) and EOS API (srajanai.ipynb) for deriving numeric values of the vegetation indices of a given area over the months January 2024 to July 2024 and then visualizing them.

The data is being visualized by sending OGC requests- WMS and WCS to Sentinel Hub requests builder at https://apps.sentinel-hub.com/requests-builder/, and thus fetching information from there. At the end, the data is being fetched using an evalscript.
