# 🏭 Manufacturing AI Use Case Dashboard

A comprehensive Streamlit dashboard for analyzing and prioritizing AI use cases in the manufacturing industry.

## 🚀 Features

### 📊 **Interactive Analytics**
- **29 Manufacturing AI Use Cases** with complete data
- **Priority Scoring System** based on business impact, ROI, timeline, and risk
- **Interactive Visualizations** using Plotly
- **Real-time Filtering** by sector, priority level, and risk

### 🎯 **Use Case Categories**
- **Production & Scheduling**: Production planning, workforce allocation, OEE analysis
- **Quality Management**: Defect management, quality assurance, automated inspection
- **Maintenance**: Predictive maintenance, tool life estimation, spare parts optimization
- **Digital Transformation**: Digital command tower, knowledge management, SOP creation
- **Sustainability**: Energy management, carbon footprint reduction
- **Analytics**: Warranty analytics, production timeline prediction, demand optimization

### 📈 **Key Metrics**
- Business Impact (1-5 scale)
- Implementation Complexity (1-5 scale)
- Estimated ROI (%)
- Implementation Timeline (months)
- Risk Level (Low/Medium/High)
- Priority Score (calculated)

## 🛠️ Installation

1. **Clone the repository:**
```bash
git clone https://github.com/YOUR_USERNAME/manufacturing-ai-dashboard.git
cd manufacturing-ai-dashboard
```

2. **Install dependencies:**
```bash
pip install -r requirements.txt
```

3. **Run the dashboard:**
```bash
streamlit run manufacturing_dashboard.py
```

## 📋 Requirements

- Python 3.8+
- Streamlit 1.25+
- Pandas 1.5+
- Plotly 5.15+
- Other dependencies listed in `requirements.txt`

## 🎨 Dashboard Components

### **Main Dashboard**
- Key performance metrics
- Priority distribution charts
- ROI vs Implementation timeline analysis
- Sector breakdown visualization

### **Detailed Analysis**
- Expandable use case details
- Individual metrics and scores
- Strategic recommendations
- Implementation guidance

### **Strategic Insights**
- Quick Wins identification
- High Impact Projects
- Focus Areas for optimization
- Risk assessment

## 🏗️ Data Structure

The dashboard includes comprehensive data for each use case:
- **Use Case Name**: Specific AI application
- **Sector**: Common, Automotive, Industrial, Manufacturing
- **Value Chain**: Manufacturing focus
- **Persona**: Target user roles
- **Description**: Detailed use case description
- **Metrics**: Impact, complexity, ROI, timeline, risk

## 🚀 Deployment

### **Local Development**
```bash
streamlit run manufacturing_dashboard.py
```

### **Streamlit Cloud**
1. Connect your GitHub repository
2. Set main file path to: `manufacturing_dashboard.py`
3. Deploy automatically

### **Other Platforms**
- Heroku
- AWS
- Google Cloud Platform
- Docker containers

## 📊 Priority Scoring Algorithm

Priority Score = (Business Impact × 0.4) + (ROI Factor × 0.3) + (Timeline Factor × 0.2) + (Risk Factor × 0.1)

- **Business Impact**: 40% weight
- **ROI**: 30% weight (normalized to 5-point scale)
- **Timeline**: 20% weight (faster = higher score)
- **Risk**: 10% weight (lower risk = higher score)

## 🎯 Use Cases Included

1. **Raw Material Management** - Inventory optimization and reporting
2. **Press Shop Tool Maintenance** - Predictive maintenance scheduling
3. **Production Scheduling** - Workforce and resource optimization
4. **Maintenance Functions** - Spare parts and lifecycle management
5. **Quality Management** - Defect prediction and automated inspection
6. **Digital Command Tower** - Real-time decision making
7. **Predictive Maintenance** - Asset performance monitoring
8. **Knowledge Management** - SOP creation and knowledge preservation
9. **Energy Management** - Sustainability and cost optimization
10. **Production Analytics** - Timeline prediction and sequence optimization

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 📞 Support

For questions or support, please open an issue in the GitHub repository.

---

**Built with ❤️ using Streamlit, Pandas, and Plotly**
