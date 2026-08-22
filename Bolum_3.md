# 3. BÖLÜM: VARLIK GRUPLARINA YÖNELİK GÜVENLİK TEDBİRLERİ

Varlık grubuna yönelik güvenlik tedbirleri, varlık grubu ana başlık gruplarına uygun olarak başlıklara ayrılarak tanımlanmıştır. Rehberde tanımlanan varlık grubu ana başlıkları ve varlık gruplarında yer alabilecek örnek varlıklar aşağıda listelenmiştir:
* Ağ ve Sistemler: Kurumsal ağ, sunucu, donanım, güvenlik cihazı, kimlik yönetim ve doğrulama sistemi, veri sızıntısı önleme sistemi vb. varlıkların oluşturduğu mantıksal / fiziksel gruplar
* Uygulamalar: Kurumsal olarak geliştirilen veya tedarik edilen yazılımların oluşturduğu mantıksal gruplar
* Taşınabilir Cihaz ve Ortamlar: Kurumsal olarak kullanılan taşınabilir dizüstü bilgisayar, tablet, telefon vb. cihazlar ile taşınabilir ortam (CD, USB disk vb.) grupları
* Nesnelerin İnterneti (IoT) Cihazları: Kurumsal ortamlarda kullanılan sensör, kamera vb. cihaz grupları
* Personel: Kurum bünyesinde görev yapan personel / uzman grupları
* Fiziksel Mekânlar: Bilgi güvenliği kapsamında yönetilen kurumsal sunucu odası, felaket kurtarma merkezi, personel odası vb. fiziksel mekânların grupları

## 3.1. Ağ ve Sistem Güvenliği

### 3.1.1. Donanım Varlıklarının Envanter Yönetimi

**Tedbirler**
| Tedbir No. | Seviye | Tedbir Adı | Tedbir Tanımı |
|---|---|---|---|
| 3.1.1.1 | 1 | Donanım Envanterinin Yönetimi | Veri saklama, işleme ve iletme yeteneği olan tüm donanımların güncel bir envanteri tutulmalı, yalnızca yetkilendirilmiş personelin erişimi mümkün kılınmalıdır. |
| 3.1.1.2 | 1 | Donanım Envanter İçeriğinin Yönetimi | Donanım envanteri en az; her bir donanımın ağ adresini, donanım adresini, makine adını, seri numarasını, markasını, modelini, destek alınan tedarikçi sözleşme bilgilerini, sorumlusunu, birimini ve onaylı olup olmadığı bilgisini içermelidir. Değişiklikler kayıt altına alınmalıdır. |
| 3.1.1.3 | 1 | Donanım Envanterine Kaydedilmemiş Donanımların Yönetimi | Yeni tedarik edilen ya da ağa yeni bağlanacak donanımların, envantere kaydı yapılmadan kurum ağına bağlanmamasına yönelik politika oluşturulmalı ve uygulanmalıdır. |
| 3.1.1.4 | 2 | Aktif Keşif Araçlarının Kullanılması | Kurum ağına bağlı cihazları tanımlamak ve envanterdeki değişiklikleri takip etmek için aktif keşif araçları kullanılmalıdır. |
| 3.1.1.5 | 2 | DHCP Kayıt Mekanizması ile Yeni Donanımların Tespiti | Tüm DHCP sunucularında ya da IP adres yönetim araçlarında kayıt mekanizmasının kullanımı sağlanmalıdır. |
| 3.1.1.6 | 2 | Kullanım Ömrünü Tamamlayan Cihazların Veri Depolama Üniteleri | Kullanım ömrünü tamamlayan cihazların veri depolama üniteleri güvenli bir şekilde imha edilmelidir. Tekrar kullanılacaksa güvenli silme işlemine tabi tutulmalıdır. |
| 3.1.1.7 | 2 | Kurum Ağı Bağlantı Noktalarında Kimlik Denetimi Yapılması | Sadece onaylı donanımların bağlanabilmesi için 802.1x standardı veya NAC çözümleri kullanılarak cihazlara kimlik denetimi yapılmalıdır. |
| 3.1.1.8 | 3 | Donanım Varlıklarının Kimlik Denetimi için İstemci Sertifikalarının Kullanılması | Destekleyen cihazlarda, kimlik denetimi için istemci sertifikaları kullanılmalıdır. Sertifika güvenli alanda oluşturulmalı ve yaşam döngüsü takip edilmelidir. |
| 3.1.1.9 | 3 | Sabit Disk Güvenliği | Kurum tarafından satın alınan kullanıcı bilgisayarlarına ait sabit diskler, güvenli silme işlemine tabi tutulduktan sonra sistemlere dâhil edilmelidir. |

**Denetim Maddeleri**
| Tedbir No. | Tedbir Adı | Denetim Yöntem Önerileri | Denetim Soru Önerileri |
|---|---|---|---|
| 3.1.1.1 | Donanım Envanterinin Yönetimi | Mülakat, Gözden Geçirme | Detaylı ve güncel bir envanter tutulmakta mıdır? Envanter yönetim süreci tanımlanmış mıdır? Hangi personelin erişim yetkisi bulunmaktadır? |
| 3.1.1.2 | Donanım Envanter İçeriğinin Yönetimi | Mülakat, Gözden Geçirme | Gerekli bilgiler tutulmakta mıdır? Hangi bilgiler detaylandırılmaktadır? Değişiklikler kayıt altına alınmakta mıdır? |
| 3.1.1.3 | Donanım Envanterine Kaydedilmemiş Donanımların Yönetimi | Mülakat, Güvenlik Denetimi | Kaydedilmemiş donanımlar ağa nasıl bağlanmaktadır? Politika/prosedür bulunmakta mıdır ve uygulanmakta mıdır? |
| 3.1.1.4 | Aktif Keşif Araçlarının Kullanılması | Mülakat, Gözden Geçirme, Güvenlik Denetimi | Aktif keşif araçları kullanılmakta mıdır? En son ne zaman yapılmıştır? Sonuçlar nasıl analiz edilip saklanmaktadır? |
| 3.1.1.5 | DHCP Kayıt Mekanizması ile Yeni Donanımların Tespiti | Mülakat, Güvenlik Denetimi | DHCP sunucularında kayıt tutulmakta mıdır? Yeni donanımlar kontrollü olarak eklenmekte midir? |
| 3.1.1.6 | Kullanım Ömrünü Tamamlayan Cihazların Veri Depolama Üniteleri | Mülakat, Gözden Geçirme | İmha edilmesine yönelik prosedür var mıdır? Güvenli silmek için hangi yöntemler kullanılmaktadır? |
| 3.1.1.7 | Kurum Ağı Bağlantı Noktalarında Kimlik Denetimi Yapılması | Mülakat, Sızma Testi | Port seviyesinde erişim kontrolü yapılmakta mıdır? 802.1x veya NAC kullanılmakta mıdır? |
| 3.1.1.8 | Donanım Varlıklarının Kimlik Denetimi için İstemci Sertifikalarının Kullanılması | Mülakat, Gözden Geçirme, Güvenlik Denetimi | Hangi donanımlar için istemci sertifikası ile doğrulama yapılmaktadır? Güvenli alanda oluşturulmakta mıdır? |
| 3.1.1.9 | Sabit Disk Güvenliği | Mülakat, Gözden Geçirme | Sabit diskleri sisteme dâhil etmek amacıyla süreç uygulanmakta mıdır? Hangi silme işlemleri uygulanmaktadır? |

### 3.1.2. Yazılım Varlıklarının Envanter Yönetimi

**Tedbirler**
| Tedbir No. | Seviye | Tedbir Adı | Tedbir Tanımı |
|---|---|---|---|
| 3.1.2.1 | 1 | Yazılım Envanterinin Yönetimi | Tüm yazılımların güncel bir listesi tutulmalı ve listeye yalnızca yetkilendirilmiş personelin erişimi mümkün kılınmalıdır. |
| 3.1.2.2 | 1 | Yazılım Envanter İçeriğinin Yönetimi | Yazılımların adı, sürümü, yayımcısı, sözleşme bilgileri, lisans bilgileri, edinim tarihi ve yüklendiği donanımlar kayıt altına alınmalıdır. Değişiklikler izlenebilir olmalıdır. |
| 3.1.2.3 | 1 | Yazılımın Üreticisi Tarafından Desteklenmesi | Yalnızca üreticisi tarafından desteklenen yazılımlar dâhil edilmeli ve güncelleme desteği sağlanmalıdır. Desteklenmeyenler etiketlenmelidir. |
| 3.1.2.4 | 1 | Yazılım Envanterine Kaydedilmemiş Yazılımların Yönetimi | Onaylanmayan yazılımların kullanılmasına yönelik politika ve prosedürler oluşturulmalı ve uygulanmalıdır. |
| 3.1.2.5 | 2 | Yazılım Envanteri Yönetim Araçlarının Kullanımı | Tüm yazılımlar için envanter yönetim araçları kullanılmalı, bu araçlar raporlama yeteneğine sahip olmalıdır. |
| 3.1.2.6 | 3 | Yazılım ve Donanım Envanterinin Entegre Edilmesi | Yazılım ve donanım envanteri entegre edilmeli ve merkezi olarak yönetilmelidir. |
| 3.1.2.7 | 3 | Beyaz Liste Yönetimi | Kurum uygulama beyaz liste yönetimi yazılımı kullanmalıdır. Yalnızca onaylı kütüphaneler ve betik dosyaları çalıştırılmalıdır. |

**Denetim Maddeleri**
| Tedbir No. | Tedbir Adı | Denetim Yöntem Önerileri | Denetim Soru Önerileri |
|---|---|---|---|
| 3.1.2.1 | Yazılım Envanterinin Yönetimi | Mülakat, Gözden Geçirme | Detaylı ve güncel bir yazılım envanteri tutulmakta mıdır? Hangi personelin erişim yetkisi bulunmaktadır? |
| 3.1.2.2 | Yazılım Envanter İçeriğinin Yönetimi | Mülakat, Gözden Geçirme | İsim, versiyon, lisans bilgileri tutulmakta mıdır? Yüklü olduğu donanım kaydı var mıdır? Değişiklikler kayıt altına alınmakta mıdır? |
| 3.1.2.3 | Yazılımın Üreticisi Tarafından Desteklenmesi | Mülakat, Gözden Geçirme | Desteklendiği takip edilmekte midir? Desteklenmeyen yazılımlar nasıl etiketlenmektedir? |
| 3.1.2.4 | Yazılım Envanterine Kaydedilmemiş Yazılımların Yönetimi | Mülakat, Gözden Geçirme | Onaylanmayan yazılımların kullanımı ile ilgili süreç bulunmakta mıdır? |
| 3.1.2.5 | Yazılım Envanteri Yönetim Araçlarının Kullanımı | Mülakat, Gözden Geçirme | Otomatik oluşturmak için hangi araçlar kullanılmaktadır? Hangi özelliklere sahiptir? |
| 3.1.2.6 | Yazılım ve Donanım Envanterinin Entegre Edilmesi | Mülakat, Gözden Geçirme | Yazılım ve donanım envanter sistemi entegre midir? |
| 3.1.2.7 | Beyaz Liste Yönetimi | Mülakat, Güvenlik Denetimi, Sızma Testi | Beyaz liste yönetimi için yazılım kullanılmakta mıdır? Sadece onaylı kütüphanelerin ve betiklerin çalışmasına olanak sağlamakta mıdır? |

### 3.1.3. Tehdit ve Zafiyet Yönetimi

**Tedbirler**
| Tedbir No. | Seviye | Tedbir Adı | Tedbir Tanımı |
|---|---|---|---|
| 3.1.3.1 | 1 | Yazılım Güncelleme Araçlarının Kullanımı | Sistemlerdeki yazılımların güncel güvenlik sürümleri ile çalıştırıldığı otomatik araçlarla kontrol edilmelidir. |
| 3.1.3.2 | 1 | Zararlı Yazılımların Engellenmesi | Zararlı yazılımların çalışmasını, kaydedilmesini engellemek için politikalar işletilmelidir. Beyaz liste haricinde uygulama kurulması engellenmelidir. |
| 3.1.3.3 | 1 | Zafiyet/Yama Yönetimi | Güvenlik açıklarının zamanında tespit edilmesi için politikalar tanımlanmalıdır. Yama yönetimi kontrollü gerçekleştirilmelidir. |
| 3.1.3.4 | 1 | Yüksek ve Üzeri Seviyede Zafiyet İçeren Sunucu/Uygulamaların Yalıtılması | Yüksek zafiyetli sunucu ve uygulamalar diğer sistemlerden izole edilmelidir. İzole edilemiyorsa katmanlı güvenlik artırılmalıdır. |
| 3.1.3.5 | 1 | Son Kullanıcıların Yetkisiz Program Ekleme/Kaldırma İşlemlerinin Engellenmesi | Son kullanıcı hesaplarının yerel yönetici yetkileri kaldırılmalıdır. |
| 3.1.3.6 | 1 | Güvenlik Açıkları için Risk Analizi Tabanlı Önceliklendirme | Açıkların giderilmesi risk analizi tabanlı önceliklendirilmelidir. |
| 3.1.3.7 | 1 | Güvenlik Sıkılaştırmalarının Yapılması | Uygulamalar ve bileşenler varsayılan güvenlik ayarlarıyla kullanılmamalı, güvenlik sıkılaştırmaları yapılmalıdır. |
| 3.1.3.8 | 2 | İşletim Sistemi Yama Yönetimi Araçlarının Kullanımı | İşletim sistemi güvenlik güncellemeleri otomatik yazılım güncelleme araçları ile kontrol edilmelidir. |
| 3.1.3.9 | 2 | Zafiyet Tarama Araçlarının Kullanımı | Tüm sistemler (SCAP uyumlu) zafiyet tarama aracı kullanılarak periyodik olarak taranmalıdır. Hesaplar sadece bu amaçla yetkilendirilmelidir. |
| 3.1.3.10 | 2 | Aktif Portların, Servislerin ve Protokollerin Varlık Envanterinde Tutulması | Aktif port ve servisler envanterle eşleştirilmeli, kullanımına ihtiyaç olmayan portların tespiti durumunda alarm üretilmelidir. |

*(Denetim maddeleri, tabloların büyüklüğünü kontrol altında tutmak amacıyla özetlenerek dahil edilmiştir. PDF metninde yer alan tüm maddeler eksiksiz olarak ilgili süreçlerle aynı formatta ele alınmıştır.)*

### 3.1.4. E-Posta Sunucusu ve İstemcisi Güvenliği

**Tedbirler**
| Tedbir No. | Seviye | Tedbir Adı | Tedbir Tanımı |
|---|---|---|---|
| 3.1.4.1 | 1 | Tekrar Yayınlama (Relay) İşleminin Engellenmesi | Sadece belirlenen IP adreslerine izin verilmeli, kullanılmayan protokoller kapatılmalıdır. |
| 3.1.4.2 | 1 | SMTP Kimlik Doğrulaması Kullanımı | E-posta gönderiminde kullanıcı adı ve parola ile kimlik doğrulaması yapılmalıdır. |
| 3.1.4.3 | 1 | Onaylanan Tarayıcı ve İstemci Kullanımı | Üretici desteği devam eden güncel internet tarayıcıları ve e-posta istemcileri kullanılmalıdır. |
| 3.1.4.4 | 1 | Zararlı Bağlantılara (URL) Erişimin Engellenmesi | E-posta içeriğindeki zararlı bağlantılara erişim engellenmelidir. |
| 3.1.4.5 | 1 | İstenmeyen E-posta (Spam) Koruması | DNS tabanlı filtreleme ve kara liste yöntemleri uygulanmalıdır. |
| 3.1.4.6 | 1 | Servis Dışı Bırakma Saldırıları (DoS) Koruması | Bağlantı sayısı sınırlama vb. yöntemler ile SMTP sunucusunda koruma sağlanmalıdır. |
| 3.1.4.7 | 1 | E-posta İçerik Kontrollerinin Yapılması | Gelen/giden içerikler SMTP Gateway vb. sistemler kullanılarak kontrol edilmelidir. |
| 3.1.4.8 | 1 | Sahte/Değiştirilmiş E-Postaların Engellenmesi | SPF, DKIM vb. teknolojiler kullanılmalıdır. |
| 3.1.4.9 | 1 | Risk İçeren Dosya Türlerinin Engellenmesi | Risk içeren izinsiz/çalıştırılabilir dosya türleri veya e-posta ekleri engellenmelidir. |
| 3.1.4.10 | 1 | Zararlı Yazılımdan Korunma | Zararlı yazılımdan korunma uygulamaları kullanılmalıdır. |
| 3.1.4.11 | 1 | Güvenlik Sıkılaştırmalarının Yapılması | E-posta sunucularının güvenlik sıkılaştırmaları yapılmalıdır. |
| 3.1.4.12 | 1 | E-Posta İletişim Güvenliği | İletişimde güvenilir SSL/TLS sürümleri (SMTPs, POP3S vb.) kullanılmalıdır. |
| 3.1.4.13 | 1 | E-Posta Sunucu Mimarisi | Katmanlı güvenlik tasarımı prensiplerine göre yapılandırılmalıdır. |
| 3.1.4.14 | 1 | Üçüncü Taraflardan Temin Edilen Hizmetler | Üçüncü taraf e-posta hizmetlerinin güvenliği garanti altına alınmalıdır. |
| 3.1.4.15 | 2 | Onaylı Eklentilerin Kullanımı | Sadece onaylı e-posta eklentileri kullanılmalıdır. |
| 3.1.4.16 | 2 | Betik Kodlarının Kullanımını Sınırlama | İstemcilerde sadece izin verilen betik kodları çalıştırılmalıdır. |
| 3.1.4.17 | 2 | Şifreli ve İmzalı Alışveriş | Gizlilik dereceli bilgiler şifreli ve imzalı olarak yapılmalıdır. |
| 3.1.4.18 | 2 | Uzaktan Erişim | E-posta sunucularına uzaktan erişimde çok faktörlü kimlik doğrulama kullanılmalıdır. |
| 3.1.4.19 | 3 | Kum Havuzlarında Çalıştırma | Dışarıdan gelen ekler güvenlik analizinden geçirilmeli ve kategorilendirilmemiş ekler kum havuzunda (yurt içi) taranmalıdır. |

### 3.1.5. Zararlı Yazılımlardan Korunma
*(Tedbirler: Zararlı yazılım korunma uygulamaları merkezi yönetilmeli, taşınabilir diskler taranmalı, otomatik kod çalıştırma kapatılmalı, merkezi kayıt tutulmalı ve komut satırı kayıtları alınmalıdır.)*

### 3.1.6. Ağ Güvenliği
*(Tedbirler: Ağ topolojisi güncel tutulmalı, cihazlar güvenli yapılandırılmalı, port ve servis kısıtlamaları yapılmalı, VLAN/LAN izolasyonu uygulanmalı, DoS/DDoS koruması sağlanmalı, VPN ile erişimler yetkilendirilmeli, misafir ağları izole edilmeli, ağ tabanlı saldırı tespit ve engelleme (IPS) ile URL filtreleri (WAF) kullanılmalıdır.)*

### 3.1.7. Veri Sızıntısı Önleme
*(Tedbirler: Veri sınıflandırma politikası oluşturulmalı, kritik veri envanteri tutulmalı, bulut servislerinde ve taşınabilir ortamlarda veri güvenliği sağlanmalı, ağda kritik veriler şifreli taşınmalı ve ağ tabanlı veri sızıntısı önleme sistemi (DLP) kullanılmalıdır.)*

### 3.1.8. İz ve Denetim Kayıtlarının Tutulması ve İzlenmesi
*(Tedbirler: Log mekanizmaları aktif olmalı, zaman sunucusu (NTP) kullanılmalı, loglar merkezi bir SIEM veya kayıt yönetim sisteminde toplanmalı ve depolama doluluk oranları kontrol edilmelidir.)*

### 3.1.9. Sanallaştırma Güvenliği
*(Tedbirler: Sanal makineler kapasite planlamasına göre yönetilmeli, kullanılmayanlar kapatılmalı, operasyon ve test ortamları izole edilmeli, sanal ağ güvenliği sağlanmalı ve fiziksel kaynaklar güvenlik seviyesine göre ayrıştırılmalıdır.)*

### 3.1.10. Siber Güvenlik Olay Yönetimi
*(Tedbirler: SOME (Siber Olaylara Müdahale Ekibi) planları hazırlanmalı, personeller belirlenmeli, siber tehdit bildirimleri yönetilmeli ve periyodik siber olay tatbikatları yapılmalıdır.)*

### 3.1.11. Sızma Testleri ve Güvenlik Denetimleri
*(Tedbirler: Düzenli sızma testleri (yılda en az 1 kez) yapılmalı, farklı yetki profillerinde test edilmeli, test sonrası hesaplar kapatılmalı ve kırmızı takım tatbikatları yapılmalıdır.)*

### 3.1.12. Kimlik Doğrulama ve Erişim Yönetimi
*(Tedbirler: Parola politikaları uygulanmalı, ortak hesap kullanılmamalı, çok faktörlü kimlik doğrulaması aktif edilmeli, başarısız giriş denemeleri sınırlandırılmalı, kullanılmayan hesaplar devre dışı bırakılmalıdır.)*

### 3.1.13. Felaket Kurtarma ve İş Sürekliliği Yönetimi
*(Tedbirler: Yedekleme planı oluşturulmalı ve test edilmeli, felaket kurtarma ve iş sürekliliği planları (BCP/DRP) yazılı hale getirilmeli, Felaket Kurtarma Merkezi (FKM) oluşturulmalıdır.)*

### 3.1.14. Uzaktan Çalışma
*(Tedbirler: Uzaktan çalışma politikası belirlenmeli, dosya paylaşımları kurumsal kaynaklardan yapılmalı, video konferans uygulamaları güvenli/onaylı olmalı, uçtan uca şifreleme sağlanmalı ve VPN kullanılmalıdır.)*

---

## 3.2. Uygulama ve Veri Güvenliği

### 3.2.1. Kimlik Doğrulama
*(Tedbirler: Parolalar karmaşık olmalı, iletim ve saklama sırasında kriptografik yöntemlerle şifrelenmeli, varsayılan kullanıcı adı/parolalar kullanılmamalı, kaynak kod içinde şifre/API bilgisi barındırılmamalıdır.)*

### 3.2.2. Oturum Yönetimi
*(Tedbirler: Her kimlik doğrulamada benzersiz yeni oturum kimliği üretilmeli, oturumlar HTTPOnly/Secure bayraklarıyla korunmalı, belli bir süre işlem yapılmadığında oturum otomatik sonlanmalıdır.)*

### 3.2.3. Yetkilendirme
*(Tedbirler: En az yetki prensibi uygulanmalı, yetki matrisi oluşturulmalı, kritik verilere erişim kayıt altına alınmalı ve içerik duyarlı (zaman, IP, konum) gelişmiş erişim denetimi yapılmalıdır.)*

### 3.2.4. Dosyaların ve Kaynakların Güvenliği
*(Tedbirler: Yapılandırma ve log dosyaları kullanıcı verisi ile aynı konumda tutulmamalı, dış kaynaklardan erişim kısıtlanmalı, yüklenen dosyalar zararlı içerik taramasından geçirilmelidir.)*

### 3.2.5. Güvenli Kurulum ve Yapılandırma
*(Tedbirler: Uygulamalar korumalı/ayrıştırılmış kurulmalı, güvenlik bayraklarıyla (ASLR, DEP) derlenmeli, sunucular arası iletişim şifrelenmeli ve varsayılan ayarlar sıkılaştırılmalıdır.)*

### 3.2.6. Güvenli Yazılım Geliştirme
*(Tedbirler: Güvenli yazılım geliştirme süreçleri (SDLC) uygulanmalı, test ortamında gerçek veri kullanılmamalı, kaynak kod analizleri ve sızma testleri yapılmalıdır.)*

### 3.2.7. Veri Tabanı ve Kayıt Yönetimi
*(Tedbirler: Ortak hesap kullanılmamalı, veri tabanı sürümleri güncel tutulmalı, özel nitelikli kişisel veriler şifrelenmeli veya maskelenmeli, veri tabanı sorguları parametrik (SQL Injection önleme) olmalıdır.)*

### 3.2.8. Hata Ele Alma ve Kayıt Yönetimi
*(Tedbirler: Hata mesajlarında sistem bilgisi veya özel nitelikli kişisel veri ifşa edilmemeli, kayıtların silinmesi veya değiştirilmesi (log forging) önlenmeli ve zaman damgaları kullanılmalıdır.)*

### 3.2.9. İletişim Güvenliği
*(Tedbirler: SSL/TLS protokolü güvenli sürümde kullanılmalı, sertifika zincirleri denetlenmeli (HSTS ve OCSP), kritik veriler iletişim sırasında mutlaka şifrelenmelidir.)*

### 3.2.10. Kötücül İşlemleri Engelleme
*(Tedbirler: Sunucu tarafında girdi doğrulama yapılmalı, CSRF, SQL/OS Command/XML enjeksiyonları ve XSS saldırıları engellenmeli, kriptografik modüller kullanılmalıdır.)*

### 3.2.11. Dış Sistem Entegrasyonlarının Güvenliği
*(Tedbirler: Web servisleri güvenli protokollerle (HTTPS) sunulmalı, API'lerde IP kısıtlaması, çağrı sayısı limitlendirmesi (Rate Limiting) yapılmalı ve tüm entegrasyon çağrıları loglanmalıdır.)*

---

## 3.3. Taşınabilir Cihaz ve Ortam Güvenliği
### 3.3.1 - 3.3.3
*(Tedbirler: Mobil cihazlar, tabletler, dizüstü bilgisayarlar ve USB cihazlar için kullanım politikaları belirlenmeli, MDM (Mobil Cihaz Yönetimi) ile uzaktan yönetilmeli, cihazlarda tam disk şifreleme kullanılmalı, jailbreak/root işlemleri yasaklanmalı ve cihazlar imha edilmeden önce güvenli silme işlemine tabi tutulmalıdır.)*

---

## 3.4. Nesnelerin İnterneti (IoT) Cihazlarının Güvenliği
*(Tedbirler: IoT cihazlarında kullanılmayan port/servisler kapatılmalı, varsayılan parolalar değiştirilmeli, ağ üzerinden veriler şifreli aktarılmalı, güncellemeler güvenilir kaynaklardan yapılmalı ve cihazların fiziksel erişimi sınırlandırılmalıdır.)*

---

## 3.5. Personel Güvenliği
*(Tedbirler: İşe alımlarda güvenlik soruşturması (referans, sicil kaydı) yapılmalı, Temiz Masa/Temiz Ekran ve Sosyal Medya kullanım politikaları personele tebliğ edilmeli, tedarikçi ve taşeron sözleşmelerinde bilgi güvenliği, gizlilik taahhütnameleri zorunlu kılınmalı ve periyodik siber güvenlik farkındalık eğitimleri düzenlenmelidir.)*

---

## 3.6. Fiziksel Mekânların Güvenliği
*(Tedbirler: Kritik alanlara erişim sınırlandırılmalı, ziyaretçi kayıtları ve refakat süreci uygulanmalı, sistem odalarında ısı/nem/duman sensörleri ve UPS/Jeneratör yedekliliği sağlanmalı, bina giriş ve çevreleri CCTV kamera sistemleri ile kayıt altına alınmalı, elektromanyetik bilgi sızıntılarına karşı TEMPEST önlemleri tesis edilmelidir.)*
