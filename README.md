### **Airline and Airport Flight Delay and Cancellation Analysis (Texas)**

#### **Project Overview**

This project analyzes flight delay data from January 2023 to April 2025 for six major Texas airports: Austin (AUS), Dallas/Fort Worth (DFW), Houston Bush (IAH), Houston Hobby (HOU), El Paso (ELP), and San Antonio (SAT). The primary goal is to identify and analyze the root causes of non-weather-related flight delays, understand their temporal patterns, and provide actionable insights for both travelers and industry professionals.

-----

#### **Key Questions Addressed**

  * What are the primary causes of non-weather-related delays, and how do they vary across different airlines and airports?
  * Are there observable trends in delays based on time (e.g., monthly, day of the week, seasonality)?
  * Is there a correlation between the number of flights and the number of delays?
  * How can data visualization be used to communicate these complex insights effectively?

-----

#### **Data Source**

The dataset used for this analysis was sourced from the **Bureau of Transportation Statistics (BTS)**, providing detailed information on airline performance, delays, and cancellations across various U.S. airports.

-----

#### **Methodology & Tools**

The project follows a comprehensive data analysis workflow:

1.  **Data Cleaning & Exploration:** The raw data was cleaned and prepared using **Python** with the **pandas** library. Missing values were handled, and columns were formatted for analysis.
2.  **Exploratory Data Analysis (EDA):** Initial analysis was performed in **Python** to identify top delay causes and trends.
3.  **Visualization & Dashboard Creation:** A professional, interactive dashboard was built using **Power BI** to present the key findings. This dashboard allows users to filter data by airport, airline, and time period.
4.  **DAX Measures:** Custom **DAX measures** were written to perform complex calculations, such as calculating the average delay minutes per flight and capping outlier values for a more accurate average.

**Tools Used:**

  * **Python:** For data cleaning and initial analysis.
  * **Pandas & Matplotlib:** Python libraries for data manipulation and visualization.
  * **Power BI:** For building an interactive and professional dashboard.
  * **GitHub:** For version control and portfolio presentation.

-----

#### **Key Findings**

The analysis revealed that flight delay causes are highly specific to individual airports and airlines. Key insights include:

  * **Airport-Specific Delay Profiles:**
      * **Dallas (DFW):** Delays are significantly influenced by **Late Aircraft** and **NAS (National Aviation System)** delays, particularly for major carriers.
      * **Houston Bush (IAH):** **NAS delays** are a dominant factor, suggesting high susceptibility to air traffic and airport-related congestion.
      * **San Antonio (SAT):** **Carrier-related delays** are a major issue for a number of airlines, including JetBlue Airways and SkyWest Airlines.
  * **Temporal Trends:**
      * **Seasonality:** A strong correlation was found between flight volume and delays, with a clear peak in delays during the summer months (June-August).
      * **Day of the Week:** Delays are not evenly distributed, with Friday and Sunday often showing the highest number of delays.
  * **Quantifying Delays:**
      * The average delay minutes were calculated and refined using custom DAX measures to provide a more accurate and representative metric for the average flight delay, rather than a misleadingly high number caused by extreme outliers.

-----

#### **Visualizations**

The Power BI dashboard provides an interactive and dynamic experience. Below are some key visualizations included in the final report:

<img width="1294" height="737" alt="image" src="https://github.com/user-attachments/assets/0b10afe9-7784-4a2a-a22f-95203c0771ae" />
*Caption: This visualization highlights the percentage breakdown of non-weather delay causes for airlines operating at a specific Texas airport (DFW).*


<img width="1309" height="737" alt="image" src="https://github.com/user-attachments/assets/f8e58884-f14d-4a1f-b9ba-a4b5fb329211" />
*Caption: A detailed look at the delays specific to Austin (AUS) airport.*


<img width="1304" height="734" alt="image" src="https://github.com/user-attachments/assets/f9167f84-b5d3-407e-821d-889b7ba9274d" />
*Caption: A look into the delays for United Airlines at Houston Bush (IAH) airport for the year 2024.*
