# 📝 Simple Web Blog 

Sebuah aplikasi blog sederhana yang dikembangkan menggunakan Python dan Flask. Proyek ini memungkinkan pengguna untuk melihat dan mengelola postingan blog melalui antarmuka web yang ringan dan elegan.

## 🚀 Fitur Utama

- Tampilkan daftar artikel blog
- Buat dan simpan postingan baru
- Validasi form menggunakan Flask-WTF
- Template dinamis dengan Jinja2
- Struktur proyek terorganisir (modular)
- Pemisahan antara konten statis (CSS/JS/Image) dan template HTML

## 🛠️ Teknologi yang Digunakan

- Python 3.x
- Flask
- Flask-WTF
- HTML/CSS (Jinja2 templating)
- Bootstrap (jika digunakan di template)
- Git untuk version control

## 📂 Struktur Proyek

.
├── static/ # Aset statis (CSS, JS, gambar)

├── templates/ # Template HTML

├── forms.py # Definisi form menggunakan Flask-WTF

├── main.py # Entry point aplikasi Flask

├── requirements.txt # Daftar dependensi Python

└── .gitignore # File/folder yang tidak dilacak Git


## ⚙️ Instalasi

1. **Clone repositori ini:**
   ```bash
   git clone https://github.com/jie3116/blog-app.git
   cd blog-app

Aktifkan virtual environment (opsional tapi disarankan):
python -m venv venv
source venv/bin/activate  # Untuk Unix/Mac
venv\Scripts\activate     # Untuk Windows

Instal dependensi:
pip install -r requirements.txt

Jalankan aplikasi:
python main.py

Akses di browser:
http://localhost:5000
❗ Catatan
Folder static/assets/img sudah dihapus dari tracking Git melalui .gitignore untuk mencegah file gambar yang besar atau sensitif masuk ke repository.

Pastikan direktori tersebut tetap ada secara lokal agar template dapat merender gambar dengan benar.

🤝 Kontribusi
Pull request sangat diterima! Jika ingin menyumbangkan fitur atau perbaikan, silakan fork repo ini dan buat PR.

Terima kasih telah melihat proyek ini! 🌟
