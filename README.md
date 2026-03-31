📊 Custom Image Scoreboard
Minecraft sunucunuzdaki Scoreboard alanında tamamen özelleştirilebilir görseller (PNG) göstermenizi sağlayan gelişmiş bir sistem. Bu proje, hem sunucu tarafındaki plugin hem de client tarafındaki asset modifikasyonu ile senkronize çalışır.

🚀 Özellikler
Dinamik Görsel Desteği: Scoreboard üzerinde statik text yerine şık PNG görselleri.

Optimize Edilmiş Altyapı: EntityCustomPlayer sınıfları üzerinden doğrudan müdahale.

Modern Görünüm: Sunucunuza premium bir hava katar.

🛠 Kurulum Adımları
Bu sistemin düzgün çalışması için üç ana aşamayı tamamlamanız gerekmektedir:

1. Sunucu Tarafı (Plugin)

Derlenen scoreboard.jar dosyasını sunucunuzun /plugins klasörüne atın.

Sunucuyu başlatıp durdurarak gerekli konfigürasyon dosyalarının oluşmasını sağlayın.

2. Spigot Modifikasyonu (Kritik Adım)

Pluginin scoreboard görsellerini işleyebilmesi için Spigot çekirdeğinizde değişiklik yapmanız gerekir:

Kullandığınız Spigot dosyasını bir arşiv yöneticisi (WinRAR vb.) ile açın.

entitycustomplayer.class dosyasını bulun.

Bu dosya yerine, bu projenin içeriğinde bulunan EntityCustomPlayer dosyasını yerleştirin.

3. Client Tarafı (Varlık Paketi)

Oyuncuların görselleri görebilmesi için kullandıkları Client'ın asset klasörüne görseli eklemesi gerekir:

Kullanılan Client'ın assets.jar dosyasını WinRAR ile açın.

Şu dizine gidin: assets/minecraft/textures/gui/

Hazırladığınız görseli scoreboard.png adıyla bu klasöre kaydedin.

📸 Önizleme
[!TIP]
En iyi sonuçlar için scoreboard.png dosyanızın boyutlarını Scoreboard ölçeklerine uygun (örneğin 256x256 veya 512x512) ayarlamayı unutmayın.

💻 Geliştirici Notu
Bu proje Java diliyle, Minecraft protokolleri ve entity render sistemleri üzerinde derinlemesine bir çalışma sonucunda oluşturulmuştur. Herhangi bir sorunda issue açmaktan çekinmeyin!
