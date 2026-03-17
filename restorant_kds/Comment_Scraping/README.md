# 🗣️ Müşteri Yorumları Kazıma Modülü (Comment Scraping)

> Yemeksepeti ve Trendyol Yemek platformlarındaki restoranlara ait müşteri yorumlarının toplanması, temizlenmesi ve yapılandırılması süreçlerini yöneten temel modüldür.

## 📑 Sisteme Genel Bakış
Bu dizin, e-ticaret gıda platformlarındaki kullanıcı geri bildirimlerini NLP (Doğal Dil İşleme) ve LLM eğitim süreçlerinde kullanılmak üzere ham veri formatında toplamak için tasarlanmıştır.

### 🗂️ Modül İçeriği
* **`trendyol_yorumlar/`**: Trendyol Yemek platformuna özgü Selenium bazlı scraping script'leri.
* **`yemeksepeti_yorumlar/`**: Yemeksepeti platformuna özgü scraping kodları.
* **Jupyter Notebooks**: Veri analiz, temizleme ve ön işleme adımlarını barındıran (`restoran_comment.ipynb` ve `restoran_comment_clear.ipynb`) dosyaları.
* **Veri Çıktıları**: Konsolide edilmiş, JSONL ve CSV formatlı yorum arşivleri.

---
**📍 Not:** Kazınan tüm veriler, yasal sınırlar ve platform politikalarına uygun şekilde sadece akademik/eğitim amaçlı kullanılmak üzere anonimize edilmelidir.
