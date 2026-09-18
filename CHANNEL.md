# Channel 2.4 dan 5G
Kalau yang dimaksud **rekomendasi channel Wi-Fi untuk kelas/sekolah di Indonesia**, saya sarankan konfigurasi berikut untuk meminimalkan interferensi:

 ### 2,4 GHz

 Gunakan **20 MHz saja** dan pilih:

 - **Channel 1**
- **Channel 6**
- **Channel 11**

 Jika ada beberapa access point (AP) di sekolah, bagi AP secara bergantian **1 → 6 → 11 → 1 → 6 → 11**. Hindari channel 2–5 atau 7–10 karena saling tumpang tindih.

 ### 5 GHz

 Untuk ruangan kelas, pilihan awal yang praktis:

 - **Channel 36**
- **40**
- **44**
- **48**

 Band 5150–5350 MHz memang termasuk rentang RLAN yang diperbolehkan untuk penggunaan indoor di Indonesia.  JDIH Kemkomdigi+1

 Untuk kelas dengan **banyak siswa/perangkat**, saya lebih menyarankan:

 - **5 GHz: 20 atau 40 MHz**, bukan 80 MHz jika banyak AP berdekatan.
- **2,4 GHz: 20 MHz**.
- Jangan menaikkan transmit power terlalu tinggi; antar-AP yang berdekatan justru bisa saling mengganggu.

 **Contoh 3 kelas bersebelahan:**

 | Kelas | 2,4 GHz | 5 GHz |
| --- | --- | --- |
| Kelas A | Ch 1 | Ch 36 |
| Kelas B | Ch 6 | Ch 44 |
| Kelas C | Ch 11 | Ch 48 |

Kalau kamu memberi tahu **berapa jumlah AP, ukuran/denah kelas, dan apakah AP-nya Wi-Fi 5/6/6E**, saya bisa buatkan **channel plan seluruh sekolah** (2,4 GHz + 5 GHz) agar AP yang berdekatan tidak saling mengganggu.

## Channel 5 G Ruckus
Di Indonesia, channel Wi-Fi 5 GHz yang diperbolehkan digunakan secara bebas (tanpa lisensi khusus) untuk perangkat konsumen adalah 36, 40, 44, 48, 149, 153, 157, dan 161.

 **Contoh 3 kelas bersebelahan:**

 | Kelas | 2,4 GHz | 5 GHz |
| --- | --- | --- |
| Kelas A | Ch 1 | Ch 149 |
| Kelas B | Ch 6 | Ch 157 |
| Kelas C | Ch 11 | Ch 161 |
