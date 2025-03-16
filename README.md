# Hospital
 Bu proje, acil servisteki hasta kayıt ve işleyiş süreçlerini dijital ortamda simüle etmek amacıyla geliştirilmiştir.
Hastane Acil Servis Sistemi

📌 Proje Açıklaması

Bu proje, C dili ile yazılmış bir Hastane Acil Servis Sistemi uygulamasıdır. Öncelik bazlı hasta sıralama, doktora atama, reçete numarası üretme gibi temel işlevleri içermektedir. Bağlı liste, öncelik kuyruğu, dairesel kuyruk ve hash tablosu gibi veri yapıları kullanılmıştır.

🚀 Kullanılan Veri Yapıları

Bağlı Liste: Hasta kayıtlarının saklanması için kullanıldı.

Öncelik Kuyruğu: Hastaların aciliyet durumuna göre sıralanması sağlandı.

Dairesel Kuyruk: Hastaların doktora atanmasını yönetmek için kullanıldı.

Hash Tablosu: Reçete numaralarının saklanması ve hızlı erişim için kullanıldı.

📂 Dosya Yapısı

📁 Hastane_Acil_Servisi
│── 📄 main.c        # Ana program dosyası
│── 📄 README.md     # Proje açıklamaları
│── 📄 flowcharts/   # Akış şemaları

⚙️ Kurulum ve Çalıştırma

Derleme:

gcc main.c -o hastane

Çalıştırma:

./hastane

🏥 Uygulama İşleyişi

Hasta ekleme → Hasta bilgileri sisteme kaydedilir.

Triage sıralama → Önceliğe göre hastalar sıralanır.

Doktora atama → Sıradaki hasta doktora yönlendirilir.

Reçete üretimi → Hastaya reçete numarası atanır.

Hasta taburcu etme → Muayenesi biten hasta sistemden çıkarılır.

Hasta listesini görüntüleme → Kayıtlı hastalar listelenir.

📊 Akış Şemaları

1️⃣ Hasta Kayıt Süreci

Başla → Hasta bilgileri al → Sisteme kaydet → Kayıt tamamlandı

2️⃣ Triage Öncelik Sıralama

Başla → Hastaları önceliğe göre sırala → Öncelikli hasta belirle → Bitir

3️⃣ Doktora Atama

Başla → Sıradaki hastayı belirle → Doktora ata → Bitir

4️⃣ Hasta Taburcu

Başla → Muayene tamamlandı mı? → Evet → Taburcu et → Bitir

📜 Lisans

Bu proje eğitim amaçlı geliştirilmiştir ve açık kaynak olarak paylaşılmıştır.

