# 🎨 AI Visual Master & Asset Isolator Library
*Kumpulan Skill Code JSON untuk mengubah AI Teks (seperti Gemini & ChatGPT) menjadi Sutradara Visual & Desainer Aset Tingkat Lanjut.*

---

## 🌟 Tentang Repositori Ini
Repositori **Open-Source** ini dirancang untuk para kreator, desainer, dan *Prompt Engineer* yang ingin mendapatkan hasil visual yang konsisten, berdefinisi tinggi (*High-Fidelity*), dan siap eksekusi dari AI Image Generator (seperti Midjourney, DALL-E 3, atau Stable Diffusion). 

Daripada pusing memikirkan kata-kata teknis setiap saat, gunakan *Skill Code* di library ini untuk memaksa AI meracik prompt visual yang mutlak dan detail untuk Anda!

## ✨ Fitur & Modul Utama

Library ini dibagi menjadi dua modul *Skill Code* utama:

### 1. 🎬 Cinematic & High-Fidelity Generator
Fokus pada estetika, komposisi, dan teknik pencahayaan kamera profesional.
* **Gaya Visual:** Photorealistic, hyper-detailed, cinematic.
* **Spesifikasi Kamera:** 4K/8K resolution, 35mm/50mm prime lens, shot on Arri Alexa / Sony A1.
* **Pencahayaan:** Volumetric lighting, golden hour, neon glow, Rembrandt lighting.

### 2. ✂️ Asset Isolator (PNG Maker Studio)
Fokus pada pembuatan elemen desain yang mudah dipotong latar belakangnya (*background removal*).
* **Isolasi Latar:** *Pure white* (#FFFFFF) atau *Chroma green screen*.
* **Penghilangan Elemen:** *No floor, no cast shadows, no environment.*
* **Gaya Aset:** *Die-cut stickers*, 3D props, elemen UI/UX, karakter terisolasi.

---

## 📂 Struktur Direktori

```text
📁 ai-visual-library/
├── 📁 1-cinematic-prompts/
│   ├── 📄 skill-arsitektur.json      (Prompt desain eksterior & interior)
│   ├── 📄 skill-karakter.json        (Prompt potret manusia/karakter 3D)
│   └── 📄 skill-pemandangan.json     (Prompt lanskap & world-building)
├── 📁 2-asset-isolator/
│   ├── 📄 skill-png-produk.json      (Prompt barang e-commerce tanpa latar)
│   └── 📄 skill-png-stiker.json      (Prompt stiker vektor dengan outline putih)
└── 📄 README.md
