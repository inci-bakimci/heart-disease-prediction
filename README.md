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
