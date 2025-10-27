# 🧾 Dashboard Perolehan HCTM (Versi Web Gelap)

Dashboard ini dibangunkan untuk **memantau status kontrak dan perolehan Unit Stor HCTM**, termasuk:
- Jumlah nilai kontrak (RM)
- Bilangan perolehan
- Kontrak **aktif** dan **tamat**
- Carta **trend tahunan** dan **pecahan jenis kontrak**

---

## 📁 Struktur Fail

| Fail | Kegunaan |
|------|-----------|
| `index.html` | Fail utama untuk dashboard web (paparan interaktif) |
| `data.json` | Sumber data utama dalam format JSON |
| `data.csv` | Versi data dalam format CSV (untuk semakan Excel) |
| `README.md` | Panduan penggunaan projek |

---

## 🚀 Cara Guna (GitHub Pages)

1. Buka GitHub dan buat repo baharu, contohnya:
   ```
   hctm-dashboard
   ```

2. Upload semua fail berikut:
   ```
   index.html
   data.json
   data.csv
   README.md
   ```

3. Pergi ke:
   **Settings → Pages → Source → pilih `main` branch dan folder `/root`**

4. Klik **Save**.  
   Selepas beberapa saat, pautan GitHub Pages akan muncul — contoh:
   ```
   https://username.github.io/hctm-dashboard/
   ```

---

## 🔄 Kemas Kini Data

Jika ingin kemas kini data:
1. Edit fail `data.json` (atau gantikan dengan fail baharu)  
2. Push ke GitHub — dashboard akan automatik paparkan data terkini  

---

## 🧠 Teknologi Digunakan
- **TailwindCSS** (reka bentuk moden & responsif)  
- **Chart.js** (graf interaktif)  
- **JavaScript Vanilla** (tanpa backend — terus dari JSON)

---

© HCTM | Dashboard dibangunkan secara automatik untuk kegunaan dalaman.
