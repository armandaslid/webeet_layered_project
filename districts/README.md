# Berlin Districts Table Creation

This script creates a simple PostGIS-enabled table called `districts` in the `berlin_data` schema. It defines Berlin's 12 administrative districts and their geometries.

## Table Definition

The table includes:

| Column        | Type                          | Description                          |
|---------------|-------------------------------|--------------------------------------|
| `district_id` | `VARCHAR(2)`                  | Unique ID for each district (primary key) |
| `district`    | `VARCHAR(32)`                 | Name of the district                 |
| `geometry`    | `geometry(MULTIPOLYGON, 4326)`| District boundary geometry (WGS 84)  |