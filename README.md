✨ Özellikler

🏪 Mağaza
🎯 300+ oyun kataloğu – GitHub CDN üzerinden otomatik senkronize
🖼️ Cinematic kartlar – Hover'da açılan detay popup (screenshot slideshow + blur arka plan)
🏷️ Akıllı rozetler – YENİ / ONLINE / MOD / 🇹🇷 Türkçe Dublaj etiketleri
🎲 Rastgele oyun seç – Filtreye göre cinematic animasyonlu seçim dialog'u
📁 Hiyerarşik kategoriler – Ana kategori / alt kategori yapısı (GTA Modları, Age of Empires vs.)
❤️ İstek listesi – Kalp ikonuyla favorileme + popup / tam sayfa görünüm
🔍 Anlık arama & filtreleme – Kategoriye, isme, tarihe göre sırala
🎨 Zoom slider – Kart boyutunu dinamik değiştir (150–300 px)

📚 Kütüphane
🎮 EXE otomatik takip – Drag & drop ile .exe sürükle, oyun otomatik eklensin
⏱️ Süre takibi – Her oyun için oynama süresi (dakika hassasiyeti)
🏆 Bitirilen oyunlar – Tamamlama tarihi + kutlama animasyonu
📂 Koleksiyonlar – Kendi kategorilerini oluştur (Favoriler, RPG, Bitirdiklerim vb.)
🎨 3 farklı görünüm – Grid / Liste / Detay
💾 Save yedekleme – Oyun kapanınca otomatik save yedeği (tekli veya tarihli çoklu)
🎯 Steam/Epic/UPlay desteği – Kısayol (.url/.lnk) ile launcher oyunları takip
🔐 Yönetici izinli oyunlar – UAC ile otomatik yükseltme (GTA V vb.)
📜 Betik sistemi – Oyun başında/sonunda .exe çalıştır (mod yöneticisi, RPCS3 vb.)
🎬 Cinematic rastgele oyun – Kapak + screenshot + daktilo açıklama efekti

📥 İndirme Sistemi
🧲 Torrent + HTTP – Magnet, .torrent dosyası, doğrudan link
📊 Kuyruk yönetimi – Aynı anda 1–10 indirme (ayardan seçilebilir)
⏸️ Duraklat / Devam – Kaldığın yerden devam
⚡ Hız limiti – Global veya indirmeye özel (KB/s)
🚀 100+ tracker – Otomatik yönetim, torrent'te maksimum hız optimizasyonu
📁 Google Drive / MediaFire / GoFile – Cloud servislerinden doğrudan indirme
🔄 Windows sağ tık – .torrent dosyalarına çift tık = Game Launcher'da aç
📊 Taskbar progress – Chrome tarzı görev çubuğunda yüzde göstergesi

📱 Uygulamalar
🛠️ Faydalı programlar – Winrar, DirectX, VC Redist gibi araçlar tek yerde
🎨 Ekran görüntüleri – Her uygulamanın detaylı sayfası
📊 İstatistikler
⏱️ Toplam oynama süresi
🏆 Bitirilen oyun sayısı ve listesi
📅 Aktivite grafiği – Günlük/haftalık oynama analizi
🎯 En çok oynanan oyunlar sıralaması

⚙️ Ayarlar
🎨 Frameless pencere – Custom title bar, native Windows davranışı
💾 Otomatik yedekleme – 7 günde bir tüm veri yedeklenir
🚀 Windows başlangıcı – Otomatik açılma (görev çubuğu / tray)
🔔 Bildirimler – Toast bildirim sistemi (7 farklı ses efekti)
📁 Save yedekleme yönetimi – Klasör seç, mod seç, maksimum yedek sayısı
🎮 Oyun başlatma davranışı – Küçült / tray'e in / kapat
🎯 Oyun bittiğinde – Pencereyi geri al veya simge durumunda bırak
⚙️ Performans ayarları – Cache limiti, otomatik temizleme

🔥 Öne Çıkan Özellikler
🌐 GitHub CDN entegrasyonu – Sürekli güncellenen oyun kataloğu
🎯 RAWG API – Otomatik oyun bilgisi çekme (kapak, screenshot, açıklama)
🖼️ SteamGridDB API – Yüksek kaliteli kapak resimleri
⏰ HowLongToBeat – Otomatik bitirme süresi tahmini
📊 FPS Tahmini – PC'ndeki donanıma göre oyunun kaç FPS çalışacağını hesaplar (300+ GPU / 200+ CPU veritabanı)
🎨 Splash screen – Animasyonlu açılış (gamepad + orbit spinner + progress bar)
🔐 Admin sistemi – HMAC + machine ID tabanlı yetkilendirme
🎯 Tek instance – İkinci açılışta mevcut pencereyi öne getirir
📌 JumpList – Windows sağ tık menüsünde Mağaza / Kütüphane / Ayarlar kısayolları
🖱️ Sistem tepsisi – Son oynanan oyunlara hızlı erişim
💬 Toast bildirimleri – Modern, native olmayan bildirimler
🎮 Oyun kısayolu oluşturma – Masaüstünde kısayol → çift tık = oyun başlat
🌍 Türkçe arayüz – Tam Türkçe (tarih formatları dahil)
🎨 6 tema motoru – Genişletilebilir tema sistemi
🎭 Cinematic animasyonlar – Kapak, blur, daktilo, göz kırpma, kalp bounce, orbit spinner

🐛 Kullanıcı Katkısı
🐞 Bug bildirimi – Uygulamadan doğrudan hata bildir
📝 Oyun isteği – Katalogda olmayan oyunları talep et
💬 Yorum sistemi – Her oyunun kendi yorum bölümü

🛠️ Teknik Detaylar
Framework: PyQt6
Torrent: libtorrent
Backend: GitHub API (CDN) + Supabase (fallback)
Windows API: ctypes, DWM (dark title bar)
Async loading: Multithreading (4 worker image loader)
Cache sistem: LOCALAPPDATA disk cache
File association: Windows registry (.torrent handler)

📥 Kurulum
En son sürümü indir
GameLauncher.exe dosyasına çift tık
İlk açılışta mağaza otomatik senkronize olur (~30 saniye)

🎯 Sistem Gereksinimleri
Windows 10 / 11 (64-bit)
4 GB RAM
500 MB disk alanı (uygulama için)
İnternet bağlantısı (mağaza senkronizasyonu için)

Not: Bu proje kişisel kullanım için geliştirilmiştir. Ticari amaç taşımaz.
