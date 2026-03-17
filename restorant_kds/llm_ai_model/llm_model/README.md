# ⚙️ Model Konfigürasyon ve Eğitim Scriptleri

> Transformer tabanlı modellerin, projeye özgü verilerle eğitilmesi ve mimarisinin ayarlanması için gereken ana operasyon merkezi.

## 📜 Temel Dosyalar ve Açıklamaları
| Dosya Adı | Açıklama |
| :--- | :--- |
| **`prepare_model.py`** | Ön eğitimli modelin (Base Model) yüklenmesi, PEFT/LoRA adaptör konfigürasyonlarının yapılması ve tokenizer hazırlıkları. |
| **`train_model.py`** | Eğitim döngüsünün (Training Loop), epoch hesaplamalarının, ve hiperparametre optimizasyonlarının yürütüldüğü ana script. |
| **`build_llm_dataset.py`** | CSV veya ham veri kaynaklarını, Prompt-Response mantığına göre formatlayarak `llm_data` klasörüne aktaran ETL modülü. |
| **`llm_json.py`** | JSON manipülasyonu ve LLM validasyonları için yardımcı kurgular. |
