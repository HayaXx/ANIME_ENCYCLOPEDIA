<div align="center">

# 🎌 ANIME ENCYCLOPEDIA

</div>
<div align="center">

![Anime Encyclopedia Banner](https://via.placeholder.com/1280x400/667eea/ffffff?text=ANIME+ENCYCLOPEDIA)

<p align="center">
  <a href="https://github.com/HayaXx/github-readme-stats/actions">
    <img alt="Tests Passing" src="https://github.com/HayaXx/github-readme-stats/workflows/Test/badge.svg" />
  </a>
  <a href="https://github.com/HayaXx/github-readme-stats/graphs/contributors">
    <img alt="GitHub Contributors" src="https://img.shields.io/github/contributors/HayaXx/github-readme-stats" />
  </a>
  <a href="https://codecov.io/gh/HayaXx/github-readme-stats">
    <img alt="Tests Coverage" src="https://codecov.io/gh/HayaXx/github-readme-stats/branch/master/graph/badge.svg" />
  </a>
  <a href="https://github.com/HayaXx/github-readme-stats/issues">
    <img alt="Issues" src="https://img.shields.io/github/issues/HayaXx/github-readme-stats?color=0088ff" />
  </a>
  <a href="https://github.com/HayaXx/github-readme-stats/pulls">
    <img alt="GitHub pull requests" src="https://img.shields.io/github/issues-pr/HayaXx/github-readme-stats?color=0088ff" />
  </a>
  <a href="https://securityscorecards.dev/viewer/?uri=github.com/HayaXx/github-readme-stats">
    <img alt="OpenSSF Scorecard" src="https://api.securityscorecards.dev/projects/github.com/HayaXx/github-readme-stats/badge" />
  </a>
  <br />
  <br />
  <a href="https://vercel.com?utm\_source=github\_readme\_stats\_team\&utm\_campaign=oss">
    <img src="./powered-by-vercel.svg"/>
  </a>
</p>

**Platform ensiklopedia anime lengkap dengan database terstruktur, API powerful, dan antarmuka yang indah**

[📖 Dokumentasi](docs/) • [🚀 Demo Live](https://demo.anime-encyclopedia.com) • [💬 Komunitas](https://discord.gg/anime-encyclopedia) • [🐛 Laporkan Bug](issues/)

</div>

---

## 📋 Daftar Isi

- [Tentang Project](#-tentang-project)
- [Fitur Unggulan](#-fitur-unggulan)
- [Demo & Screenshot](#-demo--screenshot)
- [Instalasi Cepat](#-instalasi-cepat)
- [Cara Penggunaan](#-cara-penggunaan)
- [API Documentation](#-api-documentation)
- [Struktur Data](#-struktur-data)
- [Kontribusi](#-kontribusi)
- [Roadmap](#-roadmap)
- [FAQ](#-faq)
- [Lisensi](#-lisensi)

---

## 🌟 Tentang Project

**Anime Encyclopedia** adalah platform open-source yang menyediakan informasi lengkap tentang anime, karakter, studio, dan berbagai metadata lainnya. Project ini lahir dari kecintaan terhadap anime dan kebutuhan akan sumber informasi yang terstruktur, mudah diakses, dan dapat dikembangkan oleh komunitas.

### 🎯 Visi

Menciptakan Wikipedia untuk dunia anime yang:
- 📊 **Terstruktur** - Data terorganisir dengan baik dan mudah diakses
- 🔍 **Searchable** - Sistem pencarian canggih dengan filter multi-kriteria
- 🎨 **Beautiful** - Antarmuka yang estetik dan ramah pengguna
- 🌐 **Open** - API terbuka untuk developer dan komunitas
- 📈 **Scalable** - Arsitektur yang siap berkembang

### 📊 Statistik Project

- **150+ Anime Entries** - Database yang terus berkembang
- **500+ Karakter** - Informasi detail karakter utama
- **50+ Studio** - Daftar lengkap studio produksi
- **1000+ User Aktif** - Komunitas yang terus tumbuh
- **99.9% Uptime** - Reliabilitas tinggi

---

## ✨ Fitur Unggulan

### 🎬 Katalog Anime Lengkap
- **Metadata Komprehensif**: Judul, tahun rilis, studio, genre, rating
- **Multiple Titles**: Dukungan judul alternatif (romaji, english, japanese)
- **Rich Synopsis**: Deskripsi detail dengan spoiler protection
- **Episode Tracking**: Informasi episode dan season

### 🔍 Pencarian & Filter Canggih
- **Smart Search**: Pencarian fuzzy dengan typo tolerance
- **Advanced Filters**: Genre, tahun, studio, status, rating
- **Real-time Results**: Update hasil pencarian secara instant
- **Sort Options**: Urutkan berdasarkan popularitas, rating, atau tahun

### 🎭 Database Karakter
- **Character Profiles**: Bio lengkap dengan gambar high-quality
- **Voice Actors**: Informasi seiyuu untuk setiap karakter
- **Relationships**: Network karakter dan hubungan antar-karakter
- **Character Rankings**: Top karakter berdasarkan voting komunitas

### 🏢 Studio Information
- **Studio Profiles**: Sejarah dan portfolio studio anime
- **Production Timeline**: Timeline produksi anime
- **Staff Directory**: Database staff dan kontributor

### 🛠️ Developer-Friendly
- **RESTful API**: API documentation lengkap dengan examples
- **GraphQL Support**: Query flexible untuk kebutuhan spesifik
- **Multiple Formats**: Export/import JSON, YAML, Markdown
- **SDK Libraries**: Library untuk JavaScript, Python, dan Go

### 🎨 UI/UX Excellence
- **Responsive Design**: Optimal di desktop, tablet, dan mobile
- **Dark/Light Mode**: Theme switching dengan preferensi tersimpan
- **Anime Aesthetics**: Design terinspirasi dari anime culture
- **Smooth Animations**: Transisi dan animasi yang fluid

---

## 📸 Demo & Screenshot

<div align="center">

### 🏠 Homepage
![Homepage](https://via.placeholder.com/800x450/764ba2/ffffff?text=Homepage+Preview)
*Landing page dengan featured anime dan trending section*

### 🔎 Search Interface
![Search](https://via.placeholder.com/800x450/f093fb/ffffff?text=Search+Interface)
*Powerful search dengan real-time filtering*

### 📱 Mobile View
<img src="https://via.placeholder.com/300x600/4facfe/ffffff?text=Mobile+View" alt="Mobile" width="300"/>

*Fully responsive untuk semua device*

</div>

**🎥 [Tonton Video Demo](https://youtube.com/demo)** | **🌐 [Coba Live Demo](https://demo.anime-encyclopedia.com)**

---

## 🚀 Instalasi Cepat

### Prerequisites

Pastikan Anda memiliki:
- Node.js >= 16.x
- npm atau yarn
- Git

### Langkah Instalasi

```bash
# 1. Clone repository
git clone https://github.com/yourusername/anime-encyclopedia.git
cd anime-encyclopedia

# 2. Install dependencies
npm install
# atau dengan yarn
yarn install

# 3. Setup environment variables
cp .env.example .env
# Edit .env dengan konfigurasi Anda

# 4. Inisialisasi database
npm run db:init

# 5. Import sample data (opsional)
npm run seed

# 6. Jalankan development server
npm run dev

# Server akan berjalan di http://localhost:3000
```

### 🐳 Docker Installation

```bash
# Build dan jalankan dengan Docker Compose
docker-compose up -d

# Aplikasi akan tersedia di http://localhost:3000
```

---

## 📖 Cara Penggunaan

### 1️⃣ Menambahkan Entry Anime Baru

#### Via Web Interface

1. Login ke dashboard
2. Klik tombol **"Add New Anime"**
3. Isi form dengan informasi lengkap
4. Upload cover image (JPG/PNG, max 5MB)
5. Klik **"Submit"** untuk menyimpan

#### Via Markdown File

Buat file di `data/anime/[anime-slug].md`:

```markdown
---
title: "Attack on Titan"
alt_titles:
  romaji: "Shingeki no Kyojin"
  japanese: "進撃の巨人"
  english: "Attack on Titan"
year: 2013
seasons: 4
episodes: 87
studio:
  - "Wit Studio"
  - "MAPPA"
genres:
  - "Action"
  - "Drama"
  - "Dark Fantasy"
rating: 9.0
status: "completed"
---

# Attack on Titan

## 📝 Sinopsis

Seratus tahun yang lalu, para Titan muncul dan mendorong umat manusia ke ambang kepunahan. Untuk bertahan hidup, manusia membangun tiga tembok konsentris yang sangat tinggi. Eren Yeager bersumpah untuk membasmi semua Titan setelah menyaksikan kematian tragis ibunya...

## 🎭 Karakter Utama

### Eren Yeager
- **Role**: Protagonist
- **Age**: 15-19
- **Voice Actor**: Yuki Kaji
- **Description**: Protagonis utama yang bersumpah membasmi semua Titan

### Mikasa Ackerman
- **Role**: Main Character
- **Age**: 15-19
- **Voice Actor**: Yui Ishikawa
- **Description**: Saudara angkat Eren dan prajurit terkuat

## 🏆 Penghargaan

- Best Anime 2013 - Crunchyroll Anime Awards
- Best Action Anime - Tokyo Anime Award 2014

## 🔗 Referensi

- [MyAnimeList](https://myanimelist.net/anime/16498)
- [AniList](https://anilist.co/anime/16498)
- [Official Website](https://shingeki.tv)
```

### 2️⃣ Menggunakan Pencarian

#### Basic Search

```javascript
// Cari anime berdasarkan judul
searchAnime("naruto")

// Hasil akan menampilkan semua anime yang cocok
```

#### Advanced Search dengan Filter

```javascript
// Cari dengan multiple criteria
searchAnime({
  query: "shounen",
  genres: ["Action", "Adventure"],
  year: { min: 2015, max: 2020 },
  studio: "Bones",
  rating: { min: 8.0 },
  status: "completed",
  sort: "rating-desc"
})
```

### 3️⃣ Export/Import Data

#### Export ke JSON

```bash
# Export semua data
npm run export --format=json --output=backup.json

# Export anime tertentu
npm run export --format=json --filter="year:2020" --output=anime-2020.json
```

#### Import dari File

```bash
# Import dari JSON
npm run import --source=backup.json

# Import dari YAML
npm run import --source=data.yaml --format=yaml
```

---

## 🔌 API Documentation

### Base URL

```
Production: https://api.anime-encyclopedia.com/v1
Development: http://localhost:3000/api/v1
```

### Authentication

```bash
# Dapatkan API key dari dashboard
API_KEY="your_api_key_here"

# Gunakan di header request
Authorization: Bearer YOUR_API_KEY
```

### Endpoints Overview

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | `/anime` | List semua anime |
| GET | `/anime/:id` | Detail anime spesifik |
| POST | `/anime` | Tambah anime baru |
| PUT | `/anime/:id` | Update anime |
| DELETE | `/anime/:id` | Hapus anime |
| GET | `/search` | Pencarian anime |
| GET | `/characters` | List karakter |
| GET | `/studios` | List studio |

### 📘 Contoh Penggunaan API

#### 1. Mendapatkan List Anime

**Request:**
```bash
curl -X GET "https://api.anime-encyclopedia.com/v1/anime?page=1&limit=20" \
  -H "Authorization: Bearer YOUR_API_KEY"
```

**Response:**
```json
{
  "status": "success",
  "data": {
    "anime": [
      {
        "id": "aot-001",
        "title": "Attack on Titan",
        "year": 2013,
        "rating": 9.0,
        "genres": ["Action", "Drama"],
        "studio": ["Wit Studio", "MAPPA"],
        "episodes": 87,
        "status": "completed",
        "cover_image": "https://cdn.anime-encyclopedia.com/covers/aot.jpg"
      }
    ],
    "pagination": {
      "page": 1,
      "limit": 20,
      "total": 150,
      "pages": 8
    }
  }
}
```

#### 2. Detail Anime Spesifik

**Request:**
```bash
curl -X GET "https://api.anime-encyclopedia.com/v1/anime/aot-001" \
  -H "Authorization: Bearer YOUR_API_KEY"
```

**Response:**
```json
{
  "status": "success",
  "data": {
    "id": "aot-001",
    "title": "Attack on Titan",
    "alt_titles": {
      "romaji": "Shingeki no Kyojin",
      "japanese": "進撃の巨人",
      "english": "Attack on Titan"
    },
    "synopsis": "Seratus tahun yang lalu...",
    "year": 2013,
    "seasons": 4,
    "episodes": 87,
    "rating": 9.0,
    "genres": ["Action", "Drama", "Dark Fantasy"],
    "studio": ["Wit Studio", "MAPPA"],
    "status": "completed",
    "aired": {
      "start": "2013-04-07",
      "end": "2023-11-05"
    },
    "characters": [
      {
        "id": "char-001",
        "name": "Eren Yeager",
        "role": "Main"
      }
    ],
    "related": [
      {
        "id": "aot-002",
        "title": "Attack on Titan: Junior High",
        "relation": "spin-off"
      }
    ]
  }
}
```

#### 3. Search dengan Filter

**Request:**
```bash
curl -X GET "https://api.anime-encyclopedia.com/v1/search?q=action&genre=Action&year_min=2015&rating_min=8.0&sort=rating" \
  -H "Authorization: Bearer YOUR_API_KEY"
```

**Response:**
```json
{
  "status": "success",
  "data": {
    "results": [
      {
        "id": "mha-001",
        "title": "My Hero Academia",
        "year": 2016,
        "rating": 8.4,
        "match_score": 0.95
      }
    ],
    "total": 45,
    "query": "action",
    "filters_applied": {
      "genre": "Action",
      "year_min": 2015,
      "rating_min": 8.0
    }
  }
}
```

#### 4. Menambahkan Anime Baru

**Request:**
```bash
curl -X POST "https://api.anime-encyclopedia.com/v1/anime" \
  -H "Authorization: Bearer YOUR_API_KEY" \
  -H "Content-Type: application/json" \
  -d '{
    "title": "Demon Slayer",
    "alt_titles": {
      "romaji": "Kimetsu no Yaiba",
      "japanese": "鬼滅の刃"
    },
    "year": 2019,
    "genres": ["Action", "Supernatural"],
    "studio": ["ufotable"],
    "episodes": 26,
    "rating": 8.7,
    "synopsis": "Tanjiro Kamado, seorang anak baik hati..."
  }'
```

**Response:**
```json
{
  "status": "success",
  "message": "Anime berhasil ditambahkan",
  "data": {
    "id": "ds-001",
    "title": "Demon Slayer",
    "created_at": "2024-01-15T10:30:00Z"
  }
}
```

### 🔧 SDK Libraries

#### JavaScript/TypeScript

```bash
npm install @anime-encyclopedia/sdk
```

```javascript
import { AnimeEncyclopedia } from '@anime-encyclopedia/sdk';

const client = new AnimeEncyclopedia({
  apiKey: 'YOUR_API_KEY'
});

// Mendapatkan anime
const anime = await client.anime.get('aot-001');

// Search
const results = await client.search({
  query: 'naruto',
  genres: ['Action'],
  rating: { min: 8.0 }
});

// Pagination
for await (const anime of client.anime.list({ limit: 50 })) {
  console.log(anime.title);
}
```

#### Python

```bash
pip install anime-encyclopedia
```

```python
from anime_encyclopedia import Client

client = Client(api_key='YOUR_API_KEY')

# Mendapatkan anime
anime = client.anime.get('aot-001')

# Search
results = client.search(
    query='naruto',
    genres=['Action'],
    rating_min=8.0
)

# Iterasi dengan pagination
for anime in client.anime.list(limit=50):
    print(anime.title)
```

### 📊 Rate Limiting

- **Free Tier**: 1000 requests/hari
- **Basic Tier**: 10,000 requests/hari
- **Pro Tier**: 100,000 requests/hari
- **Enterprise**: Unlimited

Rate limit headers:
```
X-RateLimit-Limit: 1000
X-RateLimit-Remaining: 999
X-RateLimit-Reset: 1640995200
```

---

## 🗂️ Struktur Data

### Schema Anime

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | ✅ | Unique identifier (auto-generated) |
| `title` | string | ✅ | Judul utama anime |
| `alt_titles` | object | ❌ | Judul alternatif (romaji, japanese, english) |
| `year` | number | ✅ | Tahun rilis (format: YYYY) |
| `seasons` | number | ❌ | Jumlah season |
| `episodes` | number | ✅ | Total episode |
| `studio` | array | ✅ | Studio produksi |
| `genres` | array | ✅ | Genre anime (min. 1) |
| `rating` | number | ❌ | Rating (0.0 - 10.0) |
| `status` | enum | ✅ | Status: `ongoing`, `completed`, `upcoming` |
| `synopsis` | string | ❌ | Deskripsi singkat |
| `cover_image` | string | ❌ | URL gambar cover |
| `trailer` | string | ❌ | URL trailer video |
| `aired` | object | ❌ | Tanggal tayang (`start`, `end`) |
| `sources` | array | ❌ | Referensi external |
| `tags` | array | ❌ | Tag tambahan |

### Contoh JSON Lengkap

```json
{
  "id": "aot-001",
  "title": "Attack on Titan",
  "alt_titles": {
    "romaji": "Shingeki no Kyojin",
    "japanese": "進撃の巨人",
    "english": "Attack on Titan"
  },
  "year": 2013,
  "seasons": 4,
  "episodes": 87,
  "studio": ["Wit Studio", "MAPPA"],
  "genres": ["Action", "Drama", "Dark Fantasy"],
  "rating": 9.0,
  "status": "completed",
  "synopsis": "Seratus tahun yang lalu, para Titan muncul...",
  "cover_image": "https://cdn.anime-encyclopedia.com/covers/aot.jpg",
  "trailer": "https://youtube.com/watch?v=...",
  "aired": {
    "start": "2013-04-07",
    "end": "2023-11-05"
  },
  "sources": [
    {
      "name": "MyAnimeList",
      "url": "https://myanimelist.net/anime/16498"
    },
    {
      "name": "Official Website",
      "url": "https://shingeki.tv"
    }
  ],
  "tags": ["military", "post-apocalyptic", "survival"],
  "created_at": "2024-01-01T00:00:00Z",
  "updated_at": "2024-01-15T10:30:00Z"
}
```

---

## 🤝 Kontribusi

Kami sangat terbuka untuk kontribusi dari komunitas! Ada banyak cara untuk berkontribusi:

### 🌟 Cara Berkontribusi

1. **Menambahkan Data Anime**
   - Fork repository
   - Tambahkan entry anime baru di `data/anime/`
   - Submit pull request

2. **Memperbaiki Bug**
   - Cek [Issues](issues/) untuk bug yang perlu diperbaiki
   - Buat branch baru untuk fix
   - Submit pull request dengan deskripsi jelas

3. **Menambahkan Fitur**
   - Diskusikan fitur di [Discussions](discussions/)
   - Buat proposal di Issues
   - Implementasi dan submit PR

4. **Memperbaiki Dokumentasi**
   - Typo, grammar, atau informasi yang outdated
   - Tambahkan contoh penggunaan
   - Terjemahkan ke bahasa lain

### 📝 Contribution Guidelines

```bash
# 1. Fork dan clone
git clone https://github.com/YOUR_USERNAME/anime-encyclopedia.git
cd anime-encyclopedia

# 2. Buat branch baru
git checkout -b feature/anime-jujutsu-kaisen

# 3. Lakukan perubahan
# ... edit files ...

# 4. Commit dengan conventional commits
git commit -m "feat: add Jujutsu Kaisen entry"

# 5. Push ke fork Anda
git push origin feature/anime-jujutsu-kaisen

# 6. Buat Pull Request di GitHub
```

### 📜 Commit Convention

```
feat: menambahkan fitur baru
fix: memperbaiki bug
docs: update dokumentasi
style: perubahan formatting
refactor: refactoring code
test: menambah test
chore: maintenance tasks
```

### 🏆 Top Contributors

<a href="https://github.com/yourusername/anime-encyclopedia/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=yourusername/anime-encyclopedia" />
</a>

---

## 🗺️ Roadmap

### ✅ Phase 1: Foundation (Q1 2024) - COMPLETED
- [x] Basic data structure
- [x] Core API endpoints
- [x] Simple web interface
- [x] Search functionality

### 🚧 Phase 2: Enhancement (Q2 2024) - IN PROGRESS
- [x] Advanced filtering
- [x] User authentication
- [x] Rating system
- [ ] Comment system
- [ ] User watchlists

### 📋 Phase 3: Community (Q3 2024)
- [ ] User submissions
- [ ] Moderation system
- [ ] Community voting
- [ ] Discussion forums
- [ ] User profiles

### 🚀 Phase 4: Advanced Features (Q4 2024)
- [ ] Recommendation engine
- [ ] Similar anime finder
- [ ] Watch party system
- [ ] Mobile app (iOS/Android)
- [ ] Chrome extension

### 🌟 Future Ideas
- [ ] AI-powered summaries
- [ ] Streaming integration
- [ ] Social features
- [ ] Merchandise integration
- [ ] Event calendar

---

## ❓ FAQ

### 📌 Pertanyaan Umum

**Q: Apakah project ini gratis?**  
A: Ya, 100% gratis dan open-source. API tier gratis tersedia dengan limit 1000 requests/hari.

**Q: Bagaimana cara mendapatkan API key?**  
A: Daftar di [dashboard](https://anime-encyclopedia.com/dashboard), verifikasi email, dan API key akan digenerate otomatis.

**Q: Apakah saya bisa menggunakan data ini untuk project komersial?**  
A: Ya, selama mengikuti lisensi MIT. Atribusi dihargai tapi tidak wajib.

**Q: Berapa sering data diupdate?**  
A: Database diupdate setiap hari dengan anime season baru dan informasi terbaru.

**Q: Bagaimana cara melaporkan informasi yang salah?**  
A: Buka [Issues](issues/) dan gunakan template "Data Correction" atau edit langsung via pull request.

**Q: Apakah ada plan untuk aplikasi mobile?**  
A: Ya! Mobile app untuk iOS dan Android sedang dalam development (planned Q4 2024).

---

## 📄 Lisensi

Project ini dilisensikan di bawah [MIT License](LICENSE).

```
MIT License

Copyright (c) 2024 Anime Encyclopedia

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software...
```

---

## 🙏 Acknowledgments

Terima kasih kepada:

- **MyAnimeList** - Inspirasi dan referensi data
- **AniList** - API design inspiration  
- **Jikan API** - Technical reference
- **Komunitas Anime Indonesia** - Dukungan dan feedback
- **All Contributors** - Yang telah berkontribusi ke project ini

---

## 📞 Kontak & Dukungan

- 💬 **Discord**: [Join Server](https://discord.gg/anime-encyclopedia)
- 🐦 **Twitter**: [@AnimeEncyclopedia](https://twitter.com/animeencyclopedia)
- 📧 **Email**: support@anime-encyclopedia.com
- 📝 **Blog**: [blog.anime-encyclopedia.com](https://blog.anime-encyclopedia.com)

---

<div align="center">

### ⭐ Jika project ini membantu Anda, berikan star di GitHub!

**Made with ❤️ by the Anime Community**

[⬆ Kembali ke atas](#-anime-encyclopedia)

</div>