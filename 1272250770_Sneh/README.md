# Computer Vision & Cloud Service Analysis

**FYMCA - D**  
**Name:** Patel Sneh  
**PRN:** 1272250770

---

## Overview

This repository contains two comprehensive data analysis projects focusing on AI/Computer Vision and Cloud Service Outages. Both projects utilize Kaggle datasets and perform extensive exploratory data analysis (EDA) with visualizations.

## Projects

### 1. AI & Computer Vision Dataset Analysis

**Notebook:** `AI&ComputerVision.ipynb`

#### Dataset
- Source: [AI and Computer Vision Dataset](https://www.kaggle.com/datasets/khushikyad001/ai-and-computer-vision-dataset)
- Downloaded via: `kagglehub`

#### Analysis Includes
- Distribution of computer vision subdomains by category
- Anomaly detection analysis (severity by type)
- Image quality metrics analysis:
  - Blur Level vs Confidence Score
  - Brightness Level vs Confidence Score
  - Noise Level vs Confidence Score
- Correlation heatmap of numerical features
- Equation complexity analysis (string length distribution)
- Bounding box analysis:
  - Aspect ratio distribution
  - Area vs confidence score relationship
- Label distribution analysis
- Quality metrics distribution by category (violin plots)

#### Key Features
- Confidence score distribution analysis
- Bounding box geometry analysis (width, height, area, aspect ratio)
- Image quality assessment across multiple dimensions
- Category-wise quality metric comparisons

---

### 2. Cloud Service Outage Dataset Analysis

**Notebook:** `CloudServiceOutageDataset.ipynb`

#### Dataset
- Source: [Cloud Service Outage Dataset](https://www.kaggle.com/datasets/mirzayasirabdullah07/cloud-service-outage-dataset)
- Downloaded via: `kagglehub`

#### Analysis Includes
- Distribution analysis:
  - Cloud providers
  - Outage severity levels
  - Root cause categories
- Temporal analysis:
  - Outage duration distribution
  - Estimated revenue loss distribution
- Comparative analysis:
  - Duration by severity (box plots)
  - Revenue loss by cloud provider (box plots)
- Correlation heatmap of numerical features
- Root cause impact analysis (violin plots)

#### Key Metrics
- Duration (minutes)
- Estimated revenue loss (USD)
- Severity levels
- Cloud provider performance
- Root cause categorization

