# Symfony Url Kısaltma Uygulaması Ödevi

## Gereksinimler
  - symfony kullanılacak
  - arayüz için bootstrap veya varsa başka tercih edilen fw kullanılabilr
  - javascript tarafında jquery kullanılabilir
  - veritabanı olarak mysql kullanılacak
  - auth işlemleri için symfony kendi bundle'ları kullanılacak

## Uygulama Özellikleri
  Tasarım ve özellikler için genel yaklaşım olarak bit.ly referans alınabilir.
  
  ### CMS 
  - Tüm içerik sayfaları admin panelden yönetilebilir olacak, güncelleme,silme vb ( hakkımızda, kullanım şartları, cookie policy vs )
  - Yeni sayfalar yaratılabilecek
  
  ### Anasayfa
    - Slider / Banner alanı admin panelden yönetilebilir olacak.
    - App 'de bulunan özellikleri içeren features alanı olacak ve yine admin panelden yönetilebilir olacak

  ### İletişim
    - İletişim formu olacak ve buradan ( email, adsoyad, mesaj ) bilgileri toplanacak veri tabanına yazılacak.
    - Admin panelde buradan gelen mesajlar listenebilir halde olacak ve okundu / okunmadı ayrıca yanıtlandı / yanıtlanmadı şeklinde işaretlenebilecek
    - Admin panelde iletişim formundan gelen mesajların okunma ve yanıtlanma durumuna göre filtrelenebilmesi sağlanacak

  ### Terms, Privacy, Cookie vb 
    - İçerikler db 'den çekilecek ve admin panelden yönetilecek. 

  ### User Panel
    - Kullanıcı giriş yaptığında kendi panelini görebilecek
    - User panel üzerinde üye kendi profil bilgilerini güncelleyebilecek
    - Yaratmış olduğu kısaltmaları ve bu kısaltmalara dair istatistikleri görebilecek: ( her bir url kaç defa tıklanmış, top 5 kısaltma, top 5 browser, top 5 device, ek olarak istediğiniz eklemeleri yapmakta da özgürsünüz )

  ### Admin Panel
    - Kayıtlı tüm kullanıcıları listeleme
    - Tüm kullanıcıların bilgilerini güncelleyebilme, silebilme, askıya alma
    - seçilen kullanıcının yaratmış olduğu kısaltmaları listeyebilme
    - Yeni admin yaratabilme
    - Tüm içerik sayfalarını görebilme ve düzenleyebilme, yenisini yaratabilme.
    - Tüm url kısaltmalarının bir listesi
    - Kısaltmaları düzenleyebilme, silebilme, yeni kısaltma yaratabilme ( askıya alabilme, yönlendirilen adresi değiştirebilme vb )
    - En çok tıklanan top 10 domain (örn : facebook.com) , kısaltma, tarayıcı, dil, çöznürlük, en çok kısaltma yaratan top 10 user
    
   ### Bonus
    - şifremi unuttum özelliği
    - çoklu dil özelliği
    - dark mode özelliği
    - ( bu alana extra bonuslar gelebilir :) ) 
