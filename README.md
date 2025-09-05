# Hospital Booking System UI/UX, A/B Test

## 📋 Project Overview
An A/B test was conducted to evaluate a redesigned booking system.

## 🎯 Business Problem

- **Challenge**: Booking conversion rates declined 8% year-over-year
- **Impact**: $2.3M annual loss from missed appointments
- **Solution**: Test new UI with simplified forms, progress indicators.
- **Decision**: Rollout ($200K investment) vs. explore alternatives

## 📊 Dataset

- **Source**: `Dataset created for portfolio demonstration purposes`
- **Duration**: January - June 2024
- **Sample Size**: 30,247 users
- **Test Groups**: 
  - Group A (Control): Current booking system
  - Group B (Treatment): New streamlined UI

### Key Columns
- `test_group`: A/B group assignment
- `booking_completed`: Primary success metric (0/1)
- `session_duration`: User engagement metric
- `age`, `device_type`, `department`: Segmentation variables

## 📈 Key Performance Indicators

### Primary Metrics
- **Control Conversion Rate**: 62%
- **Treatment Conversion Rate**: 69.5%
- **Absolute Lift**: +7.5 percentage points
- **Relative Lift**: +12% improvement
- **Net Revenue Uplift**: $421,000 6 months
- **ROI (6-month)**: 210%

### Statistical Validation
- **Statistical Significance**: ✅ Yes (p < 0.001)
- **Confidence Level**: 95%
- **Effect Size**: Large
- **Risk Level**: Low

### Key Insights
- ✅ **Treatment performs better across ALL user segments**
- 💰 **Strong ROI with 2.9-month payback period**
- 📊 **Statistically significant with high confidence**


## 📊 Results Summary

| Metric | Control (A) | Treatment (B) | Improvement |
|--------|-------------|---------------|-------------|
| Conversion Rate | 62% | 69.5% | +7.5 |
| Sample Size | 15,124 | 15,123 | - |
| Additional Bookings | - | 1,827 | +1,827 |
| Revenue Impact | - | $420k | +$420K |

## 🎯 Business Recommendation

**✅ FULL ROLLOUT APPROVED**

- **Confidence Level**: High (95% statistical confidence)
- **Financial Impact**: $420K net 6 months gain, 210% ROI
- **Risk Assessment**: Low risk, positive across all segments
- **Implementation**: Ready for rollout

## 📁 Repository Structure

- ├── dataset/
│   ├── backup/
│   ├── cleaned/
│   └── hospital_dataset_raw.csv
- ├── notebook/
│   ├── AB Testing Report.ipynb
│   └── hospital_booking_ab_test_cleaned.pkl
- ├── outputs/
│   ├── charts/
│   ├── power bi dashboard/
│   └── report/
│       └── Hospital Booking system UI A-B Testing Report.pdf
└── README.md

## 🛠️ Tools Used
- **Python** - Full analysis using libraries (pandas, numpy, z-test, matplotlib)
- **Power BI Desktop** - Dashboard development
- **DAX** - Calculated measures and KPIs
- **Statistical Analysis** - Hypothesis testing, confidence intervals
- **Business Intelligence** - Executive reporting and visualization

## 📧 Contact

- Zahoor Ishfaq
- zahoor.ishfaaq@gmail.com
- www.linkedin.com/in/zahoor-ishfaq

---


*This project demonstrates A/B testing analysis, statistical validation, and executive-level business intelligence reporting in a healthcare technology context.*



