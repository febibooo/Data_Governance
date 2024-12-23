# Data_Governance
README TAKEL - DATA LINEAGE
Kelompok 2
Gambaran Umum
Proyek ini menunjukkan proses lengkap pengelolaan, analisis, dan visualisasi data lineage untuk 
dataset bisnis. Proses yang dilakukan meliputi:
1.	Pemuatan Data: Memuat dataset pelanggan, layanan, penyedia, umpan balik, dan 
transaksi.
2.	Pemeriksaan Data: Memeriksa nilai kosong, jumlah nilai unik, dan ringkasan statistik.
3.	Pra-pemrosesan Data: Membersihkan dan memformat data untuk memastikan 
konsistensi.
4.	Validasi Data: Memverifikasi hubungan antar dataset.
5.	Visualisasi Data Lineage: Membuat representasi visual dari hubungan antar dataset.
6.	Analisis dan Visualisasi Tambahan: Menyajikan wawasan dari umpan balik dan 
penilaian layanan.

Berkas yang Digunakan
Script Python
Script Python ini melakukan hal-hal berikut:
1.	Pemeriksaan Data:
o	Menampilkan gambaran umum dataset (head, info, nilai kosong, jumlah nilai 
unik, dan statistik).
o	Mengidentifikasi hubungan yang hilang (misalnya, CustomerID yang hilang 
dalam transaksi).
2.	Pra-pemrosesan Data:
o	Mengonversi kolom tanggal ke format datetime.
o	Membersihkan dan menstandarkan kolom numerik (misalnya, menghapus simbol 
mata uang).
o	Menangani nilai yang hilang atau tidak valid dan menghapus duplikasi.
3.	Visualisasi Data Lineage:
o	Memvisualisasikan hubungan antar dataset menggunakan grafik terarah.
4.	Analisis Tambahan:
o	Distribusi penilaian umpan balik.
o	Rata-rata penilaian per layanan.
o	Analisis sentimen berdasarkan penilaian umpan balik.
Dataset Contoh
Dataset yang digunakan meliputi:
*	Customers: Informasi pelanggan.
*	Services: Detail layanan yang disediakan.
*	Providers: Informasi penyedia layanan.
*	Feedback: Umpan balik pelanggan terhadap layanan.
*	Transactions: Catatan transaksi layanan.
Berkas Output
1.	Diagram Data Lineage: Berkas PNG yang menunjukkan hubungan antar dataset.
2.	Visualisasi:
o	Histogram penilaian umpan balik.
o	Diagram batang rata-rata penilaian per layanan.
o	Plot distribusi sentimen.
Prasyarat
Pastikan Anda memiliki pustaka Python berikut terinstal:
*	pandas
*	matplotlib
*	graphviz
*	seaborn
Anda dapat menginstalnya menggunakan perintah:
pip install pandas matplotlib graphviz seaborn
Cara Menjalankan
1.	Tempatkan dataset di direktori yang sama dengan script.
2.	Perbarui jalur file di script jika diperlukan.
3.	Jalankan script di lingkungan Python (misalnya, Jupyter Notebook atau Google Colab).
4.	Periksa output di konsol untuk hasil pemeriksaan dan validasi data.
5.	Tinjau visualisasi yang dihasilkan di direktori kerja.
Wawasan dari Analisis
1.	Analisis Penilaian:
o	Mengidentifikasi layanan dengan penilaian tinggi dan area yang perlu 
ditingkatkan.
2.	Analisis Sentimen:
o	Memahami sentimen pelanggan berdasarkan penilaian umpan balik.
Catatan
*	Pastikan semua dataset memiliki skema yang konsisten untuk menghindari kesalahan 
selama pemrosesan.
*	Gunakan diagram data lineage untuk memahami dan melacak hubungan dengan lebih 
efektif.
Contoh Output
Diagram Data Lineage
Grafik yang menunjukkan hubungan seperti CustomerID antara Customers dan Transactions.
Wawasan Visualisasi
*	Histogram: Frekuensi penilaian umpan balik.
*	Diagram Batang: Rata-rata penilaian untuk setiap layanan.
*	Distribusi Sentimen: Jumlah umpan balik positif dan negatif.

