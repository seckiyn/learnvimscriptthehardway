Önsöz
=======

Yazılımcılar fikirleri yazıya aktarırlar.

Bu yazılar önce sayılara ve bu sayılar diğer sayılara katıla katıla bir
şeylerin olmasını sağlarlar.

Yazılımcılar olarak, biz yazı editörlerini fikirlerimizi aklımızdan çıkarıp
bizim "yazılım" dediğimiz parçalara dönüştürmek için kullanırız. Tam zamanlı yazılımcılar yaşamlarını on binlerce saatlerini yazı editörleri ile 
cebelleşerek, şunları yapmaya çalışırız:

* Akıllarındaki ham yazıyı bilgisayara aktarmak.
* O yazılardaki hataları düzeltmek.
* O yazıyı probleme farklı bir açıdan bakmak için yeniden inşa etmek.
* Bir şey nasıl ve neden öyle yapıldı belgelemek.
* Ve diğer yazılımcılarla tüm bu şeyler hakkında ileteşebilmek için.

Vim is incredibly powerful out of the box, but it doesn't truly shine until you
take some time to customize it for your particular work, habits, and fingers.
This book will introduce you to Vimscript, the main programming language used to
customize Vim.  You'll be able to mold Vim into an editor suited to your own
personal text editing needs and make the rest of your time in Vim more
efficient.

Vim hiçbir şey yapılmasa dahi inanılmaz güçlüdür ama kendi işiniz, 
alışkanlıklarınız ve parmaklarınız için ayarlamak için biraz zaman 
harcayana kadar tamamen parlamaz.
Bu kitap sizi Vim'i ayarlamak için kullanılan ana programlama dili olan 
Vimscript ile tanıştıracak.
Vim'i keyfinize göre kalıba döküp kendi  yazı editleme ihtiyaçlarınıza 
uygun ve çok daha verimli hale getirebileceksiniz

Anlatımım boyunca Vimscript ile alakalı olmayan şeyler de anlatacağım, bunlar
genellikle öğrenmek ve nasıl daha verimli olunur hakkında olacak. Eğer tüm gün
küçük küçük editörle uğraşarak günü geçirirseniz Vimscrit pek de yardımcı
olmayacaktır sizin için bu yüzden bir denge sağlamak mühimdir.

The style of this book is a bit different from most other books about
programming languages.  Instead of simply presenting you with facts about how
Vimscript works, it guides you through typing in commands to see what they do.

Bu kitabın tarzı diğer programlama dili kitaplarından biraz farklıdır. Size
Vimscript nasıl çalışır hakkında bir iki şey anlatmaktansa size komutları
kullanarak ne yapıyor onu görmenize rehberlik eder.

Bu kitap bazenleri size problemi çözmek için "asıl" yolu göstermektense birkaç
yanlış yolu gösterecek. Çoğu kitap genelde bunun tersini yapar, asıl yolu
gösterdikten sonra sorun çıkarabilecek şeyleri *sonraya* bırakır. Ama herkes
bilir ki bu gerçek yaşamda olanın tam tersidir. Genelde bir parça Vimscript
yazdıktan sonra programlama dilinin tuhaflıkları ile karşılaşır ve onu çözmeniz
gerekir.  Üstünkörü anlatmak yerine adım adım giderek tuhaflıklarına alışacak
ve gözden kaçabilecek hataları bulurken işineze yarayacak. İşleyen demir
ışıldar.

Kitabın her bölümü tek bir konuya odaklı. Kısalar ama bilgi ile tıka basa
dolular yani sakın "şöyle bir gözden geçirmeyin" eğer gerçekten öğrenmek ve
kitabın sunduklarını sonuna kadar almak istiyorsanız teker teker komutları
yazmanız gerekli. Çoktan okuduğu kodu anlayan deneyimli bir yazılımcı
olabilirsiniz. Öyleyse bile önemli değil. Vim ve Vimscript'i öğrenmek normal
bir programlama dilini öğrenmekten çok daha farklı bir serüven.

**Tüm komutları yazmanız** gerek.

***Tüm*** **egzersizleri tamamlamanız** gerek.

Bunun çok önemli olmasını iki nedeni var: Birincisi, Vimscript eskidir ve bir sürü tozlu ve harabe yollardan oluşur. Sadece bir yapılandırma ayarı tüm dilin nasıl çalıştığını değiştirebilir. *Tüm* derslerdeki *tüm* komutları yazarak ve tüm egzersizleri yaparak Vim sürümünüz ve yapılandırmanızla ilgili sorunları daha küçük komutlarda fark edeceksiniz ki bu da o sorunları tanımlamanız ve çözmenizi kolaylaştıracak.

İkincisi, Vimscript Vim'in ta kendisidir. Vim'de bir dosya kaydetmek için
:write (ya da kısası :w) yazar ve enter tuşuna basılır. Vimscript'te write
komutunu kullanırsınız. Öğreneceğiniz birçok Vimscript komutunu aynı zamanda
günlük işleriniz için de kullanabilirsiniz ama sadece kas hafızanızda kayıtlı
ise size yardımcı olurlar yoksa sadece okumakla günlük hayatta kullanamazsınız. 

Umarım bu kitabı faydalı bulursunuz. Vimscript adına tüm her şeyi içine alınmak
gayesi ile yazılmadığını unutmayın. Asıl gayesi Vim'i kendi isteğinize göre bir
şekle sokmaya yetecek rahatlığa gelmeniz, diğer kullanıcılar için basit
pluginler yazabilmeniz, diğer insanların yazdıklarını okuyabilmeniz(tabii ki
:help'i sık sık ziyaret ederek) ve bazı çok karşılaşılan tehlikeleri
görebilmeniz.

İyi şanslar!
