# Eksperimen Sekuens Protein Berbasis Ideomotor

## Gambaran Umum

Repositori ini mendokumentasikan eksperimen eksploratif yang melibatkan pembuatan sekuens nukleotida melalui proses ideomotor, translasi sekuens menjadi protein, dan prediksi struktur protein secara komputasional.

Eksperimen ini bertujuan mendokumentasikan hasil pengamatan serta menyediakan data untuk ditinjau dan dipelajari lebih lanjut.

Repositori ini tidak dimaksudkan sebagai bukti bahwa metode ideomotor merupakan metode desain protein yang valid, dapat direproduksi secara konsisten, atau memiliki keunggulan dibandingkan metode lain.

## Isi Repositori

* `sequence.dna.002.txt` — data sekuens nukleotida yang berkaitan dengan eksperimen.
* `protein.png` — visualisasi struktur protein hasil prediksi.
* `image/readme/` — gambar pendukung dokumentasi.
* `readme.md` — dokumentasi eksperimen.

## Alur Eksperimen

Secara umum, eksperimen dilakukan melalui tahapan berikut:

1. Menghasilkan sekuens nukleotida melalui proses ideomotor.
2. Menerjemahkan sekuens nukleotida menjadi sekuens asam amino, jika memenuhi persyaratan translasi.
3. Memasukkan sekuens protein ke perangkat lunak prediksi struktur protein.
4. Mencatat hasil prediksi dan metrik yang tersedia.
5. Mendokumentasikan hasil sebagai pengamatan awal untuk evaluasi lebih lanjut.

Proses pembuatan sekuens dalam eksperimen ini masih bersifat eksploratif dan belum ditetapkan sebagai metode baku.

## Hasil Pengamatan Awal

Dokumentasi eksperimen mencantumkan hasil prediksi struktur protein dengan metrik berikut.

| Metrik                                                     | Nilai yang dilaporkan |
| ---------------------------------------------------------- | --------------------: |
| Predicted TM-score (pTM)                                   |                  0,62 |
| Rata-rata predicted Local Distance Difference Test (pLDDT) |                 88,54 |

![1792762509970](image/readme/1792762509970.png)

Nilai tersebut merupakan metrik yang dilaporkan oleh sistem prediksi komputasional. Nilai-nilai ini tidak secara langsung membuktikan bahwa protein dapat melipat dengan stabil dalam kondisi nyata, memiliki aktivitas biologis, atau menjalankan fungsi tertentu.

Interpretasi hasil juga bergantung pada perangkat lunak, model, konfigurasi, dan sekuens yang digunakan.

## Keterbatasan

Eksperimen ini memiliki beberapa keterbatasan:

* Prosedur pembuatan sekuens masih bersifat eksploratif dan mungkin sulit direproduksi secara konsisten.
* Satu hasil prediksi belum cukup untuk menunjukkan hubungan umum antara proses pembuatan sekuens dan kualitas prediksi struktur.
* Metrik kepercayaan prediksi tidak dengan sendirinya membuktikan kestabilan fisik atau fungsi biologis protein.
* Belum ada klaim mengenai keunggulan metode ini dibandingkan metode desain protein yang telah tersedia.
* Kesimpulan yang lebih kuat memerlukan pengulangan eksperimen, pembanding yang sesuai, dan validasi tambahan.

## Pengembangan Selanjutnya

Beberapa langkah yang dapat dilakukan untuk memperdalam eksperimen ini meliputi:

* Mendokumentasikan sekuens nukleotida dan asam amino secara lengkap.
* Mencatat perangkat lunak prediksi, versi model, konfigurasi, dan parameter yang digunakan.
* Mengulangi eksperimen dengan prosedur yang terdokumentasi.
* Membandingkan hasil dengan sekuens kontrol dan metode pembanding yang sesuai.
* Melakukan analisis komputasional tambahan terhadap struktur yang diprediksi.
* Mempertimbangkan validasi eksperimental apabila diperlukan dan memungkinkan.

## Tujuan Repositori

Repositori ini berfungsi sebagai dokumentasi terbuka atas eksperimen komputasi biologi yang masih bersifat eksploratif.

Tujuannya adalah menyimpan data, menjelaskan alur kerja, mencatat hasil pengamatan, serta memungkinkan pihak lain meninjau dan mengevaluasi eksperimen tersebut secara kritis.

Hasil yang tersedia saat ini sebaiknya dipandang sebagai pengamatan awal untuk membentuk dan menguji hipotesis, bukan sebagai bukti bahwa suatu metode desain protein telah terbukti.


## Lisensi dan Penggunaan Data

Dokumentasi dan materi orisinal dalam repositori ini dilisensikan berdasarkan [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/), kecuali dinyatakan lain.

Penggunaan yang diizinkan mencakup penyalinan, distribusi, adaptasi, penelitian, dan pemanfaatan materi untuk pengembangan serta pelatihan model machine learning, termasuk penggunaan komersial, dengan tetap memenuhi ketentuan lisensi dan memberikan atribusi yang sesuai.

Pengguna bertanggung jawab memastikan bahwa materi pihak ketiga, perangkat lunak, dan keluaran prediksi yang disertakan dapat digunakan sesuai ketentuan masing-masing.

Pemberian lisensi ini tidak menyatakan bahwa metode eksperimen telah tervalidasi secara ilmiah atau bahwa hasil prediksi memiliki fungsi biologis tertentu.
