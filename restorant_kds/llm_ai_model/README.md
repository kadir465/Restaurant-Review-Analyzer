# 🧠 LLM (Büyük Dil Modeli) Eğitim & Entegrasyon Modülü

> Toplanan restoran yorumları ve işletme spesifikasyonlarını kullanarak, bir dil modelinin (Large Language Model) projeye özel kullanım durumlarına adapte edilmesi (fine-tuning ve test) sürecini yönetir.

## 🚀 Mimari ve Akış
1. **Veri Hazırlığı (`llm_data/`)**: Ham verilerin model eğitimine uygun instruction-response (JSONL vs.) formatlarına dönüştürülmesi.
2. **Model Eğitimi (`llm_model/`)**: Transformer kütüphaneleri ve PEFT (Parameter-Efficient Fine-Tuning) konfigürasyonlarıyla eğitim döngülerinin oluşturulması.

## 🛠️ Temel Gereksinimler
- `transformers`
- `datasets`
- `peft` & `trl`
- `torch` (CUDA Destekli tavsiye edilir)
