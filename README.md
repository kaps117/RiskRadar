# RiskRadar-10K

**A Colab-based toolkit for extracting and visualizing Item 1A risk factors from SEC EDGAR 10-K filings.**

---

## 🚀 Project Overview

RiskRadar-10K automates the process of pulling the **Item 1A (Risk Factors)** section from a set of 10-K filings, extracting risk‐factor titles, and presenting a suite of visual insights—all within a single Google Colab notebook.

**Key features:**

* **Data Extraction:** Uses SEC’s JSON API and HTML parsing to gather risk-factor titles for each CIK/year pair.
* **Visualization Suite:** From tables and line charts to heatmaps, boxplots, and word clouds—explore patterns in risk disclosures.
* **Interactive Enhancements:** Interactive Plotly graphs and Seaborn-styled visuals coded directly in Colab.

---

## 📦 Files Provided

* **`rasamplemini_rfdtitle_output.csv`**: Sample output dataset containing columns

  ```text
  cik, filing_year, filing_date, reporting_date, rfdtitle
  ```
* **`RiskRadar-10K.ipynb`**: Google Colab notebook with all scraping code, visualizations, and narrative explanations.

---

## ▶️ How to Use in Colab

1. **Open the Notebook**
   Go to your Google Drive or Colab environment and open `RiskRadar-10K.ipynb`.

2. **Upload the Dataset**
   When prompted, upload `rasamplemini_rfdtitle_output.csv` via the Colab Files pane.

3. **Run All Cells**
   Execute each cell in order—this will:

   * Fetch and parse 10-K filings
   * Extract and normalize risk titles
   * Generate tables, line charts, heatmaps, boxplots, word clouds, and interactive charts

4. **Explore & Interpret**
   Read the accompanying text cells for context and insights. Feel free to modify filters, add new visuals, or extend the analysis.

---

## 🤝 Contributing & Extension

This notebook serves as a template. You can:

* **Add new visualizations** (e.g., scatter plots, topic modeling).
* **Integrate external data** (e.g., financial metrics).
* **Customize the scraping logic** for other SEC forms (e.g., 8-K, 10-Q).

Simply fork the notebook, make your changes, and share your improved version!

---

## 📄 License

This project is released under the **MIT License**. See the `LICENSE` file for details.

*Built for Professor Moon’s Research Assistant screening project.*
