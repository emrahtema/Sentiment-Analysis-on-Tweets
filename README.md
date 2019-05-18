# Sentiment-Analysis

Türkçe cümlelerdeki duyguların çıkarımını yapabilmek amacıyla gerçekleştirdiğim lisans bitirme projem 3 aşamadan oluşmaktadır.

Birinci aşama Veri Madenciliği: 4 temel duygudan birini içeren 3000+ adet tweet, Twitter.com'dan toplandı. Tweetler toplaması kolay olduğundan burada temsili cümlelerimiz-verilerimiz olarak kullanılmıştır, toplandıkları andan itibaren etiketleme işlemleri yapılmıştır.

İkinci aşama Doğal Dil İşleme: Bu aşamada toplanan tweetlerdeki bozuk kelimeler düzeltilmiş, istenilmeyen kelimeler, noktalama işaretleri ve diğer pek çok kirlilik yaratan şey kaldırılmıştır. Sınıflandırmaya en uygun olan veri tipini tespit edebilmek amacıyla da veriler birkaç farklı şekilde kaydedilmiş ve bu sayede Data klasörü içindeki Conf'lar oluşturulmuştur. Her birinin içindeki verilere uygulanmış işlemler birbirinden farklıdır.

Üçüncü aşama Sınıflandırma: Buradaki uygulama dosyaları bu aşamanın ürünüdür, burada önceki aşamalarla ilgili kod bulunmamaktadır. Burada farklı yaklaşımlar ve veri şekillendirme işlemleriyle farklı sınıflandırmalar yapılmış ve 3 adet makine öğrenmesi algoritması test edilmiştir. Genellikle yapılan sınıflandırmalarda Conf2 verileri kullanılmıştır. Aynı zamanda bir derin öğrenme algoritması kullanılarak oluşturulmuş olan yapay sinir ağı da bulunmaktadır.
