# Music Streaming User Analysis - Insights

Bu projede bir müzik dinleme platformuna ait kullanıcı verileri Excel, SQL ve Python kullanılarak analiz edilmiştir.

## Amaç

Bu çalışmada amaç:

- kullanıcı davranışlarını anlamak
- free ve premium kullanıcıları karşılaştırmak
- churn davranışını incelemek
- dinleme süresi ve skip rate gibi metriklerden içgörü çıkarmaktır

## Temel Bulgular

### 1. Premium kullanıcılar daha yüksek dinleme süresine sahiptir

Premium kullanıcıların ortalama günlük dinleme süresi free kullanıcılara göre daha yüksektir.
Bu durum premium kullanıcıların platformdan daha fazla değer aldığını gösterebilir.

### 2. Free kullanıcılar churn açısından daha riskli görünmektedir

Churn eden kullanıcıların önemli bir kısmı free kullanıcı grubundadır.
Bu durum ücretsiz kullanıcıların platforma bağlılığının daha düşük olabileceğini gösterir.

### 3. Skip rate churn için önemli bir sinyal olabilir

Churn eden kullanıcıların ortalama skip rate değeri daha yüksektir.
Bu, kullanıcıların içerikten memnun kalmadığında platformu bırakma eğiliminde olabileceğini düşündürür.

### 4. Mobile kullanıcılar daha yoğun bir kullanıcı grubudur

Veri setinde mobile kullanıcıların sayısı dikkat çekmektedir.
Bu nedenle mobil deneyim, kullanıcı memnuniyeti ve retention açısından kritik olabilir.

### 5. Outlier değerler analiz sonucunu etkileyebilir

Daily minutes kolonunda olağan dışı yüksek bir değer bulunmaktadır.
Bu tarz outlier değerler ortalama hesaplarını etkileyebileceği için analiz öncesinde mutlaka kontrol edilmelidir.

### 6. Eksik veri analize başlamadan önce kontrol edilmelidir

Skip rate kolonunda eksik değerler bulunmaktadır.
Eksik veriler analiz sonuçlarını etkileyebileceği için yorumlama sürecinde dikkate alınmalıdır.

## Sonuç

Bu proje, bir veri analistinin aynı veri setini farklı araçlarla nasıl analiz edebileceğini göstermektedir.

Excel ile temel inceleme, SQL ile sorgulama ve Python ile analiz/görselleştirme yapılarak kullanıcı davranışlarına dair anlamlı içgörüler üretilmiştir.
