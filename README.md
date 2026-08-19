# data-science-2026

## Informasi Mahasiswa
* **Nama Lengkap:** MMuhammad Rizki
* **NIM:** 240401010030
* **Program Studi:** PJJ Informatika
* **Kelas:** IF401
* **Institusi:** Universitas Siber Asia (UNSIA)

Dalam Mata Kuliah Data Science ini saya mengharapkan dan bertujuan untuk memperdalam terkait pengetahuan akan analisis dan visualisasi data, infrasturtur data, dan menambah skil kehlian dalam statistik yang kuat. 

Di dalam repositori ini, terdapat kumpulan berkas notebook (.ipynb) hasil praktikum saya dari Pertemuan 1 hingga Pertemuan 13. Isi di dalamnya mencakup fondasi dasar bahasa Python, pembersihan data, visualisasi, Machine Learning tingkat lanjut (Supervised & Unsupervised Learning), Market Basket Analysis, Recommendation System, hingga Neural Network dan Natural Language Processing (NLP).

berikut link hasil seluruh Pembelajaran(1-13)
Pertemuan	Topik / Materi Pembelajaran	Tautan Notebook (Google Colab / GitHub)
| Pertemuan | Topik / Materi Pembelajaran | Tautan Notebook (Google Colab / GitHub) |
| :---: | :--- | :--- |
| **01** | Pengenalan Dasar Python, Variabel, Perulangan, & Fungsi | [Buka Notebook](./Pertemuan1_Afriansyah_Akbar_250401020013.ipynb) |
| **02** | Eksplorasi Data Awal dan Manipulasi Tabel dengan Pandas | [Buka Notebook](./Pertemuan2_Afriansyah_Akbar_250401020013.ipynb) |
| **03** | Pembersihan Data Kotor (*Data Cleaning* & *Imputation*) | [Buka Notebook](./Pertemuan3_Afriansyah_Akbar_250401020013.ipynb) |
| **04** | Analisis Data Eksploratif (EDA) & Statistik Deskriptif | [Buka Notebook](./Pertemuan4_Afriansyah_Akbar_250401020013.ipynb) |
| **05** | Visualisasi Data Kreatif & Penyusunan *Dashboard* Grafis | [Buka Notebook](./Pertemuan5_Afriansyah_Akbar_250401020013.ipynb) |
| **06** | Jaringan Persiapan Data (*Preprocessing Pipeline* Klasifikasi) | [Buka Notebook](./Pertemuan6_Afriansyah_Akbar_250401020013.ipynb) |
| **07** | Implementasi End-to-End Jalur Regresi Linear & Evaluasi Metrik | [Buka Notebook](./Pertemuan7_Afriansyah_Akbar_250401020013.ipynb) |
| **08** | Pemilihan Model & Hyperparameter Tuning (GridSearchCV/RandomizedSearchCV) | [Buka Notebook](./Pertemuan8_Afriansyah_Akbar_250401020013.ipynb) |
| **09** | Pemilihan Model & Hyperparameter Tuning (GridSearchCV/RandomizedSearchCV) | [Buka Notebook](./Pertemuan9_Afriansyah_Akbar_250401020013.ipynb) |
| **10** | Ensemble Learning (Random Forest & Gradient Boosting) | [Buka Notebook](./Pertemuan10_Afriansyah_Akbar_250401020013.ipynb) |
| **11** | Unsupervised Learning: Segmentasi Pelanggan (K-Means & Hierarchical Clustering) | [Buka Notebook](./Pertemuan11_Afriansyah_Akbar_250401020013.ipynb) |
| **12** | Market Basket Analysis (Apriori) & Content-Based Filtering | [Buka Notebook](./Pertemuan12_Afriansyah_Akbar_250401020013.ipynb) |
| **13** | Neural Network (Batas Non-Linear) & Sentiment Analysis (TF-IDF NLP) | [Buka Notebook](./Pertemuan13_Afriansyah_Akbar_250401020013.ipynb) |


Alat & Library yang Digunakan
Seluruh analisis dan pemrograman dalam repositori ini diselesaikan menggunakan ekosistem Python beserta beberapa alat (tools) dan library pendukung berikut:
Lingkungan Kerja: Google Colab, GitHub.
Pengolah Data & Tabel: Pandas, NumPy.
Pembuat Grafik Visual: Matplotlib, Seaborn.
Komputasi Statistik & Machine Learning: SciPy, scikit-learn, mlxtend.
Deep Learning & NLP: TensorFlow / Keras, NLTK / Scikit-learn Text.

Kesimpulan Selama Perjalanan Belajar (Pertemuan 1 – 13)
Melalui rangkaian praktikum Pertemuan 1 hingga 13, perjalanan pembelajaran Data Science ini membentuk pemahaman yang utuh dan sistematis (end-to-end data science lifecycle), mulai dari dasar pemrograman hingga pemodelan tingkat lanjut:
1. Fondasi Pemrograman & Pengenalan Data (Pertemuan 1–3):
   Diawali dengan penguasaan dasar-dasar Python (variabel, perulangan, fungsi), perjalanan ini berlanjut ke eksplorasi tabel data nyata (studi kasus Titanic) menggunakan Pandas, hingga praktik Data Cleaning seperti penghapusan duplikat, penyeragaman format teks, imputasi nilai kosong, dan penanganan nilai ekstrem (outlier) dengan metode IQR.
2. Eksplorasi & Persiapan Data (Pertemuan 4–6):
   Tahap ini menegaskan bahwa kualitas model berakar dari kualitas data. Melalui Analisis Data Eksploratif (EDA) dan berbagai visualisasi, pola dan hubungan antar-variabel menjadi lebih mudah dibaca. Kemampuan ini lalu disempurnakan dengan penyusunan preprocessing pipeline yang lengkap: encoding variabel kategorik, feature scaling, dan pembagian data latih-uji secara stratify agar siap diolah model tanpa bias.
3. Pemodelan Supervised Learning (Pertemuan 7, 9, & 10):
   Memahami bagaimana algoritma memprediksi luaran numerik maupun kategori. Dimulai dari Regresi Linear end-to-end untuk memprediksi gaji , dilanjutkan dengan perbandingan model klasifikasi (Logistic Regression vs Decision Tree) pada kasus deteksi kanker, hingga penerapan Ensemble Learning (Random Forest) untuk menangani data tidak seimbang (imbalanced data) pada kasus customer churn — sekaligus memahami mengapa metrik seperti Recall, F1-Score, dan ROC-AUC jauh lebih relevan dibanding Accuracy semata dalam kasus bisnis semacam ini.
4. Pola Tersembunyi & Sistem Rekomendasi (Pertemuan 11–12):
   Eksplorasi Unsupervised Learning membuka wawasan mengenai pengelompokan alami pelanggan menggunakan K-Means (divalidasi dengan Dendrogram & skor Silhouette), serta penggalian aturan hubungan antar-item (Association Rules / Market Basket Analysis dengan Apriori) yang dipadukan dengan Content-Based Filtering. Kombinasi metode ini sangat berdaya guna dalam skenario nyata seperti segmentasi pasar dan sistem rekomendasi bisnis.
5. Deep Learning & Teks/NLP (Pertemuan 13):
   Sebagai penutup, kemampuan pemodelan diperluas untuk menangani batas keputusan non-linear yang kompleks menggunakan Neural Network, serta mengolah data tak terstruktur berupa teks menjadi representasi TF-IDF untuk analisis sentimen dengan Logistic Regression.
Secara keseluruhan, rangkaian praktikum ini membawa saya dari sekadar mengetik baris kode Python hingga mampu membangun, mengevaluasi, dan menginterpretasikan model Machine Learning maupun Deep Learning secara menyeluruh. Setiap pertemuan turut melatih kebiasaan reflektif dengan mempertanyakan keterbatasan model dan mencari cara penyempurnaannya, sehingga membentuk fondasi teoritis sekaligus keterampilan praktis yang solid untuk menghadapi tantangan pengolahan data di dunia industri.

terima kasih
