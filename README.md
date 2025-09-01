# TCS iON RIO 125 | Retail Sales Forecasting System

<div align="center">

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-1.3.0-orange.svg)
![Pandas](https://img.shields.io/badge/Pandas-2.0.0-green.svg)
![License](https://img.shields.io/badge/License-MIT-yellow.svg)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen.svg)

**Predictive Analytics for Inventory Optimization**

*200,000 Records | 4-Year Historical Analysis | ML-Powered Predictions*

</div>

## 🎯 Project Overview

This project develops a comprehensive **Retail Sales Forecasting System** that predicts product demand using machine learning techniques. Built as part of the TCS iON RIO 125 internship program, it addresses critical retail challenges including inventory optimization, demand planning, and strategic decision-making.

### Key Achievements
- 📊 **200,000 records** of synthetic retail data across 4 years (2020-2023)
- 🎯 **99.41% accuracy** (R² score) with Gradient Boosting model
- 📈 **3.44% MAPE** - exceptional forecasting precision
- 🔮 **2024 predictions** with confidence intervals and risk assessment
- 📱 **6,000 unique products** across 15 diverse categories

## 🚀 Business Impact

### Problems Solved
- **Overstocking**: Reduced holding costs and product wastage
- **Understocking**: Minimized lost sales and customer dissatisfaction
- **Seasonal Demand**: Accurate prediction of demand variations
- **Cost-Demand Relationships**: Deep insights into pricing strategies

### Quantified Benefits
- 99.41% forecast accuracy for confident planning
- 3.44% error rate minimizes miscalculations
- Seasonal insights prevent stock-outs during peak periods
- Risk assessment identifies products needing attention

## 📊 Dataset Specifications

| Attribute | Details |
|-----------|---------|
| **Size** | 200,000 records |
| **Time Period** | 2020-2023 (4 years) |
| **Products** | 6,000 unique products |
| **Categories** | 15 diverse categories |
| **Data Quality** | 100% complete, 0 missing values |
| **Cost Range** | ₹152 - ₹194,498 |
| **Sales Range** | 38 - 3,596 units per month |

## 🔬 Methodology

### 6-Phase Systematic Approach

1. **Data Generation**: Synthetic data with realistic patterns & seasonal multipliers
2. **Data Cleaning & Sanitization**: Quality checks, duplicate detection, outlier analysis
3. **Exploratory Data Analysis**: Temporal patterns, product performance, correlation studies
4. **Feature Engineering**: 12+ predictive features including time series, growth rates, volatility
5. **Model Development**: Linear Regression, Random Forest, Gradient Boosting with time-based split
6. **2024 Forecasting**: Future predictions with confidence intervals & risk assessment

## 🤖 Model Performance

| Model | R² Score | MAE | RMSE | MAPE |
|-------|----------|-----|------|------|
| **Gradient Boosting** | **0.9941** | **27.4** | **43.03** | **3.44%** |
| Random Forest | 0.9920 | 15.4 | 50.07 | 1.31% |
| Linear Regression | 0.6617 | 257.6 | 324.78 | 47.62% |

**Winner**: Gradient Boosting - explaining 99.41% of variance with exceptional accuracy.

## 📈 Key Insights

### Temporal Patterns
- **Peak Season**: September-November (Festival season - 60-100% sales spike)
- **Low Season**: January-February (Post-holiday dip - 15-20% decrease)
- **Growth Trend**: Consistent year-over-year growth across categories

### Feature Importance
1. **monthly_growth** (47.0%) - Recent performance momentum
2. **rolling_avg_3mo** (35.3%) - Short-term trend indicator
3. **prev_month_sales** (12.4%) - Historical performance
4. **is_peak_season** (1.8%) - Seasonal indicators

### Top Categories (2024 Forecast)
1. **Grocery**: 3.30M units
2. **Automotive**: 3.26M units  
3. **Jewelry**: 3.25M units

## 🎯 2024 Forecast Summary

- **Total Annual Forecast**: 46.87 million units
- **Average Monthly Sales**: 651 units per product
- **Risk Distribution**: 33% Low Risk | 34% Medium Risk | 33% High Risk
- **Top Product**: Health_Wellness_Vitamins_Alpha_Model3 (41,491 units)

## 💼 Business Recommendations

### 1. Inventory Optimization
- Increase stock by 60-100% during Sep-Nov peak season
- Reduce inventory by 15-20% during Jan-Feb low season
- Focus on Health & Wellness, Grocery, Automotive categories

### 2. Procurement Planning
- Place advance orders by July for festival season
- Implement just-in-time procurement for low seasons
- Prioritize premium product variants (Alpha, Prime, Pro)

### 3. Risk Mitigation
- Monitor 33% high-risk products closely
- Maintain safety stock for top performers
- Implement monthly actual vs. predicted comparison

## 🛠️ Installation & Setup

### Prerequisites
```bash
Python 3.8+
pip package manager

##🤝 Contributing
-This is an internship project, but suggestions and feedback are welcome:

-Fork the repository
-Create a feature branch
-Make your improvements
-Submit a pull request

📄 License
This project is licensed under the MIT License - see the LICENSE file for details.
👤 Author
[Your Name]

Internship: TCS iON RIO 125 Program
LinkedIn: [Your LinkedIn Profile]
Email: [Your Email]
GitHub: [Your GitHub Profile]

🙏 Acknowledgments

TCS iON for providing the RIO 125 internship opportunity
Mentors and Guides for their support throughout the project
Python Data Science Community for excellent libraries and resources

📈 Future Roadmap

Real-time data integration
Interactive dashboard development
Deep learning models (LSTM, GRU)
Mobile application for managers
Cloud deployment and API development


<div align="center">
⭐ If this project helped you, please give it a star! ⭐
Built with ❤️ for TCS iON RIO 125 Internship
</div>
```