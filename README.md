# SSS-Schema

This repository contains metadata, schemas, and sample outputs for the **Chonburi Survey** conducted using side-scan sonar equipment. The project aims to demonstrate a standardized metadata schema (SeabedX-Schema) and FAIR-compliant publication pipeline for marine geospatial data.

---

## 📁 Dataset Contents

| File | Description |
|------|-------------|
| `SeabedX_metadata.json` | JSON-LD metadata file (SeabedX-Schema format) |
| `SeabedX_mosaic.tif` | GeoTIFF Mosaic of sonar channel 0 data (generated using pyxtf + GDAL) |
| `edit5.py` | Python ETL pipeline used to parse XTF, extract metadata, and generate GeoTIFF |

---

## 🧭 Project Metadata

| Field | Value |
|-------|-------|
| **Project Name** | Chonburi Survey |
| **Survey Date** | 2025-02-24 |
| **Operator** | Marine Institute |
| **Sonar Model** | Humminbird |
| **Grid Resolution** | 1.0 meter |
| **Processing Workflow** | `pyxtf + GDAL` |
| **License** | CC-BY 4.0 |
| **DOI** | [`10.1234/chonburi.survey.2025`](https://doi.org/10.1234/chonburi.survey.2025) |

---

## 🌐 Data Access

### 🔗 GeoTIFF Mosaic

> *Note: This is a placeholder link to demonstrate FAIR-A compliance during prototyping.*

- 📥 Download: [`SeabedX_mosaic.tif`](https://zenodo.org/record/1234567/files/SeabedX_mosaic.tif)
- 📐 Format: GeoTIFF
- 🔒 License: CC-BY 4.0
- 🔑 SHA-256 Checksum: `e3b0c44298fc1c149afbf4c8996fb92427ae41e4649b934ca495991b7852b855`

---

## 🧪 FAIR Metadata (JSON-LD)

- The metadata file `SeabedX_metadata.json` follows the [Schema.org Dataset](https://schema.org/Dataset) and [SeabedX-Schema](https://schema.org/) extensions.
- It includes:
  - Dataset-level info (ProjectName, DOI, BoundingBox)
  - Ping-level sensor data (Pitch, Roll, Altitude, etc.)
  - Product info (License, Resolution, Format)

> 💡 Use this file to register your dataset in FAIR Data Portals, Zenodo, MGDS, or as supplementary material in publications.

---

## 📞 Contact

- **Creator**: Dr. John Anderson  
- **Affiliation**: Marine Geoscience Data System (MGDS)  
- **Email**: `j.anderson@mgds.org`  
- **ORCID**: [0000-0000-0000-0000](https://orcid.org/0000-0000-0000-0000)

---

## 🛠️ How to Reproduce

```bash
python edit5.py
