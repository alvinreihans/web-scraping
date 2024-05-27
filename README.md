# Proyek Web-Scraping untuk Pengumpulan Data Kemahasiswaan

Proyek ini bertujuan untuk mengumpulkan data terkait kemahasiswaan dari situs web [if.unila.ac.id](https://if.unila.ac.id) menggunakan teknik web-scraping. Proses pengambilan data dilakukan dengan bantuan library Beautiful Soup 4 dan Request dalam bahasa pemrograman Python.

## Deskripsi Proses

Data yang diambil merupakan artikel-artikel yang berkaitan dengan kemahasiswaan. Berikut adalah langkah-langkah utama yang dilakukan dalam proses ini:

1. **Pengumpulan Data**: Data diambil dari situs [if.unila.ac.id](https://if.unila.ac.id) dengan menggunakan teknik web-scraping.

2. **Preprocessing Data**: Data kemudian melalui proses preprocessing untuk membersihkan dari markup HTML, karakter khusus, serta menghilangkan duplikasi dan entri data yang kosong.

3. **Penyimpanan Data**: Data yang telah diproses disimpan dalam format JSON untuk kemudahan penggunaan dan analisis lebih lanjut.

## Penggunaan

Untuk menggunakan proyek ini, pastikan Anda memiliki Python dan library Beautiful Soup 4 dan Request terpasang di lingkungan pengembangan Anda. Kemudian, ikuti langkah-langkah berikut:

1. **Clone Repository**: Clone repositori ini ke dalam sistem lokal Anda.

2. **Instal Library**: Pastikan untuk menginstal library yang diperlukan dengan menjalankan perintah `pip install -r requirements.txt`.

3. **Jalankan Skrip**: Jalankan skrip `scrape_data.py` untuk memulai proses web-scraping.

4. **Analisis Data**: Data yang telah dikumpulkan akan disimpan dalam format JSON di dalam direktori proyek. Anda dapat menganalisis data tersebut sesuai kebutuhan Anda.

## Kontribusi

Kontribusi dan saran perbaikan sangat dihargai. Silakan buat _pull request_ jika Anda memiliki ide untuk meningkatkan proyek ini.

## Lisensi

Proyek ini dilisensikan di bawah Lisensi MIT. Lihat file [LICENSE](LICENSE) untuk informasi lebih lanjut.
