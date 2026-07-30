# AB Testing: Marketing Campaigns (Facebook vs AdWords)

## 📊 Project Overview

A comprehensive statistical analysis comparing the performance of **Facebook Ads** vs **AdWords campaigns** across the entire year 2019 (365 days of campaign data). This project identifies which advertising platform delivers better ROI, cost-effectiveness, and conversion metrics.

**Key Question:** Which ad platform is more effective in terms of conversions, clicks, and overall cost-effectiveness?

---

## 🎯 Business Problem

As a marketing agency optimizing client advertising spend, understanding which platform yields better results is crucial for:
- **Maximizing ROI** on advertising budgets
- **Resource allocation** across platforms
- **Strategic decision-making** for campaign optimization
- **Cost efficiency** improvement

---

## 📈 Dataset Overview

- **Time Period:** Full year 2019 (January 1 - December 31)
- **Records:** 365 daily observations
- **Campaigns:** Facebook Ads vs AdWords
- **Size:** ~36 KB CSV file

### Key Metrics Analyzed:
- **Ad Views** - Total impressions per campaign
- **Ad Clicks** - Click-through performance
- **Ad Conversions** - Actual conversions achieved
- **Cost per Ad** - Daily advertising spend
- **Click-Through Rate (CTR)** - Views → Clicks efficiency
- **Conversion Rate** - Clicks → Conversions efficiency
- **Cost per Click (CPC)** - Cost-effectiveness metric

---

## 🔧 Tools & Technologies

- **Python 3.x**
- **Pandas** - Data manipulation & analysis
- **Matplotlib & Seaborn** - Data visualization
- **SciPy & Statsmodels** - Statistical testing
- **Scikit-learn** - Regression analysis
- **Jupyter Notebook** - Interactive analysis environment

---

## 📊 Analysis Highlights

The notebook includes:

### 1. **Exploratory Data Analysis (EDA)**
   - Data loading and cleaning
   - Descriptive statistics for both platforms
   - Data quality checks

### 2. **Statistical Testing**
   - Hypothesis testing (t-tests, z-tests)
   - Correlation analysis between metrics
   - Cointegration analysis for time-series relationships

### 3. **Time-Series Analysis**
   - Seasonal decomposition
   - Trend analysis across months
   - Performance patterns over time

### 4. **Comparative Performance Metrics**
   - CTR comparison (Facebook vs AdWords)
   - Conversion rate comparison
   - Cost-per-click (CPC) efficiency
   - Total ROI calculations

### 5. **Regression Analysis**
   - Linear regression models
   - R² score evaluation
   - Predictive insights

### 6. **Visual Insights**
   - Time-series plots
   - Distribution comparisons
   - Box plots & violin plots
   - Heatmaps for correlations

---

## 🚀 Quick Start

### Prerequisites
```bash
python 3.6+
pip
```

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/ab-testing-marketing-campaigns.git
   cd ab-testing-marketing-campaigns
   ```

2. **Create a virtual environment** (recommended)
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Launch Jupyter Notebook**
   ```bash
   jupyter notebook
   ```

5. **Open the analysis**
   - Navigate to `notebooks/AB_Testing_Marketing_Campaigns.ipynb`
   - Run all cells or explore section by section

---

## 📁 Project Structure

```
ab-testing-marketing-campaigns/
│
├── README.md                              # Project documentation
├── requirements.txt                       # Python dependencies
├── .gitignore                            # Git ignore file
│
├── notebooks/
│   └── AB_Testing_Marketing_Campaigns.ipynb    # Main analysis notebook
│
├── data/
│   └── marketing_campaign.csv             # 365 days of campaign data
│
└── results/
    └── (Optional: exported visualizations & findings)
```

---

## 📊 Key Findings

*(Complete findings after running the notebook)*

- **Winner Platform:** [To be determined after analysis]
- **Best Metric:** [Performance differentiator]
- **Cost Efficiency:** [CPC & ROI comparison]
- **Consistency:** [Stability over time]

---

## 💡 Skills Demonstrated

✅ **Data Analysis:** EDA, data cleaning, exploratory techniques  
✅ **Statistical Testing:** Hypothesis testing, correlation analysis  
✅ **Time-Series Analysis:** Seasonal decomposition, trend analysis  
✅ **Machine Learning:** Regression modeling, R² evaluation  
✅ **Data Visualization:** Multi-dimensional charts, distribution plots  
✅ **Business Acumen:** Marketing metrics, ROI analysis, strategic insights  
✅ **Technical Skills:** Python, Pandas, Jupyter, version control  

---

## 🔄 Workflow

1. **Data Loading & Exploration** → Understand the dataset structure
2. **Data Cleaning** → Handle missing values, data type conversions
3. **Descriptive Statistics** → Get baseline metrics for both platforms
4. **Statistical Testing** → Determine if differences are significant
5. **Time-Series Analysis** → Identify trends and seasonal patterns
6. **Visualization** → Create compelling visual comparisons
7. **Regression Modeling** → Predict and evaluate relationships
8. **Conclusions** → Actionable recommendations for clients

---

## 📝 How to Use This Project

### For Learning:
- Read through the notebook cells sequentially
- Understand the statistical tests applied
- Study the visualization techniques used
- Adapt the methodology for your own datasets

### For Portfolio:
- Showcase your analytical thinking
- Demonstrate statistical knowledge
- Show data visualization skills
- Highlight business problem-solving approach

### For Your Business:
- Apply similar analysis to your own campaigns
- Customize metrics and time periods
- Generate client reports automatically
- Build a competitive advantage in campaign optimization

---

## 📚 References & Concepts

- **Hypothesis Testing:** Comparing means between two independent groups
- **Cointegration:** Long-run equilibrium relationship in time-series
- **Seasonal Decomposition:** Breaking down trends, seasonality, and residuals
- **Cost-Per-Click (CPC):** Industry-standard efficiency metric
- **Conversion Rate:** Key performance indicator for marketing success

---

## 🤝 Contributing

Found insights or improvements? Feel free to:
- Fork the repository
- Create a feature branch
- Submit a pull request
- Open an issue for discussions

---

## 📧 Contact & Feedback

- **GitHub Issues:** Report bugs or suggest improvements
- **Questions?** Feel free to reach out



---

## 🎓 Next Steps

- Export findings to PDF report format
- Build an interactive dashboard (Plotly/Dash)
- Create a Power BI visualization
- Develop an automated pipeline for real-time analysis
- Present findings to stakeholders

---

**Happy analyzing! 📊**
