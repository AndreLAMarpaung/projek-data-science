# Cara Menjalankan Bike Share Dashboard

## Berikut adalah langkah-langkah untuk menjalankan dashboard Bike Share menggunakan Streamlit:

## 1. Membuat Environment dengan Conda
## Dashboard ini menggunakan dataset yang disimpan dalam file hour.csv. Pastikan file dataset tersebut ada dalam direktori yang sama dengan file Python dashboard.
conda create --name main-ds python=3.9
conda activate main-ds

## 2. Instalasi Dependencies
## Pastikan Anda sudah menginstal library yang diperlukan. Buka terminal dan jalankan perintah berikut:
pip install numpy pandas scipy matplotlib seaborn jupyter streamlit babel

## 3. Buat Kode
## Buat dashboard Bike Share ke dalam file Python (misalnya, dashboard.py).

## 4. Jalankan Dashboard
## Buka terminal di direktori yang berisi file Python dan dataset. Jalankan perintah berikut:
streamlit run dashboard.py

## 5. Akses Dashboard
## Setelah menjalankan perintah di atas, terminal akan memberikan URL lokal tempat dashboard dapat diakses. Buka URL tersebut di web browser Anda untuk mengakses dashboard Bike Share.