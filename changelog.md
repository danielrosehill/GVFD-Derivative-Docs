# Changelog - Derivative Dataset

The following is a list of formatting modifications applied to V1 of the source dataset:

## Data formatting modifications

- Dolllar symbols were removed from the original dataset. The currency will be noted instead in manifest fields for each topic.

## Metadata

- Non-data elements were added as JSON files nested within each subject.

For example:

```
{
  "Name": "Water Pollution Value Factors",
  "Methodology Status": "Interim",
  "Update Date": "October 15, 2024",
  "Price Year": 2023,
  "Currency": "USD"
}
```

## Territory names and ISO 3166 matching

The names of 18 countries and territories were modified slightly to reflect vernacular usage.

Countries and territories were mapped onto their corresponding values in ISO-3166 (using Alpha-2 identifiers).