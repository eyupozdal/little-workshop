# English

[Türkçe için](#türkçe)

A simple desktop app for tracking your projects, tasks, and project visuals all in one place.

## Features

- **Projects:** Add a title, description, due date, and size. Size is indicated by 1, 2, or 3 gears.
- **Tasks:** Add tasks to each project. Click to mark a task as complete; the progress percentage is calculated automatically.
- **Labels:** Add colored labels to projects (green, purple, orange, red, blue, pink, white, navy-purple). You can filter by label.
- **Sorting:** Sort by name, progress, due date, size, or order added.
- **Archive:** Move completed or on-hold projects to the archive. You can restore them from the archive at any time.
- **Project images:** Add, edit, and delete images for projects.

All data is stored on your computer. No information is sent over the internet.

## Installation

1. Download the latest version’s `.exe` file from the **Releases** section on the right.
2. Run the file. If Windows displays a “Protected by Windows” warning, select **More info → Run anyway**. This warning is caused by the application not being digitally signed.

No installation required; it is a single file.

## Development

Requirements: [Node.js](https://nodejs.org) (version 20 or higher)

```bash
npm install     # bağımlılıkları kur
npm start       # uygulamayı geliştirme modunda aç
npm run build   # dist klasöründe .exe üret
```
The user interface is in the `index.html` file, and the window settings are in the `main.js` file.
GitHub automatically generates the `.exe` file for Windows and adds it to the **Releases** page.



# Türkçe

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
GitHub, Windows için `.exe` dosyasını otomatik üretir ve **Releases** sayfasına ekler.
