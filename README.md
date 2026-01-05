# Step Around Bogor - Virtual Tour Guide AR

Aplikasi **Step Around Bogor** adalah aplikasi web berbasis Augmented Reality (AR) yang dirancang untuk memudahkan pengguna dalam melakukan eksplorasi virtual area Kebun Raya Bogor melalui scanning logo destinasi.



---

## Fitur Utama

- **Pengenalan Marker Logo Destinasi**  
  Pengguna dapat melakukan scan pada logo-logo destinasi di Kebun Raya Bogor, seperti:
  - Taman Mexico
  - Taman Nepenthes
  - Griya Anggrek
  - Istana Bogor
  - Taman Akuatik

- **Objek 3D Interaktif**  
  Masing-masing marker memunculkan objek 3D yang merepresentasikan destinasi tersebut, seperti kubus berwarna dengan ikon tanaman pada marker.

- **Panel Informasi Dinamis**  
  Setelah scanning, akan muncul panel informasi berisi:
  - Judul destinasi dengan huruf jelas dan ukuran yang mudah dibaca
  - Deskripsi singkat yang informatif
  - Gambar utama destinasi
  - Dua foto tambahan terkait destinasi yang bisa discroll horizontal
  
  Panel ini tetap ditampilkan meskipun pengguna menjauh dari marker, hingga ditutup secara manual.

- **Instruksi Scan**  
  Panduan visual untuk mengarahkan kamera ke marker tersedia saat marker belum terdeteksi.

- **Status Kamera dan Scan**  
  Indikator status memberikan feedback saat marker ditemukan atau kamera siap digunakan.

---

## Cara Penggunaan

1. Buka aplikasi melalui browser yang mendukung WebAR (disarankan Chrome mobile).  
2. Izinkan akses kamera saat diminta.  
3. Arahkan kamera ke logo destinasi yang tersedia.  
4. Objek 3D dan panel informasi destinasi akan muncul.  
5. Panel informasi akan tetap tampil meskipun menjauh dari marker, hingga Anda menutupnya.  
6. Untuk scan destinasi lain, cukup arahkan kamera ke logo destinasi yang diinginkan.

---

## Teknologi yang Digunakan

- **AR.js** dan **A-Frame** sebagai teknologi WebAR berbasis marker pattern.  
- **HTML5, CSS3, dan JavaScript** untuk implementasi UI, interaktivitas, dan desain responsif.  
- Marker pattern dibuat menggunakan tool resmi AR.js untuk pemindaian logo yang akurat.

---

## Lisensi

Aplikasi ini bersifat open-source dan dapat Anda modifikasi sesuai kebutuhan.

---

Terima kasih telah menggunakan **Step Around Bogor** — mari eksplorasi Kebun Raya Bogor dengan mudah dan interaktif!
