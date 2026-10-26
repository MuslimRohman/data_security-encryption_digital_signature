# Implementasi Keamanan Data Menggunakan Digital Signature, Enkripsi, dan Secure Session

**Keamanan dan Integritas Data | Kriptografi | Python | FastAPI**

## Deskripsi Proyek

Proyek ini bertujuan untuk membangun layanan API berbasis **FastAPI** sebagai *Trusted Authority Server* yang mendukung keamanan komunikasi digital melalui penerapan **Digital Signature, enkripsi AES-256, dan autentikasi JWT**.

Sistem dirancang untuk mengelola public key, memverifikasi keaslian pesan, mengenkripsi komunikasi antar pengguna, serta melakukan penandatanganan digital pada dokumen PDF.

## Tools & Teknologi

- **Python** – Pengembangan sistem keamanan data.
- **FastAPI** – Pembangunan layanan API.
- **Uvicorn** – Menjalankan server aplikasi.
- **AES-256** – Enkripsi dan dekripsi pesan.
- **Digital Signature** – Verifikasi keaslian dan integritas data.
- **JWT** – Autentikasi dan pengelolaan sesi pengguna.

## Fitur Utama

1. **Autentikasi Pengguna:** Login menggunakan token JWT.
2. **Public Key Management:** Penyimpanan dan pengelolaan public key pengguna.
3. **Digital Signature Verification:** Verifikasi keaslian pesan menggunakan tanda tangan digital.
4. **Secure Message Relay:** Pengiriman pesan terenkripsi menggunakan AES-256.
5. **Message Decryption:** Dekripsi pesan untuk demonstrasi proses enkripsi.
6. **PDF Digital Signature:** Penandatanganan hash dokumen PDF menggunakan private key server.

## Hasil Implementasi

- Layanan API berhasil dijalankan sebagai Trusted Authority Server.
- Sistem dapat menyimpan public key dan memverifikasi digital signature.
- Enkripsi AES-256 berhasil diterapkan pada proses pengiriman dan dekripsi pesan.
- Autentikasi JWT digunakan untuk membatasi akses endpoint tertentu.
- Sistem berhasil menghasilkan hash dan tanda tangan digital dokumen PDF.

## Struktur Repository

- `File Output/` — Berkas keluaran dari implementasi sistem kriptografi.
- `Laporan/` — Dokumentasi dan materi presentasi proyek.
  - `Project Akhir KID_Kelompok 1.pdf` — Laporan akhir proyek.
  - `PPT_Project Akhir KID_Kelompok 1.pdf` — Materi presentasi.
- `Source Code/` — Folder kode program.
  - `api.py` — Implementasi layanan API, autentikasi, enkripsi, dan verifikasi tanda tangan digital.
  - `client.py` — Pembuatan pasangan kunci dan penandatanganan pesan di sisi klien.
  - `main.py` — Menjalankan server FastAPI menggunakan Uvicorn.
- `README.md` — Dokumentasi repository.

## Anggota Tim

- **Nagatan Alief Putra Silahen**
- **Muslim Fazlur Rohman**
- **Muhammad Ramadhan Albaary Putra**
- **Kafka Praya Firmansyah**

**Program Studi Sains Data | Universitas Negeri Surabaya | 2025**
