# 🏪 Restoran Meta Veri Kazıma (Info Scraping)

> Platformlardaki restoranların puan, adres, minimum paket tutarı, mutfak tipi gibi işletme meta verilerini yapılandırılmış veri olarak elde eden operasyon klasörü.

## 🎯 Amaç
Karar Destek Sistemi'nin (KDS) temel analiz fonksiyonlarına besin oluşturmak üzere bölgesel restoran verilerini çekmek. Yorumlar, bu demografik bilgilerle birleştirilerek anlamlı içgörüler (insights) yaratılır.

## 📂 Dizin Yapısı
1. **`trendyol_restoran_scraping/`**: Trendyol algoritmasına ve sayfa DOM yapısına özgü script'ler.
2. **`yemeksepeti_restoran_scraping/`**: Yemeksepeti liste ve detay sayfalarına özgü script'ler.
3. **Data Temizliği**: `restoran_data_clear.ipynb` dosyası toplanan verilerdeki kirliliği giderir ve `.csv` dosyalarını standardize eder.
