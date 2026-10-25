<div align="center">

# 🌐 Nexora — 3B Teknoloji Sitesi

[![Live Website](https://img.shields.io/badge/Website-yusuftunga1.github.io/nexora--site-5CC8E8.svg?style=for-the-badge&logo=google-chrome&logoColor=white)](https://yusuftunga1.github.io/nexora-site/)
[![License: MIT](https://img.shields.io/badge/License-MIT-00ff88.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)](https://en.wikipedia.org/wiki/HTML5)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6.svg?style=for-the-badge&logo=css3&logoColor=white)](https://en.wikipedia.org/wiki/CSS)
[![JavaScript](https://img.shields.io/badge/Vanilla_JS-F7DF1E.svg?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Three.js](https://img.shields.io/badge/Three.js-r128-000000.svg?style=for-the-badge&logo=three.js&logoColor=white)](https://threejs.org)

[🚀 Canlı Siteyi Aç](https://yusuftunga1.github.io/nexora-site/) · [✨ Öne Çıkanlar](#-öne-çıkanlar) · [🛠️ Teknik](#️-teknik-özellikler) · [🔒 Güvenlik](#-güvenlik)

</div>

---

Yapay zekâ, bulut ve uç bilişimi tek platformda anlatan, 3B animasyonlu tek sayfalık teknoloji sitesi. Ziyaretçi kaydırdıkça kamera hero'daki düğümün içinden geçiyor ve sayfa bölüm bölüm açılıyor.

> **Nexora.** Gelecek çoktan kodlandı.

---

## 📦 Ne var burada?

Tek `index.html`. Çerçeve yok, derleme adımı yok, npm bağımlılığı yok.  
Dosyayı sunucuya kopyalamak siteyi yayına almak için yeterli.

---

## ✨ Öne Çıkanlar

- 🌀 **Kaydırmalı 3B Hero:** Sayfayı kaplayan parlak bir düğüm (torus knot). Hero ekranda sabit kalıyor, kaydırdıkça kamera düğümün içinden geçiyor ve Veri, Model, Uç bölümleri sırayla geliyor.
- 🔬 **Katman Perdesi:** Sürüklenen şerit, 3B çipin parlak görünümü ile mühendislik çizimi arasında geçiş yapıyor. Şerit fareyle, dokunmatikle ve klavyeyle kullanılabiliyor.
- 🧊 **Cam Panel:** Buzlu cam üzerinde büyük kelime yarı bulanık yarı net duruyor. Panel fareyle 3B eğiliyor, manzara farklı hızda kayarak derinlik veriyor.
- 🧭 **Adıma Özel 3B Sahneler:** Süreç bölümünde Keşfet için taranan küre, Tasarla için kurulan kafes, Dağıt için paketlerin aktığı ağ, Ölçekle için büyüyen çubuklar.
- 📱 **Mobil Uyumluluk:** Telefonda hero sabitlenmiyor, düzen ayrı bir kompozisyon olarak kuruluyor.
- ♿ **Erişilebilirlik:** İçeriğe atlama bağlantısı, klavye odağı, `prefers-reduced-motion` desteği ve WebGL yoksa 2B yedek.

---

## 🛠️ Teknik Özellikler

| Özellik | Değer |
|---|---|
| **Diller** | HTML, CSS, JavaScript (Vanilla / Çerçevesiz) |
| **3B** | Three.js r128 (WebGL) |
| **Derleme (Build)** | Yok (Doğrudan çalışır) |
| **Yazı Tipleri** | *Barlow Condensed*, *Barlow* |
| **Sayfa Boyutu** | ~65 KB (Three.js hariç) |

---

## 🔒 Güvenlik

- Three.js, **Subresource Integrity (SRI)** özetiyle yükleniyor; dosya değişirse tarayıcı çalıştırmıyor.
- `Content-Security-Policy` ile yalnızca cdnjs betikleri ve Google Fonts'a izin veriliyor.
- `referrer` bilgisi gönderilmiyor.
- Depoda API anahtarı, jeton ya da kişisel veri yok. Sayfadaki iletişim formu sunucuya veri göndermiyor, yalnızca ziyaretçinin e-posta uygulamasını açıyor.

---

## 🚀 Yerelde Çalıştırma

Sayfayı doğrudan tarayıcıda açabilir veya yerel bir statik sunucuyla çalıştırabilirsiniz:

```bash
# Python ile
python3 -m http.server 5173

# Veya Node ile
npx http-server . -p 5173 -c-1
```

Ardından tarayıcınızda `http://localhost:5173` adresine gidebilirsiniz. Three.js ve yazı tipleri internetten yüklenir.

---

## 📂 Klasör Yapısı

```
.
├── index.html              # Tüm sayfa, stiller ve betikler
├── LICENSE                 # MIT Açık Kaynak Lisansı
├── README.md               # Proje dokümantasyonu
└── .gitignore
```

---

## ⚠️ Örnek İçerik

Marka adı, rakamlar, ürün adları ve `merhaba@nexora.example` adresi örnektir. Yayına almadan önce kendi bilgilerinizle değiştirin.

---

## 🌌 Diğer Projeler

- ⚡ **[3d-portfolio](https://github.com/yusuftunga1/3d-portfolio)**: React 19, Three.js ve Tailwind CSS v4 ile geliştirilmiş etkileşimli 3D parçacık ve WebGL portfolyosu ([Canlı Demo](https://yusuftunga1.github.io/3d-portfolio/)).
- 🎬 **[portfolio-site](https://github.com/yusuftunga1/portfolio-site)**: Kaydırma ile açılan sinematik kişisel site ([Canlı Demo](https://yusuftunga1.github.io/portfolio-site/)).

---

## 📜 Lisans

Bu proje [MIT Lisansı](LICENSE) ile lisanslanmıştır.

---

<div align="center">

Crafted with 💙 by [**Yusuf Tunga**](https://github.com/yusuftunga1)

</div>
