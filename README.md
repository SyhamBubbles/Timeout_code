# Case 1 - Multiclass Text Classification MBG
**Tim: Timeout**

## Deskripsi
Notebook ini membangun model klasifikasi teks untuk mengkategorikan tweet terkait 
program Makan Bergizi Gratis (MBG) ke dalam 8 kelas menggunakan TF-IDF dan LinearSVC.

## Struktur Notebook
1. Load Data
2. Explorasi Data (EDA)
3. Preprocessing
4. Modeling
5. Hyperparameter Tuning
6. Inferensi

## Requirements
Install semua library yang dibutuhkan:
pip install pandas matplotlib seaborn nltk scikit-learn openpyxl

## Download NLTK Data
Jalankan sekali di terminal sebelum menjalankan notebook:
python -c "import nltk; nltk.download('stopwords')"

## Dataset
Letakkan file berikut di folder yang sama dengan notebook:
- case_1_labeled_data.xlsx
- case_1_text_to_predict.xlsx
- case_1_template_sheet.xlsx

## Cara Menjalankan
1. Pastikan semua requirements sudah terinstall
2. Pastikan semua file dataset ada di folder yang sama dengan notebook
3. Buka Timeout_code.ipynb
4. Jalankan semua cell secara berurutan dari atas ke bawah
5. Hasil prediksi akan tersimpan sebagai Timeout.xlsx

## Hasil
- Model: TF-IDF (Word + Char n-gram) + LinearSVC
- Balanced Accuracy: 0.6265
- Metrik evaluasi: Balanced Accuracy