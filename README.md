# 🎧 Music Streaming User Analysis

Bu proje, bir müzik dinleme platformuna ait kullanıcı verileri üzerinden temel veri analizi yapmayı amaçlamaktadır.

## 🎯 Proje Amacı

Bu çalışmada amaç:

- kullanıcı davranışlarını analiz etmek
- free ve premium kullanıcıları karşılaştırmak
- churn davranışını incelemek
- skip rate ve daily minutes gibi metriklerden içgörü üretmek
- Excel, SQL ve Python araçlarını aynı proje içinde kullanmaktır

## 🗂️ Dataset

Dataset, bir müzik streaming platformundaki kullanıcı aktivitelerini temsil etmektedir.

Kolonlar:

- user_id → kullanıcı ID
- age → kullanıcı yaşı
- country → ülke
- subscription_type → abonelik tipi
- device → kullanılan cihaz
- daily_minutes → günlük dinleme süresi
- favorite_genre → favori müzik türü
- skip_rate → şarkı geçme oranı
- ads_clicked → reklam tıklama durumu
- churned → kullanıcının platformu bırakıp bırakmadığı

## 🛠️ Kullanılan Araçlar

- Excel
- SQL
- Python
- Google Colab
- Pandas
- Matplotlib
- GitHub

## 📌 Yapılan Analizler

Bu projede aşağıdaki sorulara cevap aranmıştır:

- Free ve premium kullanıcıların ortalama dinleme süreleri farklı mı?
- Churn eden kullanıcıların skip rate değeri daha yüksek mi?
- Hangi ülkelerde kullanıcı yoğunluğu daha fazla?
- Hangi cihaz tipinde kullanıcı davranışı farklılaşıyor?
- Hangi müzik türlerinde skip rate daha yüksek?
- Eksik veri ve outlier değerler var mı?

## 📈 Öne Çıkan İçgörüler

- Premium kullanıcıların ortalama dinleme süresi daha yüksektir.
- Free kullanıcılar churn açısından daha riskli görünmektedir.
- Yüksek skip rate, churn için erken sinyal olabilir.
- Mobile kullanıcı deneyimi retention açısından önemlidir.
- Outlier ve eksik veri kontrolleri analiz kalitesi için kritiktir.

## 📁 Proje Dosyaları

- `dataset.csv` → Kullanılan veri seti
- `queries.sql` → SQL sorguları
- `python_analysis.ipynb` → Python analiz notebook’u
- `analysis.md` → Analiz yorumları ve içgörüler
- `README.md` → Proje açıklaması

## 🚀 Sonuç

Bu proje, veri analizi sürecinde farklı araçların nasıl birlikte kullanılabileceğini göstermektedir.

Excel ile veri inceleme, SQL ile sorgulama ve Python ile analiz/görselleştirme yapılarak kullanıcı davranışlarına dair temel iş içgörüleri üretilmiştir.

---

👩‍💻 Bu proje Yıldız Kariyerim Data Analyst Bootcamp kapsamında hazırlanmıştır.
