# 🌐 GitHub Pages Deployment Demo
### (GitHub Pages ile Web Yayına Alma ve Demo Sistemi)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)](#)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)](#)
[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-222222?style=flat&logo=github&logoColor=white)](#)

Bu proje, bir web sitesinin GitHub Pages kullanılarak nasıl yayına alınacağını gösteren, yapılandırma ve deployment süreçlerini içeren bir demo çalışmasıdır.

## 📚 İçindekiler
- [Proje Hakkında](#proje-hakkında)
- [Özellikler](#özellikler)
- [Kullanılan Teknolojiler](#kullanılan-teknolojiler)
- [Kurulum ve Kullanım](#kurulum-ve-kullanım)
- [Proje Yapısı](#proje-yapısı)
- [Geliştirme Süreci](#geliştirme-süreci)
- [Katkıda Bulunma](#katkıda-bulunma)
- [İletişim](#iletişim)
- [Lisans](#lisans)

---

## Proje Hakkında
Bu çalışma, statik web içeriklerinin GitHub altyapısı üzerinde ücretsiz ve hızlı bir şekilde barındırılmasını (hosting) deneyimlemek amacıyla oluşturulmuştur. CI/CD (Continuous Integration/Continuous Deployment) süreçlerinin temel bir örneğini sunar.

* **Geliştirici:** Haluk Can SARIÖZ
* **Tür:** Web Deployment Demo
* **Canlı Demo:** [https://halukcansarioz.github.io/gh-pages-demo](https://halukcansarioz.github.io/gh-pages-demo)

---

## Özellikler
* **Otomatik Yayınlama:** Ana dala (main branch) yapılan push işlemlerinin otomatik olarak yayına alınması.
* **Responsive Tasarım:** Mobil, tablet ve masaüstü cihazlarla tam uyumlu arayüz.
* **Hızlı Yükleme:** Statik dosya optimizasyonu ile yüksek performans.
* **Özel Domain Desteği:** GitHub Pages üzerinden özel alan adı (custom domain) yapılandırma örneği.

---

## Kullanılan Teknolojiler
* **HTML5:** Sayfa yapısı ve semantik içerik.
* **CSS3:** Görsel tasarım ve animasyonlar.
* **GitHub Actions:** Otomatik dağıtım (deployment) iş akışları.
* **Git:** Versiyon kontrolü.

---

## Kurulum ve Kullanım

### 1. Depoyu Klonlayın
```bash
git clone https://github.com/halukcansarioz/gh-pages-demo.git
```

### 2. Proje Dizinine Gidin
```bash
cd gh-pages-demo
```

### 3. Bağımlılıkları Yükleyin
*(Not: Statik bir proje olduğu için genellikle paket yüklemesi gerekmez, ancak varsa npm paketlerini yükleyin)*
```bash
npm install
```

### 4. Uygulamayı Başlatın
Yerel sunucuda görüntülemek için:
```bash
# Eğer bir live server kullanıyorsanız
# (Örn: VS Code Live Server veya basit bir http-server)
npx http-server .
```

---

## Proje Yapısı
```text
gh-pages-demo/
├── .github/
│   └── workflows/      # GitHub Actions deployment ayarları
├── assets/             # Resimler, ikonlar ve fontlar
├── css/                # Stil dosyaları
├── js/                 # Script dosyaları
├── index.html          # Ana sayfa
└── README.md           # Proje dökümantasyonu
```

---

## Geliştirme Süreci

### 1. Forklama
Projeyi kendi hesabınıza kopyalayıp kendi GitHub Pages ayarlarınızla denemeler yapabilirsiniz.

### 2. Yeni Dal (Branch) Oluşturma
```bash
git checkout -b ozellik/yeni-tasarim
```

### 3. Kodları Gönderme (Push)
```bash
git push origin ozellik/yeni-tasarim
```

---

## Katkıda Bulunma
1. Bu depoyu **Fork**'layın.
2. Bir **Branch** oluşturun (`git checkout -b feature/YeniOzellik`).
3. Değişikliklerinizi yapın ve **Commit** edin (`git commit -m 'Ekleme: Yeni özellik'`).
4. Kodlarınızı **Push**'layın (`git push origin feature/YeniOzellik`).
5. Bir **Pull Request** açın.

---

## İletişim
**Haluk Can Sarıöz** - [GitHub Profilim](https://github.com/halukcansarioz)  
**Proje Linki:** [https://github.com/halukcansarioz/gh-pages-demo](https://github.com/halukcansarioz/gh-pages-demo)

---

## Lisans
Bu proje [MIT Lisansı](LICENSE) ile lisanslanmıştır.
```
