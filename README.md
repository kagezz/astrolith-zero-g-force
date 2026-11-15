# ASTROLITH: ZERO G FORCE
### *Terk Edildiler. Ama Unutulmadılar. · Abandoned but not Forgotten*

[![Next.js 16](https://img.shields.io/badge/Next.js-16.4.3-black?style=for-the-badge&logo=next.js)](https://nextjs.org/)
[![React 19](https://img.shields.io/badge/React-19.0.0-blue?style=for-the-badge&logo=react)](https://react.dev/)
[![Three.js](https://img.shields.io/badge/Three.js-r187-black?style=for-the-badge&logo=three.js)](https://threejs.org/)
[![React Three Fiber](https://img.shields.io/badge/R3F-v9-red?style=for-the-badge)](https://r3f.docs.pmnd.rs/)
[![Tailwind CSS v4](https://img.shields.io/badge/Tailwind_CSS-v4-38B2AC?style=for-the-badge&logo=tailwind-css)](https://tailwindcss.com/)
[![Web Audio API](https://img.shields.io/badge/Web_Audio_API-Procedural-green?style=for-the-badge)](https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.7-3178C6?style=for-the-badge&logo=typescript)](https://www.typescriptlang.org/)
[![Static Export](https://img.shields.io/badge/Build-Static_Export_(out/)-success?style=for-the-badge)](https://nextjs.org/docs/app/building-your-application/deploying/static-exports)

---

## 🌌 Genel Bakış / Overview

**Astrolith: Zero G Force**, insanlığın Güneş Sistemi'nin derinliklerinde, Ay'da ve Mars yüzeyinde sessizliğe gömülmüş tarihi 13 efsanevi uzay aracını etkileşimli ve gerçekçi 3 boyutlu bir evrende yeniden canlandıran yeni nesil bir web deneyimidir.

NASA JPL ve Mission Control standartlarına dayalı katı bir **"Modern Aerospace"** tasarım diliyle geliştirilmiştir. Standart yapay zeka neonlarından ve abartılı parlamalardan arındırılmış; derin uzay obsidyeni (`#050810`, `#080B10`), mat titanyum dokuları ve VisionOS tarzı yüzen buzlu cam panelleriyle donatılmıştır.

---

## ✨ Temel Özellikler / Key Features

### 1. 🪐 Gerçek Zamanlı 3B Güneş Sistemi & Gök Cisimleri
* **Güneş'ten Neptün'e Kesintisiz Seyahat (0.1 AU – 30 AU):**
  * **Dünya & Ay:** Yüksek çözünürlüklü krater dokuları ve gerçekçi gölge haritaları.
  * **Mars:** Olympus Mons ve Valles Marineris kabartmalı kırmızı gezegen yüzeyi.
  * **Asteroit Kuşağı (Ceres & 433 Eros):** NEAR Shoemaker görev verilerine dayanan resmi 3B şekil modeli (`eros.glb`) ve kriyovolkanik Ahuna Mons'a sahip cüce gezegen Ceres.
  * **Saturn (8K):** Ekvatoral atmosfer şeritleri ve Cassini bölümüne sahip çift taraflı gölge düşüren halka diski.
  * **Uranus (8K):** Dikey halka sistemi ve 97.8° eksen eğikliği.
  * **Neptune (8K):** Kriyojenik aydınlatma ve derin azur atmosferik saçılma.

### 2. 🛰️ 13 Tarihi NASA Görevinin Resmi 3B Donanım Modelleri (`.glb`)
Tüm araçlar parçalanmayan, tek parça resmi `.glb` modelleri olarak yüklenir ve dinamik PBR malzeme enjeksiyonuyla yüzeye sıfır temasla yerleştirilir:
* **Ay (Moon):**
  * `Apollo 11 Eagle Lunar Module`
  * `Lunar Roving Vehicles (LRV)` – Tozlu alüminyum şasi ve tel örgülü tekerlekler.
  * `ALSEP Bilim Paketleri` – Yansıtıcı titanyum, beyaz termal boya ve Kapton altın folyo.
  * `Surveyor 3 İniş Aracı` – Tripod iniş ayakları, beyaz gövde ve düzlemsel güneş paneli.
* **Mars:**
  * `Sojourner Mars Rover` – Tozlu alüminyum şasi ve parlak koyu renkli güneş panelleri.
  * `Spirit & Opportunity (MER)`
  * `Viking 1 & 2 Landers`
  * `Phoenix & InSight Sismometre İstasyonları`
  * `Ingenuity Mars Helikopteri` – Karbon fiber rotor kanatları.
* **Yörünge & Asteroitler:**
  * `Kepler Uzay Teleskobu`
  * `Dawn (Vesta & Ceres)`
  * `NEAR Shoemaker (433 Eros)`
* **Derin Uzay:**
  * `Pioneer 10 & 11` – Yıldızlararası yörüngede altın plakalı parabolik yüksek kazançlı anten.

### 3. 🧊 "ZERO G FORCE" Buz Kırma Giriş Animasyonu (Ayrıştırılmış 1.5s Mantığı)
* **3 Aşamalı Etkileşim:** İlk iki tıklamada yayılan kristal çatlaklar ve düşen don partikülleri.
* **Sıralı Ayrışma:**
  1. 3. tıklamada buz kütlesi kırılır ve parçalar etrafa saçılır.
  2. **"ZERO G FORCE"** yazısı kırılma anından sonra ekranda **tam 1.5 saniye (1500 ms) boyunca tamamen hareketsiz ve net olarak kalır**.
  3. 1.5 saniyelik gecikmenin ardından minyatür booster roket motorları harflerin altına kenetlenip ateşlenir ve harfleri uzaya taşır.
* **Ses Ayrıştırması:** Cam patlama sesi ilk anda, roket uğultusu ise tam 1.5 saniye sonra roketler devreye girdiğinde çalar.

### 4. 🎛️ Yüzen VisionOS Navbar & Ses Kontrolü
* **Marka:** Sol tarafta statik, tıklanamayan şık `"zero"` etiketi.
* **Hızlı Filtre Sekmeleri:** Tümü, Ay, Mars, Asteroit, Derin Uzay.
* **Ses Açma / Kapama Butonu:** Derin Uzay ile Dil seçici arasında, navbar'ın buzlu cam yapısıyla birebir uyumlu interaktif ses anahtarı (`Volume2` / `VolumeX`).
* **Çift Dil Desteği:** Tek tıkla anında Türkçe (TR) ve İngilizce (EN) geçişi.
* **Detaylı Görev Paneli (Side Panel):** Resmi NSSDCA kimlikleri, koordinatlar, görev yılları, NASA arşiv fotoğrafları ve "Sinyal Gönder" etkileşimi.

### 5. 🔊 %100 Prosedürel Web Audio API Ses Motoru
* Dıştan yüklenen ses dosyası gerektirmeden tarayıcıda canlı sentezlenen sesler:
  * Kozmik derin uzay ambient uğultusu (`startCosmicAmbientDrone`)
  * Telemetri daktilo tıkırtıları (`playTelemetryBlip`)
  * Derin uzay sinyal çınlaması (`playSignalPing`)
  * Brütal buz çatlama ve roket alev sesleri

---

## 📂 Dizin Yapısı / Directory Structure

```text
astrolith-main/
├── app/
│   ├── globals.css          # Tailwind CSS v4 kuralları ve font tanımları
│   ├── layout.tsx           # Kök layout, SEO meta verileri, viewport
│   └── page.tsx             # Ana deneyim giriş noktası
├── components/
│   ├── experience.tsx       # Ana durum yöneticisi, kamera & görev orkestrasyonu
│   ├── IceIntroOverlay.tsx  # "ZERO G FORCE" 3 aşamalı buz kırma ve roket animasyonu
│   ├── overlay/
│   │   ├── site-header.tsx  # Yüzen pill Navbar ("zero" rozeti, filtreler, ses ikonu, dil)
│   │   ├── story-modal.tsx  # NASA arşiv fotoğraflı telemetri ve hikâye çekmecesi
│   │   ├── hero.tsx         # Giriş başlığı ve hızlı rehber
│   │   └── loading-screen.tsx
│   └── space/
│       ├── solar-system-scene.tsx # 3B Güneş Sistemi, gezegenler ve yörüngeler
│       ├── spacecraft-models.tsx  # 13 uzay aracının useGLTF yükleyicisi ve PBR malzemeleri
│       ├── lunar-rover.tsx        # LRV GLB bileşeni
│       ├── alsep.tsx              # ALSEP GLB bileşeni
│       ├── surveyor.tsx           # Surveyor 3 GLB bileşeni
│       └── mars-rover.tsx         # Sojourner GLB bileşeni
├── lib/
│   ├── equipment.ts         # 13 görevin tüm bilimsel koordinatları, NSSDCA ID'leri
│   ├── i18n.ts              # Türkçe ve İngilizce tam dil sözlüğü
│   ├── audio.ts             # Web Audio API prosedürel ses sentezleyici
│   └── geo.ts               # Küresel enlem/boylam 3B vektör dönüşümleri
├── public/
│   ├── models/              # Resmi NASA 3D .glb modelleri (lrv, alsep, surveyor3, sojourner...)
│   ├── textures/            # 8K/4K gezegen kaplamaları, Kapton folyo bump & solar ızgaraları
│   └── spacecraft/          # NASA JPL arşiv fotoğrafları
├── out/                     # 🚀 ÜRETİME HAZIR STATİK WEB SİTESİ EXPORT DİZİNİ
├── dist/                    # Next.js derleme çıktısı
├── next.config.mjs          # output: 'export' ve statik optimizasyon ayarları
└── package.json
```

---

## 🚀 Çalıştırma ve Kurulum / Getting Started

### Gereksinimler
* Node.js 18+ (önerilen: Node.js 20 veya 22)
* npm, pnpm veya yarn

### 1. Bağımlılıkları Yükleme
```bash
npm install
# veya
pnpm install
```

### 2. Geliştirme Sunucusunu Başlatma
```bash
npm run dev
```
Tarayıcınızda [http://localhost:3000](http://localhost:3000) adresine gidin.

---

## 📦 Statik Çıktı ve Dağıtım / Static Export (`out/`)

Bu proje **Next.js Static Export (`output: 'export'`)** modunda yapılandırılmıştır.

### Üretim Derlemesi Oluşturma
```bash
npm run build
```
Bu komut çalıştığında:
1. Next.js tüm sayfaları, 3B Three.js bileşenlerini ve stilleri tamamen statik HTML, JS ve CSS'e dönüştürür.
2. Derlenen dosyalar anında **`out/`** dizinine kopyalanır.
3. `out/` dizini sunucu bağımsız (Node.js gerektirmeyen) saf statik dosyalardan oluşur.

### `out/` Klasörünün İçeriği
```text
out/
├── index.html           # Ana uygulama
├── 404.html             # Bulunamadı sayfası
├── _next/               # Optimize edilmiş JS ve CSS paketleri
├── models/              # Tüm 3B .glb donanım modelleri
├── textures/            # Gezegen ve PBR malzeme dokuları
└── spacecraft/          # NASA arşiv fotoğrafları
```

### `out/` Klasörünü Yerel Olarak Test Etme
Derlenen statik siteyi test etmek için herhangi bir statik HTTP sunucusu kullanabilirsiniz:
```bash
npx serve out -l 5000
# veya Python ile:
cd out && python -m http.server 5000
```
Ardından tarayıcınızdan `http://localhost:5000` adresini açarak projenin çalıştığını doğrulayabilirsiniz.

---

## 🌐 GitHub / Vercel / Netlify Dağıtımı

### 1. GitHub Pages
* Projeyi GitHub deposuna gönderdikten sonra **Settings -> Pages** sekmesine gidin.
* Kaynak olarak **GitHub Actions** seçeneğini işaretleyin.
* Proje kök dizinindeki `.github/workflows/deploy.yml` dosyası sayesinde `main` dalına her `push` yapıldığında `out/` klasörü otomatik olarak derlenip yayına alınır.

### 2. Vercel
* Projeyi Vercel'e aktarmanız yeterlidir. `next.config.mjs` otomatik olarak algılanır.

### 3. Netlify / Cloudflare Pages
* Build command: `npm run build`
* Publish directory: `out`

---

## 🛠️ Kullanılan Teknolojiler / Tech Stack

* **Çatı:** [Next.js 16 (App Router)](https://nextjs.org/)
* **Görsel Kütüphane:** [React 19](https://react.dev/)
* **3B Grafik Motoru:** [Three.js](https://threejs.org/) & [@react-three/fiber](https://github.com/pmndrs/react-three-fiber) & [@react-three/drei](https://github.com/pmndrs/drei)
* **Stil & Tasarım:** [Tailwind CSS v4](https://tailwindcss.com/)
* **Animasyon:** [Framer Motion](https://www.framer.com/motion/)
* **İkonlar:** [Lucide React](https://lucide.dev/)
* **Ses Sentezi:** Web Audio API (Native Prosedürel)
* **Tip Güvenliği:** TypeScript 5.7

---

## 📜 Lisans & Teşekkür / License & Acknowledgements

* **Veri & Modeller:** NASA 3D Resources, NASA JPL Photojournal, NSSDCA Master Catalog.
* **Lisans:** MIT License. Eğitim ve açık kaynak uzay keşfi amaçlarıyla özgürce kullanılabilir.
