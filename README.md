# Deepfake-Detection

Deepfake Detection using AI/ML
📌 Project Overview

The rapid advancement of deepfake technology has made it increasingly difficult to distinguish between real and manipulated images. This project focuses on the development of an AI/ML-based solution for detecting deepfake content by extracting meaningful features and applying machine learning models to classify data as real or fake.
The system emphasizes feature-based detection rather than raw data storage, ensuring efficiency and ethical handling of data.

🎯 Objectives

To analyze visual patterns and symmetry differences between real and deepfake media

To extract meaningful features for effective classification

To build and evaluate machine learning models for deepfake detection

To provide a scalable and reproducible solution

🧠 Methodology

Feature Extraction

Facial landmarks

Symmetry-based features

Vision Transformer (ViT) features

Modeling Techniques

Early fusion of extracted features

Fine-tuned transformer-based representations

Machine learning classifiers for final prediction

Evaluation

Comparison of real vs fake symmetry results

Performance analysis using extracted features

📁 Project Structure

Deepfake-Detection/
│
├── early_fusion_model/        # Models and scalers for feature fusion
├── landmarks/                # Landmark-based feature extraction
├── vit_features/             # ViT extracted features
├── vit_finetuned_features/   # Fine-tuned ViT representations
├── Features/                 # Combined feature sets
│
├── symmetry_results.csv
├── final_symmetry_results/
│   ├── symmetry_real.csv
│   └── symmetry_fake.csv
│
├── README.md
└── .gitignore

📊 Results

The system successfully captures symmetry variations between real and deepfake samples.
Feature fusion improves classification robustness.
CSV-based outputs provide transparent and interpretable results.

Note: Raw datasets are intentionally excluded from the repository to ensure ethical usage and storage efficiency.

🛠️ Technologies Used

Python
NumPy, Pandas
Scikit-learn
Vision Transformers (ViT)
Google Colab
Git & GitHub

🚀 How to Run

1. Clone the repository:

git clone https://github.com/sadiya595/Deepfake-Detection.git


2. Navigate to the project directory:

cd Deepfake-Detection

Run feature extraction and model scripts in Google Colab or a local Python environment.

📌 Applications

Media authenticity verification
Social media misinformation detection
Digital forensics
Cybersecurity and content moderation

👩‍💻 Author

Sadiya Noor
BE – Computer Science Engineering
GitHub: https://github.com/sadiya595

📜 Disclaimer

This project is developed for academic and research purposes only. It does not promote misuse of AI-generated content.
