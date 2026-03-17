# 🛒 Trendyol Yorum Entegrasyonu

> Trendyol Yemek platformundan döner, pizza gibi spesifik kategoriler altındaki işletmelerin müşteri yorumlarını dinamik olarak elde eden veri kazıma botları.

## ⚙️ Teknik Altyapı
- **Kütüphaneler**: `Selenium`, `BeautifulSoup` (varsa), `Pandas`
- **İşlem Tipi**: Dinamik DOM manipülasyonu ve sonsuz kaydırma (infinite scrolling) mekanizmalarını aşacak şekilde yapılandırılmış asenkron veri çekme.

## 📁 Ana Dosyalar Kullanımı
- **`trendyol_doner_yorumlar_selenium.py`**: Ağırlıklı olarak döner satışı yapan restoranlara spesifik hedefleme botu.
- **`trendyol_pizza_yorumlar.py`**: Pizza kategorisi için geliştirilmiş yorum toplama botu.
- **Çıktılar (`.csv`)**: `pandas` DataFrame üzerinden normalize edilmiş, metin madenciliğine hazır ham veri.
