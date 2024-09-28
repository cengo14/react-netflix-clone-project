# React Netflix Clone

Bu proje, TMDB API'si kullanarak film ve dizi verilerini çeken ve kullanıcıların bu içerikleri görüntülemesini sağlayan dinamik bir Netflix klonudur. Proje, **React Redux**, **Redux Thunk**, **React Router DOM**, **Axios**, **React Icons**, **Splide** ve **Tailwind CSS** gibi kütüphaneler kullanılarak geliştirilmiştir. Ayrıca, kullanıcılar favori filmleri listeye ekleyip çıkarabilir ve favori listesini görüntüleyebilir.

## Demo

*Ana Sayfa - Öne çıkan içerikler, kategoriler ve slayt gösterisi*

*Film/Dizi Detay Sayfası - İçerik bilgisi ve önerilenler*

*Favori Listesi - Kullanıcı tarafından favorilere eklenen filmler ve diziler*

## Özellikler

- **Redux ve Redux Thunk** ile global state yönetimi
- **TMDB API** kullanarak dinamik içerik getirme
- Çok sayfalı yapı: Ana sayfa, film/dizi detay sayfası, favori listesi
- **Axios** ile API istekleri
- **React Router DOM** ile sayfalar arası geçiş
- **React Icons** ile ikon desteği
- **Splide** kullanılarak içeriklerin kaydırılabilir şekilde gösterimi
- **Tailwind CSS** ile modern ve esnek bir tasarım
- **Favorilere ekleme ve çıkarma** özelliği
- **Favori Listesi Görüntüleme**: Kullanıcılar favorilerine ekledikleri filmleri/dizileri listeleyebilir
- Mobil uyumlu ve responsive tasarım

## Kurulum

Projeyi yerel ortamınıza kurmak için aşağıdaki adımları takip edebilirsiniz.

### Gereksinimler

- Node.js (v14.0.0 veya üstü)
- NPM veya Yarn

### Adımlar

1. Bu repository'i klonlayın:

   ```bash
   git clone https://github.com/cengo14/react-netflix-clone-project.git
   cd react-netflix-clone-project
   ```

2. Gerekli bağımlılıkları yükleyin:

   ```bash
   npm install
   # veya
   yarn install
   ```


3. Projeyi başlatın:

   ```bash
   npm run dev
   ```

4. Tarayıcınızda `http://localhost:XXXX` adresini ziyaret edin.

## Kullanılan Teknolojiler

- **React** - Kullanıcı arayüzünü oluşturmak için
- **Redux & Redux Thunk** - State yönetimi ve asenkron işlemler
- **Axios** - HTTP istekleri yapmak için
- **React Router DOM** - Sayfalar arası yönlendirme
- **React Icons** - UI'da kullanılan ikonlar
- **Splide** - İçerik kaydırma (slider) işlevi için
- **Tailwind CSS** - Responsive ve modern bir stil çerçevesi
- **TMDB API** - Film ve dizi verileri sağlamak için

## Özellikler Detayları

### Favorilere Ekleme/Çıkarma

Kullanıcılar bir film veya diziyi favorilerine ekleyebilir ve favori listesinden çıkarabilir. Bu işlem, **Redux** store'da takip edilir ve favori listesi sayfasından bu içerikler görüntülenebilir.

1. **Favorilere Ekleme**: Film/dizi detay sayfasındaki favori butonuna tıklayarak içerik favorilere eklenir.
2. **Favori Listesi**: Favori listesi sayfasında tüm favorilere eklenen içerikler listelenir.
3. **Favoriden Çıkarma**: Favori listesinde yer alan içerikler, bir butona tıklanarak favorilerden çıkarılabilir.


*Detay Sayfası - Favorilere ekleme butonu*

### Ekran Görüntüleri

### Ana Sayfa
![Ana Sayfa](desktop.gif)


## Proje Yapısı

```
├── public/
│   └── ...
├── src/
│   ├── components/      # React bileşenleri
│   ├── redux/             # Redux store, aksiyonlar ve reducer'lar
│   ├── pages/          # Sayfa bileşenleri
│   ├── utils/         # Yardımcı dosyalar
│   ├── index.css          # Stillendirme dosyası
│   ├── App.jsx          # Ana bileşen
│   ├── main.jsx        # Giriş noktası
│   └── ...
├── index.html
├── .env                 # Çevresel değişkenler
├── package.json         # Proje bağımlılıkları
└── README.md            # Proje belgeleri
```

## API

Bu proje, [TMDB API](https://www.themoviedb.org/documentation/api)'sini kullanmaktadır. API istekleri Axios aracılığıyla yapılır ve veriler Redux store'da saklanır.

## Gelecekteki Geliştirmeler

- **Kullanıcı Kimlik Doğrulama**: Firebase veya JWT ile kullanıcı girişi ve favori içerik ekleme.
- **Daha Fazla Sayfa**: Kullanıcı profili, arama sonuçları sayfası.
- **Yüksek Performans Optimizasyonu**: Lazy loading ve React memo kullanımı.

## Katkıda Bulunma

Projeye katkıda bulunmak isterseniz, lütfen bir **pull request** oluşturun. Geri bildirimleriniz ve önerileriniz değerlidir!

## Lisans

Bu proje MIT lisansı altında lisanslanmıştır.

---
