# webeet.io Layered Project

### 📝 Overview

A showcase of data projects from my time at webeet.io on the **Layered** project. This repository includes raw public Berlin data along with Python scripts for cleaning, clustering, and preparing the data for database integration.

### ✨ My Contributions

This repository contains the following main component:

- [districts/](districts) - Contains clean geojson data, a script for creating the `districts` table with primary keys and geometries for Berlin’s 12 administrative districts.

- [regional_statistics/](regional_statistics) — Contains raw PDF files, source data extracted from these PDFs, a README with detailed explanations, and Python script for cleaning the data and populating the database.

- [short_time_listings/](short_time_listings) - Contains raw CSV and GEOJSON files, README with detailed explanations, and Python script for cleaning the data and populating the database.


### ⚙️ Technologies Used

- Python 3.x: Pandas, psycopg2, SQLAlchemy, GEOPandas, geoalchemy2, RE, zipfile.