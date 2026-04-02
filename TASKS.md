# TASKS — syafidmy Portfolio

## Status Semasa
File utama: `syafidmy.html` (akan deploy ke Vercel)
Assets: `assets/` (syafid_ipad.png, syafid_bento.png)

---

## ✅ Siap

- [x] Hero section + bento grid
- [x] About Me + orbit badges
- [x] Kemahiran & Kepakaran — redesign Option C (3 featured cards + tag cloud + animations)
- [x] Projek section (proj-card layout)
- [x] Sumber & Tools — card layout baru (hidden buat masa ini)
- [x] Testimonials section
- [x] Blog / Konten section
- [x] Contact section
- [x] Footer
- [x] Scroll reveal animations (IntersectionObserver)
- [x] Nav scroll effect

---

## 🔧 Pending / TODO

### Sumber & Tools (§8) — hidden, aktifkan bila ready
- [ ] Aktifkan semula: buang `style="display:none"` pada `<section class="resources">`
- [ ] Aktifkan semula nav link: uncomment `<!-- <li><a href="#resources">Sumber</a></li> -->`
- [ ] Aktifkan semula footer link: uncomment `<!-- <a href="#resources" ...>Sumber</a> -->`
- [ ] Isi URL sebenar pada semua `href="#"` dalam kad sumber

### Projek — isi kandungan sebenar
- [ ] Tambah URL sebenar untuk setiap projek (Lihat Lanjut / GitHub)
- [ ] Tambah screenshot / mockup sebenar (ganti placeholder emoji)

### Deploy ke Vercel
- [ ] Setup repo GitHub untuk folder `syafidmy/`
- [ ] Connect ke Vercel, set root directory
- [ ] Test semua section pada mobile
- [ ] Test semua anchor links (#about, #skills, #projects, #contact)

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
