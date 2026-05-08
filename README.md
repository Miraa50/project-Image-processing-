Traffic Sign Image Processing Project
Amira — Image Dataset Collection
Hager — Preprocessing
Rawan — Image Filtering
Habiba — Edge Detection & Segmentation
 Documentation & GitHub

Dataset
Source: GTSRB (German Traffic Sign Recognition Benchmark)
Total Classes: 43
Format: PNG/PPM images organized by class folders


Project Pipeline
Data Collection — Downloaded dataset, organized into folders, removed corrupted images
Preprocessing — Resize to 64×64, Grayscale, Normalize [0–1], CLAHE Enhancement
Filtering — Gaussian Blur, Median Filter, Sharpening
Edge Detection — Sobel, Canny, Otsu Segmentation, Contour Detection

Output Files
processed_output/preprocessed/ — CLAHE enhanced images
processed_output/filtered/ — Gaussian, Median, Sharpened images
processed_output/edges/ — Canny, Sobel, Otsu images
processed_output/metadata.csv — Full dataset info
P1_distribution.png — Class distribution chart
P2_preprocessing.png — Preprocessing pipeline demo
P3_filtering.png — Filter comparison
P4_edges_segmentation.png — Edge detection results
P5_full_report.png — Full pipeline summary

Libraries Used
OpenCV, NumPy, Pandas, Matplotlib, PIL, tqdm

How to Run
Open the notebook in Google Colab
Run all cells from top to bottom
Upload the dataset ZIP when prompted
All outputs will be saved and downloaded automatically
