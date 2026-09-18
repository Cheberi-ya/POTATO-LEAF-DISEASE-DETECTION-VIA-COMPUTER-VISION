# **POTATO-LEAF-DISEASE-DETECTION-VIA-COMPUTER-VISION**
Deep Learning Application of 2 MobileNet variants for Potato Leaf Disease Detection
## **Overview**

Potato (Solanum tuberosum) is Kenya's second most important food crop, consumed at 1–2 million tons annually and cultivated by ~800,000 smallholder farmers across 158,000 hectares. However, current yields (8–10 tons/ha) fall significantly short of the potential 25–35 tons/ha achieved in other regions.

Two major fungal and oomycete diseases heavily suppress these yields:

- **Early Blight (Alternaria solani):** Thrives in warm, humid conditions; causes target-like concentric rings on older foliage.

- **Late Blight (Phytophthora infestans):** Thrives in cool, wet weather; causes dark, water-soaked lesions and rapid foliage rot.

This project uses computer vision to detect and classify early and late blight early, enabling targeted treatment and protecting crop yield.

### **Problem Statement**
Early disease detection in Kenya is severely hindered by two factors:

- **Critical Staff Shortages:** Kenya’s extension officer-to-farmer ratio stands at 1:1,000, drastically below the UN FAO recommendation of 1:400.

- **Misdiagnosis & Soil Degradation:** Farmers frequently confuse Early and Late Blight, leading to inappropriate, blanket spraying of fungicides that harms soil fertility and long-term land productivity.

By training edge-compatible computer vision models, this project enables offline, real-time disease diagnosis directly in farmers' hands.

### **Project Objectives**

- **Model Training:** Design and fine-tune lightweight Convolutional Neural Network (CNN) variants (MobileNetV2 and MobileNetV3 large) using transfer learning.

- **Evaluation & Benchmarking:** Benchmark model performance using Accuracy, Precision, Recall, F1-Score, and Confusion Matrices.

- **Edge Optimization:** Optimize the best-performing architecture for lightweight, offline deployment in resource-constrained rural agricultural settings.