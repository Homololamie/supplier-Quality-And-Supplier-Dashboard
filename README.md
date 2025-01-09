
![image](https://github.com/user-attachments/assets/0869fed3-0154-496e-8b11-df7df602b5f4

# Project Title: Supplier-Quality-And-Performance-Dashboard
This Repository Contains Supplier Quality And Performance Analysis Across Multiple Dimensions Such As Vendors, Plants, Materials, And Defect Types. 

## Table Of Content

[Project Overview](#project-overview)

[Data Sources](#data-sources)

Tool  Used
Data Cleaning and Preparations
Data Model
Data Visualizations And Insight Generation
Key Findings
Recommendations

## Project Overview

The case study presented focuses on a manufacturing company struggling to monitor and improve supplier performance effectively. By leveraging business intelligence tools, the company centralized procurement data and generated actionable insights to address critical challenges such as material defects, vendor reliability, and production downtime.
Power BI is used to analyze supplier quality and performance across key dimensions, including vendors, plants, materials, and defect types. The dashboard delivers a comprehensive view of defects, downtime, and their financial impact, enabling manufacturers to pinpoint problem areas and implement strategies to enhance supplier quality and reduce operational inefficiencies.


## Data Sources

The Dataset Utilized In This Project Originates From Real-World Business Operations Provided By Enerprise Manufacturer Ltd. To Ensure Confidentiality, The Data Has Been Anonymized And Cannot Be Directly Attributed To Any Specific Organization.

The Data Obtained Contains 7 Tables Representative Of The Operations In The Organization. The Tables Are:
- Category Data
- Defect Type Data
- Defect Data
- Material Type
- Metrics (Facts Table)
- Vendor Data
- Plant Data

## Tool  Used
  - Microsoft PowerBI
      i Power Query Was Used For Data Cleaning
      ii Powerbi was Used For Analysis
      iii Data Visualization

##  Data Cleaning and Preparations
The Data Cleaning Process Include The Following Steps
-Header Promotion: Ensured That The First Row Of Data Is Used As The Header For Better Clarity.
- Data Type Formatting: Adjusted Data Types To Ensure Accurate Analysis And Compatibility With Power BI.
- Calculated Columns: Added New Calculated Field To Facilitate Deeper Insights.
- Column Merging And Extraction: Combined And Extracted Relevant Columns To Streamline The Dataset.
- Data Trimming: Removed Unnecessary Whitespace From The Dataset For Cleaner Data Presentation.
- Standardization: Standardized Column Names, Date Formats, And Currency To Maintain Consistency Throughout The Dataset.
- Data Profiling: Conducted Data Profiling To Ensure Quality Assurance And Identify Any Data Anomalies On The Entire Dataset.
- Removal Of Unwanted Columns And Duplicates: Cleared Out Irrelevant Columns And Eliminated Duplicate Entries To Refine The Dataset.

##  Data Model
The Dashboard Was Built Using A Star Schema Data Model For Optimal Performance And Ease Of Analysis. 
The Schema For The Table Is Presnted Below

![image](https://github.com/user-attachments/assets/a580fd4e-4f46-4a5f-bf20-3ac3ad489754)



## Data Visualizations And Insight Generation

##### Dashboard Overview

![image](https://github.com/user-attachments/assets/a9457b06-2bb7-4898-9b20-594973e83500)


The Key Performance Indicators (Kpis) For The Current Month Indicate A 4.25% Increase In Defect Quantity, A 4.39% Increase In Downtime Hours, And A 4.39% Rise In Downtime Cost Per Hour Compared To The Previous Month. The Total Defect Quantity Stands At 2.60 Billion, With A Downtime Of 216,000 Hours And A Downtime Cost/ Hour Of $2.16 Million. These Metrics Suggest That Vendors Supplied Lower-Quality Materials, Negatively Impacting The Production Process.
For 2019 Year The Months Of September And October Recorded The Highest Defect Quantities And Downtime Hours. This Surge May Be Linked To Increased Vendor Orders In Preparation For The Festive Period Which Led To A Higher Supply Of Substandard Materials.Avamm, Meejo, And Yombu Are The Worst-Performing Vendors By Defect Quantity, While The Worst-Performing Plants By Defect Quantity Are Hingham, Charles City, And Twin Rocks. Among Materials Raw Materials,  Corrugates And Film Are The Worst Performers.  By Category, The Worst Performers Are Mechanical, Logistics, And Packaging .

#### Vendor Performance

![image](https://github.com/user-attachments/assets/63a303ca-8627-4825-95d1-4647599ec05d)


#### Plant Performance

![image](https://github.com/user-attachments/assets/0dfa878d-38ea-4d24-902a-1d7c37d48308)


#### Material Performance

![image](https://github.com/user-attachments/assets/4e54d949-a14e-4dec-9715-968ab85b2b17)


Raw Materials Account For The Highest Defect Quantity And Downtime, Closely Followed By Corrugate , Film, Labels, And Cartons. The Most Significant Defect With The Highest Defect Quantity And Downtime Is Not Certified, Followed By Bad Smith, Misc, Foreign Material, Spec. This Suggests Material Supply Quality Issues Or Delays In The Certification Process.
The Category "Mechanical" Dominates With The Highest Defect Quantity And Downtime Hours, Indicating Issues With Equipment Or Machinery. Followed By Gistics, Materials & Components, Goods & Service And Lastly Electrical. The Dominance Of The Mechanical Category Suggests Recurring Maintenance Or Equipment Breakdown Which Could Exacerbated By Aging Machinery, Lack Of Preventive Maintenance, Or Improper Handling.
The Defect Quantity And Downtime Hours Spike Significantly In October And November Respectively For Both Mechanical And Logistic Categories, Suggesting Potential Seasonal Or Process-Related Challenges. The Spike Could Indicate A Surge In Demand Or Increased Production Pressure Leading To More Defects And Equipment Stress.

-------------------------------------------------------------------------------------

#### Downtime Impact

![image](https://github.com/user-attachments/assets/28943ac4-ad1e-4083-b5a1-f39ee995d783)


## Key Findings 
The Dashboard Analysis Has Identified The Following As The Primary Causes Of The High Defect Quantity And Increased Downtime

- Operational Inefficiencies Such As Inefficient Machinery Or Aging Equipment Or Poorly Maintained Equipment .
- Quality Control Issues: Weak Or Inconsistent Quality Assurance Practices 
- Material Quality: This Suggests Material Supply Quality Issues Or Delays In Certification Processes 
- Geographical Challenges: Certain Locations May Face Logistical Issues, Environmental Challenges Or Staffing Shortages That Impact Production Quality.

## Recommendations
- Collaborate With Underperforming Vendors To Address Quality Issues. 
- Conduct  Performance Reviews And Implement Strict Quality Control Measures. Reward Low-Risk Vendor(I.E Vendor With Low Defect Quantity And Downtime Hours) To Encourage Sustained 
  Performance.
- Address Raw Material Quality: By Working Closely With Suppliers To improve the Quality And Ensure Timely Certification Of Raw Materials.
- Enhance Preventive Maintenance: This Can Be Done By Developing Robust Preventive Maintenance Schedule For Machinery
- Monitor Defects Regularly: By Analyzing Production Processes In months with High Defect Quantity And Downtime Hours To Identify Causes And Adjust Processes To Handle Seasonal Spikes 
  Efficiently.

## Limitations 
Absence Of The Total Orders Of Supplies  Data  By Each Vendor 

### Contact
For any questions or support, please contact:

Name: Oladipo Omolola
Email: oladipoomolola29@gmail.com



