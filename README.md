# 📊 HR Analytics Dashboard

A comprehensive Power BI dashboard designed to provide real-time insights into organizational workforce metrics, enabling data-driven HR decisions and strategic talent management.

## 🎯 Overview

This project analyzes employee data across multiple dimensions—demographics, departments, education, satisfaction, and performance—to identify attrition patterns, satisfaction trends, and actionable insights for HR strategy. The dashboard transforms raw HR data into strategic intelligence for better decision-making on retention, resource allocation, and workforce planning.

## 🚀 Key Features

- **📈 KPI Tracking**: Monitor total employees, attrition count, attrition rate, active employees, and average age at a glance
- **👥 Demographic Analysis**: Gender distribution, marital status breakdown, and age band segmentation
- **🏢 Department Insights**: Employees and attrition patterns by department (R&D, Sales, HR)
- **📚 Education Segmentation**: Active employees by education field and qualification level
- **😊 Satisfaction Metrics**: Job satisfaction ratings across 9+ job roles
- **⭐ Performance Tracking**: Department-level performance ratings and trends
- **💰 Compensation Analysis**: Monthly income trends across job roles
- **🔍 Interactive Filters**: Dynamic filtering and drill-down capabilities for detailed analysis

## 📊 Dashboard Metrics

| Metric | Value |
|--------|-------|
| Total Employees | 1,470 |
| Active Employees | 1,233 |
| Attrition Count | 237 |
| **Attrition Rate** | **16.1%** |
| Average Age | 37 |

## 🎨 Visualizations Included

- KPI Cards (headcount, attrition metrics)
- Pie Charts (gender, marital status, education field, department performance)
- Bar Charts (employees by department, satisfaction by role, age band distribution)
- Line Charts (monthly income trends by job role)
- Heatmaps (job satisfaction rating matrix)
- Interactive Tables (detailed satisfaction data by role)

## 🛠️ Technologies Used

- **Power BI** - Dashboard design, visualization, and interactivity
- **SQL Server** - Data source and management
- **Excel** - Data integration and preprocessing
- **DAX** - Calculations and measures

## 📋 File Structure

```
HR-Analytics-Dashboard/
├── README.md
├── HR_DASHBOARD.pbix          # Power BI file
├── Data/
│   ├── HR_Data.xlsx           # Raw employee data
│   ├── Attrition_Data.csv     # Attrition records
│   └── Performance_Data.csv   # Performance ratings
├── Screenshots/
│   ├── Dashboard_Overview.png
│   ├── Attrition_Analysis.png
│   └── Satisfaction_Metrics.png
└── Documentation/
    ├── Data_Dictionary.md
    └── Insights_Summary.md
```

## 🔑 Key Insights & Findings

### Critical Issues Identified
- ⚠️ **Healthcare Representative roles** show dangerously low job satisfaction (1-2 rating), directly correlating with department turnover
- 📉 **Sales department** exhibits elevated attrition rates requiring immediate intervention
- 📊 **16.1% attrition rate** is significantly above industry benchmark (8-10%)

### Best Practices Identified
- ✅ **Research Scientists** demonstrate exceptional satisfaction (75-86 rating) with high retention
- 🏆 **R&D department** leads in employee engagement and satisfaction metrics
- 📈 Entry-level roles (ages 25-34) show different retention patterns compared to senior staff

### Business Impact
- 💼 **Cost Reduction**: Targeted retention strategies could reduce attrition from 16.1% to 8-10%, saving significant recruitment costs
- 🎯 **Strategic Focus**: Identified high-risk roles requiring immediate HR intervention
- 📊 **Data-Driven Decision Making**: Enabled proactive vs. reactive HR management
- 🔄 **Continuous Monitoring**: Real-time dashboard enables ongoing workforce optimization

## 🚀 Getting Started

### Prerequisites
- Power BI Desktop (latest version)
- SQL Server or Excel data source
- Administrator access to connect to data sources

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/HR-Analytics-Dashboard.git
   cd HR-Analytics-Dashboard
   ```

2. **Open Power BI**
   - Launch Power BI Desktop
   - Open `HR_DASHBOARD.pbix` file

3. **Connect Data Sources**
   - Update data source connections in Power BI
   - Configure SQL Server credentials or Excel file paths
   - Refresh data to load latest information

4. **Customize (Optional)**
   - Modify filters and slicers based on your organization
   - Adjust color schemes and themes
   - Add additional departments or metrics as needed

## 📖 Usage

### Navigating the Dashboard

1. **Overview Tab**
   - View key metrics and KPIs
   - Monitor attrition trends
   - Check active employee count

2. **Department Analysis Tab**
   - Filter by specific departments
   - Analyze attrition by department
   - Compare performance ratings

3. **Employee Satisfaction Tab**
   - View satisfaction ratings by job role
   - Identify low-satisfaction areas
   - Benchmark satisfaction levels

4. **Compensation Analysis Tab**
   - Review income trends by job role
   - Identify salary disparities
   - Analyze compensation by department

### Interactive Features
- Use date slicers to filter by time period
- Click on charts to filter related visualizations
- Hover over data points for detailed information
- Export reports to PDF or Excel

## 💡 Recommendations & Actions

### Immediate Actions (0-30 days)
- [ ] Conduct exit interviews for Healthcare Representative departures
- [ ] Implement satisfaction survey in low-satisfaction roles
- [ ] Establish task force for Sales department retention

### Short-term (1-3 months)
- [ ] Implement role redesign for Healthcare Representatives
- [ ] Launch targeted compensation review
- [ ] Develop mentorship programs for entry-level employees

### Long-term (3-12 months)
- [ ] Establish career progression framework
- [ ] Implement quarterly satisfaction pulse surveys
- [ ] Create department-specific retention programs
- [ ] Develop leadership training initiatives

## 📊 Data Sources

The dashboard pulls data from:
- **Employee Master Data**: Demographic information, job roles, departments
- **Attrition Records**: Employee separations with effective dates
- **Performance Data**: Annual performance ratings and reviews
- **Satisfaction Surveys**: Employee job satisfaction scores

## 🔐 Data Privacy & Security

- Employee data is anonymized in visualizations
- Access is restricted to authorized HR personnel
- Data complies with organizational privacy policies
- Regular data audits ensure accuracy and compliance

## 📈 Future Enhancements

- [ ] Add predictive analytics for attrition risk scoring
- [ ] Implement real-time data refresh from HRIS systems
- [ ] Add career path analysis and succession planning
- [ ] Include training & development investment ROI metrics
- [ ] Create mobile-responsive dashboard version
- [ ] Add drill-through capabilities for employee details

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/YourFeature`)
3. Commit changes (`git commit -m 'Add YourFeature'`)
4. Push to branch (`git push origin feature/YourFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see LICENSE file for details.

## 👤 Author

**Your Name**
- GitHub: [@yourusername](https://github.com/yourusername)
- LinkedIn: [Your LinkedIn](https://linkedin.com/in/yourprofile)
- Email: your.email@example.com

## 📞 Support & Contact

For questions, issues, or suggestions:
- Open an [GitHub Issue](https://github.com/yourusername/HR-Analytics-Dashboard/issues)
- Contact the author directly
- Check the [Documentation](./Documentation/) folder for detailed guides

## 🙏 Acknowledgments

- Power BI Community for templates and best practices
- HR analytics best practices from industry leaders
- Data sources and organizational support

## 📚 Related Resources

- [Power BI Documentation](https://docs.microsoft.com/en-us/power-bi/)
- [HR Analytics Best Practices](https://www.shrm.org/)
- [Employee Retention Strategies](https://www.linkedin.com/learning/)

---

**Last Updated**: June 2026  
**Dashboard Version**: 1.0  
**Status**: ✅ Active & Maintained

⭐ If you find this dashboard helpful, please consider giving it a star!
