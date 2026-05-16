<div align="center">

# 🌟 We Will Shine

<p>
  <a href="https://opensource.org/licenses/MIT"><img src="https://img.shields.io/badge/license-MIT-10b981?style=flat-square" alt="MIT License" /></a>
  <a href="https://kit.svelte.dev/"><img src="https://img.shields.io/badge/SvelteKit-ff3e00?style=flat-square&logo=svelte&logoColor=white" alt="SvelteKit" /></a>
  <a href="https://tailwindcss.com/"><img src="https://img.shields.io/badge/Tailwind-06b6d4?style=flat-square&logo=tailwindcss&logoColor=white" alt="Tailwind CSS" /></a>
  <a href="https://ainjiner.github.io/we-will-shine/"><img src="https://img.shields.io/badge/demo-live-10b981?style=flat-square" alt="Live Demo" /></a>
  <img src="https://img.shields.io/badge/for-Indonesia-ef4444?style=flat-square" alt="For Indonesia" />
</p>

**Career Guidance & Student Wellbeing Platform — powered by AI, built for Indonesia 🇮🇩**

*Membantu siswa menemukan jalan mereka. Memberikan Guru BK data untuk menolong lebih banyak.*

[**Live Demo →**](https://ainjiner.github.io/we-will-shine/) · [**Discussions →**](https://github.com/ainjiner/we-will-shine/discussions) · [**Support the project →**](https://github.com/sponsors/ainjiner)

</div>

---

## Origin Story

Project ini **digagas oleh [sandikodev](https://github.com/sandikodev)** atas rasa syukur telah mendapat kesempatan untuk mengajar anak-anak SMP IT Masjid Syuhada yang soleh dan solehah.

Berawal dari hadiah sepatu yang diberikan siswa kepada guru — project ini menjadi hadiah balasan yang jauh lebih bermakna. Bukan hanya coklat manis, tapi sebuah aplikasi yang memberi nilai edukatif untuk masa depan mereka. **Sebuah bentuk terima kasih yang berbuah manfaat berkelanjutan.** 💝

Kini We Will Shine berkembang menjadi platform nasional open-source untuk membantu siswa Indonesia dan Guru BK di seluruh nusantara.

---

## The Problem We're Solving

```
Rasio Guru BK : Siswa di Indonesia  →  1 : 500+
Standar UNESCO yang seharusnya      →  1 : 250

Siswa SMA yang mengalami tekanan psikologis signifikan  →  ~34%
Dari mereka yang pernah berkonsultasi ke Guru BK        →  ~18%

Artinya: 82% siswa yang butuh bantuan tidak pernah mendapatkannya.
```

We Will Shine hadir untuk menutup gap tersebut — dengan AI yang berempati, jurnal yang aman, dan data yang berguna untuk para Guru BK.

---

## Tentang Project

**We Will Shine** adalah platform career guidance & student wellbeing yang membantu siswa:

- 🎯 Mengeksplorasi karir teknologi masa depan
- 🧠 Memahami kepribadian melalui quiz interaktif
- 🤖 Belajar dan berkembang bersama AI Mentor
- 💝 Memiliki ruang curhat yang aman dan anonim
- ✨ Merencanakan impian melalui Dream Board
- 🏆 Termotivasi dengan sistem gamifikasi (points, levels, achievements)
- ☪️ Memahami nilai Islam dalam setiap profesi dan pilihan karier

### Our Vision: Free & Open Source for All Schools

We Will Shine akan menjadi **platform open-source nasional** untuk membantu Guru BK di seluruh Indonesia:

- 💝 Memberikan siswa **tempat aman untuk curhat** — tanpa rasa malu, tanpa takut dihakimi
- 🤖 **AI yang peduli** sebagai teman bicara 24/7 ketika Guru BK tidak tersedia
- 📊 **Data insights** untuk Guru BK — aggregated, privacy-first, actionable
- 🏫 **100% gratis** untuk semua sekolah — negeri maupun swasta
- 🌟 **Open source** — dikembangkan bersama komunitas, untuk komunitas

→ Baca lebih lengkap: [Open Source Vision](docs/OPEN-SOURCE-VISION.md) | [Ethics Framework](docs/ETHICS-FRAMEWORK.md)

---

## Features

### Student App (`/app`)

| Fitur | Deskripsi | Status |
|-------|-----------|--------|
| **Unlock System** | Login dengan kode unik | ✅ |
| **Session Auth** | Code tersimpan di localStorage, auto-expiry 7 hari | ✅ |
| **8 Karir Teknologi** | Software Dev, UI/UX, Data Analyst, AI/ML, Cybersecurity, Cloud, Game Dev, IoT | ✅ |
| **Personality Quiz** | 6 pertanyaan dengan motivasi personal 300+ kata per jawaban | ✅ |
| **AI Mentor** | Chat interaktif untuk guidance karier & kesehatan mental | ✅ |
| **Dream Board** | Tulis & track impian masa depan dengan visual goals | ✅ |
| **Gamifikasi** | Points, levels, 8 unique achievements | ✅ |
| **Mobile-Optimized** | Bottom navbar, compact layout, touch-first UX | ✅ |
| **Clean URLs** | Tidak ada code parameter di URL — privacy by default | ✅ |
| **Islamic Values** | Konteks nilai Islam dalam setiap eksplorasi profesi | ✅ |

### Counselor Dashboard (`/dashboard`)

| Fitur | Deskripsi | Status |
|-------|-----------|--------|
| **Students Management** | Track progress dan engagement setiap siswa | ✅ |
| **Analytics** | Engagement metrics, leaderboard, career popularity heatmap | ✅ |
| **QR Generator** | Generate QR codes untuk distribusi kode akses | ✅ |
| **Export Data** | Download CSV untuk reporting ke kepala sekolah | ✅ |
| **Column Visibility** | Customize tampilan tabel per kebutuhan Guru BK | ✅ |
| **Wellbeing Alerts** | Notifikasi otomatis ketika siswa membutuhkan perhatian khusus | 🔜 |

---

## URL Structure

```
https://ainjiner.github.io/we-will-shine/
├── /                   ← Landing page
├── /unlock             ← Student login (dengan kode)
├── /login              ← Admin / Guru BK login ⭐
│
├── /app/               ← Student portal ⭐
│   ├── /careers        ← Eksplorasi 8 karir teknologi
│   ├── /quiz           ← Quiz kepribadian & minat
│   ├── /achievements   ← Capaian & gamifikasi
│   ├── /ai-mentor      ← AI chat — guidance & curhat
│   └── /dream-board    ← Rencana impian masa depan
│
└── /dashboard/         ← Counselor panel (Guru BK) ⭐
    ├── /students        ← Manage & track siswa
    ├── /analytics       ← Engagement & wellbeing insights
    ├── /qr-generator    ← Buat kode akses siswa
    └── /settings        ← Konfigurasi sekolah
```

→ Dokumentasi routing lengkap: [Routing Structure](docs/ROUTING-STRUCTURE.md)

---

## Quick Start — Development

```bash
# Clone repo
git clone https://github.com/ainjiner/we-will-shine.git
cd we-will-shine

# Install dependencies
pnpm install

# Jalankan development server
pnpm run dev

# Buka di browser
open http://localhost:5173
```

---

## Deploy ke GitHub Pages

### 1. Fork & Setup Repository

```bash
git init
git add .
git commit -m "feat: initial We Will Shine setup"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/we-will-shine.git
git push -u origin main
```

### 2. Aktifkan GitHub Pages

1. Buka repo di GitHub
2. Settings → Pages → Source → **GitHub Actions**
3. Deploy otomatis setiap push ke `main`

### 3. Update Base Path (jika nama repo berbeda)

Di `svelte.config.js`:

```js
paths: {
  base: process.env.NODE_ENV === 'production' ? '/nama-repository-anda' : ''
}
```

Website tersedia di: `https://USERNAME.github.io/we-will-shine/`

---

## Build & Testing

```bash
# Production build
pnpm run build

# Preview production build lokal
pnpm run preview

# End-to-end tests (Playwright)
pnpm run test:e2e

# Tests dengan UI mode (interactive)
pnpm run test:e2e:ui
```

**Test coverage meliputi:**
- ✅ Navigation antar semua halaman
- ✅ Quiz functionality & state management
- ✅ Gamification & achievement triggers
- ✅ localStorage persistence & auto-expiry
- ✅ Admin dashboard data rendering

---

## Project Structure

```
we-will-shine/
├── src/
│   ├── routes/          ← Halaman & routing (SvelteKit file-based)
│   │   ├── +layout.svelte
│   │   ├── app/         ← Student portal
│   │   └── dashboard/   ← Guru BK panel
│   ├── lib/             ← Shared components & utilities
│   └── app.css          ← Global styles (Tailwind)
├── static/              ← Static assets (favicon, images)
├── docs/                ← Dokumentasi lengkap
├── .github/workflows/   ← GitHub Actions CI/CD
├── svelte.config.js     ← Konfigurasi SvelteKit + adapter-static
└── playwright.config.ts ← E2E test config
```

---

## Technical Configuration

### `svelte.config.js`

- Menggunakan `@sveltejs/adapter-static` untuk static site generation
- Base path dikonfigurasi untuk GitHub Pages
- Fallback ke `404.html` untuk client-side SPA routing

### `src/routes/+layout.ts`

```typescript
export const prerender = true;
export const trailingSlash = 'always';
```

### `static/.nojekyll`

Mencegah GitHub Pages menggunakan Jekyll processor — penting untuk folder/file berawalan underscore.

---

## Troubleshooting

### CSS / JS tidak ter-load

Pastikan `base` path di `svelte.config.js` sesuai dengan nama repository GitHub Anda.

### 404 saat refresh halaman

Pastikan `fallback: '404.html'` terkonfigurasi di adapter-static.

### Build gagal di GitHub Actions

Cek log di tab **Actions** di repository GitHub.

### Halaman dengan server-side logic tidak berfungsi

GitHub Pages hanya mendukung static files. Halaman yang menggunakan:
- Server actions (form actions)
- Server-side rendering (SSR)
- Cookies atau server-managed session

Harus dikonversi ke client-side:

1. Hapus `+page.server.ts` atau set `export const ssr = false`
2. Set `export const prerender = true` di `+page.ts`
3. Gunakan localStorage untuk state management
4. Verifikasi dengan `pnpm run build` bahwa file `.html` ter-generate di `build/`

---

## Documentation

### Core Documentation

| Dokumen | Isi |
|---------|-----|
| 📖 [Product Vision](docs/PRODUCT-VISION.md) | Comprehensive product strategy & roadmap ⭐ |
| 🏗️ [Technical Architecture](docs/TECHNICAL-ARCHITECTURE.md) | Complete technical implementation guide ⭐ |
| 🛣️ [Development Roadmap](docs/DEVELOPMENT-ROADMAP.md) | Detailed development timeline & milestones ⭐ |
| 🤝 [Contributing Guide](docs/CONTRIBUTING.md) | Community contribution guidelines ⭐ |
| 📚 [API Documentation](docs/API-DOCUMENTATION.md) | Complete API reference & integration guide ⭐ |
| 🔒 [Security & Privacy](docs/SECURITY-PRIVACY.md) | Comprehensive security & privacy guidelines ⭐ |
| 🧪 [Testing Guide](docs/TESTING-GUIDE.md) | Complete testing strategy & quality assurance ⭐ |
| 🚀 [Deployment Guide](docs/DEPLOYMENT-GUIDE.md) | DevOps & deployment documentation ⭐ |
| 📖 [User Guide](docs/USER-GUIDE.md) | Comprehensive user manual & tutorials ⭐ |
| 🔧 [Troubleshooting & FAQ](docs/TROUBLESHOOTING-FAQ.md) | FAQ & troubleshooting guide ⭐ |
| 📋 [Changelog](docs/CHANGELOG.md) | Complete release notes ⭐ |

### Legacy & Reference Documentation

| Dokumen | Isi |
|---------|-----|
| 📖 [Development Journey](docs/DEVELOPMENT-JOURNEY.md) | Complete development timeline & key decisions |
| 🗺️ [Project Roadmap](docs/ROADMAP.md) | Future plans (Phase 2–8, Vision 2030) |
| 🌍 [Open Source Vision](docs/OPEN-SOURCE-VISION.md) | Free platform untuk semua sekolah Indonesia |
| 🔒 [Ethics Framework](docs/ETHICS-FRAMEWORK.md) | Privacy & ethical AI guidelines |
| 🎓 [Admin Guide](docs/ADMIN-GUIDE.md) | Panduan menggunakan admin dashboard |
| 📱 [Career Quest App](docs/CAREER-QUEST-APP.md) | Student app features & usage |
| 🛣️ [Routing Structure](docs/ROUTING-STRUCTURE.md) | URL structure & session management |
| 🔄 [Supabase Migration](docs/SUPABASE-MIGRATION-GUIDE.md) | Upgrade localStorage → Database |
| 🔧 [Fix Sverdle 404](docs/FIX-SVERDLE-404.md) | Technical fix documentation |
| ⚙️ [Workflows Guide](docs/WORKFLOWS-GUIDE.md) | GitHub Actions & CI/CD |

### Community

| Dokumen | Isi |
|---------|-----|
| 🤝 [CONTRIBUTING.md](CONTRIBUTING.md) | How to contribute |
| 📜 [Code of Conduct](CODE_OF_CONDUCT.md) | Community guidelines |
| 🔒 [Security Policy](SECURITY.md) | Report vulnerabilities |
| 📄 [LICENSE](LICENSE) | MIT License |

---

## Roadmap

| Phase | Focus | Status |
|-------|-------|--------|
| **v1.0** | Career Quest MVP — 8 careers, quiz, AI mentor, gamification | ✅ Live |
| **v1.1** | Wellbeing features — jurnal anonim, wellbeing indicators | 🔄 In Progress |
| **v2.0** | Guru BK Dashboard — full counselor tools, alerts, reporting | 🔜 Planned |
| **v3.0** | Open Source National Platform — multi-school, Kemendikbud integration | 🔜 Planned |
| **Vision 2030** | 50,000+ siswa, 100+ sekolah, research-backed impact | 🔜 Long-term |

→ Detail lengkap: [Development Roadmap](docs/DEVELOPMENT-ROADMAP.md) | [Org Roadmap](https://github.com/ainjiner/ainjiner.github.io/blob/main/docs/ROADMAP.md)

---

## Contributing

Kami menyambut kontribusi dari semua kalangan — developer, desainer, pendidik, atau siapa saja yang peduli dengan pendidikan Indonesia.

**Cara berkontribusi:**

- 💻 **Code** — features, bug fixes, performance improvements
- 📚 **Documentation** — guides, translations ke Bahasa Indonesia
- 🎨 **Design** — UI/UX improvements, accessibility
- 🧪 **Testing** — bug reports, QA, edge case exploration
- 💬 **Community** — support di Discussions, mentoring contributors baru
- 🏫 **Partnerships** — hubungkan kami dengan sekolah atau Guru BK

```bash
# Fork & clone
git clone https://github.com/YOUR_USERNAME/we-will-shine.git

# Install
pnpm install

# Start dev
pnpm run dev

# Run tests
pnpm run test
```

→ Baca panduan lengkap: [CONTRIBUTING.md](CONTRIBUTING.md)

---

## Contributors

**Founder & Creator:**
- [@sandikodev](https://github.com/sandikodev) — Founder, Creator & Lead Developer
  > *"Atas rasa syukur telah mendapat kesempatan mengajar anak-anak SMP IT Masjid Syuhada yang soleh dan solehah"*

**Want to be listed here?** Make a contribution and you'll be added! See [CONTRIBUTING.md](CONTRIBUTING.md).

---

## Contact & Support

| Keperluan | Kontak |
|-----------|--------|
| **Sekolah / Partnership** | hello@ainjiner.ai |
| **Penelitian / Kolaborasi** | hello@ainjiner.ai |
| **Bug Reports** | [GitHub Issues](https://github.com/ainjiner/we-will-shine/issues) |
| **Diskusi Umum** | [GitHub Discussions](https://github.com/ainjiner/we-will-shine/discussions) |
| **Security** | hello@ainjiner.ai (subject: `[SECURITY]`) |

---

## Acknowledgments

**Special Thanks:**
- 💝 Siswa-siswi 7D Putri SMP IT Masjid Syuhada — untuk inspirasi hadiah sepatu & menjadi pilot users pertama
- 🎓 SMP IT Masjid Syuhada — untuk kepercayaan dan dukungan
- 👨‍🏫 Ustadz & Ustadzah — untuk guidance, feedback, dan doa
- 👨‍💻 All contributors & supporters
- 🌟 Open source community Indonesia

**Built with:**
- [SvelteKit](https://kit.svelte.dev/) — Application framework
- [TailwindCSS](https://tailwindcss.com/) — Styling
- [Supabase](https://supabase.com/) — Backend (planned Phase 2)
- [Gemini AI](https://deepmind.google/technologies/gemini/) — AI mentor (planned)
- [GitHub Pages](https://pages.github.com/) — Hosting
- [Playwright](https://playwright.dev/) — E2E testing

---

## Part of the Ainjiner Ecosystem

We Will Shine adalah proyek flagship dari [Ainjiner](https://github.com/ainjiner) — organisasi open-source AI engineering dari Indonesia. Bersama [2USE](https://github.com/ainjiner/2USE) dan [AI Lab](https://github.com/ainjiner/ai-lab), We Will Shine merupakan bagian dari ekosistem tools AI untuk pendidikan yang kami bangun.

**Dukung perkembangan We Will Shine:**

[![Support via GitHub Sponsors](https://img.shields.io/badge/sponsor-GitHub-ea4aaa?style=flat-square&logo=github-sponsors)](https://github.com/sponsors/ainjiner)
[![Open Collective](https://img.shields.io/badge/donate-Open%20Collective-3b82f6?style=flat-square&logo=opencollective)](https://opencollective.com/ainjiner)
[![Ko-fi](https://img.shields.io/badge/ko--fi-ainjiner-f97316?style=flat-square&logo=ko-fi&logoColor=white)](https://ko-fi.com/ainjiner)
[![Trakteer](https://img.shields.io/badge/trakteer-ainjiner-ef4444?style=flat-square)](https://trakteer.id/ainjiner)

---

## License

[MIT](LICENSE) — Free to use, modify, and distribute. Gratis untuk semua sekolah, selamanya.

---

<div align="center">

**We Will Shine — Inspiring Tomorrow's Leaders, Supporting Wellbeing Today** 🌟

*"Built with ❤️ for students, by people who care"*

[⭐ Star us on GitHub](https://github.com/ainjiner/we-will-shine) · [🚀 Live Demo](https://ainjiner.github.io/we-will-shine/) · [💬 Discussions](https://github.com/ainjiner/we-will-shine/discussions)

</div>
