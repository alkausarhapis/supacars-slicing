# Supacars Slicing 🚗

Slicing project dari desain [Supacars Car Rent Web Design](https://shaynakit.com/details/supacars-car-rent-web-design) menggunakan **Tailwind CSS**.

🔗 Live Preview: [https://alkausarhapis.github.io/supacars-slicing/](https://alkausarhapis.github.io/supacars-slicing/)

## 📁 Struktur Folder
supacars-slicing/
├── dist/ # Output hasil build
├── src/ # File sumber (input Tailwind)
├── index.html # File utama HTML
├── tailwind.config.js # Konfigurasi Tailwind
├── package.json # Dependency dan script

## ⚙️ Teknologi yang Digunakan
- HTML5
- Tailwind CSS
- Node.js (untuk build Tailwind)

## 🚀 Cara Menjalankan

1. Clone repo:
   ```bash
   git clone https://github.com/alkausarhapis/supacars-slicing.git
   cd supacars-slicing

2. Install Dependency
  ```bash
   npm install
  ```
3. Jalankan Tailwind
```bash
npx tailwindcss -i ./src/input.css -o ./dist/output.css --watch
```
4. Buka index.html di browser untuk melihat hasilnya.
