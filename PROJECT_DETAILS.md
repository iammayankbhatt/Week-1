# Project Details & Technical Documentation

## 📋 Problem Statement

### The Global Waste Crisis
- **2.01 billion tonnes** of municipal solid waste generated annually
- **Only 16%** of plastic waste is properly recycled
- **30-40%** of recyclables end up in landfills due to improper sorting

### SDG 12 Alignment
Directly addresses **SDG 12.5**: *"Reduce waste generation through recycling and reuse"*

## 📊 Dataset Information

### Source & Description
- **Dataset:** [Waste Classification Data](https://www.kaggle.com/datasets/techsash/waste-classification-data)
- **Total Images:** 22,500+ across 15 categories
- **Classes:** Organic and Recyclable materials

## 🏗️ Technical Architecture

### Model Selection: EfficientNetB0
- State-of-the-art accuracy with computational efficiency
- Pre-trained on ImageNet for effective transfer learning
- Mobile-friendly architecture

### Training Strategy
1. **Phase 1 - Feature Extraction:** Frozen base model, train classification head
2. **Phase 2 - Fine-tuning:** Unfreeze last layers with lower learning rate

## 🎯 Performance Metrics

### Target Metrics
- **Accuracy:** >90% on validation set
- **Inference Time:** <100ms on CPU
- **Model Size:** <50MB optimized version

## 🌱 Sustainability Impact

### Environmental Benefits
- **Increased Recycling Rates:** 15-25% improvement
- **Reduced Landfill Waste:** Proper classification reduces contamination
- **Carbon Emission Reduction:** Recycling produces less CO2

### Social Impact
- **Public Awareness:** Educational tool for waste segregation
- **Accessibility:** Mobile app makes classification accessible to all

---

*Technical Documentation | AICTE Edunet Foundation Internship*