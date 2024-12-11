# Economic Complexity and Global Supply Chain Resilience: Insights through Advanced Data Visualization

---
## Table of Contents
1. [Project Overview](#project-overview)
2. [Authors](#authors)
3. [Disclaimer](#disclaimer)
4. [Acknowledgments](#acknowledgments)
5. [Table of Contents](#table-of-contents)
6. [Navigation Instructions](#navigation-instructions)
    - [Dataset](#dataset)
    - [Mapfile](#mapfile)
    - [CODE](#CODE)
7. [How to Run the Code](#how-to-run-the-code)
8. [Interactive Visualization Product](#Interactive-Visualization-Product)
9. [Statement of Intellectual and Professional Growth](#statement-of-intellectual-and-professional-growth)
10. [Embedded Media](#embedded-media)
---
## Project Overview
This project explores the interplay between economic complexity and global supply chain resilience using advanced data visualization techniques. The objective is to uncover patterns and vulnerabilities in trade networks and provide actionable insights for policymakers, researchers, and businesses.

---

## Authors
- **Name**: Yifei Wang
- **Role**: Project Lead and Developer


---
## Disclaimer
This repository contains the final project for **INFOSCI 301 Data Visualization and Information Aesthetics**, instructed by **Prof. Luyao Zhang** at **Duke Kunshan University in Autumn 2024**.

---

## Acknowledgments
- Prof. Luyao Zhang for invaluable guidance and feedback.
- INFOSCI 301 Classmates for collaborative discussions and feedback insights.
- AIGC tools like ChatGPT for drafting and revising project documentation.
- Thanks to Chakraborty et al. for providing data on exposure,  the UN Comtrade Database for providing Trade data, and ECI data

---

## Navigation Instructions
### Dataset
The `Dataset/` folder contains three key datasets used in this project:
1. **Export Competitiveness Data (`Export COMPET_.csv`)**:
   - Contains data on trade exports and competitiveness for various countries.
   - Includes indicators for export performance and specialization in global markets.
   - Used for generating visualizations on trade flows and economic diversity.

2. **Systemic Risk Data (`Fig2a-avg_exposure.csv`)**:
   - Highlights systemic risk exposure within global supply chains.
   - Contains average exposure metrics for firms and regions to disruptions.
   - Used to visualize cascading effects and vulnerabilities in supply networks.

3. **Economic Complexity Index Data (`multidimensional_eci_data.csv`)**:
   - Provides multidimensional metrics on economic complexity for countries.
   - Includes data on trade sophistication, technological outputs, and industrial diversity.
   - Central to mapping economic complexity and its correlation with resilience.
### Mapfile
The `Mapfile/` folder includes:
- **`ne_110m_admin_0_countries.shp`**: A shapefile for geographic mapping.
### Code
The `CODE/` folder includes:
- **`INFOSCI_301_Final_Project_Yifei_Wang.ipynb`**: The code for visulization.

---

## How to Run the Code
The code for this project is available in the `CODE/` folder as `INFOSCI_301_Final_Project_Yifei_Wang.ipynb`.

### Instructions for Running the Code in Google Colab
1. Open [Google Colab](https://colab.research.google.com).
2. Upload the `INFOSCI_301_Final_Project_Yifei_Wang.ipynb` file to your Colab environment.
3. Upload the required datasets and map files:
    - Datasets: 
      - `Export COMPET_.csv`
      - `Fig2a-avg_exposure.csv`
      - `multidimensional_eci_data.csv`
    - Mapfile:
      - `ne_110m_admin_0_countries.shp` (and its associated files like `.dbf` and `.prj`).
4. Ensure all files are in the same working directory in Colab.
5. Install required libraries by running the following command in a Colab cell:
    ```python
    !pip install geopandas plotly pandas
    ```
6. Run the script by executing the cells in the `INFOSCI_301_Final_Project_Yifei_Wang.ipynb` file.

---
## Interactive Visualization Product
The interactive visualization product, developed using Dash, is available in another GitHub repository.  
[View the Dash Interactive Visualization Repository](https://github.com/Yifei-unavailable/dash-yifei.git)
### In GitHub Codespace of dash-repository
  ```
pip install -r requirements.txt
python Fianlapp.py
  ```

---
## Statement of Intellectual and Professional Growth
This project provided an opportunity to develop expertise in:
- Data visualization techniques and tools like Python, Plotly, and Dash.
- Analyzing economic complexity and supply chain resilience through multidimensional datasets.
- Collaborative research and documentation using GitHub.

---
## Embedded Media
### Demo Video
[Download Demo Video](Demo%20Video_INFOSCI%20301_Yifei%20Wang.mp4)

### Poster
![Project Poster](Poster/Poster-1.png)


