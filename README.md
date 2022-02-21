# Scss 7+1 Pattern

[SCSS](https://sass-lang.com/) için 7+1 dosya yapısı.

## Hızlı Başlangıç

Terminal kullanarak indir

```bash
  git clone https://github.com/drementer/Scss-7-1-Pattern.git
```

## Dosyalama

```txt
sass/
|
|– base/
|   |– _reset.scss       # Reset
|   |– _typography.scss  # Tipografi
|   ...                  # Vesayre
|
|– components/
|   |– _buttons.scss     # Butonlar
|   |– _carousel.scss    # Carousel
|   ...                  # Vesayre
|
|– layouts/
|   |– _header.scss      # Header
|   |– _footer.scss      # Footer
|   ...                  # Vesayre
|
|– pages/
|   |– _home.scss        # Ana sayfaya özel stiller
|   |– _contact.scss     # Contact sayfasına özel stiller
|   ...                  # Vesayre
|
|– themes/
|   |– _default.scss     # Varsayılan tema
|   |– _dark.scss      	 # Karanlık tema
|   ...                  # Vesayre
|
|– utils/
|   |– _variables.scss   # Scss değerleri
|   |– _functions.scss   # Scss fonksiyonları
|   |– _mixins.scss      # Scss mixinleri
|
|– vendors/
|   |– _bootstrap.scss   # Bootstrap
|   |– _jquery-ui.scss   # jQuery UI
|   ...                  # Vesayre
|
|
`– main.scss             # Ana Scss dosyası
```