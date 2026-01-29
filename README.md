# React Internship Technical Test (Advanced Level)

## 📌 Overview

Tes ini dirancang untuk menguji kemampuan **advanced-level React** bagi calon **anak magang**. Fokus utama adalah:

* Arsitektur frontend yang rapi (best practice)
* Penggunaan **Vite + React + TypeScript**
* Konsumsi **Open Source Public API**
* State management, performa, dan maintainability

Peserta diharapkan mampu menulis kode yang **production-ready**, bukan sekadar "berjalan".

---

## 🛠️ Tech Stack (WAJIB)

Gunakan stack berikut:

* **Vite**
* **React 18**
* **TypeScript**
* **React Router**
* **Fetc & SWR**
* **State Management** (Context API atau alternatif lain yang relevan)
* **CSS Modules / Tailwind / Styled Components** (pilih salah satu)

> ❌ Tidak diperbolehkan menggunakan Next.js

---

## 🌐 API yang Digunakan

Gunakan **Open Source Public API** berikut:

### Option 1 (Direkomendasikan)

**DummyJSON**

* [https://dummyjson.com/](https://dummyjson.com/)
* Endpoint utama:

  * `/products`
  * `/products/search?q=`
  * `/products/{id}`

### Option 2

**JSONPlaceholder**

* [https://jsonplaceholder.typicode.com/](https://jsonplaceholder.typicode.com/)

Peserta bebas memilih salah satu, namun **DummyJSON lebih disarankan** karena kompleksitas data.

---

## 🎯 Studi Kasus

### Aplikasi: **Product Management Dashboard**

Buat sebuah aplikasi dashboard frontend dengan fitur berikut:

---

## 🧩 Functional Requirements

### 1️⃣ Product List Page

* Menampilkan daftar produk dari API
* Pagination (client-side atau server-side)
* Search produk berdasarkan keyword
* Loading & error state yang jelas

### 2️⃣ Product Detail Page

* Navigasi ke halaman detail produk
* Data diambil berdasarkan `id`
* Menampilkan informasi detail secara lengkap
* Handle error jika data tidak ditemukan

### 3️⃣ Global State

* Simpan data berikut di global state:

  * Keyword pencarian
  * Data user preference (contoh: grid/list view)
* Jelaskan **alasan pemilihan state management**

### 4️⃣ Performance & UX

* Debounce pada search input
* Optimasi re-render komponen
* Pisahkan komponen presentational & container

---

## 🧱 Struktur Project (WAJIB)

Gunakan struktur **best practice** berikut (boleh dikembangkan):

```
src/
│── api/
│   └── product.api.ts
│── components/
│   ├── common/
│   └── product/
│── hooks/
│── pages/
│   ├── ProductList.tsx
│   └── ProductDetail.tsx
│── store/ (atau context/)
│── types/
│── utils/
│── App.tsx
│── main.tsx
```

---

## 🧪 Bonus Point (Opsional tapi Bernilai Tinggi)

* Unit test (Vitest / Jest)
* Custom hook (`useProducts`, `useDebounce`)
* Error Boundary
* Responsive layout
* Clean commit history

---

## 📝 Aturan Pengerjaan

* Gunakan **TypeScript dengan strict typing**
* Tidak boleh menggunakan `any`
* Kode harus mudah dibaca dan scalable
* Sertakan komentar **hanya jika perlu**

---

## 📦 Submission

Peserta wajib mengumpulkan:

1. Repository Git (GitHub / GitLab)
2. File `README.md` berisi:

   * Cara menjalankan project
   * Penjelasan arsitektur
   * Keputusan teknis yang diambil
3. Screenshot aplikasi

---

## ⏱️ Estimasi Waktu

* **2 – 3 Hari pengerjaan**

---

## 🧠 Penilaian

| Aspek                 | Bobot |
| --------------------- | ----- |
| Struktur & Arsitektur | ⭐⭐⭐⭐  |
| TypeScript Usage      | ⭐⭐⭐⭐  |
| Code Quality          | ⭐⭐⭐⭐⭐ |
| UX & Performance      | ⭐⭐⭐⭐  |
| Best Practice         | ⭐⭐⭐⭐⭐ |

---

## 🚀 Catatan Akhir

Kami **tidak mencari hasil sempurna**, tetapi:

* Cara berpikir
* Struktur kode
* Keputusan teknis

Selamat mengerjakan, dan tunjukkan kualitas terbaik Anda 🚀
