# 5. BÖLÜM: SIKILAŞTIRMA TEDBİRLERİ

## 5.1. İşletim Sistemi Sıkılaştırma Tedbirleri

**Amaç**
Bu güvenlik tedbiri ana başlığının amacı, işletim sistemi güvenlik sıkılaştırmaları çerçevesinde ele alınan tedbir listeleri ve denetim sorularını belirlemektir. "İşletim Sistemi Sıkılaştırma Tedbirleri" ana başlığı kapsamında ele alınan güvenlik tedbirleri alt başlıkları aşağıda yer almaktadır:
* Genel Sıkılaştırma Tedbirleri
* Linux İşletim Sistemi Sıkılaştırma Tedbirleri
* Windows İşletim Sistemi Sıkılaştırma Tedbirleri

### 5.1.1. Genel Sıkılaştırma Tedbirleri

**Tedbirler**
| Tedbir No. | Seviye | Tedbir Adı | Tedbir Tanımı |
|---|---|---|---|
| 5.1.1.1 | 1 | Kurulum Güvenliği | Kurulumda kullanılan işletim sistemi dosyalarının özet bilgisi orijinal dağıtıcı özet değerleriyle teyit edilmelidir. |
| 5.1.1.2 | 1 | Servis Güvenliği | Gerekli olmayan tüm servisler kapatılmalıdır. Çalışan servisler en az yetki ile çalışmalıdır ve döndürdükleri başlık bilgileri (banner) bilgi ifşasına yol açmayacak şekilde değiştirilmelidir. |
| 5.1.1.3 | 1 | Güncel İşletim Sistemi ve Uygulamaların Kullanılması | Güncel ve güvenlik desteği devam eden işletim sistemleri kullanılmalıdır. |
| 5.1.1.4 | 1 | Şifreli Haberleşen Servislerin Kullanılması | Şifresiz haberleşen servisler (Telnet, FTP, HTTP vb.) yerine şifreli muadilleri (SSH, SFTP, HTTPS vb.) kullanılmalıdır. |
| 5.1.1.5 | 1 | Parola Politikasının Belirlenmesi | Güçlü parola politikası belirlenmeli, belirli süreden sonra yenilenmeli ve hatalı girişlerde hesap kilitlenmelidir. |
| 5.1.1.6 | 1 | Son Kullanıcı Bilgisayarlarında Ağ Erişiminin Kısıtlanması | Ağ üzerinden erişim yetkisi sadece yönetici hesapları ve uzak masaüstü kullanıcıları ile sınırlandırılmalıdır. |
| 5.1.1.7 | 1 | Hata ve Sorun Bilgilerinin Üretici ile Paylaşılmaması | İşletim sistemindeki hata/sorun bilgilerinin üretici ile paylaşılması pasif hale getirilmelidir. |
| 5.1.1.8 | 1 | Kablosuz Ağ Arayüzlerinin Kapatılması | Kullanılmayan kablosuz ağ arayüzleri pasif hale getirilmelidir. |
| 5.1.1.9 | 1 | Sistem Üzerinde Düzenli Olarak Zafiyet ve Zararlı Yazılım Taraması Yapılması | Sistemde düzenli zafiyet ve zararlı yazılım taraması yapılmalıdır. |
| 5.1.1.10 | 1 | Yerel Güvenlik Duvarı Ayarlarının Yapılması | *(Bkz. 3.1.6.11)* Yerel güvenlik duvarı aktif edilmelidir. |
| 5.1.1.11 | 1 | Sunucularda Zaman Senkronizasyonunun Sağlanması | Sunucularda NTP ayarlamaları yapılarak zaman senkronizasyonu sağlanmalıdır. |
| 5.1.1.12 | 1 | Güvenli Süreç (Process) İşleme Ayarlarının Yapılması | DEP, ASLR, XD/NX gibi savunma özellikleri aktif olmalıdır. |
| 5.1.1.13 | 2 | Kullanılmayan Uygulamaların Kaldırılması | Sistemlerde kullanılmayan uygulamalar kaldırmalıdır. |
| 5.1.1.14 | 2 | Merkezi Güncelleme Sunucusu | İşletim sistemi güncellemeleri için merkezi bir sunucu kullanılmalıdır. |
| 5.1.1.15 | 2 | IPv6 Pasif Hale Getirilmesi | Kurumda IPv6 kullanılmıyorsa pasif hale getirilmelidir. |
| 5.1.1.16 | 2 | Sistem İz Kayıtlarının Aktif Edilmesi | Zaman ayarları, erişim kontrolleri, yetkisiz dosya okuma/silme ve yönetici hareketleri kayıt altına alınmalıdır. |
| 5.1.1.17 | 2 | Sistem İz Kayıtlarının Merkezi Bir Sunucuda Toplanması | İz kayıtları merkezi bir kayıt yönetim sistemine gönderilmelidir. |
| 5.1.1.18 | 2 | Merkezi Kimlik Yönetimi Servisinin Kullanılması | Kimlik doğrulaması için merkezi kimlik servisi kullanılmalıdır. |
| 5.1.1.19 | 3 | Sunucularda Çalışan Servislerin Takibi | Sunucunun işleyişi dışında açılan bir servis olursa alarm üretilmeli ve kapatılmalıdır. |
| 5.1.1.20 | 3 | Bilgisayar Tabanlı Saldırı Tespit ve Engelleme Sistemlerinin Kullanılması | Makine özelinde HIDS/HIPS kullanılmalıdır. |
| 5.1.1.21 | 3 | Disk Kotalarının Belirlenmesi | Kullanıcılar için disk kota politikaları belirlenmelidir. |
| 5.1.1.22 | 3 | Disk Seviyesinde Şifreleme Yapılması | Kritik bilgi içeren makinelerde disk seviyesinde şifreleme yapılmalıdır. |

**Denetim Maddeleri**
*(Genel sıkılaştırma tedbirleri maddelerinin uygulanıp uygulanmadığını kontrol eden güvenlik denetimi, mülakat, sızma testi gibi soru yönergeleri yer alır.)*

### 5.1.2. Linux İşletim Sistemi Sıkılaştırma Tedbirleri

**Tedbirler**
| Tedbir No. | Seviye | Tedbir Adı | Tedbir Tanımı |
|---|---|---|---|
| 5.1.2.1 | 1 | Kullanılmayan Dosya Sistemlerinin Pasif Hale Getirilmesi | cramfs, freevxfs, hfs vb. dosya sistemleri pasif hale getirilmelidir. |
| 5.1.2.2 | 1 | Yetkili Kullanıcı Hesap Yönetimi | Her kişiye ayrı hesap açılmalı, root login engellenmeli, UID 0 olan tek kullanıcı root olmalı ve sistem kullanıcılarının kabuğu /sbin/nologin olmalıdır. |
| 5.1.2.3 | 2 | Dosya Sistemi Güvenli Erişim Düzenlemeleri | SUID, SGID, cron, /etc/passwd gibi dosyaların yetkileri düzenlenmeli ve umask değeri en az yetki prensibine göre ayarlanmalıdır. |
| 5.1.2.4 | 2 | Güvenli Disk Bölümlendirme | İşletim sistemi dosyaları ile /home, /root, /tmp birimleri ayrı disk bölümlerinde tutulmalıdır. |
| 5.1.2.5 | 2 | Otomatik Başlatma (Mount) Özelliğinin Pasif Hale Getirilmesi | USB, CD/DVD gibi medyaların otomatik başlatılması pasif hale getirilmelidir. /tmp gibi mount noktalarında çalıştırılabilir dosyalar pasif edilmelidir. |
| 5.1.2.6 | 2 | Dosya Sistemi Bütünlük Kontrollerinin Düzenli Olarak Yapılması | Önemli dosyaların bütünlüğü düzenli olarak kontrol edilmelidir. |
| 5.1.2.7 | 2 | Önyükleme (Boot) Ayarlarının Güvenli Şekilde Yapılandırılması | Bootloader parolası belirlenmeli, tek kullanıcı modu için kimlik doğrulaması yapılmalı ve boot cihaz listesi kısıtlanmalıdır. |
| 5.1.2.8 | 3 | Zorunlu Erişim Kontrolünün (MAC) Aktif Edilmesi | SELinux, AppArmor vb. servislerle zorunlu erişim kontrolü sağlanmalıdır. |

### 5.1.3. Windows İşletim Sistemi Sıkılaştırma Tedbirleri

**Tedbirler**
| Tedbir No. | Seviye | Tedbir Adı | Tedbir Tanımı |
|---|---|---|---|
| 5.1.3.1 | 1 | Kullanıcı Haklarının Kısıtlanması | En az yetki prensibi uygulanarak hak kısıtlaması yapılmalıdır. |
| 5.1.3.2 | 1 | Otomatik Güncellemenin Aktif Olması | Kullanıcı makinelerinde otomatik güncelleme özelliği aktif olmalıdır. |
| 5.1.3.3 | 1 | SMB Protokolü Güvenliği | SMB v1 yerine daha güncel/güvenli SMB protokol versiyonları kullanılmalıdır. |
| 5.1.3.4 | 1 | Yerel Yönetici Hesapları Yönetimi | Gerekli olmayan yerel yönetici hesapları kapatılmalı, aynı olan parolalar değiştirilmelidir. |
| 5.1.3.5 | 1 | Ayrıcalıklı Hesap Sayılarının Sınırlandırılması | Domain Admin, Enterprise Admin vb. yetkili hesapların sayısı sınırlandırılmalıdır. |
| 5.1.3.6 | 1 | Yetkili Hesapların Parola Özetlerinin Çalınmasının Engellenmesi | Domain admin hesabıyla yerel PC'lerde işlem yapılmamalı, parola özeti tutulma sayısı 0 yapılmalı ve yetkili hesaplar Protected Users grubuna alınmalıdır. |
| 5.1.3.7 | 2 | Kullanılmayan Hesapların Devre Dışı Bırakılması | Aktif dizinde uzun süre kullanılmayan hesaplar tespit edilip pasife alınmalıdır. |
| 5.1.3.8 | 2 | Varsayılan Yönetici ve Misafir Hesaplarının Yapılandırılması | Varsayılan yönetici (Administrator) ve misafir (Guest) hesapları pasif hale getirilmelidir. |
| 5.1.3.9 | 2 | Standart Kullanıcıların Betik Çalıştırma Motorlarına Erişiminin Kısıtlanması | Standart kullanıcıların Powershell, Command Prompt vb. motorlara erişimi engellenmelidir. |
| 5.1.3.10 | 2 | Aktif Dizin Sorguları Güvenliği | Aktif dizin sorguları LDAP yerine güvenli LDAPS protokolü ile yapılmalıdır. |
| 5.1.3.11 | 2 | Yönetici Hesaplarının İzlenmesi | Etki alanı gruplarına ekleme/çıkarma işlemleri izlenmelidir. |
| 5.1.3.12 | 2 | Güvenli Yönetici İş İstasyonu Kullanımı | Domain Controller yönetimi için ayrı, güvenli bir iş istasyonu konumlandırılmalı; bu istasyondan e-posta, internet vb. erişim yapılmamalıdır. |
| 5.1.3.13 | 2 | Devre Dışı Bırakılan Hesabın Mail Erişiminin Engellenmesi | Devre dışı bırakılan hesabın Activesync e-posta erişimi anında kesilmelidir. |

---

## 5.2. Veri Tabanı Sıkılaştırma Tedbirleri

**Amaç**
Bu güvenlik tedbiri ana başlığının amacı, veri tabanı güvenlik sıkılaştırmaları çerçevesinde ele alınan tedbir listeleri ve denetim sorularını belirlemektir.

### 5.2.1. Genel Sıkılaştırma Tedbirleri

**Tedbirler**
| Tedbir No. | Seviye | Tedbir Adı | Tedbir Tanımı |
|---|---|---|---|
| 5.2.1.1 | 1 | Güncelleme ve Yama Yönetimi | Veri tabanı en kararlı ve güncel versiyon ile kullanılmalı, güvenlik yamaları hızlıca yüklenmelidir. |
| 5.2.1.2 | 1 | Veri Tabanı Parametrelerinin Güvenli Yapılandırılması | Üretici tarafından yayınlanan güvenli kullanım önerileri dikkate alınarak parametreler yapılandırılmalıdır. |
| 5.2.1.3 | 1 | Varsayılan Hesap ve Parolaların Kullanılmaması | Varsayılan kullanıcı hesapları ve parolalar kullanılmamalıdır. |
| 5.2.1.4 | 1 | Veri Tabanı Kullanıcıları için Parola Politikalarının Oluşturulması | Güçlü parola politikaları oluşturulmalı ve uygulanmalıdır. |
| 5.2.1.5 | 1 | Veri Tabanına Yapılan Uzak Bağlantıların Güvenliğinin Sağlanması | Uzak bağlantı sadece yetkili kullanıcılara açık olacak şekilde sınırlandırılmalıdır. |
| 5.2.1.6 | 1 | Kullanılmayan Hesapların Kapatılması | Kullanılmayan kullanıcılar pasif hale getirilmelidir. |
| 5.2.1.7 | 1 | Anonim Hesapların Bulunmaması | Ortak hesap kullanılmamalıdır, işlemler tekil bir kişi/sistemi işaret etmelidir. |
| 5.2.1.8 | 1 | Veri Tabanı Rol ve Yetkilerinin Kısıtlanması | Ayrıcalıklar doğrudan kullanıcı yerine rollere verilmeli, kullanılmayan veya gereksiz roller/yetkiler kaldırılmalıdır. |
| 5.2.1.9 | 1 | İşletim Sistemi Üzerindeki Ayrıcalıkların Sınırlandırılması | Veri tabanının, işletim sistemindeki komut çalıştırma veya yerel dosya okuma/yazma gibi ayrıcalıkları sınırlandırılmalıdır. |
| 5.2.1.10 | 1 | Komut/Sorgu Geçmişi Kayıtlarının Güvenliğinin Sağlanması | Çalıştırılmış komut ve sorgu geçmişi dosyalarının güvenliği sağlanmalıdır. |
| 5.2.1.11 | 1 | Yedeklerin Güvenliğinin Sağlanması | Yedek dosyaları yetkisiz kişilere karşı şifreleme ve dosya izni ayarlarıyla korunmalıdır. |
| 5.2.1.12 | 1 | Adanmış Sunucu Kullanılması | Saldırı yüzeyini düşürmek için veri tabanı adanmış (dedicated) bir sunucu üzerinde çalışmalıdır. |
| 5.2.1.13 | 1 | Kurulum Dosyalarının Güvenilir Kaynaklardan Temin Edilmesi | Kurulum paketleri güvenilir kaynaklardan elde edilmelidir. |
| 5.2.1.14 | 1 | Örnek Verilerin Silinmesi | Kurulum ile gelen örnek tablolar, kayıtlar vb. veri tabanından silinmelidir. |
| 5.2.1.15 | 2 | Veri Tabanı Sistem Dosyalarının ve İz Kayıtlarının Aynı Disk Bölümü Üzerinde Bulunmaması | Sistem dosyaları ve iz kayıtları farklı disk bölümlerinde tutulmalıdır. |
| 5.2.1.16 | 2 | Veri Tabanında Tablo ve Nesne Düzeyinde Yetkilendirme Yapılması | Kritik veri içeren tablolar için nesne/tablo bazında yetkilendirme yapılmalıdır. |
| 5.2.1.17 | 2 | Veri Tabanı Servisi Çalıştıran Kullanıcıların Yönetici Haklarına Sahip Olmaması | Veri tabanı servisini çalıştıran işletim sistemi kullanıcısı yönetici haklarına sahip olmamalıdır. |
| 5.2.1.18 | 2 | Kümeleme veya Replikasyon İçinde Sunucular Arası İletişimin Şifrelenmesi | Replikasyon içindeki veri tabanları şifreli iletişim kurmalı ve hesap yetkileri en az yetki ile sınırlandırılmalıdır. |
| 5.2.1.19 | 2 | Merkezi Kimlik Doğrulama Sisteminin Kullanılması | Veri tabanı destekliyorsa, merkezi kimlik doğrulama sistemi kullanılmalıdır. |
| 5.2.1.20 | 3 | Durağan Verinin Güvenliğinin Sağlanması | Kritik veri içeren veri tabanı sunucularında disk/depolama seviyesinde veriler şifrelenmelidir. |
| 5.2.1.21 | 3 | Veri Tabanı Sunucusu ile İstemci Arasındaki İletişimin Şifreli Olması | Veri tabanı sunucusu ile istemci arasındaki bağlantı şifreli olmalıdır. |

---

## 5.3. Sunucu Sıkılaştırma Tedbirleri

**Amaç**
Bu güvenlik tedbiri ana başlığının amacı, sunucu güvenlik sıkılaştırmaları çerçevesinde ele alınan tedbir listeleri ve denetim sorularını belirlemektir.
* Web Sunucusu Sıkılaştırma Tedbirleri
* Sanallaştırma Sunucusu Sıkılaştırma Tedbirleri

### 5.3.1. Web Sunucusu Sıkılaştırma Tedbirleri

**Tedbirler**
| Tedbir No. | Seviye | Tedbir Adı | Tedbir Tanımı |
|---|---|---|---|
| 5.3.1.1 | 1 | Güncel Web Sunucu Yazılımlarının Kullanılması | Web sunucusu en güncel, desteklenen, kararlı sürümünde olmalı ve yamalar takip edilmelidir. |
| 5.3.1.2 | 1 | WebDAV Desteğinin Kaldırılması | WebDAV desteği ve modülleri pasif hale getirilmelidir. |
| 5.3.1.3 | 1 | Web Sunucusu Kullanıcı Yönetimi | Özel olarak oluşturulmuş bir hesapla çalıştırılmalı, varsayılan hesaplar kaldırılmalıdır. |
| 5.3.1.4 | 1 | Web Sunucusunun Bilgi İfşalarını Önleyecek Şekilde Yapılandırılması | Varsayılan hata/kurulum sayfaları ile HTTP başlıklarındaki versiyon bilgileri kaldırılmalıdır. |
| 5.3.1.5 | 1 | Desteklenen HTTP Metotlarının Kısıtlanması | Sadece POST, GET, OPTIONS ve HEAD vb. kısıtlı metotlar desteklenmelidir. PUT/DELETE gereksizse engellenmelidir. |
| 5.3.1.6 | 1 | Dizin Listelemenin Pasif Hale Getirilmesi | Directory Listing özelliği pasif hale getirilmelidir. |
| 5.3.1.7 | 1 | Debug Modunun Kapalı Olması | Yazılım debug modunda çalıştırılmamalıdır. |
| 5.3.1.8 | 1 | İstek Limitlerinin Tanımlanması | İstekler için limitler belirlenmelidir. |
| 5.3.1.9 | 1 | İz Kayıtlarının Alınması | Web sunucu iz kayıtları (log) alınmalıdır. |
| 5.3.1.10 | 1 | Yazma İzni Olan Dizinlerin Kısıtlanması | Sadece dosya yükleme ihtiyacı olan dizinlere yazma izni verilmeli, bu dizinlerde çalıştırma izni engellenmelidir. |
| 5.3.1.11 | 1 | SSL/TLS Kullanımı | Güvenilir ve zafiyetsiz SSL/TLS sürümleri kullanılmalıdır. |
| 5.3.1.12 | 1 | İsteklerin HTTP'den HTTPS'e Yönlendirilmesi | HTTP istekleri otomatik olarak HTTPS'e yönlendirilmelidir. |
| 5.3.1.13 | 1 | Kullanılmayan Modüllerin Kaldırılması | Sadece kullanılan aktif modüller çalışmalıdır. |
| 5.3.1.14 | 1 | Açık Portların Kısıtlanması | Yalnızca yetkili portlar dinlenmeli, kullanımda olmayan portlar kapatılmalıdır. |
| 5.3.1.15 | 1 | Kaynak Kullanım Optimizasyonu | DoS engellemek adına IP başına bağlantı sayısı, zaman aşımı ve hız limitleri belirlenmelidir. |
| 5.3.1.16 | 1 | Sunucunun Korumalı ve Ayrıştırılmış Şekilde Kurulumu | İnternete açık web sunucuları izole bir DMZ bölgesinde konumlandırılmalıdır. |
| 5.3.1.17 | 1 | Sunucuda Koruyucu HTTP Başlıklarının Kullanımı | X-Frame-Options, Strict-Transport-Security vb. koruyucu HTTP başlıkları eklenmelidir. |
| 5.3.1.18 | 1 | Sunucunun Özel Anahtarının (Private Key) Korunması | SSL özel anahtarı yetkisiz erişime karşı korunmalıdır. |
| 5.3.1.19 | 2 | İz Kayıtlarının Merkezi Kayıt Sistemine Gönderilmesi | Web sunucusu logları merkezi SIEM/Log sunucusuna iletilmelidir. |
| 5.3.1.20 | 2 | Sunucuya IP Adresi Üzerinden Erişimlerin Engellenmesi | Doğrudan IP adresi üzerinden yapılan HTTP bağlantı istekleri engellenmelidir. |

### 5.3.2. Sanallaştırma Sunucusu Sıkılaştırma Tedbirleri

**Tedbirler**
| Tedbir No. | Seviye | Tedbir Adı | Tedbir Tanımı |
|---|---|---|---|
| 5.3.2.1 | 1 | Güncel Sanallaştırma Yazılımının Kullanılması | Sanallaştırma yazılımı ve yamaları güncel olmalıdır. |
| 5.3.2.2 | 1 | Ana Makine Üzerinde Sıkılaştırmaların Yapılması | Konteyner veya sanal makinenin çalıştığı hypervisor/host makinede işletim sistemi sıkılaştırmaları yapılmalıdır. |
| 5.3.2.3 | 1 | Zaman Senkronizasyonu | Sanal makineler arasında zaman senkronizasyonu olmalıdır. |
| 5.3.2.4 | 1 | Sanallaştırma Yazılımı Güvenlik Duvarının Aktif Olması | Kendi güvenlik duvarı aktif edilmeli, sadece ihtiyaç duyulan port ve IP'lere izin verilmelidir. |
| 5.3.2.5 | 1 | Mantıksal Birim Numarası (LUN) Maskelemesi Yapılması | SAN etkinliğini ayırmak için LUN maskeleme kullanılmalıdır. |
| 5.3.2.6 | 1 | Sanallaştırma Ünitesi Üzerinden Konsol Erişimlerinin Kısıtlanması | Yetkisiz kişilerin VM konsol ekranlarını görüntülemesi engellenmeli, kimlik doğrulama zorunlu olmalıdır. |
| 5.3.2.7 | 1 | Kullanıcı Yetkilendirme | En az yetki prensibiyle kullanıcı rolleri atanmalıdır. |
| 5.3.2.8 | 1 | Gereksiz Hizmetlerin ve Kullanılmayan Donanımların Kaldırılması | Pano/dosya paylaşımı gibi gereksiz hypervisor hizmetleri ve sanal ağ/CD sürücüleri devre dışı bırakılmalıdır. |
| 5.3.2.9 | 1 | Disk Küçültme Konfigürasyonuna Erişimin Kısıtlanması | Sanal disk küçültme işlemi sadece yetkili kullanıcılara açılmalıdır. |
| 5.3.2.10 | 2 | Sanallaştırma Yazılımının Merkezi Olarak Güncellenmesi | Sanallaştırma yazılımı, sunucularda eş zamanlı merkezi güncellenmelidir. |
| 5.3.2.11 | 2 | Sanal Makineler için İz Kayıtlarının Yönetilmesi | Sanal makinelerden alınan loglar kalıcı olarak merkezi sisteme kaydedilmelidir. |
| 5.3.2.12 | 2 | Sanal Makinelerin Güvenli İmhası | Makine silinmeden önce disk dosyalarına sıfır yazılmalı ve kalıcı silme işlemi yapılmalıdır. |
| 5.3.2.13 | 2 | Bellek Paylaşımı Özelliklerinin Kullanımı | Bellek paylaşımı kullanılmıyorsa kapatılmalı; kullanılacaksa sanal makineler arasında gruplandırma yapılmalıdır. |
| 5.3.2.14 | 2 | Sunucu Yedeklerinin Alınması | Sistem yedekleri alınmalı, güvenli tutulmalı ve geri dönüş testleri yapılmalıdır. |
| 5.3.2.15 | 3 | Disk ve İmajların Şifreli Olarak Saklanması | Sanal makineye ait disk, imaj ve snapshot'lar (anlık görüntüler) şifrelenmelidir. |
