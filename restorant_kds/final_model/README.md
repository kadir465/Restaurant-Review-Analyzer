# 🏆 Üretim Modeli (Final Production Model)

> Tüm temizleme, etiketleme ve Fine-Tuning süreçlerini tamamlamış nihai Karar Destek Sistemi Modeli'nin (LLM) barındığı yer.

## 📦 İçerik
- **`adapter_config.json`**: PEFT (LoRA vd.) adaptör yapılandırma metni. Eğitilmiş model ağırlıkları genellikle saf model yerine bir adaptör katmanı olarak sisteme eklenir.

## 🚀 Deployment (Canlıya Alma)
Geliştirilmiş olan bu model inference (çıkarım) aşamasında, orijinal taban modeli (`Base Model`) ve buradaki ağırlıkların birleştirilmesiyle `Hugging Face / vLLM` platformlarında hizmet verecek formattadır.
