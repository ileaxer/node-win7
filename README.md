# node-16-win7
Bildiğimiz üzere v11 ve v12 apileri kalkıyor bu durumdan ötürü v13 geçmek gerekiyor ve windows 7'te node 16 kurulmuyor maalesef bunun bir çözümü var bunu sırasıyla anlatacağım ilk yapacağımız şey;

1 - Node 16'nın zip dosyasını indirmek, şimdilik bunla bi işimiz yok fakat masaüstüne atarsanız fena olmaz. (https://nodejs.org/dist/v16.14.0/node-v16.14.0-win-x86.zip) 

2 - Gelişmiş sistem özelliklerini açmak .

3 - Burdan ortam değişkenleri adlı yere tıklamak.

4 - Orda karşımıza çıkan ".. için kullanıcı değişkenleri" ve "Sistem değişkenleri" bizim kullanıcı değişkenleriyle işimiz yok ondan dolayı sistem değişkenlerine geliyoruz. Geldikten hemen sonra Yeni'ye basıp Değişken Adına **NODE_PATH** yazıp Değişken Değerine** C:/nodejs/node_modules** giriyoruz burası değişebilir sizin nereye kaydettiğinizle ilgili ondan sonra tekrar Yeni tuşuna basıyoruz ve Değişken Adına **NODE_SKIP_PLATFORM_CHECK** yazıp Değişken Değerine **1** yazıp tamam diyoruz bunların hepsini yaptıktan sonra Uygula tuşuna basıp bilgisayarı yeniden başlatıyorsunuz.

5 - Bilgisayarı kapatıp açtıktan sonra cmd açıyoruz(Yönetici ile çalıştırın) yapacağınız şey `set NODE_SKIP_PLATFORM_CHECK 1` bunu yazdıktan sonra zip dosyasından çıkartıyoruz bu sıra test etmek amaçlı yapacağınız şey klasörün içine cmd çalıştırıp `node --version` yazmak versionu veriyorsa sorunsuz çalışıyordur bunların hepsini CTRL + A yaparak kopyalıyoruz ve `Program Dosyaları (86x)`'in içindeki nodejs klasörüne yapıştırıyoruz her şeyi onaylayın ve diğer bir işlem ise `Program Files`'a gelip aynı işlemleri yaptıktan sonra işlem tamamlanacaktır bunu resimlerle anlatmak isterdim fakat çok uzun olur ama anlatabilirsem anlatırım.

Elimden geldiğince anlatmaya çalıştım yapamazsanız #💻・diğer kanalından yardım isteyebilirsiniz.

https://media.discordapp.net/attachments/694246505430909010/943931934197829692/unknown.png?width=326&height=371
https://media.discordapp.net/attachments/694246505430909010/943932557697904720/unknown.png?width=300&height=338
https://cdn.discordapp.com/attachments/694246505430909010/943932558125699122/unknown.png
https://cdn.discordapp.com/attachments/694246505430909010/943932558545137765/unknown.png
https://cdn.discordapp.com/attachments/694246505430909010/943932558884892782/unknown.png
