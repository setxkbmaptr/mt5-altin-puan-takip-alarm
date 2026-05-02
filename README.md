# 📈 MT5 Altın (XAU/USD) Puan Farkı Takip ve Alarm Sistemi

MetaTrader 5 terminalinden gerçek zamanlı Altın (XAU/USD) verilerini çekerek anlık puan / kapanış pip takibi yapan ve kullanıcının belirlediği özel seviyelerde bildirim gönderen Windows masaüstü uygulaması.

---

## 📖 Proje Hakkında

Bu proje, XAU/USD paritesindeki fiyat hareketlerini anlık ve hassas bir şekilde takip etmesi gereken trader'lar için geliştirilmiştir. MetaTrader 5 terminaline doğrudan bağlanarak gecikmesiz veri alır. Kullanıcının belirlediği puan eşikleri aşıldığında veya kritik seviyelere ulaşıldığında Windows bildirimleri (sesli ve görsel) aracılığıyla uyarı verir.

---

## 🖼️ Uygulama Görselleri

![Uygulama Ana Ekranı](https://img.lightshot.app/isBYnxPyQGyfLFVvTGFN_A.png)
---
![Uygulama Ana Ekranı](https://img.lightshot.app/clM2spLAT7WLx4LR4jkEYw.png)
---
![Uygulama Ana Ekranı](https://img.lightshot.app/ky31YxLASV6J3L0sFjStpw.png)
---

## ✨ Temel Özellikler

* **Gerçek Zamanlı Veri Entegrasyonu:** MT5 Python API kullanılarak yerel terminalden anlık close tick verisi çekimi.
* **Dinamik Puan Takibi:** Belirlenen referans fiyat ile anlık fiyat arasındaki puan/pip farkının canlı hesaplanması.
* **Özelleştirilebilir Alarm Sistemi:** Alt ve üst fiyat sınırları veya puan farkları için özel alarmlar kurabilme.
* **Kullanıcı Dostu Arayüz:** Masaüstü kullanımı için Electron ile tasarlanmış modern, hızlı ve duyarlı GUI.

## 🛠️ Kullanılan Teknolojiler

* **Programlama Dili:** Python & JavaScrit = Electron.
* **Veri Entegrasyonu:** `MetaTrader5` kütüphanesi.
* **Çalışma Mantığı:** RAM bellek üzerinde çalışır.

## 🚀 Kurulum ve Çalıştırma

### Gereksinimler
* Windows 10 Üzeri İşletim Sistemi
* Cihazda kurulu ve hesaba giriş yapılmış **MetaTrader 5** terminali ( Demo hesaplar geçerlidir. )
* Python 3.x +

### Adımlar
