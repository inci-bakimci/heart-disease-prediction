# Kalp Hastalığı Tahmin Sistemi

Bu proje, makine öğrenimi tabanlı bir **Kalp Hastalığı Tahmin Sistemi**dir.  
Amaç, açık kaynaklı sağlık verileri üzerinde eğitim yapılmış bir model aracılığıyla, kullanıcıların sağlık verilerini kullanarak kalp hastalığı riskini tahmin etmektir.

## Özellikler

- **FastAPI REST API**: Kullanıcı verilerini alır ve tahmin sonucu JSON formatında döner.
- **RandomForestClassifier**: Makine öğrenimi modeli ile kalp hastalığı tahmini yapar.
- **Veri Önişleme**: Aykırı değer temizleme, ölçeklendirme ve label encoding işlemleri uygulanmıştır.
- **Web Arayüzü**: Kullanıcı dostu bir arayüz ile veriler girilip sonuçlar görselleştirilebilir.
- **Geliştirilebilir**: Model ve frontend kolayca özelleştirilebilir.

## Kullanım

1. Lokal ortamda FastAPI server çalıştır:
```bash
uvicorn app:app --reload
1.2 Tarayıcıdan Swagger UI’yi aç:

http://127.0.0.1:8000/docs


1.3 POST /predict endpoint’i ile veri gönder ve tahmini al.

Gereksinimler

Python 3.8 veya üstü

FastAPI

scikit-learn

pandas, numpy, joblib

(Opsiyonel) React veya başka frontend kütüphanesi

Kurulum
git clone https://github.com/kullaniciadi/heart-disease-prediction.git
cd heart-disease-prediction
pip install -r requirements.txt
