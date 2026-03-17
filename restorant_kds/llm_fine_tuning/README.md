# 🎯 Model İnce Ayar (Fine-Tuning) Çalışma Alanı

> Eğitim aşamasındaki model periyotlarının (checkpoint) gözlemlendiği, logların tutulduğu ve ara ağırlık güncellemelerinin kaydedildiği dizin.

## 💾 Checkpoints Sistemi
- **`results/`**: Belirli epoch ve adımlarda (Örn: `checkpoint-100`) otomatik kaydedilen adaptör sürümlerini (LoRA) içerir.
- Bir eğitim aksaklığa uğradığında, model bu checkpoint dosyalarından birini referans alarak eğitime kaldığı yerden devam edebilir (resume training).
