# Vehicle Emissions Data Analysis

## Project Overview
This project analyzes U.S. EPA light-duty vehicle emissions data to assess manufacturer compliance trends over time. The analysis focuses on identifying high-emission outliers and visualizing CO₂ emissions trends by manufacturer and model year.

The project demonstrates:
- Data cleaning and validation
- Exploratory data analysis (EDA)
- Compliance-style reporting
- Visualization for technical insights

## Dataset
- Source: [EPA Automotive Trends Data](https://www.epa.gov/automotive-trends/explore-automotive-trends-data)
- Key fields: `Model Year`, `Manufacturer`, `Fuel Type`, `CO2 Emissions (g/mi)`, `City MPG`, `Highway MPG`

## Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

## Methodology
1. **Data Cleaning:** Removed null values, selected relevant columns, and formatted types.  
2. **Trend Analysis:** Calculated average CO₂ emissions per manufacturer by model year.  
3. **Visualization:** Plotted manufacturer trends from 2010–2022 to highlight improvements and potential compliance risks.  
4. **Outlier Detection:** Identified high-emission vehicles using Median Absolute Deviation (MAD).  
5. **Compliance Reporting:** Generated summary tables simulating a regulatory report on potential non-compliant models.

## Key Findings
- Major manufacturers like Ford and GM reduced average CO₂ emissions steadily over 2010–2022.  
- Detected outlier models with unusually high emissions that may require additional review.  
- Visualizations highlight manufacturer trends and potential risk periods.

## How to Run
1. Clone this repository:  
```bash
git clone https://github.com/thatskhalid/EPA-Emissions-Analysis.git
