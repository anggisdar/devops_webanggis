# Proyek Web Server

## Deskripsi
Ini adalah proyek untuk mengonfigurasi NGINX dan Apache2 sebagai reverse proxy server dengan pengaturan rate limiting dan endpoint khusus.

## Kriteria Penilaian
1. **Port NGINX:** Ubah dari port 80 ke 3000.
2. **Rate Limiting:** Batasi 6 permintaan per menit (1 permintaan setiap 10 detik).
3. **Endpoint `/me`:** Kembalikan teks `dicoding_name`.
4. **Apache2:** Terapkan pengaturan yang sama dengan alias.

# A387-Jarkom-Labs

Untuk menjalankan project ini, pastikan `npm` sudah terinstall pada komputer/laptop Anda.

---

Tata cara menjalankan project:

1. Install node modules

```
npm install
```

2. Jalankan project

```
npm run start
```
