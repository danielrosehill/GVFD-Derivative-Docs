# Quantifying Environmental Impact in Financial Terms - The IFVI Value Factors Database Explored

[![Data Format: CSV, JSON, GeoJSON](https://img.shields.io/badge/Data%20Format-CSV%2C%20JSON%2C%20GeoJSON-blue)](https://www.ifvi.org)
[![Source: IFVI](https://img.shields.io/badge/Source-IFVI-brightgreen)](https://www.ifvi.org)

This repository provides a resource for understanding the financial implications of environmental impact. 

Derived from the IFVI Global Value Factors Database (GVFD), it translates environmental impacts (e.g., carbon emissions) into monetary values, enabling deeper financial analysis and a more holistic understanding of value creation.  

The data is available in accessible `CSV`, `JSON`, and `GeoJSON` formats (`GeoJSON` coming soon!), empowering data analysts, NGOs, and anyone else curious to explore the transformative potential of impact accounting.

This dataset is built upon the IFVI's October 2024 release, offering a valuable snapshot of how financial and non-financial performance can be integrated for a more sustainable future. 

For the complete methodology and latest updates, refer to the official [IFVI website](https://www.ifvi.org).

Static versions of their documentation are included here for historical context.


## Using This Data

The IFVI Data helps you understand the financial implications of environmental impacts. It's part of a larger movement to put impact front and center in how we define and prioritize value.  The GVFD was released with the following note:

*"To drive adoption of impact accounting and meet market needs as soon as possible, IFVI is making available four interim environmental methodologies, prior to completing an official methodology oversight process, including the VTPC Review and Due Process."*


## What are value factors?

"Value factors" convert quantity metrics (like tons of carbon dioxide emitted) into monetary terms.  The GVFD is standardized on the US dollar for convenience but is intended for global consideration.

## What are these files?

This release (V1, October 2024) contains environmental value factors only.  The topics, developed by the IFVI in partnership with the Value Balancing Alliance (VBA), are:

| Category                 | Description                                                                                                                              |
|--------------------------|------------------------------------------------------------------------------------------------------------------------------------------|
| **Air Pollution**         | Impacts from up to 6 air pollutants on health, agricultural productivity, and other impacts.                       |
| **Land Use and Conversion**| Impacts on land occupied or converted by a company, covering the loss of ecosystem services in different locations and for different land use types. |
| **Waste**                 | Impacts from waste generated and disposed of by various methods (e.g., incineration and landfill), including impacts on leachate, disamenity, climate change, and air pollution. |
| **Water Pollution**       | Impacts from 104 possible water pollutants on human health and eutrophication.                                                 |


## Licensing

This derivative dataset is subject to the same terms of use as the original database, available as `license.md` at the repository root. 

### Versioning

This repository reflects version 1 of the GVFD (October 15th).  Users seeking the latest data should refer to the IFVI website. This repository strives to mirror the original GVFD release. However, applying the database for official use requires utilizing the database in conjunction with the detailed user documentation, not provided in this repository.

## Data Formatting

The source data has been reformatted for various analytical perspectives:

| **Format**                  | **Description**                                                                                                                                                                                               |
|-----------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **By Methodology**           | JSON arrays organized by methodology parameters.                                                                                                   |
| **By Methodology, By Country** | Closely mirrors the source database (land use and conversion are split into two files).                                              |
| **By Territory**             | Organizes data geographically (by continent, territory, and US state).  US states appear in one methodology. JSON files aggregate data from various methodology tabs. |

Additional resources:

- Data in CSV format.
- The `metadata` folder contains non-data items (e.g., notes) from the original database.


## Data Modifications

No material changes were made to the source data.  Non-material changes (see changelog):

- The US dollar sign was removed to facilitate use in database systems.
- 12 country names were edited for readability (e.g., "Bahamas, The" to "Bahamas").  All territories are mapped to their ISO-3166 Alpha-2 values.

## Author (Source Database / GVFD)

The International Foundation for Valuing Impacts (IFVI)

## Author (Repository / Derivative Dataset)

Daniel Rosehill  
(public at danielrosehill dot com)
