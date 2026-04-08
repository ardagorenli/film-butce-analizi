🎬 Film Bütçeleri ve Popülarite İlişkisinin Veri Madenciliği ile Analizi

Bu proje, veri madenciliği döngüsüne uygun olarak ham verinin bilgiye dönüştürülmesi sürecini kapsayan akademik bir çalışmadır. TMDB (finansal veriler) ve IMDb (izlenme istatistikleri) veri setleri birleştirilerek, sinema endüstrisinde bütçe artışının popülariteye (izlenme oranına) etkisi istatistiksel olarak incelenmiştir.

Kullanılan Teknolojiler ve Araçlar
Dil: Python
Geliştirme Ortamı: VS code
Veri İşleme: Pandas,NumPy
Veri Görselleştirme: Matplotlib

Proje Adımları
1. Veri Temizleme: Bütçesi "0" veya anlamsız olan hatalı veriler ayıklanmış, metin standardizasyonu yapılmıştır.
2. Veri Birleştirme (Data Merging): Ortak sütun ("Orijinal Film Adı") kullanılarak iki farklı veri seti Pandas `merge` fonksiyonu ile konsolide edilmiştir.
3. Görselleştirme ve Analiz: Genel eğilim için saçılım grafikleri ve zirvedeki filmler için sütun grafikleri oluşturulmuştur.

📊 Temel Bulgular
Analiz sonucunda, yapım bütçesi arttıkça filmlerin ulaşabildiği izleyici kitlesinin (popülarite skorunun) ortalamada artış gösterdiği kanıtlanmıştır. Devasa bütçelerin küresel pazarlama kampanyalarına harcanarak filmin görünürlüğünü garanti altına aldığı görülmüştür.
