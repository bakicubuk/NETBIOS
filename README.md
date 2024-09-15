# NETBIOS

NetBIOS, Windows'ta varsayılan olarak hala etkin olan eski bir ağ protokolüdür. NetBIOS'u tamamen devre dışı bırakan bir GPO olmadığından, her ağ arayüzünün ayarlarının değiştirilmesi gerekir.
Bu işlem kurulum sırayla yapılsa bile, USB Ethernet Adaptörleri veya USB/Thunderbolt bağlantıları gibi yeni ağ arayüzlerinde NetBIOS tekrar etkinleştirilecektir.
Bu PowerShell dosyası, Windows kayıt defteri aracılığıyla tüm arayüzler için NetBIOS'u devre dışı bırakmaktadır.
Örneğin zamanlanmış bir görevle çalıştırılabilir. Değişiklikler sistemi yeniden başlatmanın ardından uygulanmaktadır.
