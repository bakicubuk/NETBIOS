# NETBIOS

NetBIOS, Windows'ta varsayılan olarak hala etkin olan eski bir ağ protokolüdür. NetBIOS'u tamamen devre dışı bırakan bir GPO olmadığından, her ağ arayüzünün ayarlarının değiştirilmesi gerekir.
Bu işlem kurulum sırasında yapılsa bile, USB Ethernet adaptörleri veya USB/Thunderbolt yuvaları gibi yeni ağ arayüzleri NetBIOS'u tekrar etkinleştirir.
Bu PowerShell betiği, Windows kayıt defteri aracılığıyla tüm arayüzler için NetBIOS'u devre dışı bırakır ve örneğin zamanlanmış bir görevle çalıştırılabilir. Değişiklikler yeniden başlatmanın ardından uygulanır
