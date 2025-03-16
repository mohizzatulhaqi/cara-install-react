# Panduan Instalasi React 

## Apa Itu React?
React adalah library JavaScript untuk membangun user interface berbasis komponen. React pertama kali dibuat oleh **Jordan Walke**, seorang insinyur di Facebook (sekarang Meta). Pada tahun 2011, React digunakan untuk mengembangkan halaman **News Feed Facebook**. Setahun kemudian, teknologi ini diadopsi oleh Instagram. Akhirnya, pada tahun 2013, React dirilis ke publik sebagai proyek open-source.

## Mengapa Menggunakan Vite?
[Vite](https://vitejs.dev/) adalah sebuah build tool modern yang dirancang khusus untuk pengembangan JavaScript, termasuk framework seperti React.

**Keunggulan Vite dibandingkan Create React App (CRA):**
- **Lebih Cepat**: Vite lebih cepat dalam proses build dan development.
- **Hot Module Replacement (HMR) yang Efisien**: Memungkinkan perubahan kode langsung terlihat tanpa perlu me-refresh halaman.
- **Menggunakan ES Modules (ESM)**: Saat pengembangan, Vite menggunakan ESM di browser, dan saat production, ia menggunakan bundling tradisional untuk optimasi maksimal.

---

##  Instalasi React dengan Vite

### 1. Pastikan Node.js Sudah Terinstal
Sebelum memulai, pastikan **Node.js** sudah terinstal di komputer. Cek dengan perintah berikut:
```sh
node -v
```
Jika belum terinstal, download versi **LTS** dari [situs resmi Node.js](https://nodejs.org/) dan lakukan instalasi.

---

### 2. Membuat Proyek React Baru dengan Vite
Buka terminal atau command prompt, lalu jalankan perintah berikut:
```sh
npm create vite@latest my-react-app
```
Gantilah `my-react-app` dengan nama proyek yang kamu inginkan.

Saat proses ini berjalan, Vite akan meminta kamu untuk memilih template. Pilih **React** dengan mengetik:
```sh
react
```
Jika ingin menggunakan TypeScript, pilih **react-ts**.

---

### 3. Masuk ke Folder Proyek dan Install Dependencies
Setelah proyek dibuat, masuk ke direktori proyek:
```sh
cd my-react-app
```
Lalu, install dependencies yang diperlukan dengan perintah berikut:
```sh
npm install
```
Atau jika menggunakan Yarn:
```sh
yarn
```

---

### 4. Menjalankan Proyek
Sekarang, jalankan proyek React dengan perintah:
```sh
npm run dev
```
Atau jika menggunakan Yarn:
```sh
yarn dev
```

Vite akan memulai server pengembangan, dan kamu bisa melihat hasilnya di browser dengan membuka:
```
http://localhost:5173/
```
Jika port default sudah digunakan oleh aplikasi lain, Vite akan memilih port alternatif.

---

### 5. Mulai Koding! 🎉
Sekarang proyek React kamu sudah siap! 


