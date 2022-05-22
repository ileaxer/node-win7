# Windows 7 Node.js
Bildiğimiz üzere v11 ve v12 apileri kalkıyor bu durumdan ötürü v13 geçmek gerekiyor ve windows 7'te node 16 kurulmuyor maalesef bunun bir çözümü var bunu sırasıyla anlatacağım ilk yapacağımız şey;

# Anlatım

1 - Başta node 13 indirin ve bunu istediğiniz yere kaydedin. 5.ci kısımıda **NODE_PATH** yazdığınız yerin değişken değerine kaydettiğiniz yeri yazın.

2 - [Node 16'nın](https://nodejs.org/dist/v16.14.0/node-v16.14.0-win-x86.zip) zip dosyasını indirmek, şimdilik bunla bi işimiz yok fakat masaüstüne atarsanız fena olmaz. 

3 - Gelişmiş sistem özelliklerini açmak .

4 - Burdan ortam değişkenleri adlı yere tıklamak.

5 - Orda karşımıza çıkan ".. için kullanıcı değişkenleri" ve "Sistem değişkenleri" bizim kullanıcı değişkenleriyle işimiz yok ondan dolayı sistem değişkenlerine geliyoruz. Geldikten hemen sonra Yeni'ye basıp Değişken Adına **NODE_PATH** yazıp Değişken Değerine** C:/nodejs/node_modules** giriyoruz burası değişebilir sizin nereye kaydettiğinizle ilgili ondan sonra tekrar Yeni tuşuna basıyoruz ve Değişken Adına **NODE_SKIP_PLATFORM_CHECK** yazıp Değişken Değerine **1** yazıp tamam diyoruz bunların hepsini yaptıktan sonra Uygula tuşuna basıp bilgisayarı yeniden başlatıyorsunuz.

6 - Bilgisayarı kapatıp açtıktan sonra cmd açıyoruz(Yönetici ile çalıştırın) yapacağınız şey `set NODE_SKIP_PLATFORM_CHECK 1` bunu yazdıktan sonra zip dosyasından çıkartıyoruz bu sıra test etmek amaçlı yapacağınız şey klasörün içine cmd çalıştırıp `node --version` yazmak versionu veriyorsa sorunsuz çalışıyordur bunların hepsini CTRL + A yaparak kopyalıyoruz ve (Burda kısacası demek istediğim nodejs'in kurulu olduğu dosyanın içine atmak) `Program Dosyaları (86x)`'in içindeki nodejs klasörüne yapıştırıyoruz her şeyi onaylayın ve diğer bir işlem ise `Program Files`'a gelip aynı işlemleri yaptıktan sonra işlem tamamlanacaktır bunu resimlerle anlatmak isterdim fakat çok uzun olur ama anlatabilirsem anlatırım.

# Bilgi
[![Discord Presence](https://lanyard.cnrad.dev/api/486936078280818728)](https://discord.com/users/486936078280818728)
<table>
  <tr>
        <td align="center"><a href="https://github.com/ileaxer"><img src="https://avatars.githubusercontent.com/u/90086777?s=400&u=9b753c3c97e9986c96d9a4b65133c36b98ac9ff2&v=4" width="100px;" alt=""/><br /><sub>          <b>lèãxér</b></sub></a><br /> <a href="https://github.com/ileaxer/node-16-win7" title="Code">💻</a></td>
</table>

# Fotoğraflı Anlatım
![1](https://user-images.githubusercontent.com/90086777/160903784-f4c9c1db-459c-44ea-85f6-dceed2f0f201.png)
![2](https://user-images.githubusercontent.com/90086777/160903796-83f4eebf-4f6e-4e36-b696-e6cbf0b93433.png)
![3](https://user-images.githubusercontent.com/90086777/160903805-bb020c3f-9ca2-447d-8953-787125ada6ca.png)
![4](https://user-images.githubusercontent.com/90086777/160903956-3618edac-2d56-4e8b-bb2f-955919013a40.png)
![5](https://user-images.githubusercontent.com/90086777/160903843-be9f3b46-ee93-42f1-aa16-aa074d10386d.png)
