# Data Directory

## Source
- **Dataset**: USDA Food Safety and Inspection Service (FSIS)
- **Title**: Livestock Humane Handling Inspection Task (Archive)
- **Year**: 2024 (Archive)
- **Agency**: U.S. Department of Agriculture

## Note
The original Excel file (`0postLHH_arch24.xlsx`) is not included in this repository due to size constraints. 
The analysis results and processed data summaries are available in the notebooks.

## Data Description
- **Records**: ~193,632 inspection tasks
- **Time Period**: October 1, 2023 - September 30, 2024
- **Scope**: Livestock humane handling inspections across 900+ establishments


# 🔍 USDA Livestock Inspection Analysis: Establishment Performance Intelligence

> **Analyzing 193,632 inspection records to uncover compliance patterns and rank establishment performance**

![Python](https://img.shields.io/badge/python-3.8+-blue.svg)
![Jupyter](https://img.shields.io/badge/jupyter-notebook-orange.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![Status](https://img.shields.io/badge/status-complete-success.svg)

---

## 📊 **Project Overview**

This project analyzes comprehensive USDA inspection data to identify performance patterns, rank establishments, and detect compliance issues across America's livestock facilities. Through systematic data analysis, I transformed raw inspection records into actionable intelligence for regulatory oversight.

### **Key Achievements**
- ✅ Analyzed **193,632 inspection records** from 900+ establishments
- ✅ Developed **risk scoring algorithm** for establishment assessment  
- ✅ Created **performance ranking system** based on compliance metrics
- ✅ Identified **establishments requiring enhanced oversight**
- ✅ Built **predictive indicators** for compliance risk

---

## 🗂️ **Data Source**

**Official Dataset**: USDA Food Safety and Inspection Service (FSIS)  
**Title**: Livestock Humane Handling Inspection Task (Archive)  
**Year**: 2024 (Archive)  
**Agency**: U.S. Department of Agriculture  
**Records**: 193,632 inspection tasks  
**Time Period**: October 1, 2023 - September 30, 2024  
**Scope**: Livestock humane handling inspections across 900+ establishments  

---

## 🎯 **Analysis Objectives**

### **Primary Goals**
1. **Rank establishments** by inspection volume and compliance performance
2. **Detect patterns** in violations and compliance issues
3. **Identify high-risk facilities** requiring additional oversight
4. **Benchmark performance** across different establishment types
5. **Create actionable insights** for regulatory efficiency

### **Key Questions Answered**
- Which establishments demonstrate consistent compliance excellence?
- What patterns distinguish high-performing facilities?
- How can we predict which establishments need closer monitoring?
- Where should regulatory resources be prioritized?

---

## 🔍 **Key Findings**

### **📈 Compliance Landscape**
- **Overall violation rate**: 0.44% (exceptionally low)
- **Inspection types**: 84.4% routine, 15.6% directed
- **Perfect compliance**: 89% of establishments with 10+ inspections
- **Risk correlation**: High-volume facilities often show better compliance

### **🎯 Performance Insights**
- **Top performers**: Swift Pork Company, Tyson Fresh Meats locations
- **Compliance champions**: 89% of high-volume facilities maintain perfect records
- **Risk indicators**: Directed inspection rate strongly predicts compliance issues
- **Regulation hotspots**: Violations cluster around 313.1, 313.2, 313.15

### **⚠️ Risk Detection**
- **22 establishments** flagged for multiple violations
- **Diverse violation patterns** across different regulation types
- **Early warning indicators** identified for proactive oversight
- **Resource optimization**: Data-driven inspection scheduling potential

---

## 🛠️ **Methodology**

### **Data Processing Pipeline**
1. **Data Extraction**: Processed 193K+ records from Excel format
2. **Quality Assurance**: Cleaned and validated inspection data
3. **Feature Engineering**: Created compliance metrics and risk scores
4. **Performance Calculation**: Aggregated establishment-level statistics
5. **Risk Assessment**: Developed multi-factor risk scoring algorithm

### **Risk Scoring Formula**
```python
Risk Score = (Violation Rate × 60) + (Directed Inspection Rate × 30) + (Regulation Diversity Penalty × 10)
