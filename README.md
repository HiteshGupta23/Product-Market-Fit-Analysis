# AirPure Innovations: Market Fit Analysis Dashboard

![AirPure Innovations](https://img.shields.io/badge/Project-AirPure%20Innovations-blue) ![Power BI](https://img.shields.io/badge/Tool-Power%20BI-yellow) ![Status](https://img.shields.io/badge/Status-Complete-green)

> **Transforming India's air quality crisis into a data-driven business opportunity through comprehensive market analysis and strategic insights.**

## 🌟 Project Overview

AirPure Innovations is a startup addressing India's air quality crisis, with 14 Indian cities ranking among the world's top 20 most polluted urban centers. This project delivers a comprehensive market fit analysis to guide the company's strategic decisions for air purifier product development and market entry.

## 🎯 Problem Statement

**Situation**: India faces a severe air quality crisis affecting millions of lives and creating massive healthcare costs (₹246B annually in Delhi alone).

**Task**: AirPure Innovations needs data-driven insights to answer critical business questions:
1. What pollutants should their air purifier target?
2. What essential features should be incorporated?
3. Which cities have the highest demand and market potential?
4. How can R&D align with localized pollution patterns?

**Action**: Built a comprehensive 9-page Power BI dashboard analyzing three key dimensions:
- **Severity Mapping**: Cities with persistent/worsening AQI levels
- **Health Impact Correlation**: Quantifying pollution's health burden
- **Demand Triggers**: Consumer behavior during pollution spikes

**Result**: Delivered actionable strategic roadmap identifying ₹1.2B+ market opportunity with clear launch sequence and product differentiation strategy.

## 🔍 Methodology & Analysis Framework

### **Phase 1: Data Collection & Integration**
- **AQI Data**: 291 monitored locations across India (Dec 2022 - May 2025)
- **Health Data**: Respiratory disease correlation by age groups and cities
- **Market Data**: Competitor analysis, search trends, vehicle registration data
- **Policy Data**: Government initiatives and their effectiveness

### **Phase 2: Multi-Dimensional Analysis**

#### **Severity Mapping Analysis**
```
🔴 CRITICAL: Cities showing irreversible AQI degradation
• Delhi: +26 AQI points (2022-2025) - Current: 225 AQI
• Ahmedabad: +22 AQI points - Current: 132 AQI
• Jaipur: +17 AQI points - Current: 139 AQI
```

#### **Health Impact Correlation**
```
👶 VULNERABLE GROUPS IDENTIFIED:
• Children 0-5 years: 168 hospitalizations per 100k (highest risk)
• PM2.5 levels: 6-11x WHO safety limits in target cities
• Health correlation: Every 10 μg/m³ PM2.5 = +13.86 pediatric admissions
```

#### **Demand Trigger Analysis**
```
📈 CONSUMER BEHAVIOR PATTERNS:
• Pollution emergencies → 200-300% search spikes
• Winter months (Nov-Jan): Peak demand periods
• Delhi: 100 daily searches vs 25 in other metros
```

## 📊 Key Insights & Findings

### **🎯 Priority Market Identification**

| **City** | **AQI** | **Health Cost (₹B)** | **Market Priority** | **Launch Phase** |
|----------|---------|----------------------|-------------------|-----------------|
| Delhi | 225 | 246 | 🔴 CRITICAL | Phase 1 (0-6M) |
| Ahmedabad | 132 | 28 | 🟡 HIGH | Phase 2 (6-12M) |
| Jaipur | 139 | 14 | 🟡 HIGH | Phase 2 (6-12M) |
| Kolkata | 112 | 86 | 🟢 MODERATE | Phase 3 (12-18M) |

### **🧪 Product Strategy Insights**

**Target Pollutants** (India-Specific):
- PM10: 50.6% of total pollution
- PM2.5: 29.08% of total pollution
- Regional variations: Karnataka (dust), Punjab (crop burning), Delhi (mixed sources)

**Critical Feature Gaps** (100% Competitor Gap):
- Smart AQI Sync with real-time alerts
- Predictive maintenance using IoT
- India-specific filtration for PM10/PM2.5

**Optimal Pricing Strategy**:
- Sweet spot: ₹12,000-₹18,000
- Target market: 63% gap in mid-premium segment

### **📅 Seasonal Demand Patterns**

| **Month** | **Avg AQI** | **Demand Level** | **Marketing Strategy** |
|-----------|-------------|------------------|----------------------|
| November | 158.2 | 🔴 Peak | Winter campaign launch |
| January | 151.1 | 🔴 Peak | Health-focused messaging |
| December | 148.0 | 🟡 High | Family protection angle |
| July-Sept | 60-65 | 🟢 Low | Maintenance & service |

## 🛠️ Technical Implementation

### **Dashboard Architecture**
```
📂 AirPure Dashboard Structure
├── 🏠 Executive Overview - KPI summary & market snapshot
├── 🏥 AQI × Diseases - Health correlation analysis
├── 🗺️ Regional Analysis - Geographic pollution mapping
├── 🚗 Vehicle Analysis - Transportation impact study
├── 🫁 Respiratory Impact - Age-group vulnerability analysis
├── 🏢 Competitor Analysis - Market gap identification
├── 📊 Marketing View 1 - Search trends & behavior
└── 📈 Marketing View 2 - Economic impact & pricing
```

### **Data Sources Integration**
- **Primary**: CPCB (Central Pollution Control Board)
- **Health**: WHO India Database, The Lancet Planetary Health
- **Market**: Google Trends, E-commerce platforms
- **Policy**: MOSPI, ICMR reports

## 🚀 Strategic Recommendations

### **Immediate Actions (0-6 Months)**
1. **Launch in Delhi NCR** targeting families with children 0-5 years
2. **Product Features**: Smart AQI sync + Predictive maintenance + India-specific filters
3. **Pricing**: ₹15,000 with premium positioning
4. **Marketing**: Pre-winter health awareness campaigns

### **Expansion Strategy (6-18 Months)**
1. **Phase 2 Cities**: Ahmedabad, Jaipur (high degradation markets)
2. **Product Variants**: Compact designs for Indian apartments
3. **Partnerships**: Pediatric clinics, health awareness campaigns
4. **R&D Focus**: Regional pollution-specific filter optimization

### **Long-term Vision (18+ Months)**
1. **Tier 2/3 Cities**: Based on early market performance
2. **Feature Evolution**: AI-driven pollution prediction
3. **Ecosystem**: Complete air quality management solutions

## 🎥 Demo & Resources

- **📹 [Live Dashboard]((https://app.powerbi.com/reportEmbed?reportId=021b7379-014b-4b6a-8a21-4ae7fdd74468&autoAuth=true&ctid=63086458-bcab-46d4-a771-aea85e34614c))** - Interactive Power BI Report
- **🎬 [Presentation Video](https://youtu.be/np2iS2P-n3U?si=Q7rcax4MjB4cEmet)** - Complete analysis walkthrough
- **📊 [Raw Data](./data/)** - Source datasets and calculations

## 📁 Repository Structure

```
AirPure-Market-Analysis/
│
├── 📊 dashboard/
│   ├── AirPure_Dashboard.pbix          # Main Power BI file
│   ├── dashboard_export.pdf            # Static dashboard export
│   └── visuals/                        # Individual chart exports
│
├── 📈 data/
│   ├── raw/                           # Original data sources
│   └── processed/                     # Cleaned datasets
│   
│
├── 📝 documentation/
│   ├── AirPure Innovations PRD.pdf                # Product Research Document
│   ├── AirPure Strategic Insights.pdf             # Key findings document
│   └── technical_specs.md                         # Dashboard specifications
│
├── 🎯 presentation/
│   ├── AirPure_Analysis.pptx          # Presentation slides
│   ├── video_script.md                # Presentation narrative
│   └── assets/                        # Presentation images
│
└── 📋 README.md                       # This file
```

## 🔧 How to Use This Repository

### **Prerequisites**
- Power BI Desktop (latest version)
- Python 3.8+ (for data analysis scripts)
- Basic understanding of market analysis concepts

### **Setup Instructions**
1. **Clone Repository**:
   ```bash
   git clone https://github.com/HiteshGupta23/Product-Market-Fit-Analysis.git
   cd Product-Market-Fit-Analysis
   ```

2. **Open Dashboard**:
   - Launch Power BI Desktop
   - Open `dashboard/AirPure_Dashboard.pbix`
   - Refresh data connections if needed

3. **Explore Analysis**:
   - Navigate through dashboard pages sequentially
   - Use filters for city-specific insights
   - Reference `documentation/` for detailed explanations

## 📈 Impact & Business Value

### **Quantified Outcomes**
- **Market Opportunity**: ₹1.2B+ in Delhi alone
- **Target Segment**: 2.1M families with children 0-5 years
- **Competitive Advantage**: 100% feature gap in smart capabilities
- **Health ROI**: Every ₹15K purifier can save ₹50K in medical costs

### **Strategic Clarity Achieved**
✅ **Product Roadmap**: Clear feature prioritization based on pollution patterns  
✅ **Market Entry**: Phased launch strategy with prioritized cities  
✅ **Pricing Strategy**: Data-driven pricing in optimal market segment  
✅ **Competitive Positioning**: Unique value proposition identified

## 🏆 Challenges Overcome

1. **Data Integration**: Merged diverse datasets (AQI, health, market) into cohesive analysis
2. **Regional Complexity**: Addressed India's diverse pollution patterns city-by-city
3. **Market Validation**: Connected health impacts to business opportunity
4. **Strategic Clarity**: Converted complex data into actionable business decisions

## 🔮 Future Enhancements

- **Real-time Integration**: Live AQI data feeds for dynamic insights
- **Predictive Modeling**: ML algorithms for demand forecasting
- **Mobile App**: Field data collection for sales teams
- **API Development**: Integration with CRM and inventory systems

## 🙏 Acknowledgments

This project was completed as part of the **CodeBasics Resume Project Challenge #16**.

**Special Thanks**:
- **[Dhaval Patel](https://linkedin.com/in/dhavalsays)** - Project guidance and mentorship
- **[Hemanand Vadivel](https://linkedin.com/in/hemvad)** - Technical support and feedback  
- **[CodeBasics](https://codebasics.io/)** - Platform and learning opportunity
- **[Dataful](https://dataful.com/)** - Data resources and partnership

## 📞 Contact & Feedback

**Hitesh Gupta** - *Data Analyst & Project Creator*
- **LinkedIn**: [Your LinkedIn Profile](https://linkedin.com/in/the-hitesh)
- **Email**: hitesh.hg.gupta@gmail.com
- **Portfolio**: [Your Portfolio Website](https://your-portfolio.com)

---

**"When children can't breathe freely, data analysis becomes a moral imperative."**

*This project demonstrates how data-driven insights can transform public health challenges into sustainable business opportunities, ultimately saving lives while building profitable ventures.*

---

![Footer](https://img.shields.io/badge/Made%20with-❤️%20&%20Power%20BI-red) ![CodeBasics](https://img.shields.io/badge/Challenge-CodeBasics%20%2316-orange) ![License](https://img.shields.io/badge/License-MIT-green)
