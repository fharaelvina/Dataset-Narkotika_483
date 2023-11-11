# Dokumentasi Dataset Putusan Mahkamah Agung Indonesia

## Deskripsi Dataset

Dataset ini berisi informasi putusan Mahkamah Agung Indonesia di Pengadilan Negeri Semarang terkait dengan kasus narkotika. Setiap baris dalam dataset mewakili satu putusan hukum dan mencakup informasi seperti nomor putusan, lembaga peradilan, catatan amar, dan barang bukti (jika ada).

## Struktur Dataset

Dataset ini terdiri dari dua bagian utama:

1. **Dataset**: Folder berisi file ZIP (`Narkotika.zip`) yang berisi file PDF putusan terkait kasus narkotika.

2. **Overview**: Folder berisi file Excel (`Overview.xlsx`) yang berfungsi sebagai overview dataset dan mencakup kolom-kolom seperti:

    - **nomor**: Nomor putusan hukum.
    - **lembaga_peradilan**: Nama lembaga peradilan yang mengeluarkan putusan.
    - **catatan_amar**: Isi dari catatan amar yang mencakup detail putusan hukum.
    - **barang_bukti**: Informasi mengenai barang bukti yang terkait dengan putusan hukum.

## Cara Penggunaan

1. **Download Dataset**: Anda dapat mengunduh dataset ini dengan mengklik tautan berikut:
   - [Narkotika.zip](Dataset/Narkotika.zip)
   - [Overview.xlsx](Overview/Overview.xlsx)

2. **Ekstraksi File ZIP**: Ekstrak file ZIP `Narkotika.zip` untuk mengakses file PDF putusan.

3. **Pengolahan Data**: Gunakan Python dan Pandas untuk memproses dan menganalisis data sesuai kebutuhan Anda.

4. **Ekstraksi Informasi**: Jika perlu, Anda dapat menggunakan regex atau metode lainnya untuk mengekstrak informasi spesifik dari kolom-kolom tertentu pada file Excel.

5. **Analisis Data**: Lakukan analisis data untuk mendapatkan wawasan yang berguna atau membuat visualisasi data yang informatif.

## Contoh Penggunaan Kode

Berikut adalah contoh penggunaan kode untuk mengakses dan memproses dataset ini:

```python
import pandas as pd

# Baca dataset overview
overview_dataset = pd.read_excel("Overview/Overview.xlsx")

# Baca file PDF putusan dari folder Narkotika
# ...

# Lakukan analisis atau visualisasi data
# ...

# Ekstraksi informasi tertentu dari file Excel
# ...
