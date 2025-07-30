# call-center-dashboard
# Call Center Performance Dashboard

## Overview
This Power BI dashboard analyzes call center performance metrics including:
- Total calls and answer rates
- Agent performance comparisons
- Customer satisfaction trends
- Call topic analysis

## Files
- `call-center-dashboard.pbix` - Main Power BI file
- `dashboard-export.pdf` - Static PDF version
- `data/` - Source data files (if applicable)

## Key Metrics
- Total Calls: 5,000
- Answer Rate: 81%
- Average Satisfaction: 3.40/6.81
- Average Wait Time: 67.52 seconds

## Usage
1. Download the .pbix file
2. Open in Power BI Desktop
3. Refresh data connections if needed

# Call Center Performance Dashboard

## 📊 Project Overview
This Power BI dashboard provides comprehensive analysis of call center performance metrics, agent efficiency, and customer satisfaction trends. The dashboard visualizes key operational data to identify improvement opportunities and track performance indicators.

## 📈 Key Metrics Summary
- **Total Calls:** 5,000
- **Answer Rate:** 81% (4,054 answered calls)
- **Unanswered Calls:** 946
- **Average Satisfaction Rating:** 3.40/6.81
- **Average Wait Time:** 67.52 seconds
- **Average Call Duration:** 224.92 seconds (3.75 minutes)

## 🔍 Analysis Results

### Overall Performance Summary
The call center handled **5,000 total calls** with an **81% answer rate** (4,054 answered calls), leaving 946 calls unanswered. This represents a solid but improvable performance level.

### Customer Satisfaction Analysis
**Current satisfaction rating of 3.40/6.81** indicates significant room for improvement. The satisfaction distribution shows:
- Most calls (2,398 total) received ratings of 4-5, which is positive
- However, 813 calls received lower ratings (1-3), suggesting consistent service quality issues
- The relatively low average suggests many neutral or poor experiences aren't being captured in the extremes

### Agent Performance Insights

**Workload Distribution:**
- Agents handle between 582-666 total calls, showing reasonably balanced distribution
- Jim and Martha handle the highest volumes (666 and 638 calls respectively)

**Efficiency Concerns:**
- **Average waiting times vary dramatically** from ~66 to 70+ seconds across agents
- Joe has the longest customer wait times, while Becky has the shortest
- This inconsistency suggests process or skill gaps between agents

**Resolution Performance:**
- Stewart shows the best satisfaction rating for resolved calls (~3.45)
- Martha shows concerning patterns with lower resolution satisfaction despite high call volume

### Operational Challenges

**Call Topics:** Streaming issues dominate (20.55% of calls), followed closely by technical support (20.28%), indicating potential product or service quality issues that could be addressed proactively.

**Time Management:** Average call duration of 224.92 seconds (3.75 minutes) seems reasonable, but the declining trend in total call time by agent suggests either improving efficiency or potentially rushed service.

## 🎯 Recommendations

1. **Immediate Focus:** Address the high unanswered call rate (19%) through staffing or process improvements
2. **Agent Training:** Standardize processes to reduce waiting time variations between agents
3. **Proactive Service:** Address streaming and technical issues to reduce reactive call volume
4. **Satisfaction Improvement:** Investigate why satisfaction ratings cluster in middle ranges rather than achieving higher scores

The data suggests a functional but underperforming call center that could significantly improve customer experience through targeted operational improvements.

## 🚀 Getting Started

### Prerequisites
- Power BI Desktop (latest version)
- Access to call center data sources

### Installation & Usage
1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/call-center-dashboard.git
   cd call-center-dashboard
   ```

2. **Open the dashboard:**
   - Launch Power BI Desktop
   - Open `dashboard/call-center-dashboard.pbix`
   - Refresh data connections if needed

3. **View static version:**
   - Open `dashboard/dashboard-export.pdf` for a static view

## 📊 Dashboard Features

### Overview Tab
- Total call metrics and KPIs
- Satisfaction rating distribution
- Call topic breakdown
- Monthly performance trends

### Agent Performance Tab
- Individual agent call handling statistics
- Average waiting times by agent
- Resolution rates and satisfaction scores
- Workload distribution analysis

## 🔄 Data Refresh Schedule
- **Manual Refresh:** Update data connections in Power BI Desktop
- **Automated Refresh:** Configure in Power BI Service (if published)
- **Data Sources:** Internal call center database, CRM system

## 📋 Key Performance Indicators (KPIs)

| Metric | Current Value | Target | Status |
|--------|---------------|--------|--------|
| Answer Rate | 81% | 90% | ⚠️ Below Target |
| Avg Satisfaction | 3.40/6.81 | 5.0+ | ❌ Needs Improvement |
| Avg Wait Time | 67.52s | <30s | ❌ Needs Improvement |
| Call Resolution Rate | 89.9% | 95% | ⚠️ Below Target |

## 🛠️ Technical Details
- **Tool:** Power BI Desktop
- **Data Source:** Call center database, agent performance logs
