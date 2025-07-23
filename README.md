# 📍 GarudaLacakAnak

GarudaLacakAnak adalah aplikasi pelacakan lokasi anak berbasis **Streamlit** yang memungkinkan **orang tua melihat posisi anak secara real-time** menggunakan data GPS dari browser anak (dengan persetujuan).

---

## 🚀 Fitur Utama

### 👦 Untuk Anak
- Login menggunakan nama/kode.
- Kirim lokasi GPS secara real-time.
- Data tersimpan aman dan bisa diakses orang tua.

### 👨‍👩‍👧 Untuk Orang Tua
- Lihat daftar anak yang mengirim lokasi.
- Peta interaktif (Google Maps) lokasi anak.
- Refresh manual untuk melihat posisi terbaru.

---

## 🧱 Teknologi yang Digunakan
- [Streamlit](https://streamlit.io/)
- [streamlit_javascript](https://pypi.org/project/streamlit-javascript/) — ambil lokasi via browser
- [folium](https://python-visualization.github.io/folium/) + [streamlit_folium](https://github.com/randyzwitch/streamlit-folium) — peta interaktif
- Python Standard Libraries (`json`, `os`)

---

## 📂 Struktur Folder

---

## 📦 Cara Menjalankan Lokal
1. Clone repo:
   ```bash
   git clone https://github.com/username/GarudaLacakAnak.git
   cd GarudaLacakAnak
pip install -r requirements.txt
streamlit run app.py
