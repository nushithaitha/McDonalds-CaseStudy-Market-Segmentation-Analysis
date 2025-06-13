# 🍔 McDonald's Market Segmentation Analysis 📊

A comprehensive Python implementation of customer segmentation analysis for McDonald's using machine learning techniques, converted from R to Python with enhanced visualizations and statistical analysis.

## 🎯 Project Overview
This project performs advanced market segmentation analysis on McDonald's customer data to identify distinct customer groups based on their perceptions of the brand and demographic characteristics. The analysis combines multiple statistical and machine learning techniques to provide actionable insights for marketing strategy.

## 🔧 Features

### 📈 Statistical Analysis
- **Principal Component Analysis (PCA)** - Dimensionality reduction and feature importance
- **K-means Clustering** - Customer segmentation with optimal cluster selection
- **Bootstrap Validation** - Cluster stability assessment
- **Hierarchical Clustering** - Variable relationship analysis

### 🤖 Machine Learning
- **Multi-class Classification** - Predicting customer segments using demographics
- **Binary Classification** - Individual cluster vs. others analysis
- **Feature Importance Analysis** - Identifying key demographic predictors
- **Cross-validation** - Model performance assessment

### 📊 Advanced Visualizations
- **Interactive PCA Plots** - Customer distribution in reduced dimensions
- **Dendrogram Analysis** - Variable clustering with multiple linkage methods
- **Decision Tree Visualization** - Interpretable segmentation rules
- **Heatmaps & Correlation Matrices** - Variable relationships
- **Bubble Plots** - Multi-dimensional cluster characteristics
- **Cluster Profiles** - Detailed segment analysis



## 📋 Dataset Description
- **11 Binary Variables**: Customer perceptions (yummy, convenient, spicy, fattening, greasy, fast, cheap, tasty, expensive, healthy, disgusting)
- **Demographic Variables**: Age, Gender, Visit Frequency, Like Rating
- **Sample Size**: 1000+ customer responses
- **Data Format**: CSV with Yes/No responses for perceptions

## 🚀 Quick Start

### Prerequisites
```bash
python >= 3.7
```

### Installation
```bash
git clone https://github.com/yourusername/McDonalds-CaseStudy-Market-Segmentation-Analysis
.git
cd McDonalds-CaseStudy-Market-Segmentation-Analysis
```


## 📊 Key Analysis Components

### 1. Principal Component Analysis
- Reduces 11 perception variables to key dimensions
- Identifies primary factors driving customer opinions
- Visualizes customer distribution in reduced space

### 2. K-means Clustering
- Segments customers into distinct groups (2-8 clusters tested)
- Uses elbow method and silhouette analysis for optimal k
- Validates cluster stability through bootstrap analysis

### 3. Hierarchical Clustering
- Analyzes relationships between perception variables
- Multiple distance metrics (correlation, euclidean, cosine)
- Different linkage methods (ward, complete, average)

### 4. Decision Tree Analysis
- Multi-class Classification: Predicts all 4 customer segments
- Binary Classification: Individual cluster identification
- Feature importance ranking for demographic predictors

### 5. Cluster Profiling
- Detailed characteristics of each customer segment
- Demographic composition analysis
- Behavioral pattern identification

## 📈 Key Insights
The analysis reveals **4 distinct customer segments**:

1. **Health-conscious customers** (low frequency visitors)
2. **Convenience-focused customers** (moderate visitors)
3. **Price-sensitive customers** (high frequency visitors)
4. **Brand enthusiasts** (varied visiting patterns)

## 🛠️ Technical Implementation

### Libraries Used
- **Data Analysis**: pandas, numpy
- **Machine Learning**: scikit-learn
- **Visualization**: matplotlib, seaborn
- **Statistical Analysis**: scipy
- **Clustering**: scipy.cluster, sklearn.cluster

### Analysis Pipeline
```
Data Preprocessing → Binary encoding, missing value handling
Exploratory Analysis → Correlation analysis, distribution plots
Dimensionality Reduction → PCA with component interpretation
Clustering Analysis → K-means with validation
Predictive Modeling → Decision trees for segment prediction
Results Interpretation → Business insights and recommendations
```

## 📊 Visualizations
The project generates **15+ professional visualizations** including:
- PCA scatter plots with loadings
- Cluster comparison heatmaps
- Decision tree diagrams
- Dendrogram analysis
- Feature importance charts
- Demographic distribution plots
