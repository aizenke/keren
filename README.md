# Welcome to Nautica

Sebuah repository serverless tunnel studi kasus Indonesia

# Fitur

- [x] Otomatis split protocol VLESS dan Trojan
- [x] Reverse proxy
- [x] Cache daftar proxy
- [x] Support TCP/UDP (UDP hanya untuk resolve DNS)
- [ ] Support HU (HTTP Upgrade)
- [x] Lebih efisien (Partial) (I hate Javascript btw, jadi males buat benerin)

Kode ini masih perlu banyak perbaikan, jadi silahkan berkontribusi dan berikan PR kalian!

# Cara Deploy

1. Buat akun cloudflare
2. Buat worker
3. Copy kode dari `worker.js` ke editor cloudflare worker
4. Masukkan link daftar proxy kalian ke dalam environemnt variable `PROXY_BANK_URL`
5. (Optional) Masukkan link target reverse proxy ke environment variable `REVERSE_PROXY_TARGET`
6. Deploy

- Contoh daftar proxy [proxyList.json](https://raw.githubusercontent.com/JeelsBoobz/Nautica/refs/heads/clone/proxyList.json)
- Contoh reverse proxy [example.com](https://example.com)

# Endpoint

- `/` -> Halaman utama reverse proxy

# Footnote

- Hal aneh dan anomali lain yang saya lakukan [FoolVPN](https://t.me/foolvpn)
- Contact Person [Telegram](https://t.me/d_fordlalatina)
