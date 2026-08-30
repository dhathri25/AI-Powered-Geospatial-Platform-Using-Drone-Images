# AI-Based Automated Urban Parcel Mapping System

An interactive AI-powered geospatial platform for land-use classification, cadastral feature segmentation, and real-time encroachment risk assessment from drone orthomosaic imagery.

---

## 📌 Project Overview

The **AI-Based Automated Urban Parcel Mapping System** leverages deep learning vision models to process high-resolution aerial and drone tiles. By combining multi-class land classification with high-precision instance segmentation, the system automates spatial analysis for urban planning, boundary detection, and illegal encroachment monitoring.

---

## 💡 Key Features

* **Dual-Engine AI Pipeline**:
  * **ResNet-18 (Land Use Classification)**: Classifies orthomosaic tiles into land-use categories such as *Commercial*, *Industrial*, or *Residential*.
  * **YOLOv8-Seg (Cadastral Feature Segmentation)**: Extracts roof footprints, spatial boundaries, and detects structural encroachments (`encroachment_mask`).
* **Real-Time Interactive Dashboard**: Built with Streamlit to enable fast imagery uploads, visual side-by-side comparison, and customizable engine toggles.
* **Dynamic Confidence Tuning**: Adjustable threshold sliders (0.10 to 1.00) to fine-tune object segmentation sensitivity live.
* **Automated Encroachment Analytics**:
  * **Feature Extraction**: Outputs precise bounding box coordinates and detection confidence scores.
  * **Encroachment Index Calculation**: Computes the percentage of detected encroachment area.
  * **Automated Risk Assessment**: Dynamically tags spatial zones with severity levels (*LOW*, *MEDIUM*, *HIGH*).

---

## 🛠️ Tech Stack & Architecture

* **Frontend / Dashboard**: Streamlit
* **Computer Vision & Deep Learning**: PyTorch, YOLOv8 (Ultralytics), ResNet-18
* **Image Processing**: OpenCV, PIL, NumPy
* **Deployment / Tunneling**: Google Colab, Localtunnel / Pyngrok

---

## 🚀 Getting Started

### Prerequisites

Ensure you have Python 3.8+ installed along with PyTorch and CUDA support (optional for GPU acceleration).

### Installation

1. **Clone the repository**:
   ```bash
   git clone [https://github.com/your-username/urban-parcel-mapping.git](https://github.com/your-username/urban-parcel-mapping.git)
   cd urban-parcel-mapping



   <img width="800" height="445" alt="ScreenRecording2026-08-30175725-ezgif com-video-to-gif-converter" src="https://github.com/user-attachments/assets/b5715277-cbf5-417e-baca-0cd7b211d5f3" />

