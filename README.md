# PMX-Bank-Mortgage-Analysis
Interactive Tableau dashboard analyzing mortgage performance and delinquency trends across Canada.

**Project Status:** ✅ Complete - Analysis & Visualization Ready

## 📋 Overview
This project demonstrates end-to-end data analysis skills, including data cleaning, metric calculation, and business intelligence visualization. The interactive Tableau dashboard focuses on mortgage client distribution, mortgage values, and delinquency rates by region, providing actionable insights to support risk management and strategic decision-making.

## 🎯 Business Case
PMX Bank is facing concerns about rising mortgage delinquency rates across Canada. Preliminary data from F2016 indicates that at least 1% of mortgage clients are delinquent, which could signal underlying issues in client risk management and loan performance. This issue affects both the Vice President of RESL and the Operations teams, who rely on accurate data to make financial and risk-related decisions. If left unaddressed, the bank could face increased default losses and reduced customer trust. A successful solution involves developing an interactive visualization tool to monitor delinquency rates across regions, assess correlations with other client products, and support data-driven decisions to reduce future risk.

### Situation
As an analyst for PMX Bank, you are tasked with validating data, preparing analytical tools, and creating a dashboard to monitor mortgage delinquency rates. Collaboration with the Technology Team is required to ingest data from Online Transactional Systems and prepare it for analysis. The key metrics to monitor include the number of mortgage clients, total mortgage values, and delinquent mortgages per region.

| Metric Name | Description | Unit of Measure |
|-------------|------------|----------------|
| Number of Mortgage Clients by Region | Total count of mortgage clients in each region | # |
| Value of Mortgages by Region | Total dollar value of all mortgages per region | $ |
| Delinquent Mortgages by Region | Count of mortgage clients marked as delinquent per region | # |

[View Tableau Dashboard](#)(https://public.tableau.com/app/profile/nishanee.williams/viz/PMXBankMortgagePerformanceDashboard/Dashboard1)

## 🛠️ Tech Stack
- **Tableau** – visualization & dashboard creation  
- **SQL** – data querying & preparation  
- **Python / Data Cleaning** – analytics pipeline

## 🧹 Data Preparation Process

### Data Extraction & Cleaning
1. Collected mortgage data from the F2016 dataset provided for the assignment.
2. Checked for missing or inconsistent records and standardized formats for numerical values and dates.
3. Removed any irrelevant or duplicate entries to ensure accurate metric calculations.

### Metric Calculations
1. Calculated **Number of Mortgage Clients by Region**.
2. Calculated **Total Mortgage Value by Region**.
3. Calculated **Delinquent Mortgages by Region**.
4. Verified all metrics for consistency with the business requirements.

### Filters & Dashboard Preparation
1. Applied filters for **Region** to allow dynamic exploration of metrics.
2. Ensured all views in the dashboard matched the provided template.
3. Prepared the Tableau workbook for publishing to Tableau Public with full interactivity.

### Validation
1. Checked for duplicate or missing entries.
2. Verified all calculations and filters.
3. Ensured the dashboard layout aligned with the assignment template.

## 📊 Key Analysis Areas
1. **Number of Mortgage Clients by Region**  
   - Identify client distribution across regions to highlight high- and low-concentration areas.

2. **Mortgage Value by Region**  
   - Assess total mortgage exposure by region to monitor financial risk.

3. **Delinquent Mortgages by Region**  
   - Analyze delinquency patterns and identify regions with potential risk for default.

4. **Correlation with Other Products**  
   - Explore how delinquency in mortgages relates to other products, such as credit cards, for cross-product risk insights.

## 🔍 Key Findings & Insights

1. **High-Risk Regions**  
   - Certain regions showed higher delinquency rates, suggesting a need for targeted monitoring and intervention.

2. **Client Concentration Patterns**  
   - Regions with large numbers of mortgage clients correlate with higher total mortgage values and, in some cases, higher delinquency counts.

3. **Cross-Product Risk Indicators**  
   - Delinquent mortgage clients often also held other products, highlighting potential areas for portfolio risk management.

4. **Trend Identification**  
   - Patterns across regions allow PMX Bank to prioritize resource allocation for risk mitigation and customer support.

## 💡 Recommendations

Based on the analysis, actionable recommendations for PMX Bank include:

1. **Monitor High-Risk Regions**  
   - Focus attention on regions with elevated delinquency rates.

2. **Implement Risk Mitigation Strategies**  
   - Develop region-specific intervention plans to reduce future defaults.

3. **Cross-Product Analysis**  
   - Track delinquent mortgage clients’ engagement with other products to manage portfolio risk.

4. **Resource Allocation**  
   - Prioritize operational resources to support high-risk regions and ensure effective monitoring.

## 🔗 Data Source
PMX Bank mortgage dataset provided as part of the course assignment.  

- **Dataset Type:** Mortgage clients and product data  
- **Time Period:** F2016  
- **Provided By:** Course Resources / McMaster University  
- **File Format:** Excel  
- **Note:** This dataset is provided for educational purposes as part of the school assignment.

## 🎓 Project Credit
This project is based on the PMX Bank Mortgage Analysis assignment provided as part of the Data Analytics course at McMaster University. The business requirements and dataset were provided as part of the course resources, with all analysis and visualization implemented independently.

---

![PMX Bank Mortgage Dashboard](#) <!-- Replace # with your Tableau Public screenshot link -->
