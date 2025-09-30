# Seabed Mapping Dataset (SeabedX)

## 🧭 Project Summary

This dataset contains sonar-based seabed mapping data collected off the coast of Chonburi, Thailand, using side-scan sonar in the XTF format. The dataset has been processed into a visual GeoTIFF mosaic and structured metadata following SeabedX Schema (based on schema.org and STAC).

## 📂 Repository Contents

- `SeabedX_mosaic.tif` – GeoTIFF Mosaic
- `SeabedX_metadata.json` – Dataset metadata in JSON-LD (schema.org)
- `coverage_report.json` – Field coverage evaluation
- `cq_results.json` – Competency query output
- `stac_item.json` – STAC-compliant metadata
- `index.html` – Landing page (for GitHub Pages)

## 🔖 Metadata

| Field | Value |
|-------|-------|
| Project Name | Chonburi Survey |
| Survey Date | 2025-02-24 |
| Operator | Marine Institute |
| Creator | Nitthanet Nat |
| Creator ORCID | https://orcid.org/0000-0000-0000-0000 |
| Publisher | RSU Data Lab |
| License | CC-BY 4.0 |
| DOI | (If available from Zenodo) |
| Landing Page | https://github.com/Nitthanet-Nat/SSS-Schema |
| Grid Resolution | 1.0 m |
| Sonar Model | Humminbird |
| Instrument PID | (If available from NERC L22) |
| Workflow | Python ETL (pyxtf + GDAL) |
| QC Thresholds | Roll < 5°, Pitch < 5°, Depth > 10 m |

## 📘 How to Use

You can load `SeabedX_mosaic.tif` into QGIS or ArcGIS. Metadata is available in JSON-LD for programmatic access.

## 📄 Citation

```bibtex
@dataset{SeabedX2025,
  author = {Nitthanet Nat},
  title = {Seabed Mapping Dataset: Chonburi Survey (2025)},
  year = {2025},
  publisher = {RSU Data Lab},
  doi = {10.1234/chonburi.survey.2025}
}
