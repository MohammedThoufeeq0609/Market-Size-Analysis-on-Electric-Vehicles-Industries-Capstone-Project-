# ⚡️ Electric Vehicle Market Size Analysis

A comprehensive, data-driven analysis to estimate the current and future potential of the Electric Vehicle (EV) industry. This project utilizes Python to perform a detailed market size assessment, providing actionable insights for automotive manufacturers and infrastructure stakeholders.

## 🎯 Project Goal
The primary objective is to move beyond simple EV registration counts by applying data analytics to a real-world dataset. The analysis aims to:

1.  **Quantify Market Growth:** Assess the rate at which consumers are shifting from Internal Combustion Engines (ICE) to electric powertrains (BEVs and PHEVs).
2.  **Estimate Market Potential:** Calculate the Total Available Market (TAM), Serviceable Available Market (SAM), and Serviceable Obtainable Market (SOM) to determine market boundaries and opportunities.
3.  **Identify Strategic Challenges:** Provide recommendations based on data, particularly focusing on **infrastructure scalability** to sustain market momentum.

## 📈 Key Findings & Strategic Recommendations
The analysis confirmed that the EV industry is in a **high-growth phase** with no immediate signs of saturation.

* **Significant Consumer Shift:** The transition towards Battery Electric Vehicles (BEVs) is accelerating, signaling a permanent change in consumer preference.
* **Infrastructure Challenge:** With nearly **1 million new EVs projected annually by 2030**, the biggest bottleneck to sustained growth is the lack of immediate and substantial investment in charging networks and grid capacity.

> **Strategic Recommendation:** Stakeholders must pivot from "early adopter" strategies to **"mass market"** support. Focus areas should include expanding service centers, affordable model availability, and reliable public charging corridors.

## 🛠️ Tech Stack
* **Language:** Python 3.x
* **Data Manipulation:** **Pandas**, **NumPy**
* **Visualization:** **Matplotlib**, **Seaborn**
* **Data Sourcing:** Utilizes a real-world dataset of EV registrations (specifically mentioned as being primarily from **Washington State** in the report).
* **Environment:** Jupyter Notebook / Google Colab

## ⚙️ Methodology
The project follows a standard Data Science methodology tailored for market research:

1.  **Data Acquisition & Cleaning:**
    * **Loading:** Data is loaded from the registration dataset.
    * **Imputation:** Missing values in critical fields like **Base MSRP** and **Electric Range** are handled to ensure a clean analytical base.
2.  **Exploratory Data Analysis (EDA):**
    * Analyzing the distribution and trends of EV registrations over time.
    * Calculating **penetration rate** (EVs vs. total vehicle fleet) to assess market maturity.
3.  **Market Sizing (TAM, SAM, SOM):**
    * **TAM (Total Available Market):** Calculated as the theoretical maximum number of vehicles (total addressable fleet).
    * **SAM (Serviceable Available Market):** The realistic portion of the TAM that can be served (e.g., consumers interested in the EV transition).
    * **SOM (Serviceable Obtainable Market):** The projected share of the market realistically captured by the company/segment over a specific period.
4.  **Correlation Analysis:** Investigating the relationship between key variables (e.g., **Model Year**, **Electric Range**, and **Base MSRP**).

## 📂 Project Structure & Usage
The analysis is self-contained within the Jupyter Notebook.

### **How to Run**

1.  Clone the repository:
    ```bash
    git clone [https://github.com/yourusername/ev-market-size-analysis.git](https://github.com/yourusername/ev-market-size-analysis.git)
    ```
2.  Install dependencies:
    ```bash
    pip install pandas numpy matplotlib seaborn
    ```
3.  Open the main analysis notebook:
    ```bash
    jupyter notebook Market_Size_Analysis_on_Electric_Vehicles_Industries.ipynb
    ```

### **File Descriptions**

* `Market_Size_Analysis_on_Electric_Vehicles_Industries.ipynb`: The core analytical code covering data cleaning, EDA, market size calculations, and visualization.
* `Market Size Analysis on Electric Vehicles Industries.pdf`: The final report summarizing the methodology, key findings, and strategic recommendations.
