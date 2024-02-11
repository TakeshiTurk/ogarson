# ogarson
Ogarson, her müşteri için yeni bir sanal makina oluşturulmasının önüne geçerek kaynaktan tasarruf sağlar.
Her bir sunucu sahibi kendisine bir kullanıcı oluşturulması ve kontrol panelinden sunucusu için özelleştirmeleri yapabilmesi sağlanır.
Sunucunun kritik dosyaları root kontrolündedir ve silinemez, düzenlenemez, okunabilir. Yine de sunucu panelinden izin verilen değerler değiştirilebilir.
Böylece atanan ram miktarı ve port bilgisi değişmez. Port bilgisi zaten sistem tarafından sunucu başlarken atanır.

İlerleyen dönemlerde, sunucu bazlı IP atanabilirliği ya arayüz atanması ile ya da aynı arayüzde listen'ler ile sağlanacaktır. 
İki seçenek arasında kolaylık ve güvenlik analizi gerekir.

# Yol haritası
[] Temel systemd servisi.
[] Sunucu durumları ve planları için sql veritabanı.
[] Aynı ağ arayüzünde birden fazla hizmetin sunulabilmesi için otomatik port ataması.
[] Ogarson servisi ile DNS ( BIND ) kontrolü, ondemand SRV ve A kayıtları.
[] EULA onayının kullanıcı tercihine sunulması.
[] Minecraft sunucusu sağlayabilir.
[] Kullanıcı web arayüzü
[] Yönetim web arayüzü
[] Whmcs gibi paneller ile otomatik kurulum ve yönetim için API
[] Kullanıcı bazlı RAM limiti
[] Kullanıcı bazlı soft cpu limiti
...
[] Diğer oyun sunucularını sağlayabilir.
