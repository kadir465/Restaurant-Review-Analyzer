# 📂 LLM Veri Seti Arşivi

> Yapay zeka modelinin eğitimi (Training) ve doğrulanması (Validation) için endüstri standardı formatlarda oluşturulmuş veri setleri dizini.

## 📊 Veri Formatı
Veriler ağırlıklı olarak `JSONL` formatında tutulmaktadır:
- **`train.jsonl`**: Modelin parametrelerini güncellemesinde kullanılacak temel veri seti.
- **`validation.jsonl`**: Aşırı öğrenmeyi (Overfitting) engellemek ve model gelişimini gözlemlemek için ayrılmış veri seti.
- **`training_dataset_grouped.jsonl`**: Gruplandırılmış ve bağlama oturtulmuş yüksek kaliteli eğitim verisi.
