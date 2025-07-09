# Bank Loan Analysis Project

[![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)](https://powerbi.microsoft.com/)
[![Data Analysis](https://img.shields.io/badge/Data%20Analysis-4285F4?style=for-the-badge&logo=googleanalytics&logoColor=white)](https://github.com/topics/data-analysis)
[![Finance](https://img.shields.io/badge/Finance-00875A?style=for-the-badge&logo=cashapp&logoColor=white)](https://github.com/topics/finance)

## Overview
This project provides a comprehensive analysis of bank loan data using Power BI to create interactive dashboards and visualizations. The analysis focuses on loan performance, customer demographics, and key financial metrics to support data-driven decision making in the lending business.

## Project Structure
```
Bank Analysis Project/
│
├── README.md                                    # Project documentation
├── .gitignore                                   # Git ignore rules
├── financial_loan_full.csv                     # Raw loan data (38,578 records)
├── Bank Analysis.pbix                           # Main Power BI dashboard file
├── Bank Loan Analysis PPT Power BI.pptx        # Presentation slides
├── Domain Knowledge Doc.docx                    # Business context documentation
└── images/
    ├── Bank Loan Details Dashboard.gif          # Dashboard preview
    ├── Bank Loan Overview Dashboard.gif         # Overview dashboard preview
    └── Bank Loan Summary Dashboard.gif          # Summary dashboard preview
```


## Data Description
The analysis is based on a comprehensive loan dataset containing **38,578 loan records** with the following key attributes:

### Loan Information
- **Loan Amount**: Principal loan amount
- **Interest Rate**: Applied interest rate
- **Term**: Loan duration (36 or 60 months)
- **Grade & Sub-grade**: Risk assessment categories (A-E with numerical sub-grades)
- **Loan Status**: Current status (Fully Paid, Charged Off, etc.)

### Customer Demographics
- **Employment Length**: Years of employment (< 1 year to 10+ years)
- **Employment Title**: Job position
- **Annual Income**: Customer's yearly income
- **Home Ownership**: RENT, MORTGAGE, OWN
- **Address State**: Geographic location

### Financial Metrics
- **DTI (Debt-to-Income Ratio)**: Financial health indicator
- **Installment**: Monthly payment amount
- **Total Payment**: Amount paid to date
- **Total Accounts**: Number of credit accounts

### Application Details
- **Application Type**: Individual or joint application
- **Purpose**: Loan purpose (car, etc.)
- **Verification Status**: Income verification level
- **Issue Date**: Loan origination date
- **Payment Dates**: Last payment and next payment due dates

## Dashboards

### 1. Bank Loan Summary Dashboard
![Bank Loan Summary Dashboard](images/Bank%20Loan%20Summary%20Dashboard.gif)

**Key Metrics Displayed:**
- Total Loan Applications and funded amounts
- Average Interest Rate across portfolio
- Average Debt-to-Income (DTI) ratio
- Monthly trends and performance indicators
- Good vs Bad loan distribution
- Loan status breakdown (Fully Paid, Charged Off, Current)

### 2. Bank Loan Overview Dashboard
![Bank Loan Overview Dashboard](images/Bank%20Loan%20Overview%20Dashboard.gif)

**Analysis Focus:**
- Monthly loan trends and seasonality patterns
- Regional analysis by state
- Loan term distribution (36 vs 60 months)
- Employment length impact on loan performance
- Home ownership correlation with loan outcomes
- Loan purpose breakdown and performance by category

### 3. Bank Loan Details Dashboard
![Bank Loan Details Dashboard](images/Bank%20Loan%20Details%20Dashboard.gif)

**Detailed Analytics:**
- Individual loan record exploration
- Advanced filtering capabilities by multiple criteria
- Loan grade and sub-grade performance analysis
- Customer profile deep-dive with income verification status
- Payment history and installment analysis
- Risk assessment metrics and default prediction indicators

## Key Insights & Analysis Areas

### Portfolio Performance Metrics
- **Total Loan Volume**: $435.8M in total funded amounts
- **Application Success Rate**: Analysis of approved vs. declined applications
- **Default Rate Analysis**: Charged-off loans vs. fully paid loans
- **Average Loan Size**: Typical loan amounts by customer segment
- **Interest Rate Optimization**: Rate variations by risk grade

### Risk Assessment & Credit Analysis
- **Grade Distribution**: A-E grade performance with sub-grade breakdowns
- **DTI Impact**: Debt-to-income ratio correlation with default rates
- **Employment Stability**: Length of employment vs. loan performance
- **Verification Impact**: Income verification effect on loan outcomes
- **Payment Behavior**: Installment performance and early payoff patterns

### Geographic & Market Analysis
- **State-wise Distribution**: Top performing states and regional trends
- **Market Penetration**: Loan density by geographic regions
- **Regional Risk Patterns**: Default rates by state and region
- **Growth Opportunities**: Underserved markets identification

### Customer Segmentation & Demographics
- **Income-based Segments**: Performance across different income levels
- **Home Ownership Impact**: RENT vs. MORTGAGE vs. OWN correlation
- **Employment Categories**: High-performing job sectors and industries
- **Loan Purpose Analysis**: Car loans vs. other purposes performance
- **Application Type**: Individual vs. joint application success rates

## Technical Requirements

### Software Used
- **Microsoft Power BI Desktop**: For dashboard creation and data visualization
- **Microsoft PowerPoint**: For presentation materials
- **Microsoft Word**: For documentation

### Data Format
- CSV file with 38,578 rows and 24 columns
- Clean, structured data ready for analysis
- Date fields in MM-DD-YYYY format

## Getting Started

1. **Open Power BI File**: Launch `Bank Analysis.pbix` in Power BI Desktop
2. **Refresh Data**: Update data connections if needed
3. **Explore Dashboards**: Navigate through the three main dashboard views
4. **Review Documentation**: Check `Domain Knowledge Doc.docx` for business context
5. **View Presentation**: Open `Bank Loan Analysis PPT Power BI.pptx` for executive summary

## Business Value & Strategic Applications

### For Risk Management Teams
- **Default Prediction**: Early identification of high-risk loan profiles
- **Portfolio Balancing**: Optimize risk-return ratios across loan grades
- **Credit Policy**: Data-driven lending criteria and approval guidelines
- **Loss Mitigation**: Proactive strategies for at-risk accounts

### For Business Development
- **Market Expansion**: Identify high-potential geographic markets
- **Product Development**: Tailor loan products to customer segments
- **Pricing Strategy**: Competitive interest rate optimization
- **Customer Acquisition**: Target profitable customer demographics

### For Operations & Management
- **Performance Monitoring**: Real-time dashboard tracking of KPIs
- **Resource Allocation**: Optimize staffing and budget allocation
- **Compliance Reporting**: Regulatory reporting and audit support
- **Strategic Planning**: Long-term business strategy development

### Measurable Outcomes
- Reduced default rates through better risk assessment
- Increased loan approval efficiency
- Enhanced customer satisfaction and retention
- Improved portfolio profitability and ROI

## Data Quality Notes
- Dataset contains complete records with minimal missing values
- Standardized categorical variables for consistent analysis
- Verified data integrity across all key metrics
- Time series data spans multiple years for trend analysis

## Future Enhancements
- Real-time data integration
- Predictive modeling for default probability
- Advanced customer lifetime value analysis
- Machine learning integration for risk scoring

## Repository Information

### File Upload Guidelines for GitHub

**Essential Files to Upload:**
- ✅ `README.md` - Project documentation
- ✅ `financial_loan_full.csv` - Dataset (ensure no sensitive data)
- ✅ `Domain Knowledge Doc.docx` - Business documentation
- ✅ `Bank Loan Analysis PPT Power BI.pptx` - Presentation
- ✅ `images/` folder - All dashboard GIFs
- ✅ `.gitignore` - Git ignore rules

**Large Files (Consider alternatives):**
- ⚠️ `Bank Analysis.pbix` - Consider using Git LFS or external hosting

**Files to Exclude:**
- ❌ `desktop.ini` - System file
- ❌ Any temporary or cache files

### Data Privacy Note
Please review the dataset for any sensitive customer information before uploading. Consider anonymizing personal identifiers or using a sample dataset if privacy concerns exist.

### How to Use This Repository
1. Clone the repository: `git clone <repository-url>`
2. Install Power BI Desktop
3. Open `Bank Analysis.pbix` to explore dashboards
4. Review documentation in `Domain Knowledge Doc.docx`
5. Check presentation in `Bank Loan Analysis PPT Power BI.pptx`

## Contributing
Feel free to fork this project and submit pull requests for improvements or additional analysis features.


---
