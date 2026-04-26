# Bank Customer Churn Analysis

**Comprehensive customer churn analysis across 10,000-customer European banking portfolio identifying critical retention opportunities**

## 🎯 Business Problem
Bank experiencing 20.4% annual churn (2,037 customers). Analysis identifies root causes and quantifies retention opportunities across demographics, products, and engagement patterns.

## 💡 Critical Insights Discovered

**1. Product Complexity Paradox (Most Critical)** 
- 3-4 products → 82.7-100% churn vs 2 products → 7.6% churn
- Current cross-selling strategy destroying customer value
- **Action**: Immediate halt to 3+ product campaigns; portfolio simplification program

**2. Age as Strongest Predictor**
- 55+ customers: 36.75% churn vs ≤35 customers: 7.88% churn (4.7x higher)
- Middle-aged (36-55): 26.32% churn
- **Action**: Age-appropriate service delivery + dedicated senior support

**3. Germany Market Crisis**
- 32.4% churn (2x France at 16.2% and Spain at 16.7%)
- **Action**: Dedicated task force + localized product/service redesign

**4. Engagement = Leading Indicator**
- Inactive members: 26.9% vs Active: 14.3% churn
- **Action**: Predictive model + 60-day inactivity trigger campaigns

**5. Gender Disparity**
- Females: 25.1% vs Males: 16.5% (52% higher)
- **Action**: Gender-segmented research + targeted communication

**6. Debunked Assumptions**
- Credit score: Minimal impact—churn ranges only 18.62%-21.75% across all credit categories (Poor to Excellent)
- Tenure: No protective effect—churn stays consistently around 20% across 0-10 years
- Credit card: Negligible difference (20.81% vs 20.18%, only 0.63% gap)

## 🏗️ Workflow Architecture
```
Raw CSV (10,000 records)
            ↓
Data Cleaning & Validation (Excel)
            ↓
Exploratory Data Analysis (Excel Pivot Tables)
            ↓
Segmentation & Cohort Analysis (Excel Cross-Tabulation)
            ↓
Business Insight Generation
            ↓
Interactive Dashboard (Power BI)
            ↓
Strategic Recommendations
```

## 🛠️ Tools & Technologies

**Data Processing Layer**
- Microsoft Excel
  - Pivot Tables & Cross-Tabulation
  - LOOKUP Functions
  - Data Cleaning & Validation
  - Statistical Analysis

**Business Intelligence Layer**
- Microsoft Power BI
  - DAX (Calculated Measures & KPIs)
  - Data Modeling
  - Interactive Dashboards
  - Cross-filtering & Slicers

**Analysis Techniques**
- Exploratory Data Analysis (EDA)
- Customer Segmentation
- Cohort Analysis
- Churn Rate Analysis
- Pattern Recognition
- Strategic Business Translation

## 📊 Excel Dashboard
<img width="705" alt="Dashboard" src="https://github.com/user-attachments/assets/28fbc225-f4e7-4281-a4f2-161da7c9e6a4" />

*Excel dashboard visualizing churn patterns across 9 analytical dimensions.*

## 📊 Power BI Dashboard
<img width="1349" height="803" alt="Screenshot (390)" src="https://github.com/user-attachments/assets/97fc2907-4b9c-4ef2-a255-763e7dd48082" />

*Interactive Power BI dashboard with slicers for age category and gender, featuring KPI cards, product churn analysis, geography breakdown, and age distribution.*


## 💼 Business Impact & Value Delivered

**Actionable Intelligence for Leadership:**
- Redirected retention budget from ineffective strategies (credit card promotions, tenure rewards) to high-impact interventions (Germany market fix, product simplification)
- Prevented continued investment in failed 3-4 product cross-selling that causes near-100% customer loss
- Identified Germany as requiring urgent CEO-level intervention—32% churn threatens entire market viability

**Revenue Protection Strategy:**
- Targeting 4,849 inactive members (27% churn risk) enables proactive rescue of ~1,300 at-risk customers before they leave
- Focusing on 55+ segment (800 customers at 36.75% churn = 294 losses) with specialized service could retain 150+ high-tenure customers annually
- Fixing Germany market (814 current churners) by reducing churn to baseline 16% would save ~400 customers per year

**Operational Efficiency Gains:**
- Clear prioritization of retention efforts: Germany + 55+ females + inactive members = highest ROI segments
- Eliminated wasteful spending on ineffective credit score-based or tenure-based programs
- Created data-driven framework for testing retention interventions with measurable success metrics.

## 📁 Repository Structure
```
├── README.md                        # Project documentation
├── Churn_Modelling.csv              # Dataset (10,000 customer records)
├── dashboard-preview.png            # Excel dashboard screenshot
├── BankChurnDashboard.pbix          # Power BI interactive dashboard
├── powerbi-dashboard-preview.png    # Power BI dashboard screenshot
```

## 🔮 Future Enhancements
- **Predictive Modeling**: Logistic regression or random forest to score individual churn probability
- **Customer Lifetime Value**: Calculate revenue impact of retention across segments
- **Time-Series Analysis**: Identify seasonal churn patterns and trigger points
- **A/B Testing Framework**: Design experiments to validate retention interventions
- **Python Migration**: Rebuild analysis pipeline in Python (Pandas, Seaborn) for automated insight generation

## 📊 Key Statistics Summary

| Metric | Finding | Business Implication |
|--------|---------|----------------------|
| Overall Churn | 20.4% (2,037/10,000) | 1 in 5 customers leaving annually |
| Germany Risk | 32.4% (814 churners) | Market-specific crisis requiring immediate action |
| Age Impact | 55+: 36.75% vs ≤35: 7.88% | 4.7x higher senior churn reveals service gap |
| Product Paradox | 3-4 products: 82.7-100% churn | Cross-selling strategy fundamentally broken |
| Gender Gap | Females: 25.1% vs Males: 16.5% | 52% higher female churn signals unmet needs |
| Engagement Effect | Inactive: 26.9% vs Active: 14.3% | Early warning system opportunity |

---

**Author**: Debanjali Saha  
📧 debanjalisaha04@gmail.com | 💼 [LinkedIn](https://www.linkedin.com/in/debanjali-saha-ba11aa255/)

*Developed for data analytics portfolio showcasing consulting-level business analysis*

**Tags**: `#DataAnalytics` `#Data Modelling` `#CustomerRetention` `#ChurnAnalysis` `#BusinessIntelligence` `#Excel` `#Power BI` `#Banking`
