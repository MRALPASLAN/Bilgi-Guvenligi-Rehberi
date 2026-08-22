# 4. BÖLÜM: UYGULAMA VE TEKNOLOJİ ALANLARINA YÖNELİK GÜVENLİK TEDBİRLERİ

## 4.1. Kişisel Verilerin Güvenliği

**Amaç**
Bu güvenlik tedbiri ana başlığının amacı, kişisel verilerin güvenliği çerçevesinde ele alınan tedbir listeleri ve denetim sorularını belirlemektir. "Kişisel Verilerin Güvenliği" ana başlığı kapsamında ele alınan güvenlik tedbirleri alt başlıkları aşağıda yer almaktadır:
* Kayıt Yönetimi
* Erişim Kayıtları Yönetimi
* Yetkilendirme
* Şifreleme
* Yedekleme, Silme, Yok Etme ve Anonim Hale Getirme
* Aydınlatma Yönetimi
* Açık Rıza Yönetimi
* Kişisel Veri Yönetim Sürecinin İşletilmesi

### 4.1.1. Kayıt Yönetimi

**Tedbirler**
| Tedbir No. | Seviye | Tedbir Adı | Tedbir Tanımı |
|---|---|---|---|
| 4.1.1.1 | 1 | Kişisel Veri İşleme Envanterinin Hazırlanması ve Yönetimi | Kişisel veri işleme amaçları, hukuki dayanağı, veri kategorisi, aktarılan alıcı grubu, azami muhafaza edilme süresi, yabancı ülkelere aktarımı ve alınan güvenlik tedbirlerini açıklayan bir kişisel veri envanteri oluşturulmalı ve güncellenmelidir. |
| 4.1.1.2 | 1 | Kişisel Veri Saklama ve İmha Politikasının Hazırlanması | Yönetmeliklere uygun olarak kişisel veri saklama ve imha politikası hazırlanmalıdır. |
| 4.1.1.3 | 1 | Kişisel Verilerin Veri Tabanlarında Birincil Anahtar Olarak Kullanılmaması | T.C. kimlik numarası, pasaport numarası vb. kişisel veriler birincil anahtar (primary key) olarak kullanılmamalıdır. |
| 4.1.1.4 | 1 | Veri Tabanının Dışarıya Aktarımının Yetkili Kullanıcı Tarafından Yapılması | Kişisel veri barındıran veri tabanının dışarıya aktarımı yalnızca yetkilendirilmiş kullanıcılar tarafından yapılmalıdır. |
| 4.1.1.5 | 1 | Kişisel Verilerin Güvensiz Ortamlarda Saklanmaması | Kişisel veri barındıran kayıtlar güvensiz ortamlarda saklanmamalıdır. Zorunlu hallerde güvenli yöntemler uygulanmalıdır. |
| 4.1.1.6 | 1 | Kişisel Veri Üzerinde Girdi/Çıktı Denetimi Yapılması | Uygulamanın girdi olarak kullandığı kişisel veri üzerinde girdi/çıktı doğrulama eksikliğinden kaynaklı zafiyetlere karşı güvenlik kontrolleri uygulanmalıdır. |
| 4.1.1.7 | 1 | Kişisel Verinin Gizli Alanlarda Saklanmaması | Açık rıza olmadan kişisel veri web sayfalarının gizli alanlarında saklanmamalıdır. Çerezlerde secure flag kullanılmalıdır. |
| 4.1.1.8 | 1 | Hata Mesajlarında Mahremiyetin Korunması | Özel nitelikli kişisel veri içeren hata mesajı üretilmemelidir. |
| 4.1.1.9 | 1 | Özel Nitelikli Kişisel Verinin Saklanması | Özel nitelikli kişisel veriyi barındıran kayıtlar şifreli metin olarak, güçlü algoritmalarla saklanmalıdır. |
| 4.1.1.10 | 1 | Geçici Olarak Tutulan Kişisel Verinin Yok Edilmesi | Geçici tutulan veriler, işleme gereksinimi bittiğinde geri getirilemeyecek şekilde yok edilmelidir. |
| 4.1.1.11 | 2 | Veri Tabanı Tasarımı | Yedekleme, anonimleştirme ve aktarımı kolaylaştıracak şekilde yapılmalıdır. |

**Denetim Maddeleri**
*(Her bir tedbir maddesi için Mülakat, Gözden Geçirme, Sızma Testi ve Güvenlik Denetimi yöntemleriyle doğrulama soruları içermektedir.)*

### 4.1.2. Erişim Kayıtları Yönetimi
*(Tedbirler: Erişimlerin kayıt altına alınması, arşivlenmesi, güvenliğinin sağlanması, aktarılabilir olması, yetkisiz erişimlerin tespiti ve erişim kayıtlarında özel nitelikli kişisel veri bulundurulmaması gerekliliklerini içerir.)*

### 4.1.3. Yetkilendirme
*(Tedbirler: Yetkilendirme ve kimlik doğrulama mekanizmalarının kullanılması, erişimin sınırlandırılması, çok faktörlü kimlik doğrulama kullanımı ve dış/iç sistemler arası erişimlerin doğrulanması sağlanmalıdır.)*

### 4.1.4. Şifreleme
*(Tedbirler: Sistemler arası iletişimin şifrelenmesi, verinin maskelenmesi, veri bütünlüğünün korunması ve alt bileşenler arasındaki iletişimin şifreli yapılması sağlanmalıdır.)*

### 4.1.5. Yedekleme, Silme, Yok Etme ve Anonim Hale Getirme
*(Tedbirler: Sistem yedekleri yetkili kullanıcılarca alınmalı, gereksiz veriler silinmeli veya yok edilmeli, uygun veriler anonim hale getirilmeli ve yedeklerin güvenliği sağlanıp gerektiğinde yok edilmelidir.)*

### 4.1.6. Aydınlatma Yönetimi
*(Tedbirler: İlgili kişilere doğru zamanda aydınlatma yapılmalı, aydınlatmanın yerine getirildiği ispatlanabilmeli ve metinler uygulama üzerinden güncellenebilmelidir.)*

### 4.1.7. Açık Rıza Yönetimi
*(Tedbirler: Açık rıza unsurları belirlenmeli, alınan rıza kayıt altına alınmalı, sorgulanabilmeli, gerektiğinde uygulama üzerinden alınabilmeli/geri çekilebilmeli ve ıslak imzalı metinler saklanmalıdır.)*

### 4.1.8. Kişisel Veri Yönetim Sürecinin İşletilmesi
*(Tedbirler: İlgili kişinin başvuru hakkı yönetilmeli, güncelleme/anonimleştirme/silme işlemleri yapılmalı, veri aktarılan 3. taraflar tespit edilmeli ve veri ihlali durumunda ilgili kişiler bilgilendirilmelidir.)*

---

## 4.2. Anlık Mesajlaşma Güvenliği
*(Tedbirler: Kurum içi anlık mesajlaşma için kurum kontrolündeki veya yerli/milli uygulamalar seçilmeli, iletim ortamı (SSL/TLS) şifrelenmeli, uçtan uca şifreleme sağlanmalı, kripto anahtarları güvenli depolanmalı ve çoklu cihaz kullanımlarında kimlik doğrulama zorunlu tutulmalıdır.)*

---

## 4.3. Bulut Bilişim Güvenliği
*(Tedbirler: Kritik verilerin yurt içinde depolanması sağlanmalı, hizmet kapsamı ile sözleşmeler net belirlenmeli, kaynaklar mantıksal/fiziksel izole edilmeli, bulut işlemleri kayıt altına alınmalı, DDoS saldırılarına karşı koruma sağlanmalı ve hizmet sonlandığında tüm veri/imajlar güvenli şekilde imha edilmelidir.)*

---

## 4.4. Kripto Uygulamaları Güvenliği
*(Tedbirler: Güvenli kriptografik algoritmalar seçilmeli, anahtarlar güvenli şekilde üretilip/dağıtılıp/saklanmalı, yedeklenmeli ve gerektiğinde imha edilmelidir. Kritik bilgilerin işlendiği sistemlerde TEMPEST ve COMSEC laboratuvar onaylı cihazlar tercih edilmelidir.)*

---

## 4.5. Kritik Altyapılar Güvenliği
*(Tedbirler: Ağ ve Sistem, Uygulama ve Veri, Taşınabilir Cihaz, IoT, Personel ve Fiziksel Mekân güvenliği tedbirleri eksiksiz uygulanmalıdır. Enerji sektöründe EKS ağları izole edilmeli ve SCADA güvenliği sağlanmalıdır. Elektronik Haberleşme sektöründe sinyalleşme güvenliği, sahtecilik önleme ve kritik haberleşme güvenliği temin edilmelidir.)*

---

## 4.6. Yeni Geliştirmeler ve Tedarik
*(Tedbirler: Tedarik edilen yazılım/donanım alımında güvenlik testleri yapılmalı, ürünlerin Türkçe dil desteği olmalı, alt yüklenici yönetimi süreçlere uygun işlemeli ve fonksiyonel/fonksiyonel olmayan güvenlik testleri (sızma, yük, performans) tamamlanmadan sistemler canlıya alınmamalıdır.)*
