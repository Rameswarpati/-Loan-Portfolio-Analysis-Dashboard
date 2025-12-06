# -Loan-Portfolio-Analysis-Dashboard
loan records and built interactive Excel dashboards (Pivot Tables, Maps, Month Trends). Performed Good vs Bad loan segmentation, MoM performance analysis, state-wise trends, loan purpose analysis, and presented risk insights for decision makers


Data Cleaning & Preparation

Performed in Excel before dashboard creation:

Removed/treated missing values
Checked duplicates
Converted data types (Dates, Amounts, Interest Rate, DTI)
Standardized text fields
Added calculated columns for:
Loan Status Categorization: Fully Paid, Current, Charged Off
Good Loan % & Bad Loan %
Month, Quarter, Year extraction
MTD, PMTD & MoM% comparisons
Used Excel formulas + Pivot Table calculations to create metrics.

Key Portfolio Metrics:
| Metric                    | Value       |
| ------------------------- | ----------- |
| **Total Applications**    | **38.6K**   |
| **Total Funded Amount**   | **$435.8M** |
| **Total Amount Received** | **$473.1M** |
| **Average Interest Rate** | **12.05%**  |
| **Average DTI**           | **13.33%**  |


MTD vs Previous Month (Dec vs Nov):
| Metric             | Nov    | Dec    | MoM %        |
| ------------------ | ------ | ------ | ------------ |
| Loan Applications  | 4.0K   | 4.3K   | **6.91% ↑**  |
| Funded Amount      | $47.8M | $54.0M | **13.04% ↑** |
| Total Received     | $50.1M | $58.1M | **15.84% ↑** |
| Avg. Interest Rate | 11.94% | 12.36% | **3.47% ↑**  |
| Avg. DTI           | 13.30% | 13.67% | **2.73% ↑**  |

December shows strong growth in both disbursement and repayments.


Good Loan vs Bad Loan Analysis:

Good Loans
Percentage: 86.18%
Funded Amount: $370.2M
Total Received: $435.8M

Bad Loans
Percentage: 13.82%
Funded Amount: $65.5M
Total Received: $37.3M

Most losses occur in Charged Off loans.



Monthly Trend Insights:

Applications grew from 2.3K in Jan → 4.3K in Dec
Peak lending months: Oct, Nov, Dec
Shows steady business growth across the year



Geographic Analysis (State-wise):

Top 4 states by loan volume:

California – 6.9K
New York – 3.7K
Florida – 2.8K
Texas – 2.7K

 High-volume states need stronger risk and recovery strategies.


Loan Term Distribution:

36 Months: 28.2K
60 Months: 10.3K

 Short-term loans are less risky and more preferred.


Employment Length Analysis:

Highest borrower segments:

10+ Years Experience – 8.9K
<1 Year – 4.6K
2–4 Years Combined – ~12K

Stable employment = lower default probability.


Loan Purpose Distribution

Top categories:

Debt Consolidation – 18.2K
Credit Card – 5.0K
Other – 3.8K
Home Improvement – 2.9K
Small Business – 1.8K

Majority of lending is for debt consolidation.



<img width="1651" height="874" alt="Image" src="https://github.com/user-attachments/assets/465939bc-4f89-4f68-8287-e7347e602200" />
<img width="1412" height="727" alt="Image" src="https://github.com/user-attachments/assets/65ece7ff-2cdd-4e34-a23a-e4b40bee5c0e" />

- Delivered actionable insights from 38.6k loan applications using Power BI dashboards
- Identified 86% good loan issuance rate, enabling risk segmentation and portfolio optimization
- Highlighted rising DTI and interest rates in charged-off loans, supporting predictive risk modeling
- Mapped regional and purpose-based loan trends to guide targeted marketing and product design
- Enabled executive decisions by visualizing MoM growth across funding, collections, and application volume

- Risk Mitigation:
- Focus on reducing DTI and interest rates in high-risk segments (Charged Off & Current loans)
- Introduce stricter underwriting for loans with DTI > 14%
- Product Strategy:
- Expand offerings in high-demand categories (Debt Consolidation, Credit Card)
- Explore bundling options for long-term loans (10+ years) with financial planning services
- Marketing Optimization:
- Target renters and mortgage holders with tailored campaigns
- Use state-wise heatmap to prioritize high-volume regions
- Portfolio Monitoring:
- Track MoM changes in interest rate and DTI to preempt risk shifts
- Monitor current loans closely to prevent future charge-offs



