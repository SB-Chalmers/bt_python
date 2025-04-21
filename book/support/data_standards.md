
## Making Data Easy to Use in Python

Clean, well-structured data is critical to any Python-based workflow. Help your team by ensuring:

### 📐 Data Formatting
- [ ] Use machine-readable formats: CSV, JSON, GeoJSON, shapefiles
- [ ] Avoid merged cells, multi-indexed Excel sheets
- [ ] Each row = one observation; each column = one variable
- [ ] Stick to consistent naming: lowercase_with_underscores
- [ ] Avoid empty rows, units in cells, or comments in data

### 📘 Metadata and Documentation
- [ ] Create a data dictionary (column names, units, descriptions)
- [ ] Separate README or metadata file explaining the source, frequency, and preprocessing

### 🧪 Example Rule of Thumb
If the data can’t be read with one line of code in Pandas, it’s not clean enough.

---
