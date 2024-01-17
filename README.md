# abapbootcamp
abap bootcamp project
## Projenin Amacı

Etkinliklerin ve bu etkinliğe katılan kişilerin rapor halinde gösterilmesi amaçlandı

Z'li tablolar ile veriler tutulabilecek ya da excel tablosundan çekilen veriler gösterilerek isteğe göre Z'li tablolara kaydedilebilecek.

2 adet Tab alanı kullanılacak. Birinci taab alanında tabloların key alanları yer alıcak, ikinci tabda ise excel dosyasını yükleyebileceğimiz kısım bulunacak.

Gui status alanında excel deki verileri tablolarımıza kaydetmeyi sağlayan bir buton ve tabloların sm30 kısmındaki bakım ekranlarına gitmemizi sağlayacak iki adet buton yer alacak.

##Proje

Header Table : zsk_t03
item Table   : zsk_t04
Proje        : zsk_p14

Headeer tablosunda etkinlik bilgilerinin, item tablosunda katılımcı bilgilerinin tutulduğu iki adet Z'li tablo oluşturuldu.

https://github.com/SukranKrts/abapbootcamp/blob/main/images/Ekran%20g%C3%B6r%C3%BCnt%C3%BCs%C3%BC%202024-01-17%20171648.png

https://github.com/SukranKrts/abapbootcamp/blob/main/images/Ekran%20g%C3%B6r%C3%BCnt%C3%BCs%C3%BC%202024-01-17%20171801.png

Tab1 de tablolardaki key alanlarına yer verildi. Tab2 de ise dosya yükleyebileceğimiz bir alana yer verildi.

https://github.com/SukranKrts/abapbootcamp/blob/main/images/Ekran%20g%C3%B6r%C3%BCnt%C3%BCs%C3%BC%202024-01-17%20171838.png

Tab1 alanına herhangi bir değer girilmeden execute dediğimiz zaman tablolardaki bütün veriyi getiriyor. Eğer değer girilmiş ise veriyi filtreleyip getiriyor.

https://github.com/SukranKrts/abapbootcamp/blob/main/images/Ekran%20g%C3%B6r%C3%BCnt%C3%BCs%C3%BC%202024-01-17%20171918.png

Tab2 alanından dosya seçildiğinde dosyadaki verileri rapor halide ekranda gösteriyor.

https://github.com/SukranKrts/abapbootcamp/blob/main/images/Ekran%20g%C3%B6r%C3%BCnt%C3%BCs%C3%BC%202024-01-17%20171948.png

https://github.com/SukranKrts/abapbootcamp/blob/main/images/Ekran%20g%C3%B6r%C3%BCnt%C3%BCs%C3%BC%202024-01-17%20172012.png

Yukarıdaki fotoğrafta butonlar yer almakta. İlk butonumuz excel deki verileri tabloya kaydetmeye yarıyor. ‘Bakım Ekranı’ ve ‘Bakım Ekranı2’ butonları ise tabloların sm30’daki bakım ekranlarına ulaşmamızı sağlıyor.

Sm30 ekran örneği:

https://github.com/SukranKrts/abapbootcamp/blob/main/images/Ekran%20g%C3%B6r%C3%BCnt%C3%BCs%C3%BC%202024-01-17%20172042.png
