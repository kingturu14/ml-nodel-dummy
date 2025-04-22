# ML Model Dummy

Ini adalah model machine learning sederhana (`simple_ml_model.pkl`) yang digunakan untuk latihan upload ke GitHub.

## Deskripsi
Model ini dibuat hanya sebagai contoh untuk menyimpan dan mendokumentasikan file `.pkl` (pickle file) di repository GitHub.

## Cara Pakai
1. Download file `simple_ml_model.pkl` dari repo ini
2. Gunakan di script Python kamu seperti ini:

```python
import pickle

with open('simple_ml_model.pkl', 'rb') as file:
    model = pickle.load(file)
