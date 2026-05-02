# power1st Power BI Report

This repository contains a Power BI Desktop report (`power1st.pbix`) and extracted metadata to make review and collaboration easier on GitHub.

## Contents

| Path | Purpose |
|---|---|
| `power1st.pbix` | Main Power BI report file. |
| `src/report_layout.json` | Extracted report layout for easier code review/diffing. |
| `src/metadata.json` | Extracted Power BI metadata. |
| `src/settings.json` | Extracted report/query settings. |
| `.gitattributes` | Recommends Git LFS handling for `.pbix` binary files. |

## Report summary

- Power BI file version: `1.28`
- Created from: `Cloud` `2026.04`
- Pages: `1`
- Visual containers: `12`

### Pages

| Page | Visual containers |
|---|---:|
| Page 1 | 12 |

### Visual types detected

| Visual type | Count |
|---|---:|
| `card` | 3 |
| `donutChart` | 2 |
| `textbox` | 2 |
| `barChart` | 1 |
| `lineChart` | 1 |
| `pieChart` | 1 |
| `pivotTable` | 1 |
| `slicer` | 1 |

## How to use

1. Clone this repository.
2. Install [Git LFS](https://git-lfs.com/) before committing changes to `.pbix` files.
3. Open `power1st.pbix` in Power BI Desktop.
4. Make changes, save the `.pbix`, and commit both the `.pbix` and any updated extracted JSON files if you regenerate them.

## Suggested workflow

- Keep the `.pbix` file as the source of truth for Power BI Desktop.
- Use the extracted JSON files only for review, search, and lightweight change tracking.
- Avoid committing local cache, temp, or backup files.

## Notes

- This repo does not include credentials or workspace connection secrets.
- Before publishing publicly, review data sources and embedded data for sensitive information.
