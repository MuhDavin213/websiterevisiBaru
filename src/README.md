# 🛒 Toko Nusa Indah - E-Commerce Website

Website e-commerce modern berbasis React dengan TypeScript untuk menjual berbagai produk seperti peralatan sehari-hari, snack, boneka, dan mainan.

## ✨ Fitur Utama

### 🏪 Toko & Produk
- 22 produk dalam 6 kategori
- Filter kategori dinamis
- Pencarian produk real-time
- Sorting produk (nama, harga, stok)
- Badge "Stok Terbatas"
- Upload gambar produk ke localStorage
- Tombol +/- quantity yang prominent

### 🛒 Keranjang Belanja
- Sistem keranjang lengkap
- Update quantity di keranjang
- Cek ketersediaan stok dari database
- Validasi stok real-time
- Penyimpanan di localStorage

### 🔧 Halaman Kelola (Admin)
- Password protected: `nusaindah123`
- CRUD produk lengkap
- Kelola kategori dinamis
- Kelola banner promo
- Upload gambar produk (base64)

### 🎨 UI/UX
- Tema warna emerald
- Navbar modern 2 level
- Footer profesional
- Scroll to top button
- Fully responsive (mobile, tablet, desktop)
- Mobile hamburger menu

### 📱 Fitur Tambahan
- QR Code website
- Halaman Tentang Kami
- Halaman Kontak
- Banner promo dinamis

## 🚀 Teknologi

- **React** - UI framework
- **TypeScript** - Type safety
- **Tailwind CSS** - Styling
- **localStorage** - Data persistence
- **Lucide React** - Icons
- **Sonner** - Toast notifications
- **QRCode** - QR code generation

## 📂 Struktur Project

```
├── components/
│   ├── features/     # Product cards, lists, modals
│   ├── layout/       # Header, footer, navigation
│   └── ui/           # Reusable UI components
├── features/admin/   # Admin management pages
├── hooks/            # Custom React hooks
├── pages/            # Main application pages
├── data/             # Static data & image gallery
├── utils/            # Helper functions
└── types/            # TypeScript type definitions
```

## 🔑 Kredensial Admin

- **Password**: `nusaindah123`

## 📝 Cara Ganti Data

### Ganti Password Admin
File: `/features/admin/PasswordProtection.tsx`
```typescript
const ADMIN_PASSWORD = 'nusaindah123'; // Ganti password di sini
```

### Ganti QR Code URL
Otomatis menggunakan `window.location.href` (URL saat ini)

### Ganti Kontak WhatsApp
File: `/pages/Kontak.tsx`
```typescript
// Cari dan ganti nomor berikut:
href="https://wa.me/6285640690185"
```

### Tambah/Edit Produk
Gunakan halaman Kelola → Tab "Produk" → Tambah/Edit

### Tambah/Edit Kategori
Gunakan halaman Kelola → Tab "Kategori" → Tambah/Edit

## 🎯 Fitur Unggulan

### ✅ Stock Validation System
Tombol "Cek Barang" di keranjang untuk validasi stok real-time:
- Status OK: Semua barang tersedia
- Status Insufficient: Stok tidak mencukupi
- Status Out of Stock: Barang habis

### ✅ Dynamic Category Management
- Kategori disimpan di localStorage
- Auto-sync dengan filter produk
- Real-time update di seluruh aplikasi

### ✅ Image Upload System
- Upload gambar dari komputer
- Disimpan sebagai base64 di localStorage
- Galeri preset + custom images

### ✅ Responsive Design
- Mobile: Hamburger menu, touch-friendly
- Tablet: Optimized grid layout
- Desktop: Full navigation, sidebar

## 📱 Responsiveness

- **Mobile** (<640px): 2 kolom grid, mobile menu
- **Tablet** (640-1024px): 3 kolom grid
- **Desktop** (>1024px): 4 kolom grid, full features

## 🎨 Theme Colors

- **Primary**: Emerald (600, 700)
- **Success**: Green (600)
- **Warning**: Orange (500, 600)
- **Error**: Red (500, 600)
- **Neutral**: Gray (50-900)

## 🔧 Development

Website ini siap pakai tanpa setup tambahan. Semua fitur sudah terintegrasi dan berfungsi.

## ✅ Status

Website **production-ready** dengan semua fitur lengkap dan telah dioptimasi.

---

**Toko Nusa Indah** © 2024 - E-Commerce Modern untuk Indonesia
