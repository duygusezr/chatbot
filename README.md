# 🎬 Türkçe Film Tabanlı Soru-Cevap Chatbotu (Leon: Sevginin Gücü)

Bu proje, Türkçe doğal dil işleme (NLP) uygulaması olarak, belirli bir metin bağlamına dayalı olarak kullanıcının sorduğu sorulara cevap veren bir **Soru-Cevap (Question Answering)** sistemidir. Örnek olarak *Leon: Sevginin Gücü* filmine ait özet metin kullanılmıştır.

## 🚀 Özellikler

- 🤖 BERT tabanlı Türkçe SQuAD modeli (`savasy/bert-base-turkish-squad`) ile eğitilmiş
- 🧠 Hugging Face `transformers` kütüphanesi ile QA pipeline kurulumu
- 🎯 Belirli bir bağlamda (film özeti) soruları anlama ve cevaplama yeteneği
- ⚠️ Düşük güven skorlarında otomatik “Bilmiyorum” cevabı vererek hatalı cevapların önlenmesi
- 💬 Terminal üzerinden etkileşimli soru-cevap deneyimi

## 🛠 Kurulum

### 1. Gerekli Paketleri Kur

Python ortamınızı oluşturduktan sonra aşağıdaki paketleri yükleyin:

```bash
pip install transformers
