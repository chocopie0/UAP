# -Job-Vacancy-Text-
Klasifikasi Teks Lowongan Pekerjaan Menggunakan LSTM (Long Short-Term Memory), BERT (Bidirectional Encoder Representations from Transformers), dan DistilBERT (Distilled Bidirectional Encoder Representations from Transformers).(https://img.shields.io/badge/Python-3.9%2B-blue?style=for-the-badge&logo=python&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange?style=for-the-badge&logo=tensorflow&logoColor=white)
![BERT](https://img.shields.io/badge/BERT-Transformer-yellow?style=for-the-badge)

<br>

<p align="center">
  <b>Klasifikasi otomatis teks lowongan pekerjaan berbasis NLP</b><br>
  LSTM (Long Short-Term Memory), BERT (Bidirectional Encoder Representations from Transformers), dan DistilBERT (Distilled Bidirectional Encoder Representations from Transformers).
</p>

</div>

---

## 📝 Deskripsi Proyek
Proyek ini bertujuan untuk melakukan **klasifikasi teks lowongan pekerjaan** LSTM (Long Short-Term Memory), BERT (Bidirectional Encoder Representations from Transformers), dan DistilBERT (Distilled Bidirectional Encoder Representations from Transformers).
Model dikembangkan dengan membandingkan **Neural Network konvensional** dan **Transfer Learning menggunakan pretrained BERT** untuk melihat performa klasifikasi teks yang lebih kompleks.

Proyek ini dibuat sebagai bagian dari **tugas / penelitian Machine Learning** dengan fokus pada pemanfaatan model bahasa modern untuk memahami konteks deskripsi pekerjaan.

---

📊 Dataset
Dataset yang digunakan berupa **teks lowongan pekerjaan** dalam bentuk spreadsheet.

🔗 **Link Dataset:**  
https://drive.google.com/file/d/1KEHcM81u5Iz6xbmZLWljiBAS_-gAMtUL/view?usp=drive_link

### Informasi Dataset:
- **Tipe Data:** Teks (judul & deskripsi lowongan)
- **Label:** Kategori / jenis pekerjaan
- **Bahasa:** Indonesia
- **Format:** Google Spreadsheet (.xlsx / .csv)

---

⚙️ Tahapan Preprocessing
Tahapan preprocessing teks yang dilakukan meliputi:

- Case folding (lowercase)
- Penghapusan tanda baca & karakter khusus
- Tokenisasi teks
- Stopword removal
- Padding & truncation (khusus BERT)
- Encoding label

🧠 Model yang Digunakan
Proyek ini menggunakan dua pendekatan utama:

| Model                         | Akurasi   | Keterangan                                                                                                      |
| ----------------------------- | --------- | --------------------------------------------------------------------------------------------------------------- |
| Neural Network                | 0.8x      | Cukup baik untuk klasifikasi teks sederhana, namun kurang optimal dalam menangkap konteks kalimat yang kompleks |
| LSTM (Long Short-Term Memory) | 0.8x      | Mampu mempelajari dependensi urutan kata, tetapi performanya terbatas pada teks dengan konteks panjang          |
| DistilBERT                    | 0.8x–0.9x | Lebih ringan dan efisien dibandingkan BERT, dengan performa yang relatif mendekati                              |
| BERT Pretrained               | **0.9x**  | Memberikan performa terbaik karena mampu memahami konteks semantik kalimat secara dua arah                      |
 |

 📈 Evaluasi Model
Evaluasi dilakukan menggunakan beberapa metrik berikut:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

| Model                         | Akurasi   | Keterangan                                                                                                      |
| ----------------------------- | --------- | --------------------------------------------------------------------------------------------------------------- |
| Neural Network                | 0.8x      | Cukup baik untuk klasifikasi teks sederhana, namun kurang optimal dalam menangkap konteks kalimat yang kompleks |
| LSTM (Long Short-Term Memory) | 0.8x      | Mampu mempelajari dependensi urutan kata, tetapi performanya terbatas pada teks dengan konteks panjang          |
| DistilBERT                    | 0.8x–0.9x | Lebih ringan dan efisien dibandingkan BERT, dengan performa yang relatif mendekati                              |
| BERT Pretrained               | **0.9x**  | Memberikan performa terbaik karena mampu memahami konteks semantik kalimat secara dua arah                      |

Kesimpulan
Berdasarkan hasil pengujian, model BERT pretrained menunjukkan performa paling optimal dibandingkan model Neural Network, LSTM, dan DistilBERT. Hal ini disebabkan oleh kemampuan BERT dalam memahami konteks semantik kalimat secara dua arah (bidirectional), sehingga lebih efektif dalam memproses deskripsi lowongan pekerjaan yang memiliki struktur bahasa kompleks.
Model DistilBERT dapat menjadi alternatif yang efisien dengan performa yang relatif mendekati BERT, terutama ketika keterbatasan sumber daya komputasi menjadi pertimbangan. Sementara itu, LSTM dan Neural Network konvensional masih memberikan hasil yang cukup baik, namun kurang optimal dalam menangani konteks kalimat yang panjang dan kompleks.
👨‍💻 Identitas Pengembang

Proyek ini dibuat sebagai syarat kelulusan praktikum.

Nama: Lika Anjelina

NIM: 👨‍💻 Identitas Pengembang

Proyek ini dibuat sebagai syarat kelulusan praktikum.

Nama: Lika Anjelina

NIM: 202210370311269

Kelas: Machine Learning C

Universitas: Universitas Muhammadiyah Malang

Kelas: Machine Learning C

Program Studi: Informatika

Universitas: Universitas Muhammadiyah Malang
