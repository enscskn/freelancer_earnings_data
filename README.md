# Freelancer Kazanç Analizi

## Genel Bakış
Bu proje farklı platformlardaki freelancer kazançlarını analiz eder. Saatlik ücret, iş başarı oranı, müşteri puanı ve tamamlanan iş sayısı gibi faktörlerin kazanç üzerindeki etkileri incelenmiştir.

## Veri Seti
Kullanılan veri seti şu anahtar sütunları içerir:
- **Freelancer_ID**: Her freelancer için benzersiz kimlik.
- **Job_Completed**: Tamamlanan iş sayısı.
- **Earnings_USD**: Toplam kazanç (USD cinsinden).
- **Hourly_Rate**: Saatlik ücret.
- **Job_Success_Rate**: İş başarı oranı (%).
- **Client_Rating**: Müşteri puanı.
- **Job_Duration_Days**: İş süresi (gün).
- **Rehire_Rate**: Tekrar işe alınma oranı (%).
- **Marketing_Spend**: Pazarlama harcaması.
- **Job_Category**: İşin kategorisi.
- **Platform**: Freelancer'ın çalıştığı platform.
- **Experience_Level**: Deneyim seviyesi.

## Yapılan Analizler
- Genel istatistikler (ortalama kazanç, saatlik ücret vb.)
- En popüler iş kategorileri ve en çok kazandıran platformlar.
- Deneyim seviyesine göre kazanç analizi.
- Saatlik ücretin iş başarı oranına etkisi.
- Müşteri puanı ve kazanç arasındaki ilişki.
- Tamamlanan iş sayısı ve kazanç arasındaki bağlantı.

## Önemli Bulgular
- En çok kazandıran platformlar belirlenmiştir.
- İş başarı oranı yüksek olan freelancerlar daha fazla kazanma eğilimindedir.
- Deneyim seviyesi arttıkça kazanç da artmaktadır.
- Saatlik ücret ve iş başarı oranı arasında doğrudan bir ilişki olabilir.
- Müşteri puanı yüksek olan freelancerlar daha fazla kazanmaktadır.
- Tamamlanan iş sayısı arttıkça kazanç da artmakta ancak belli bir noktada durağanlaşmaktadır.

## Kullanım
Analizi çalıştırmak için aşağıdaki adımları izleyin:
```sh
pip install pandas numpy matplotlib seaborn
python freelancer_analysis.py
```