Analisis Sentimen dan Clustering Data
Twitter: Demo Mahasiswa
Proyek ini bertujuan untuk melakukan analisis mendalam terhadap percakapan di media sosial
(Twitter/X) mengenai isu "demo mahasiswa" dan "aksi mahasiswa" menggunakan pendekatan
Data Science, Natural Language Processing (NLP), dan Social Network Analysis (SNA). Proyek
ini membantu memetakan pola opini publik dan jaringan interaksi antar pengguna.
Teknologi yang Digunakan
Kategori Teknologi
Bahasa Pemrograman Python
Data Scraping tweet-harvest, snscrape
Pemrosesan Teks Pandas, Sastrawi, RegEx
Clustering & Embedding Sentence-BERT, KMeans, Apriori
Visualisasi & Jaringan NetworkX, Matplotlib, Seaborn, Gephi
Alur Kerja Proyek
1. Crawling Data: Mengambil tweet berdasarkan kata kunci "demo mahasiswa" atau "aksi
mahasiswa" dengan batasan waktu dan bahasa tertentu.
2. Preprocessing: Pembersihan teks meliputi penghapusan URL, mention, tagar, angka,
karakter khusus, serta melakukan stopword removal dan stemming menggunakan
pustaka Sastrawi.
3. Embedding & Clustering: Mengubah teks menjadi vektor menggunakan
Sentence-BERT, kemudian mengelompokkan data ke dalam tiga klaster utama
menggunakan K-Means.
4. Frequent Term Clustering (FTC): Identifikasi pola kombinasi kata yang sering muncul
bersamaan menggunakan algoritma Apriori.
5. Social Network Analysis (SNA): Membangun graf interaksi (mentions) antar pengguna
dan melakukan deteksi komunitas untuk memahami struktur jaringan sosial.
Hasil Klasterisasi Tema
Berdasarkan analisis, data dikelompokkan menjadi tiga tema utama:
● Isu Finansial & Komersialisasi Pendidikan: Fokus pada pembahasan biaya kuliah dan
ekonomi.

● Kritik Kebijakan Negara & Gerakan Politik: Fokus pada respon terhadap kebijakan
pemerintah.
● Kebebasan Berpendapat & Tindakan Represif: Fokus pada isu hak sipil dan aksi di
lapangan.
Visualisasi
Proyek ini menghasilkan visualisasi distribusi topik serta file jaringan (GEXF, CSV) yang dapat
dibuka di Gephi untuk analisis komunitas lebih lanjut.
