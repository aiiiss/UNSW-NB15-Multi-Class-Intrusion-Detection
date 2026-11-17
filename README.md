# UNSW-NB15 Multi-Class Network Intrusion Detection (NIDS)

Repository ini berisi implementasi pipeline *Machine Learning* end-to-end untuk mendeteksi dan mengklasifikasikan berbagai jenis serangan siber (multi-kelas) menggunakan dataset benchmark **UNSW-NB15**.

## 🚀 Fitur Utama & Metodologi
- **Data Preprocessing & Cleaning:** Pembersihan dataset dan penanganan nilai kosong untuk memastikan kualitas data masukan.
- **Handling Imbalanced Data:** Menggunakan teknik **SMOTE (Synthetic Minority Over-sampling Technique)** untuk mengatasi ketidakseimbangan kelas pada data serangan siber.
- **Feature Selection:** Menerapkan **XGBoost Feature Importance** untuk memilih fitur-fitur yang paling signifikan dan mereduksi dimensi data.
- **Ensemble Learning & Optimization:** Membangun model *Stacking Classifier* yang dioptimasi menggunakan **Optuna** untuk performa klasifikasi maksimal.
- **Evaluasi Komprehensif:** Menghasilkan metrik evaluasi berupa Akurasi, *Precision*, *Recall*, *F1-Score*, serta visualisasi *Confusion Matrix*.

## 📁 Struktur Repository
- `10Kelas_FINAL_perbaikan.ipynb` / `10Kelas_FINAL_v6_optimasi.ipynb`: Notebook Jupyter berisi tahapan eksperimen, training, hingga evaluasi model.
- `confusion_matrix_final.png`: Visualisasi matriks kebingungan dari performa model akhir.
- `feature_experiment.png` & `feature_importance.png`: Grafik analisis dan seleksi fitur penting.
- `hasil_evaluasi_model_10kelas.csv`: Rekapitulasi data hasil evaluasi performa model.

## 🛠️ Teknologi & Libraries
- Python
- Scikit-learn, XGBoost
- Imbalanced-learn (SMOTE)
- Optuna (Hyperparameter Tuning)
- Pandas, NumPy, Matplotlib, Seaborn
- Jupyter Notebook / Google Colab
