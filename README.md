# carcassonne-tr.github.io

Carcassonne Türkiye topluluğunun statik web sitesi. [Hugo](https://gohugo.io) + [PaperMod](https://github.com/adityatelange/hugo-PaperMod) teması ile oluşturulmuştur, GitHub Pages üzerinde ücretsiz barındırılır.

## Yerelde çalıştırma

```sh
hugo server -D
```

## İçerik ekleme/düzenleme

- Sabit sayfalar: `content/<sayfa>/_index.md`
- Yeni blog yazısı: `hugo new content blog/yazi-basligi.md`

## Yayınlama

`main` branch'e push edildiğinde `.github/workflows/hugo.yml` otomatik olarak siteyi derleyip GitHub Pages'e yayınlar.

## Yapılacaklar

- [x] `hugo.toml` içindeki Instagram ve e-posta linklerini güncelle
- [x] `content/iletisim/_index.md` içindeki placeholder linkleri güncelle
- [x] Favicon ekle (`static/` klasörüne)
- [x] Repo ayarlarından **Settings → Pages → Build and deployment → Source: GitHub Actions** seçeneğini aktif et
- [ ] Logo ekle

## Atıflar

- Favicon, [game-icons.net](https://game-icons.net/1x1/delapouite/meeple.html) üzerindeki "Meeple" ikonuna ([Delapouite](https://delapouite.com/), [CC BY 3.0](https://creativecommons.org/licenses/by/3.0/)) kırmızı-beyaz çizgi deseni uygulanarak türetilmiştir.
