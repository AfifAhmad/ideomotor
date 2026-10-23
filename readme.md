# Matriks Ideomotor Direct-Pass untuk Desain Protein De Novo

Sebuah bukti konsep (*proof-of-concept*) metode pembuatan sekuens protein *de novo* berakurasi tinggi menggunakan penyusunan matriks asam amino $8 \times 8$ berbasis intuisi spasial. Pendekatan ini memintas algoritma *denoising* interatif tradisional (seperti RFdiffusion dan ProteinMPNN) serta menghasilkan *helical bundle* yang stabil hanya dalam satu kali eksekusi (*single pass*) via ColabFold / AlphaFold2.

## 🎯 Performa Utama

* **Skor pTM:** `0.62` (Melampaui ambang batas kestabilan struktur >0.60)
* **Rata-rata pLDDT:** `88.54` (Tingkat kepercayaan per-residu sangat tinggi)
* **Beban Komputasi:** Inferensi *single-pass* (Nol *denoising timesteps*, nol iterasi *sampling*)

## 🔬 Tinjauan Metodologi

Alur kerja biologis generatif standar sangat bergantung pada pemrosesan *sampling* berulang dan penggunaan GPU yang intensif untuk membersihkan *noise* sebelum menentukan identitas sekuens.

Repositori ini menguji pendekatan **heuristik direct-pass**:

1. Pola sekuens diturunkan melalui protokol pemetaan matriks $8 \times 8$ secara fisik.
2. Sekuens dimasukkan secara langsung ke AlphaFold2/ColabFold tanpa pencarian *template* atau pengerjaan *backbone-first diffusion*.
3. Struktur yang dihasilkan mencapai pemadatan inti hidrofobik yang rapat, tekanan torsi yang minim pada engsel *loop*, serta kestabilan global dalam satu kali coba.

## 📊 Visualisasi Struktur

Model melipat menjadi *anti-parallel helical bundle* dengan jarak antar-heliks yang optimal serta wilayah engsel yang rileks:

- **Kesejajaran Helical Bundle:** Geometri paralel-antiparalel tanpa bentrokan posisi atom (*atom clashes*).
- **Konformasi Loop:** Transisi engsel yang stabil dan tidak tegang.

![1792762509970](image/readme/1792762509970.png)

---

*Dikembangkan sebagai bukti konsep open-access untuk inisialisasi sekuens yang ringkas serta efisiensi komputasi dalam biologi struktural.*
