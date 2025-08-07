# Leproscan
# AI-Powered Leprosy Wound Assessment Web App

## 🩺 Project Overview
Leprosy-related wounds, if left untreated, can lead to severe complications including disability and social stigma. Our AI-powered web application provides an automated solution to assess wound severity and monitor healing progression using image segmentation and classification.

Built with **Streamlit**, this lightweight tool is designed for **healthcare workers, NGOs, and telemedicine teams** operating in **low-resource or rural areas**.

---

## 💡 Problem Statement
Inconsistent and manual wound monitoring can delay treatment and cause long-term harm for leprosy patients. Healthcare providers in rural settings often lack tools for objective, quantifiable wound evaluation.

---

## 🧠 AI-Based Solution
We propose a web-based system that:
- Uses a **U-Net segmentation model** to detect and segment wound regions in uploaded images.
- Computes:
  - **Wound Area**
  - **Wound-to-Limb Ratio**
  - **Severity Classification** (Mild, Moderate, Severe)
  - **Tissue Composition** Estimation (Granulation, Necrotic, Slough)
- Generates **structured PDF reports** to assist in tracking and clinical decision-making.

---

## 🚀 Features
- 📷 Upload wound images for instant analysis
- 📊 Visual segmentation and measurements
- 🧾 Auto-generated PDF report for follow-ups
- 💻 Built with lightweight ML models for fast and offline use
- 🌐 Simple UI via Streamlit for non-technical users

---

## 🛠️ Tech Stack
- Python
- U-Net (Keras / TensorFlow or PyTorch)
- OpenCV, NumPy, Pandas
- Streamlit (for UI)
- ReportLab / FPDF (for PDF generation)

---
