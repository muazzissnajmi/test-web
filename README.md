# Web Statik Sederhana

Website statik sederhana dengan HTML, CSS, dan JavaScript.

## Cara Menjalankan

Buka file `index.html` di browser, atau gunakan ekstensi **Live Server** di VS Code.

---

## 📤 Tutorial Push Website ke GitHub

### 1. Buat repository baru di GitHub
1. Login ke [github.com](https://github.com).
2. Klik tombol **+** di kanan atas → **New repository**.
3. Isi **Repository name** (contoh: `web-statik-saya`).
4. Pilih **Public** (atau Private).
5. **Jangan** centang "Add a README" (karena kita sudah punya).
6. Klik **Create repository**.

### 2. Inisialisasi Git di komputer
Buka terminal di folder project ini, lalu jalankan:

```bash
git init
git add .
git commit -m "Commit pertama: website statik sederhana"
```

### 3. Hubungkan ke repository GitHub
Ganti URL di bawah dengan URL repo kamu:

```bash
git branch -M main
git remote add origin https://github.com/USERNAME/web-statik-saya.git
```

### 4. Push ke GitHub

```bash
git push -u origin main
```

> Jika diminta login, masukkan username GitHub dan **Personal Access Token** (bukan password biasa).
> Buat token di: GitHub → Settings → Developer settings → Personal access tokens.

### 5. (Opsional) Aktifkan GitHub Pages
Agar website bisa diakses online:
1. Buka repo → **Settings** → **Pages**.
2. Bagian **Source**, pilih branch `main` dan folder `/ (root)`.
3. Klik **Save**.
4. Tunggu beberapa menit, website tersedia di:
   `https://USERNAME.github.io/web-statik-saya/`

---

## Update website berikutnya
Setelah mengubah file, jalankan:

```bash
git add .
git commit -m "Deskripsi perubahan"
git push
```

# test-web
