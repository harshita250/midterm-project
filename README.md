# CVM Claims Data Analysis (2016–2018) - README

## Project Overview
This project focuses on analyzing Medicare Chronic Vascular Management (CVM) claims from 2016 to 2018 to identify trends and provide actionable insights for optimizing sales force deployment, marketing strategies, and resource allocation.

## Objectives
1. **Evaluate HCP Behavior**:
   - Analyze claim volumes submitted by Healthcare Providers (HCPs) to identify segments based on submission patterns.
   - Guide strategies for In-Person Sales vs. Non-Personal Promotions (NPP).

2. **Examine Patient Demographics**:
   - Bucket patients into age groups based on claim volume trends.
   - Provide insights for targeted marketing budgets and promotional efforts.

3. **Analyze CVM Claims Trends**:
   - Determine CVM claims as a share of total claims over the years.
   - Identify business opportunities and recommend future analyses.

---

## Key Results

### HCP Behavior Analysis
- **Findings**:
  - 85% of HCPs submitted fewer than 10 CVM claims annually.
  - Total HCPs submitting claims increased by 27% from 2016 to 2018.
- **Actions**:
  - Prioritize in-person visits for high-volume HCPs (>10 claims annually).
  - Use digital outreach (emails, webinars, social media) for low-volume HCPs.

### Patient Demographics
- **Findings**:
  - 37% growth in claims among patients aged 70–79.
  - Significant increase in claims for patients aged 80+.
- **Actions**:
  - Allocate larger marketing budgets toward older age groups.
  - Develop preventative care messaging for younger groups (18–59).

### CVM Claims Trends
- **Findings**:
  - CVM claims consistently represented 14–15% of total claims annually.
  - Steady relevance of CVM services over the years.
- **Actions**:
  - Focus promotional efforts on regions with underperforming CVM claims.
  - Expand analysis to assess geographical and procedural trends.

---

## Tools and Techniques
- **Programming**: Python (pandas, NumPy, matplotlib, seaborn)
- **Data Cleaning**: Null value removal, deduplication, date standardization
- **Analysis Techniques**:
  - Segmentation (HCP claim volumes, patient demographics)
  - Trend analysis (CVM claims vs. total claims)
  - Visualization (stacked bar charts for claims and provider patterns)

---

## Usage Instructions
1. Clone the repository and ensure all datasets are present.
2. Run the Jupyter Notebook provided to:
   - Preprocess datasets (remove nulls, deduplicate, join datasets).
   - Generate visualizations and calculate key metrics.
3. Review charts and tables for insights into HCP behavior, patient trends, and CVM share.

---

## Future Enhancements
1. Include geographical segmentation to refine resource allocation.
2. Assess the effectiveness of promotional efforts on CVM claim growth.
3. Expand procedural analysis to uncover high-growth CVM services.

---

## Contact
For any questions or collaboration inquiries, please reach out to the project owner.
