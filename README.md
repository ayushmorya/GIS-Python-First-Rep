![image alt](https://github.com/ayushmorya/GIS-Python-First-Rep/blob/8c150988a32956e082e3d7d10e0fc8667c61ab35/Screenshot%202025-12-12%20165839.png)

# GIS Processing with Python

This repository contains my first hands‑on GIS workflow using Python.  
It demonstrates how to:

- Read the **GeoNames** dataset (tab‑delimited TSV)
- Filter hypsographic features (mountains, hills — feature class 'T')
- Convert coordinates into spatial geometry using **GeoPandas**
- Export results as a **GeoPackage (.gpkg)** or **Shapefile (.shp)**

Everything you see here is based on the notebook I built while learning GIS today.

---

## 📌 Notebook Included
- `notebooks/web_api.ipynb`

This is the exact notebook I used to:
- Load GeoNames data
- Filter mountains
- Create geometry
- Export spatial data

---

---

## 📂 Data

Due to file size, the GeoNames dataset is **NOT included**.
Download it from:

[https://download.geonames.org/export/dump/](https://download.geonames.org/export/dump/)

Example expected file:

```
data/US.txt
```


## ▶️ How to Use

Open the notebook:

```bash
jupyter notebook notebooks/web_api.ipynb
```

Run all cells to:

* Load your dataset
* Filter mountain features
* Build GeoDataFrame
* Export to a spatial format

Output will be written to the `output/` folder.

---

## 💡 What I Learned

This repo showcases my understanding of:

* Reading and cleaning geospatial data
* Converting coordinate pairs into geometry
* Using **GeoPandas** efficiently
* Exporting GIS formats for real‑world use

This serves as the base for more advanced GIS work in Python.


## 📄 data/README.md
```

This folder contains instructions only.
Do NOT add large datasets here.

Download GeoNames files from:
[https://download.geonames.org/export/dump/](https://download.geonames.org/export/dump/)

Place the file like so:
data/US.txt

```

---
