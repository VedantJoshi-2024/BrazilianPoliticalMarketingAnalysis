# Brazilian Political Marketing Analysis

A comprehensive data analysis project examining the impact of social media on Brazilian political campaigns, with focus on sentiment analysis, voter behavior, and campaign effectiveness metrics.

## 📊 Project Overview

This project analyzes Brazilian political marketing data to understand how social media interactions, sentiment, and campaign events influence voter behavior and candidate performance. The analysis covers multiple research questions related to political campaigns, social media engagement, and public perception.

## 🎯 Research Questions

The analysis addresses seven key research questions:

1. **Twitter/Instagram Sentiment Analysis**: How did social media sentiment change before and after attack events on candidates?
2. **Candidate Sentiment Influence**: How did candidate sentiment get influenced by social media interactions throughout the campaign?
3. **Haddad Announcement Impact**: How did Twitter and Instagram sentiment change before and after the Haddad announcement?
4. **Attack Impact Assessment**: How did attacks on candidates influence public perception and voting intention?
5. **Social Media Integration**: What is the correlation between social media integration and the Brazilian Index?
6. **First Round Qualifiers**: What are the differences in social media patterns between candidates who qualified for the first round versus those who didn't?
7. **Tweet Sentiment Influence**: How do different types of tweet sentiment influence other social media interactions?

## 📁 Dataset Structure

```
datasets/
├── 06a-Dataset_Political_marketing.xlsx    # Main political marketing dataset
├── 06b-Dataset_Political_Marketing.gdt     # Stata format dataset
├── 07a-Dataset_Machines_vs_Humans.xls     # Machine vs Human analysis
├── 07b-Dataset_Machines_vs_Humans.gdt     # Stata format
└── 07c-Readme-Dataset_Machines_vs_Humans.txt  # Dataset documentation
```

## 🔧 Technical Requirements

### Python Libraries
- **pandas**: Data manipulation and analysis
- **numpy**: Numerical computations
- **matplotlib**: Data visualization
- **seaborn**: Statistical data visualization
- **scikit-learn**: Machine learning preprocessing
- **openpyxl**: Excel file handling

### Installation
```bash
pip install pandas numpy matplotlib seaborn scikit-learn openpyxl
```

## 📈 Key Features

### Data Analysis Components
- **Exploratory Data Analysis (EDA)**: Comprehensive statistical analysis of the dataset
- **Missing Value Analysis**: Identification and handling of missing data
- **Correlation Analysis**: Relationships between variables
- **Outlier Detection**: Statistical outlier identification using IQR and Z-score methods
- **Temporal Analysis**: Time-series analysis of campaign events

### Social Media Metrics
- **Twitter Sentiment**: Positive, neutral, and negative sentiment analysis
- **Instagram Engagement**: Comments, shares, and follower interactions
- **Traditional Media**: Traditional media mentions and coverage
- **Integration Score**: Composite social media integration metric

### Political Metrics
- **Voting Intention**: Direct measure of voter preference
- **Candidate Sentiment**: Public perception of candidates
- **Brazilian Index**: Composite performance indicator
- **Event Impact**: Before/after analysis of key campaign events

## 📊 Analysis Methodology

### 1. Data Preprocessing
- Dataset loading and initial exploration
- Missing value identification and treatment
- Data type optimization
- Outlier detection and analysis

### 2. Temporal Event Analysis
- Event timeline identification
- Pre/post event comparisons
- Campaign period segmentation
- Impact assessment

### 3. Social Media Integration
- Multi-platform analysis (Twitter, Instagram, Traditional Media)
- Sentiment analysis across platforms
- Engagement metric correlation
- Platform-specific performance indicators

### 4. Statistical Analysis
- Correlation matrices
- Distribution analysis
- Significance testing
- Comparative analysis

## 🔍 Key Findings

### Social Media Impact
- Twitter sentiment shows significant correlation with voting intention
- Instagram engagement patterns differ between qualified and non-qualified candidates
- Social media integration score correlates with Brazilian Index performance

### Event Impact Analysis
- Attack events show measurable impact on candidate sentiment
- Haddad announcement created significant changes in social media engagement
- Different events have varying impacts on different social media platforms

### Campaign Performance
- First round qualifiers show distinct social media patterns
- Higher positive sentiment correlates with better campaign performance
- Traditional media mentions complement social media engagement

## 🚀 Usage

### Running the Analysis
1. Clone the repository
2. Install required dependencies
3. Open the Jupyter notebook: `solution/Political_Marketing.ipynb`
4. Execute cells sequentially to reproduce the analysis

### Data Requirements
- Ensure dataset files are in the `datasets/` directory
- Verify Excel files are readable (may require openpyxl)
- Check for proper file permissions

## 📝 Output and Visualizations

The analysis generates:
- **Statistical summaries** of all key metrics
- **Correlation heatmaps** showing relationships between variables
- **Timeline visualizations** of campaign events and their impacts
- **Comparative analysis** charts for different candidate groups
- **Box plots** for outlier identification
- **Scatter plots** for relationship analysis

## 🎨 Visualization Types

- Distribution plots for numerical variables
- Box plots for outlier detection
- Correlation heatmaps
- Time series plots
- Comparative bar charts
- Scatter plots with trend lines

## 📋 Data Quality Assessment

The analysis includes comprehensive data quality checks:
- Missing value patterns
- Duplicate detection
- Constant and nearly constant variables
- High cardinality categorical variables
- Statistical outlier identification

## 🔮 Future Enhancements

Potential areas for expansion:
- Machine learning models for prediction
- Advanced sentiment analysis techniques
- Geographic analysis of campaign performance
- Cross-platform sentiment correlation
- Real-time campaign monitoring

## 📚 References

- Brazilian Electoral Data
- Social Media Analytics
- Political Campaign Analysis
- Statistical Methods in Political Science

---

*This analysis provides insights into the complex relationship between social media engagement and political campaign success in the Brazilian context.*

