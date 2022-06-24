# Scss Boilerplate

[SCSS](https://sass-lang.com/) için 7+1 dosya yapısı.

## Kurulum

### Dosyaları indirmek için

Terminal kullanarak kolaylıkla indirebilirsiniz

```bash
  git clone https://github.com/drementer/scss-boilerplate.git
```

### Gerekli modul'lerin kurulumu

Gerekli moduller 'package.json' dosyasında zaten tanımlı olduğu için sadece bu satır kurulum için yeterli

```bash
  npm i
```

veya

```bash
  npm i sass
```

### Kullanım

Sass dosyaları ile projenizi geliştirdiğiniz sırada kullanmanız gerek komut

```bash
  npm run watch
```

veya

```bash
  npx sass --watch scss/main.scss css/main.min.css --style expanded --error-css
```

Sass dosyalarıyla olan geliştirme süreciniz bittiğinde yayın için kullanılacak komut

```bash
  npm run build
```

veya

```bash
  npx sass scss/main.scss css/main.min.css --style compressed --no-error-css
```

## Dosyalama

```txt
scss/
|
|– base/                 # Projenin temel dosyaları
|   |– _all.scss         # Klasördeki tüm dosyaların toplandığı dosya
|   |– _reset.scss       # Reset
|   |– _typography.scss  # Tipografi
|   ...                  # Vesayre
|
|– components/           # Projenin 'component' dosyaları
|   |– _all.scss         # Klasördeki tüm dosyaların toplandığı dosya
|   |– _buttons.scss     # Butonlar
|   |– _carousel.scss    # Carousel
|   ...                  # Vesayre
|
|– layouts/              # Projenin yerleşim şemaları
|   |– _all.scss         # Klasördeki tüm dosyaların toplandığı dosya
|   |– _footer.scss      # Footer
|   |– _header.scss      # Header
|   ...                  # Vesayre
|
|– pages/                # Sayfaya özel stiller
|   |– _all.scss         # Klasördeki tüm dosyaların toplandığı dosya
|   |– _contact.scss     # Contact sayfasına özel stiller
|   |– _home.scss        # Ana sayfaya özel stiller
|   ...                  # Vesayre
|
|– themes/               # Temaya özel stiller
|   |– _all.scss         # Klasördeki tüm dosyaların toplandığı dosya
|   |– _dark.scss      	 # Karanlık tema
|   |– _default.scss     # Varsayılan tema
|   ...                  # Vesayre
|
|– utils/                # Ayarlar & araçlar
|   |– _all.scss         # Klasördeki tüm dosyaların toplandığı dosya
|   |– _variables.scss   # Scss değerleri
|   |– _mixins.scss      # Scss mixinleri
|   |– _functions.scss   # Scss fonksiyonları
|   ...                  # Vesayre
|
|– vendors/              # Dışardan alınan hazır şeyler
|   |– _all.scss         # Klasördeki tüm dosyaların toplandığı dosya
|   |– _bootstrap.scss   # Bootstrap kütüphanesi
|   |– _jquery-ui.scss   # jQuery UI kütüphanesi
|   ...                  # Vesayre
|
`– main.scss             # Ana Scss dosyası
                         # Tüm alt klasörlerdeki '_all.scss' dosyalarının toplandığı dosya
```

## Fikir Kaynağı

[sass-boilerplate](https://github.com/KittyGiraudel/sass-boilerplate)
