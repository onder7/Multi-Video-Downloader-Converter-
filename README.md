# Multi-Downloader & Converter — Portable Edition

> **Sürüm:** v1.0.0

---

## Türkçe (TR)

### Tanıtım

Multi-Downloader & Converter, 12 farklı platformdan video indirmenizi ve YouTube videolarını MP3'e dönüştürmenizi sağlayan taşınabilir (portable) bir masaüstü uygulamasıdır. Basit, modern ve kullanıcı dostu bir arayüze sahiptir.

### Desteklenen Platformlar

* YouTube
* Instagram
* Facebook
* Twitter / X
* TikTok
* Vimeo
* LinkedIn
* SoundCloud
* Dailymotion
* Twitch
* Bandcamp
* VK

### Özellikler

* 12 farklı platformdan video indirme
* YouTube videolarını MP3'e dönüştürme (FFmpeg ile)
* Kalite seçimi (ör. 720p, 1080p, 4K)
* MP3 bitrate seçimi (128, 192, 256, 320 kbps)
* Çoklu indirme kuyruğu
* Gerçek zamanlı ilerleme takibi
* Masaüstü bildirimleri
* Karanlık/Aydınlık tema desteği
* Modern ve kullanıcı dostu arayüz

### Hızlı Başlangıç

1. `Multi-Downloader-Converter.exe` dosyasını çalıştırın.
2. İlk çalıştırmada `yt-dlp` otomatik olarak indirilecektir (~10 MB).
3. Video URL'sini yapıştırın.
4. Kalite ve/veya bitrate seçin.
5. "Start Download" veya "Convert to MP3" butonuna tıklayın.

> Not: Kalite seçimini 30 saniye içinde yapmazsanız en yüksek kalite otomatik seçilir.

### Sistem Gereksinimleri

* Windows 10/11 (64-bit)
* 4 GB RAM (önerilen)
* 500 MB boş disk alanı
* İnternet bağlantısı

### Kullanım

**Video İndirme**

1. "Download" sekmesine gidin.
2. Video URL'sini yapıştırın.
3. Video bilgileri yüklenecek; kalite seçin.
4. "Start Download" ile indirmeyi başlatın.

**MP3 Dönüştürme (YouTube için)**

1. "Convert to MP3" sekmesine gidin.
2. YouTube video URL'sini yapıştırın.
3. Bitrate seçin (varsayılan 320 kbps).
4. "Convert to MP3" butonuna tıklayın.

**Ayarlar**

* İndirme klasörünü değiştirin (varsayılan: İndirilenler / `MDC Downloads`).
* Eşzamanlı indirme sayısını ayarlayın (1–5).
* Bildirim tercihlerini yapılandırın.

**Kuyruk Yönetimi**

* "Queue" sekmesinde tüm işlemleri izleyin.
* İşlemleri iptal edebilir, yeniden deneyebilir veya kaldırabilirsiniz.
* Tamamlananları "Clear Completed" ile temizleyin.

### Sorun Giderme

* **"yt-dlp bulunamadı"** → Uygulamayı yeniden başlatın; `yt-dlp` otomatik indirilecektir.
* **Video indirme başarısız** → URL, internet bağlantısı veya kaliteyi kontrol edin; uygulamayı yeniden başlatın.
* **"Geçersiz yol"** → Ayarlardan geçerli bir klasör seçin ve yazma izinlerini kontrol edin.
* **Uygulama açılmıyor** → Antivirus / Windows Defender kontrolü; yönetici olarak çalıştırmayı deneyin; `%APPDATA%\multi-downloader-converter` klasörünü silip yeniden deneyin.
* **İndirme çok yavaş** → İnternet bağlantısını kontrol edin; eşzamanlı indirme sayısını azaltın; daha düşük kalite seçin.

### Geliştirici / Teknik Bilgiler

* Framework: Electron
* İndirme aracı: `yt-dlp` (otomatik indirilir)
* Dönüştürme: `FFmpeg`
* Teknolojiler: HTML5, CSS3, JavaScript
* Taşınabilir (portable) yürütülebilir dosya

### Katkıda Bulunma

Katkılarınız için teşekkürler! Hataları bildirmek veya özellik önermek için GitHub issues bölümünü kullanın.

### Lisans

MIT License — Ücretsiz ve açık kaynak.

### Gizlilik

* Uygulama kişisel veri toplamaz.
* İndirme geçmişi yalnızca yerel olarak saklanır.
* İnternet bağlantısı yalnızca video indirme için kullanılır.

---

## English (EN)

### Introduction

Multi-Downloader & Converter is a portable desktop application that lets you download videos from 12 different platforms and convert YouTube videos to MP3. It features a modern, user-friendly interface.

### Supported Platforms

* YouTube
* Instagram
* Facebook
* Twitter / X
* TikTok
* Vimeo
* LinkedIn
* SoundCloud
* Dailymotion
* Twitch
* Bandcamp
* VK

### Features

* Download videos from 12 platforms
* Convert YouTube videos to MP3 (using FFmpeg)
* Quality selection (e.g., 720p, 1080p, 4K)
* MP3 bitrate selection (128, 192, 256, 320 kbps)
* Multi-download queue
* Real-time progress tracking
* Desktop notifications
* Dark/Light theme support
* Clean and modern UI

### Quick Start

1. Run `Multi-Downloader-Converter.exe`.
2. On first run, `yt-dlp` will be downloaded automatically (~10 MB).
3. Paste the video URL.
4. Select quality and/or bitrate.
5. Click **Start Download** or **Convert to MP3**.

> Note: If you don't choose a quality within 30 seconds, the highest available quality will be selected automatically.

### System Requirements

* Windows 10/11 (64-bit)
* 4 GB RAM (recommended)
* 500 MB free disk space
* Internet connection

### Usage

**Downloading Videos**

1. Go to the **Download** tab.
2. Paste the video URL.
3. Video info will load; choose a quality.
4. Click **Start Download** to begin.

**MP3 Conversion (YouTube only)**

1. Go to the **Convert to MP3** tab.
2. Paste the YouTube URL.
3. Select bitrate (default 320 kbps).
4. Click **Convert to MP3**.

**Settings**

* Change the download folder (default: Downloads / `MDC Downloads`).
* Set concurrent downloads (1–5).
* Configure notification preferences.

**Queue Management**

* View all active downloads and conversions in the **Queue** tab.
* Cancel, retry, or remove tasks.
* Clear completed tasks with **Clear Completed**.

### Troubleshooting

* **"yt-dlp not found"** → Restart the app; `yt-dlp` will be downloaded automatically.
* **Download failed** → Check URL, internet connection, or try a different quality; restart the app.
* **"Invalid path"** → Choose a valid download folder in Settings and ensure write permissions.
* **App won't open** → Check antivirus/Windows Defender; try running as administrator; remove `%APPDATA%\\multi-downloader-converter` and retry.
* **Slow downloads** → Check your internet; reduce concurrent downloads; choose a lower quality.

### Developer / Technical Info

* Framework: Electron
* Downloader: `yt-dlp` (auto-downloaded)
* Conversion: `FFmpeg`
* Built with: HTML5, CSS3, JavaScript
* Portable executable

### Contributing

Thanks for contributions! Please report bugs or feature requests via GitHub Issues.

### License

MIT License — Free and open source.

### Privacy

* The app does not collect personal data.
* Download history is stored locally only.
* Internet access is used only for downloading videos.

---

> **Enjoy! / İyi kullanımlar!**
