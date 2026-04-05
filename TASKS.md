# TASKS — syafidmy Portfolio

## Status Semasa

- File utama: `syafidmy.html` (deploy ke Vercel; `vercel.json` rewrite `/` → `/syafidmy.html`)
- Folder **`assets/`** dalam repo: `syafid_bento.png`, `syafid_ipad.png`, `agentic-rph-screenshot.jpg`, `chef-5-minit-screenshot.jpg`
- Git `main` disegerakkan ke GitHub (`oyendevlab/syafidmy`) — commit terakhir termasuk spotlight + Chef 5 Minit (sahkan dengan `git log`)

### Nota kemajuan (sambungan 5 Apr 2026)

- **About — orbit pills:** jejari `cqw`, susunan jam (12h/2h/4h/6h/9h), `orbit-float` + `orbit-drift` (tiada “lari” pusat→tepi), pill satu kapsul + hover shine; reduced motion dihormati.
- **Bento kuning:** memoji `assets/syafid_bento.png`.
- **Projek Semasa (`#projects`):** urutan kad — SekolahHub → Agentic RPH → TransitPBD → **Chef 5 Minit** (SIAP, Cloud Run, screenshot); intro dikemas ke *empat aplikasi*; footer VENTURE lengkap.
- **Projek Baru (`#projek-baru`):** selepas Kemahiran — hero gelap, mock macOS + screenshot Agentic RPH, stat, CTA; pill pastel + jarak; teks *Projek Terbaru* / *Papar Agentic RPH →*.
- **Nav/footer:** pautan `#projek-baru`, pautan apps (termasuk Chef 5 Minit).

---

## ✅ Siap

- [x] Hero section + bento grid
- [x] About Me + orbit badges (susunan & animasi dikemas; memoji bento)
- [x] Kemahiran & Kepakaran — Option C (3 featured cards + tag cloud + animations)
- [x] **Projek Baru** — spotlight Agentic RPH (`#projek-baru`, selepas Kemahiran)
- [x] Projek section — kad: SekolahHub, Agentic RPH, TransitPBD, **Chef 5 Minit** (pautan live + mock/screenshot)
- [x] Sumber & Tools — markup & CSS (card layout); **disembunyikan** (`display:none` pada `<section id="resources">`) buat masa ini
- [x] Contact section
- [x] Footer (+ VENTURE links)
- [x] Scroll reveal animations (IntersectionObserver)
- [x] Nav scroll effect (+ Projek Baru dalam nav)

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

- [ ] Tambah pautan sekunder jika ada (cth. GitHub) — CTA utama ke URL live untuk semua kad utama
- [ ] Semak / naik taraf screenshot jika ada versi UI baharu (Agentic RPH, Chef 5 Minit)

### Deploy ke Vercel

- [ ] Setup repo GitHub untuk folder `syafidmy/` (jika belum)
- [ ] Connect ke Vercel, set root directory
- [ ] Test semua section pada mobile
- [ ] Test anchor links: `#about`, `#skills`, `#projek-baru`, `#projects`, `#contact` (dan `#resources` selepas diaktifkan)

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
