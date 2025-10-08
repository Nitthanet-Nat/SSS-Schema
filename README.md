# SeabedX-DB: Chonburi Side-Scan Sonar Dataset

This repository contains sonar-based seabed mapping data off the coast of Chonburi, Thailand, collected using side-scan sonar in XTF format. The dataset has been transformed into FAIR-compliant formats.

## 📂 Repository Contents

| File | Description |
|------|-------------|
| `Seabed_mosaic.tif` | GeoTIFF mosaic (COG-like, visualizable in QGIS) |
| `Seabed_metadata.json` | JSON-LD metadata conforming to schema.org |
| `stac_item.json` | STAC metadata |
| `index.html` | Landing page with embedded metadata |
| `coverage_report.json` | Field coverage statistics |
| `cq_results.json` | Competency query outputs |

## 🔖 Metadata Summary

- **Project**: Chonburi Seabed Mapping Survey
- **Survey Date**: 2025-02-24
- **Instrument**: Humminbird (SSS)
- **Operator**: Marine Institute
- **Creator**: Nitthanet Nat
- **Affiliation**: RSU Data Lab
- **License**: [CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/)
- **DOI**: `10.1594/IEDA/306159`
- **Landing Page**: [View on GitHub Pages](https://your-username.github.io/SSS-Schema/)
- **Grid Resolution**: ~1.0 meter

## 🚀 Usage

- Load `Seabed_mosaic.tif` into GIS software like QGIS or ArcGIS.
- Use `Seabed_metadata.json` in semantic pipelines.
- Reference DOI in your citations.

## 📄 Citation

```bibtex
@dataset{SeabedX2025,
  author = {Nitthanet Nat},
  title = {SeabedX-DB: Chonburi Seabed Mapping Dataset},
  year = {2025},
  publisher = {RSU Data Lab},
  doi = {10.1594/IEDA/306159}
}
