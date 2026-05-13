# Sistem Sağlık Merkezi

Windows için tek dosya, kurulumsuz **donanım & sistem sağlık tarayıcısı**. Bilgisayarınızın bileşenlerini (CPU, RAM, Disk, Ekran Kartı, Monitör, Ağ vb.) tek tek inceleyip toplam bir **sağlık skoru** üretir.

## Özellikler

- **0–100 sağlık skoru** — bilgisayarın genel durumu tek bakışta
- **Bileşen kartları** — İşlemci, Bellek, Disk, Ekran Kartı, Monitör, Ağ, PC, Sistem
- **Anlık metrikler** — Çalışma süresi, işlem sayısı, ağ hızı
- **Otomatik tarama (60s)** — istersen sürekli çalışan izleme modu
- **Envanter çıkarma** — donanım envanterini tek tıkla
- **Tek dosya, kurulumsuz** — sadece çift tıkla, çalış
- **WMI tabanlı** — Windows'un native donanım API'lerini kullanır

## Görsel

![Sistem Sağlık Merkezi - Genel Bakış](screenshots/01-genel-bakis.png)

## Kurulum

Yok. Sadece:

1. [Releases](https://github.com/ctrismail/sistem-saglik-merkezi/releases) sayfasından `Sistem-Saglik-Merkezi.exe` indir.
2. Çift tıkla.

Windows SmartScreen uyarısı çıkarsa: **Daha fazla bilgi → Yine de çalıştır**. Uygulama imzasız (sertifika maliyeti) ama açık kaynaktır.

## Sistem Gereksinimleri

- Windows 10 / 11 (x64)
- ~7 MB RAM
- Yönetici izni gerekmez (donanım okuma için sadece WMI)

## Teknik

- **Dil:** Python 3.13
- **GUI Framework:** modern dark dashboard
- **Sistem erişimi:** WMI (Windows Management Instrumentation) + pywin32
- **Paketleme:** PyInstaller (tek `.exe`)
- **Boyut:** ~16 MB

## Geliştirici

İsmail Hakkı ÇITIR — Bilgisayar Mühendisi
🌐 [ctrbilisim.com.tr](https://ctrbilisim.com.tr) · [GitHub](https://github.com/ctrismail) · [LinkedIn](https://linkedin.com/in/ctrismail)

## Lisans

MIT — bkz. [LICENSE](LICENSE)
