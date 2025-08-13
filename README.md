# Organizational Spending - Sunburst Diagram Example

**Author email:** 23f3002689@ds.study.iitm.ac.in

This repository contains:

- `spending_breakdown.csv` — sample hierarchical budget data (department, expense, amount).
- `chart.png` — sunburst diagram preview PNG (512x512 px).
- This `README.md` — instructions for producing a **genuine** RAWGraphs Sunburst Diagram.

---

## Project Overview

A Sunburst Diagram is the most appropriate visualization for showing multi-level categorical budget data.  
This example breaks down **organizational spending** by **department** and **expense type**, allowing executives to see both high-level allocations and finer subcategory details.

---

## Data Structure

The dataset contains 18 records with:

- **department**: The primary cost center (e.g., Engineering, Marketing, Sales).
- **expense**: The specific type of expenditure within a department.
- **amount**: The budget amount in currency units (integer).

### Sample (first 5 rows)
| department  | expense     | amount |
|-------------|-------------|--------|
| Engineering | Personnel   | 47614  |
| Engineering | Software    | 15230  |
| Engineering | Tools       | 8420   |
| Marketing   | Events      | 26524  |
| Marketing   | Advertising | 31200  |

---

## Creating the Sunburst in RAWGraphs

1. Go to **[RAWGraphs.io](https://rawgraphs.io/)** and click **Use it now**.
2. Import:
   - Either **upload** `spending_breakdown.csv`
   - Or **paste** its contents into the data input box.
3. Select **Sunburst Diagram** as the chart type.
4. Map data fields:
   - **Hierarchy**: Drag `department` first, then `expense`
   - **Size**: Drag `amount`
   - **Color**: Drag `department` (or `expense` if preferred)
5. Customize:
   - Choose a **professional, muted color palette** for boardroom use.
   - Enable **labels** for both category names and values.
   - Adjust **font sizes** for readability at 512×512 resolution.
6. Export:
   - Choose **PNG** format
   - Dimensions: **512 × 512 px** (within the 300–512 range)
   - Optionally export as **SVG** for vector use in reports.

---

## Repository Structure

