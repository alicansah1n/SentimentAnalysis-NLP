# Doğal Dil İşleme ile Duygu Analizi

Bu proje, Türkçe metinlerde duygu analizi gerçekleştirmek amacıyla **Doğal Dil İşleme (NLP)** tekniklerini kullanmaktadır. 📊💬

## Proje Özeti
- İTÜ'nün sağladığı **reviews.xml** adlı veri seti kullanılarak, metinlerde olumlu, olumsuz ve nötr duyguların analizi yapılmıştır.
- Projede veri setinden cümle ve duygu etiketleri ayrıştırılmış, işlenmiş ve analiz edilmiştir.
- Temel metin analizi ve duygu tespiti yapılmıştır.

## Kullanılan Yöntemler
1. **XML Veri İşleme**:
   - XML formatındaki veri seti işlenmiş, cümleler ve duygu etiketleri ayrıştırılmıştır.
2. **Manuel Kelime Tabanlı Duygu Analizi**:
   - Örnek bir cümlede olumlu ve olumsuz kelimelerin sayısı kontrol edilerek duygu analizi gerçekleştirilmiştir.
3. **Veri Çerçevesi (DataFrame) Kullanımı**:
   - Veriler pandas kütüphanesi ile DataFrame formatına dönüştürülerek kolay analiz edilebilir hale getirilmiştir.

## Veri Seti Detayları
- **Kaynak**: İTÜ Tools Sayfası
- **Format**: XML
- **İçerik**: Türkçe metinler ve metinlere ait duygu etiketleri (olumlu, olumsuz, nötr).

## Kullanım
1. Proje dosyalarını indirin ve veri setini `reviews.xml` dosya yoluna ekleyin.
2. Gerekli kütüphaneleri yüklemek için aşağıdaki komutu çalıştırın:
   ```bash
   pip install pandas
