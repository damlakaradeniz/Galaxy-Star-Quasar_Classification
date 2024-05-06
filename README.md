# Galaxy-Star-Quasar_Classification

Bu notebook'ta Akbank Makine Öğrenmesi Bootcamp'i için yapmış olduğum proje olan Yıldız, Galaksi, Kuasar Sınıflaması bulunmaktadır.

Veriler Kaggle'dan alınmıştır. Veri seti toplam 100.000 satırdan ve 18 sütundan oluşmaktadır. Boş satır bulunmamaktadır fakat çalışmanın gerekçeleri doğrutlusunda sütun sayısında azaltma yapılmıştır ve sütun sayısı 12'ye düşmüştür.

Çalışmanın amacı 'class' sütununda bulunan 3 ayrı sınıftan; yıldız, galaksi ve kuasarları özelliklerine göre sınıflamaktır. Çalışmada 4 ayrı sınıflama türü kullanılmıştır. Bunlar Random Forest, Logistic regression, Decision tree ve Bagging Classifier. Öncelikle yazdığım ilk  3 sınıflamadan en iyi model sonucunu veren 0.97 ile Random Forest olmuştur. Random Forest modelini uyguladığım zaman 0.89 sonucu çıkmıştır. Ben daha sonra merak ettiğim için Bagging Classifier uyguladım ve çok iyi öğrendiğini gördüm sonuç 0.99 çıktı.

Ben oluşturduğum modeli test etmek istedim. Bunun için yaygın olarak bilinen gök cisimlerininden birer tane seçtim ve veri setindekiyle ortak olan parametrelerini girdim. Bunların isimleri Aldebaran Star, M90 Galaxy, 3C 273 QSO. Tüm bu cisimlerin olması gerektiği gibi sınıflandırıldığını gördüm.
