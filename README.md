# About The Global Value Factors Explorer Dataset

[![Visit Website](https://img.shields.io/badge/Visit%20Website-blue)](https://gvfd-analysis.bydanielrosehill.com/)

This repository provides derivative datasets based on the International Foundation for Valuing Impacts (IFVI) Global Value Factors Database (GVFD). The GVFD converts environmental impacts, such as carbon emissions, into monetary values for use in financial analysis.  This repository aims to make the data more accessible for exploration and analysis of impact accounting.  

The original data source was published by the IFVI in October 2024 and is designed to guide organizations in preparing integrated financial accounts that incorporate both financial and non-financial data.  The value factors provided are meant to be used with quantity metrics, with the goal of promoting a holistic view of corporate financial health that considers planetary well-being.

---

## Using This Data

The IFVI data should be interpreted alongside its official methodology papers and documentation, available on the [IFVI website](https://www.ifvi.org). Static versions of these documents are included in this repository *solely for data provenance* and should **not** be considered official or authoritative.

This derivative dataset recognizes the growing movement to prioritize and define value creation based on a company's impact.

The GVFD was released by the IFVI with the following note:

*"To drive adoption of impact accounting and meet market needs as soon as possible, IFVI is making available four interim environmental methodologies, prior to completing an official methodology oversight process, including the VTPC Review and Due Process."*

## Docs for derivative database (this one)

**Documentation and notes on using this *derivative* dataset, along with my personal interpretations of the GVFD, can be found at: [https://gvfd-analysis.bydanielrosehill.com/](https://gvfd-analysis.bydanielrosehill.com/)**.  Please note that these are my own interpretations and are not official IFVI materials or endorsed by them.

[![Visit Website](https://img.shields.io/badge/Visit%20Website-blue)](https://gvfd-analysis.bydanielrosehill.com/)

---

## What are value factors?

"Value factors" convert quantity metrics (e.g., tons of CO2 emitted) into monetary terms. The GVFD uses US dollars for standardization but is intended for global use regardless of the reporting entity's local currency.

---

## What's in this Repository?

This derivative dataset is based on Version 1 (October 2024) of the GVFD and currently includes only environmental value factors.  The topics, developed by the IFVI in partnership with the Value Balancing Alliance (VBA), are:

* **Air Pollution:** Impacts of up to six air pollutants on human health, agricultural productivity, and other areas.
* **Land Use and Conversion:** Impacts of land occupation or conversion, including loss of ecosystem services across different locations and land use types.
* **Waste:** Impacts of waste generation and disposal methods (e.g., incineration, landfill), including impacts on leachate, disamenity, climate change, and air pollution.
* **Water Pollution:** Impacts of 104 potential water pollutants on human health and eutrophication.


## Licensing

This derivative dataset is subject to the same terms of use as the original database, available in `license.md` at the repository root.


## Versioning

This repository reflects GVFD Version 1 (October 15th, 2024).  It is not guaranteed to be the most recent version.  Consult the IFVI website for the latest data and updates.  While this repository aims to mirror the original GVFD, using this data for official purposes requires referencing the complete IFVI documentation, which is not included here.


## Data Formatting

The source data has been restructured for various analytical perspectives:

* **By Methodology:** JSON arrays organized by methodology parameters.
* **By Methodology, By Country:** Mirrors the source database structure (except Land Use and Conversion, which are split into two files).
* **By Territory:**  Organizes data geographically by continent, territory, and US state (US states appear in one methodology). JSON files aggregate data from various methodology tabs.

Additional resources:

* CSV format data.
* `metadata/` folder containing non-data items (e.g., notes from the original database tabs).

---

## Data Modifications

No material data changes were made.  Modifications are limited to formatting and restructuring for analysis.  Two non-material changes (documented in the changelog) are:

* Removal of US dollar signs for easier database integration.
* Standardization of 12 country names to more common versions (e.g., "Bahamas, The" to "Bahamas") and mapping all territories to their ISO-3166 Alpha-2 codes for clarity.

---

## Author (Source Database / GVFD)

The International Foundation for Valuing Impacts (IFVI)

---

## Author (Repository / Derivative Dataset)

Daniel Rosehill  
(public at danielrosehill dot com)
