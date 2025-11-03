📱 SMS Spam Detection Projesi

Bu proje, kullanıcıların aldıkları kısa mesajları (SMS) analiz ederek spam (istenmeyen) veya ham (normal) olarak sınıflandırmayı amaçlamaktadır.
Proje Naive Bayes algoritması kullanılarak geliştirilmiştir.



📊 Veri Seti Hakkında

Veri kümesi, etiketlenmiş SMS mesajlarından oluşmaktadır.
Her mesaj, iki sınıftan birine aittir:

spam → istenmeyen reklam veya dolandırıcılık içeren mesajlar

ham → normal kullanıcı mesajları

| Sütun Adı  | Açıklama                | Tür    |
| ---------- | ----------------------- | ------ |
| **sms**    | Mesaj içeriği (metin)   | object |
| **etiket** | Mesaj türü (spam / ham) | object |

🧹 Veri Ön İşleme Adımları

- Tüm mesajlar küçük harfe dönüştürüldü.

- Noktalama işaretleri, özel karakterler ve sayılar kaldırıldı.

- Stop-word (önemsiz kelimeler) temizliği yapıldı.

- Gerektiğinde kök (stem) veya gövde (lemmatization) işlemi uygulandı.

- Veriler eğitim ve test seti olarak ayrıldı.




🔍 Sonuçlar

Yapılan testlerde modeli yüksek başarı göstermiştir.
