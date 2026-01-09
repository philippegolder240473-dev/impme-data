# IMPME Data - Reference Databases

This repository contains the reference data files used by [IMPME](https://github.com/YOUR_USERNAME/impme-app).

## 📁 Files

### RNE_PrimaryLocations.csv
European railway station codes from [RNE (RailNetEurope)](https://rne.eu/).

| Column | Description |
|--------|-------------|
| Code | UIC location code (7 digits) |
| Name | Station name |
| Country | Country code (2 letters) |

### RICS_codes.csv
Railway company codes from [ERA RICS database](https://www.era.europa.eu/).

| Column | Description |
|--------|-------------|
| Code | RICS code (4 digits) |
| Name | Company name |
| Acronym | Company abbreviation |

## 🔄 Updating Data

1. Download latest data from official sources:
   - Stations: [RNE Open Data](https://rne.eu/opendata/)
   - RICS: [ERA RICS](https://www.era.europa.eu/databases/rics_en)

2. Format as CSV with headers

3. Commit and push to this repository

4. IMPME will automatically use the updated data (no redeployment needed)

## 📋 Data Sources

- **RNE Primary Locations**: https://rne.eu/it/primary-locations/
- **ERA RICS Codes**: https://www.era.europa.eu/databases/rics_en
- **NHM Codes**: https://www.wto.org/english/tratop_e/envir_e/hs_nhm.htm

## 📄 License

Data is provided under the terms of the respective source organizations.
