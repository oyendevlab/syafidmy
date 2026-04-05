# TASKS — syafidmy Portfolio

## Status Semasa

- File utama: `syafidmy.html` (deploy ke Vercel; `vercel.json` rewrite `/` → `/syafidmy.html`)
- Folder `assets/` (cth. imej hero/bento) **belum ada dalam repo** — tambah bila sedia, kemudian rujuk dalam HTML jika perlu

---

## ✅ Siap

- [x] Hero section + bento grid
- [x] About Me + orbit badges
- [x] Kemahiran & Kepakaran — Option C (3 featured cards + tag cloud + animations)
- [x] Projek section (layout kad sama seperti Sumber; SekolahHub & TransitPBD ada pautan live pada CTA utama)
- [x] Sumber & Tools — markup & CSS (card layout); **disembunyikan** (`display:none` pada `<section id="resources">`) buat masa ini
- [x] Contact section
- [x] Footer
- [x] Scroll reveal animations (IntersectionObserver)
- [x] Nav scroll effect

---

## 🔧 Pending / TODO

### Testimonials & Blog / Konten

- [ ] Dalam `syafidmy.html` hanya ada **CSS** untuk `.testimonials` dan `.blog` — **tiada markup `<section>`** untuk dua bahagian ini. Pilih salah satu: **(A)** padam CSS tidak terpakai, atau **(B)** tambah semula HTML mengikut reka bentuk sedia ada

### Sumber & Tools (§8) — hidden, aktifkan bila ready

- [ ] Aktifkan semula: buang `style="display:none"` pada `<section class="resources">`
- [ ] Aktifkan semula nav link: uncomment `<!-- <li><a href="#resources">Sumber</a></li> -->`
- [ ] Aktifkan semula footer link: uncomment `<!-- <a href="#resources" ...>Sumber</a> -->`
- [ ] Isi URL sebenar pada semua `href="#"` dalam kad sumber

### Projek — kandungan tambahan

- [ ] Tambah pautan sekunder jika ada (cth. GitHub) — CTA utama dua projek sudah ke URL live
- [ ] Tambah screenshot / mockup sebenar (ganti placeholder emoji pada kad jika mahu)

### Deploy ke Vercel

- [ ] Setup repo GitHub untuk folder `syafidmy/` (jika belum)
- [ ] Connect ke Vercel, set root directory
- [ ] Test semua section pada mobile
- [ ] Test anchor links: `#about`, `#skills`, `#projects`, `#contact` (dan `#resources` selepas diaktifkan)

### Nice-to-have

- [ ] Dark mode toggle
- [ ] OG meta tags (og:title, og:image, og:description) untuk social sharing
- [ ] Favicon
- [ ] Google Analytics / Vercel Analytics

---

## Keputusan Reka Bentuk

| Bahagian | Keputusan |
|---|---|
| Kemahiran | Option C — 3 featured cards + tag cloud |
| Sumber & Tools | Card layout baru (2-col, content + mockup preview) |
| Warna utama | --ink #0a0a0a, --green #00d97e, --yellow #ffe600 |
| Font | Sora (body) + JetBrains Mono (labels) |
| Animations | CSS spring + IntersectionObserver (no library) |
