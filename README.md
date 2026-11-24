# Little Workshop

Projelerini, görevlerini ve proje görsellerini tek bir yerden takip etmek için basit bir masaüstü uygulaması.

## Özellikler

- **Projeler:** Başlık, açıklama, son tarih ve büyüklük ekle. Büyüklük 1, 2 veya 3 çarkla gösterilir.
- **Görevler:** Her projeye görev ekle. Görevi tamamlamak için tıkla, ilerleme yüzdesi otomatik hesaplanır.
- **Etiketler:** Projelere renkli etiketler ekle (yeşil, mor, turuncu, kırmızı, mavi, pembe, beyaz, lacivert-mor). Etikete göre filtreleyebilirsin.
- **Sıralama:** Ada, ilerlemeye, son tarihe, büyüklüğe veya eklenme sırasına göre sırala.
- **Arşiv:** Bitmiş ya da beklemedeki projeleri arşive taşı. Arşivden istediğin zaman geri çıkarabilirsin.
- **Proje görselleri:** Projelere görsel ekle, düzenle ve sil.

Tüm veriler bilgisayarında saklanır. Hiçbir bilgi internete gönderilmez.

## Kurulum

1. Sağdaki **Releases** bölümünden en son sürümün `.exe` dosyasını indir.
2. Dosyayı çalıştır. Windows "Windows tarafından korunuyor" uyarısı verirse **Ek bilgi → Yine de çalıştır** seçeneğini kullan. Uyarı, uygulamanın dijital olarak imzalanmamış olmasından kaynaklanır.

Kurulum gerektirmez, tek dosyadır.

## Geliştirme

Gereksinimler: [Node.js](https://nodejs.org) (sürüm 20 veya üzeri)

```bash
npm install     # bağımlılıkları kur
npm start       # uygulamayı geliştirme modunda aç
npm run build   # dist klasöründe .exe üret
```

Arayüz `index.html` dosyasında, pencere ayarları `main.js` dosyasında.

## Sürüm yayınlama

1. `package.json` içindeki `version` değerini artır (örneğin `1.2.0`).
2. Değişiklikleri gönder ve aynı sürüm numarasıyla bir etiket (tag) oluştur:

```bash
git add .
git commit -m "Yeni özellikler"
git push
git tag v1.2.0
git push origin v1.2.0
```

GitHub, Windows için `.exe` dosyasını otomatik üretir ve **Releases** sayfasına ekler.

## Lisans

Bu proje [MIT Lisansı](LICENSE) ile lisanslanmıştır.
