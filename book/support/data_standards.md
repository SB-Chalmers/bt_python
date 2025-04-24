## Data Cleaning Guidelines for Python Workflows

Clean, well‑structured data is essential for reliable, reproducible analyses and machine learning pipelines. This guide provides best practices, examples, and exercises to help your team prepare data that can be seamlessly ingested and processed in Python.

:::::{topic} Data Formatting Best Practices

**Objective:** Ensure datasets are machine‑readable, consistent, and free of structural issues.

1. **Machine‑readable formats**: Use CSV, JSON, GeoJSON, or shapefiles. Avoid multi‑sheet or merged cells in Excel.
2. **Tabular structure**: One observation per row, one variable per column. No units or comments in cells.
3. **Consistent naming**: `snake_case`, lowercase, ASCII letters and numbers only.
4. **Single data type per column**: Store numbers as numeric types (e.g., `42`), dates as ISO strings (`YYYY-MM-DD`).
5. **Boolean and categorical encoding**:
   - **One‑hot encode** multi‑category columns (e.g., cities) into separate columns of 0/1 values.
   - Example:
     
     | city_stockholm | city_malmo | city_gothenburg |
     |:--------------:|:----------:|:---------------:|
     |       1        |     0      |        0        |
     
6. **Encoding and units**:
   - Save CSVs as UTF‑8 to preserve special characters in data values.
   - Include units in column headers (e.g., `height_m`, `energy_kwh`).

::::::



---

:::::{topic} Naming Conventions

Use descriptive, concise names with only lowercase letters, numbers, and underscores.

| ❌ Bad               | ✅ Good                 |
|----------------------|-------------------------|
| `Project Name`       | `project_name`          |
| `År`                 | `year`                  |
| `Energy (kWh)`       | `energy_kwh`            |
| `1st Floor Area`     | `first_floor_area_m2`   |

::::::

### Tip

```{tip}
Stick to standard abbreviations (e.g., `temp` for temperature) and avoid hyphens or spaces in file names: `energy_data_2024.csv`.
```

---

:::::{topic} Metadata & Documentation

Provide context so others can understand and reproduce your workflow.

- **Data dictionary**: Describe each column’s name, type, units, description, and allowed values.

  | column_name      | type    | units | description                      | allowed_values       |
  |------------------|---------|-------|----------------------------------|----------------------|
  | `project_name`   | string  |       | Name of the project              | —                    |
  | `year`           | integer |       | Project year                     | 2019, 2020, 2021…     |
  | `energy_kwh`     | float   | kWh   | Annual energy consumption        | ≥ 0                  |
  | `is_renovated`   | bool    |       | Renovation status (0 = no, 1 = yes) | 0, 1            |

- **README / metadata file**:
  1. Data source and collection method
  2. Update frequency
  3. Preprocessing steps
  4. Contact information

::::::


---

:::::{topic} Data Quality Best Practices

1. **Missing values**: Use `NaN` for numerics and empty strings for text. Avoid custom codes like `-999` or `n/a`.
2. **Duplicates**: Identify and remove unintended duplicates.
3. **Type validation**: Use `df.info()` and `df.dtypes` in pandas.
4. **Language consistency**: English for headers; UTF‑8 for value fields.
5. **No formulas, comments, or formatting** in raw data files.

::::::

### Tip

```{tip}
After loading, run `df.describe(include='all')` to surface anomalies like unexpected categories or null counts.
```

---

:::::{topic} Common Problems & Solutions

| Problem                           | Example                       | Solution                         |
|-----------------------------------|-------------------------------|----------------------------------|
| Special chars in column names     | `År`, `Energiförbrukning (kWh)` | Rename to `year`, `energy_kwh`   |
| Multiple values in one cell       | `"Stockholm; Malmö"`         | One‑hot encode into boolean cols  |
| Numbers stored as strings         | `"42"`                       | Cast to integer: `df['col']=df['col'].astype(int)` |
| Mixed date formats                | `2022-01-01`, `01/01/2022`     | Use `pd.to_datetime(..., format="%Y-%m-%d")` |
| Custom missing codes              | `-999`, `"n/a"`             | Replace with `NaN` via `df.replace()` |
| Units in data cells               | `"42 kWh"`                   | Separate unit: `energy_kwh = 42`  |
| Encoding errors                   | `MalmÃ¶`                      | Save and read as `encoding='utf-8'` |

::::::

> **Rule of Thumb**: If you can’t read the file with one line of pandas code, it needs more cleaning.

---

:::::{topic} Additional Resources & Links

- [Pandas I/O Documentation](https://pandas.pydata.org/pandas-docs/stable/user_guide/io.html)
- [PEP 8 Naming Conventions](https://peps.python.org/pep-0008/#naming-conventions)


ewpage

