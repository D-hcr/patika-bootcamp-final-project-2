# 📊 Power BI ile Satış ve Müşteri Analizi Dashboard'u

Bu proje, [Veri Analizi Bootcamp Final Projesi](https://drive.google.com/drive/folders/1uhMFLLESdg1jCUqRI3BEmDEbYlR_q-cM?usp=sharing) kapsamında gerçekleştirilmiş olup, Power BI kullanılarak bir markanın satış, müşteri ve ürün verileri analiz edilmiştir.

---

## 🎯 Projenin Amacı

Projenin temel amacı; bir markaya ait satış ve müşteri verilerini detaylı şekilde analiz ederek, veri odaklı kararlar almayı sağlayacak içgörüler sunmaktır. Proje boyunca ETL süreci, veri modelleme, DAX ile hesaplamalar ve görsel dashboard oluşturma adımları uygulanmıştır.
---

## 📂 Proje İçeriği

### 🔹 1. Veri Kaynakları

- `Users`, `Address`, `Items`, `Orders`, `OrderDetail` tabloları
- Bölge ve şehir eşlemesi için harici `bölgeler.csv` dosyası

### 🔹 2. Veri Dönüştürme Adımları

- Yaş hesaplaması (`DATEDIFF`)
- Cinsiyet, yaş grubu, kategori sınıflandırmaları için koşullu sütunlar
- Gereksiz kolonların kaldırılması, veri tiplerinin düzenlenmesi
- Modelleme: Tablolar arası ilişki kurulması (one-to-many)

### 🔹 3. Dashboard Sayfaları

| Sayfa Adı              | İçerik                                                                 |
|------------------------|------------------------------------------------------------------------|
| **Giriş Sayfası**       | Navigasyon – kullanıcı diğer sayfalara buradan yönlendirilir           |
| **Özet Sayfa**          | Toplam ciro, satış, saatlik ve haftalık satış grafikleri                |
| **Müşteri Perspektifi** | Kadın/Erkek müşteri sayısı, yaş grubu satışları, bölgesel dağılım       |
| **Kategori Perspektifi**| Genç yaş grubunun İstanbul'daki kategori bazlı harcama dağılımı         |

---

## 📈 Öne Çıkan Ölçümler (DAX)

- `ToplamCiro`
- `ToplamSatış`
- `TekilMüşteriSayısı`
- `MüşteriBaşınaCiro`, `MüşteriBaşınaAdet`
- `OrtalamaSiparişTutarı`
- `HaftaTipi` ve `SaatlikSatış` için koşullu ölçümler

---

## 📎 Proje Raporu ve Sunumu

📁 **Drive klasörü bağlantısı**:  
🔗 [Proje Sunumu, PDF Rapor ve Ekler](https://drive.google.com/drive/folders/1uhMFLLESdg1jCUqRI3BEmDEbYlR_q-cM?usp=sharing)

Drive içeriğinde şunlar bulunmaktadır:
- Power BI PDF Raporu (Dashboard çıktıları)
- Sunumda kullanılacak metin ve anlatım dosyası
- Kullanılan veri setleri ve bölge eşlemeleri (csv/excel)

---

## ✅ Sonuçlar ve Öneriler

- En yoğun satış saatleri **18:00 – 22:00**, alışveriş akşam saatlerinde zirve yapıyor.
- **Kadın kullanıcılar**, erkeklere göre daha fazla alışveriş yapıyor.
- En aktif yaş grubu **20-35 yaş arası**, bu kitleye özel kampanyalar önerilebilir.
- **Marmara ve Ege Bölgeleri**, satış ve müşteri yoğunluğunda başı çekiyor.
- **Genç İstanbul müşterileri**, ağırlıklı olarak gıda ve kozmetik ürünlerinde harcama yapıyor.

---
