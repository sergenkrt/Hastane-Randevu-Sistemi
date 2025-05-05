# Hastane Randevu Sistemi

> Hastane Randevu Sistemi projemi Python ve gui tasarımı için Tkinter kullanarak geliştirdim. 
Bu program ile hasta ve doktor kayıtları tutulabilir, Hasta ve doktorlar seçilerek randevu verilebilir ve randevular program üzerinden yönetilebilir.

*-> Program açıldığında karşımıza çıkan ana görünümü bu şekildedir:*
![image](https://github.com/user-attachments/assets/310ce2e0-9905-4959-bc0a-1d9d91f5c8a7)


> Hastane Randevu Sistemi -> Hasta Yönetimi
> 
**-** Yeni hasta bu kısımdan eklenebilir.
> 
**-** Hastanın adı soyadı sayı içermeyecek şekilde yazılmalıdır.

**-** Hastanın TC kimlik numarası 11 sayıdan oluşmalıdır.

**-** Mevcut hastalar bu kısımdan silinecek hasta kısmına tıklanarak seçilebilir ve sil yazısına tıklanarak silinebilir.


![image](https://github.com/user-attachments/assets/ae6c8046-281e-4cf7-ab7a-f2b9a58d025a)


> Hastane Randevu Sistemi -> Doktor Yönetimi
> 
**-** Yeni doktor bu kısımdan eklenebilir.
>
**-** Doktorun adı soyadında hasta eklerken olduğu gibi sayı içermemelidir.
>
**-** Doktorun uzmanlık alanı, doktorun isim soyisimi yazıldıktan sonra daha önceden kodlarda belirlenmiş kategorilerden birini seçerek belirlenebilir.
>
**-** Eğer eklenen doktorlardan herhangi birini silmek istersek silinecek doktor kısmından doktor seçtikten sonra sil butonuna basabiliriz.

![image](https://github.com/user-attachments/assets/73831e84-3345-4036-ba18-72fe1fabecb2)


> Hastane Randevu Sistemi -> Randevu Oluşturma
>
**-**Bu kısımdan hasta, doktorun uzmanlık alanı ve doktor bilgisi seçildikten sonra randevunun alınmak istediği tarihte seçilerek randevu alınabilir.
>
**-** Bu kısımda geçmiş tarihlerde randevu alınamaz.
>
**-** Aynı doktora aynı gün içerisinde birden fazla kez randevu alınamaz.
>
**-** Aynı hasta bir gün içerisinde birden fazla randevu alamaz.

![image](https://github.com/user-attachments/assets/16c3095d-466f-4dc7-aba9-857a358fd700)


> Hastane Randevu Sistemi -> Mevcut Randevular
>
**-** Randevu oluştur kısmından oluşturulan randevuler programın sol altında bulunan mevcut randevular kısmından görüntülenebilir. Eğer randevu iptal edilmek istenirse randevu seçildikten sonra "seçili randevuyu iptal et" butonuna basılmalıdır.

![image](https://github.com/user-attachments/assets/50adadf0-8f43-4c17-b5a8-aa67752d1cd6)


> Veriler Nasıl Saklanır?

**-** Veriler kodun çalıştığı klasör içerisinde data.json dosyası oluşturularak bu dosyaya kaydedilir ve uygulama tekrar açıldığında otomatik olarak yüklenir.


> Uygulama nasıl yüklenir & nasıl çalıştırılır?

**-** Visual Studio Code uygulamasını indirin.
**-** Visual Studio Code uygulamasında eklentiler (extensions) kısmından Python yazın ve indirin.
**-** Projeyi indirdikten sonra dosyayı rardan çıkartmak istediğiniz yere çıkartın. hastane_randevu isimli dosyayı daha önceden indirmiş olduğumuz Visual Studio Code ile açın.
**-** Sağ üst kısımdan oynatma tuşuna basarak uygulamayı başlatın.
