# Mchakato

## Setup local environment
```
python -m venv .env
.\.env\Scripts\activate
pip freeze > requirements.txt
```

## Dataset

Elevation data : Copernicus Global 30m Elevation dataset
Link : https://developers.google.com/earth-engine/datasets/catalog/COPERNICUS_DEM_GLO30

Direct fetch of dataset 
````
wget https://prism-dem-open.copernicus.eu/pd-desk-open-access/prismDownload/COP-DEM_GLO-90-DGED__2021_1/Copernicus_DSM_30_N06_00_W006_00.tar

tar -xvzf Copernicus_DSM_30_N29_00_E014_00.tar
``