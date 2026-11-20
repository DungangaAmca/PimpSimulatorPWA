# Pimp Simulator — PWA Yayın Paketi

Bu ZIP arşivi, **Pimp Simulator** oyununu tarayıcıda Web App / PWA (Progressive Web App) olarak yayınlamak için gerekli dosyaları ve eklediğiniz görselden üretilmiş uygulama ikonlarını içerir.

## Paket İçeriği
- `index.html`: PWA bağlantıları (`manifest.json`, ikonlar ve `sw.js` kaydı) entegre edilmiş oyun dosyası.
- `manifest.json`: PWA uygulama kimliği, görünüm (`standalone`), tema renkleri ve ikon tanımları.
- `sw.js`: Temel önbellekleme (`cache`) ve çevrimdışı yedekleme sağlayan Service Worker.
- `icon-192.png`: `192x192` boyutunda uygulama ikonu.
- `icon-512.png`: `512x512` boyutunda uygulama ikonu.
- `icon.jpg`: `512x512` kırpılmış kare ikon görseli.

## GitHub Pages ile Yayınlama
1. GitHub'da yeni bir depo (`repository`) oluşturun.
2. ZIP içindeki dosyaları deponun kök dizinine yükleyin.
3. **Settings -> Pages** menüsünden `main` dalını ve `/ (root)` klasörünü seçip kaydedin.
4. Yayınlanan HTTPS adresinden tarayıcı üzerinden oyunu açın veya "Uygulamayı yükle" seçeneğini kullanın.
