# BİLGİ VE İLETİŞİM GÜVENLİĞİ REHBERİ
## KAYNAKÇA

1. Bilişim Terimleri Sözlüğü, TSE (2006)
2. CIS (Center for Internet Security) Controls v7.1 (2019)
3. Cloud Controls Matrix 3.0.1 (2016)
4. NIST (National Institute of Standards and Technology) Framework for Improving Critical Infrastructure Cybersecurity (2018)
5. NIST IR (National Institute of Standards and Technology Internal Report) 8228 (2019)
6. OWASP (Open Web Application Security Project) Application Security Verification Standard 4.0 (2019)
7. OWASP (Open Web Application Security Project) IoT (Internet of Things) Security Guidance (2018)
8. OWASP (Open Web Application Security Project) Mobile Application Security Verification 1.1.4 (2019)
9. PCI DSS (Payment Card Industry Data Security Standard) Requirements and Security Assessment Procedures 3.2.1 (2018)
10. TS ISO/IEC 27001:2017 Bilgi Güvenliği Yönetim Sistemleri - Gereksinimler Standardı (2017)
11. 24.03.2016 tarihli ve 6698 sayılı Kişisel Verilerin Korunması Kanunu
12. 28.10.2017 tarihli Kişisel Verilerin Silinmesi, Yok Edilmesi veya Anonim Hale Getirilmesi Hakkında Yönetmelik
13. 30.12.2017 tarihli Veri Sorumluları Sicili Hakkında Yönetmelik
14. 10.03.2018 tarihli Aydınlatma Yükümlülüğünün Yerine Getirilmesinde Uyulacak Usul ve Esaslar Hakkında Tebliğ
15. 10.03.2018 tarihli Veri Sorumlusuna Başvuru Usul ve Esasları Hakkında Tebliğ
16. 04.05.2017 tarihli ve 5651 sayılı İnternet Ortamında Yapılan Yayınların Düzenlenmesi ve Bu Yayınlar Yoluyla İşlenen Suçlarla Mücadele Edilmesi Hakkında Kanun
17. TÜBİTAK BİLGEM Güvenli Yazılım Geliştirme Kılavuzu 1.1 (2018)
18. Kurumsal SOME Kurulum ve Yönetim Rehberi (2014)

---

## EKLER

### EK-A: GENELGE MADDELERİ EŞLEŞTİRME TABLOSU

06.07.2019 Tarihli ve 30823 Sayılı Resmi Gazete'de yayımlanan 2019/12 Sayılı Cumhurbaşkanlığı Genelgesi'nde yer alan 21 adet tedbirin ilgili rehber başlıklarıyla eşleşmesi aşağıdaki tabloda yer almaktadır. Söz konusu maddelerin tabloya ilaveten farklı başlıklarla da ilişkilendirilmesi mümkündür. Genelge Maddesi doğrudan Rehber başlığıyla ilişkiliyse tablodaki ilgili hücreye **A (Asıl)** yazılmıştır. Genelge Maddesi ile Rehber başlığı arasında dolaylı bir ilişki varsa tablodaki ilgili hücreye **D (Dolaylı / Destekleyici)** yazılmıştır.

| No | Genelge Maddesi | Ağ ve Sistem Güvenliği | Uygulama ve Veri Güvenliği | Taşınabilir Cihaz ve Ortam Güvenliği | Nesnelerin İnterneti (IoT) Cihazlarının Güvenliği | Personel Güvenliği | Fiziksel Mekânların Güvenliği | Kişisel Verilerin Güvenliği | Anlık Mesajlaşma Güvenliği | Bulut Bilişim Güvenliği | Kripto Uygulamaları Güvenliği | Kritik Altyapılar Güvenliği | Yeni Geliştirmeler ve Tedarik |
|:---|:---|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| 1 | Nüfus, sağlık ve iletişim kayıt bilgileri ile genetik ve biyometrik veriler gibi kritik bilgi ve veriler yurtiçinde güvenli bir şekilde depolanacaktır. | | | | | | | A | | | | | |
| 2 | Kamu kurum ve kuruluşlarında yer alan kritik veriler, internete kapalı ve fiziksel güvenliği sağlanmış bir ortamda bulunan güvenli bir ağda sağlanacak ve log kayıtları değiştirilmeye karşı önlem alınarak tutulacak, bu ağda kullanılacak cihazlara erişim kontrollü olarak sağlanacaktır. | A | D | | | | A | | | D | | | |
| 3 | Kamu kurum ve kuruluşlarına ait veriler, kurumların kendi özel sistemleri veya kurum kontrolündeki yerli hizmet sağlayıcılar hariç bulut depolama hizmetlerinde saklanmayacaktır. | | | | | | | | | A | | | |
| 4 | Mevzuatta kodlu veya kriptolu haberleşmeye yetkilendirilmiş kurumlar tarafından geliştirilen yerli mobil uygulamalar hariç olmak üzere, mobil uygulamalar üzerinden, gizlilik dereceli veri paylaşımı ve haberleşme yapılmayacaktır. | | | | | | | | A | | | | |
| 5 | Sosyal medya üzerinden gizlilik dereceli veri paylaşımı ve haberleşme yapılmayacaktır. | | | | | | | | A | | | | |
| 6 | Sosyal medya ve haberleşme uygulamalarına ait yerli uygulamaların kullanımı tercih edilecektir. | | | | | | | | A | | | | |
| 7 | Kamu kurum ve kuruluşlarınca gizlilik dereceli bilgilerin işlendiği yerlerde yayma güvenliği (TEMPEST) veya benzeri güvenlik önlemleri alınacaktır. | | | | | | A | | | | | | |
| 8 | Kritik veri, doküman ve belgelerin bulunduğu ve/veya görüşmelerin gerçekleştirildiği çalışma odalarında/ortamlarında mobil cihazlar ve veri transferi özelliğine sahip cihazlar bulundurulmayacaktır. | | | D | | | A | | | | | | |
| 9 | Gizlilik dereceli veya kurumsal mahremiyet içeren veri, doküman ve belgeler kurumsal olarak yetkilendirilmemiş veya kişisel olarak kullanılan cihazlarda (dizüstü bilgisayar, mobil cihaz, harici bellek vb.) bulundurulmayacaktır. | D | D | A | | D | | | | | | | |
| 10 | Kişisel olarak kullanılanlar da dâhil olmak üzere kaynağından emin olunmayan taşınabilir cihazlar (dizüstü bilgisayar, mobil cihazlar, harici bellek/disk, CD/DVD vb.) kurum sistemlerine bağlanmayacaktır. Gizlilik dereceli verilerin saklandığı cihazlar, ancak içerisinde yer alan veriler donanımsal ve/veya yazılımsal olarak kriptolanmak suretiyle kurum dışına çıkarılabilecek; bu amaçla kullanılan cihazlar kayıt altına alınacaktır. | D | | A | | | | | | | | | |
| 11 | Yerli ve milli kripto sistemlerinin geliştirilmesi teşvik edilerek, kurumlara ait gizlilik dereceli haberleşmenin bu sistemler üzerinden gerçekleştirilmesi sağlanacaktır. | | | | | | | | | | A | | |
| 12 | Kamu kurum ve kuruluşlarınca temin edilecek yazılım veya donanımların kullanım amacına uygun olmayan bir özellik ve arka kapı (kullanıcıların bilgisi/izni olmaksızın sistemlere erişim imkânı sağlayan güvenlik zafiyeti) açıklığı içermediğine dair üretici ve/veya tedarikçilerden imkânlar ölçüsünde taahhütname alınacaktır. | | | | | | | | | | | | A |
| 13 | Yazılımların güvenli olarak geliştirilmesi ile ilgili tedbirler alınacaktır. Temin edilen veya geliştirilen yazılımlar kullanılmadan önce güvenlik testlerinden geçirilerek kullanılacaktır. | | D | | | | | | | | | | A |
| 14 | Kurum ve kuruluşlar, siber tehdit bildirimleri ile ilgili gerekli tedbirleri alacaktır. | A | A | | | | | | | | | | |
| 15 | Üst düzey yöneticiler de dâhil olmak üzere, personelin sistemlere erişim yetkilendirmelerinin, fiilen yürütülen işler ve ihtiyaçlar nazara alınarak yapılması sağlanacaktır. | A | A | | A | A | A | | | | | | |
| 16 | Endüstriyel kontrol sistemlerinin, internete kapalı konumda tutulması sağlanacak, söz konusu sistemlerin internete açık olmasının zorunlu olduğu durumlarda ise gerekli güvenlik önlemleri (güvenlik duvarı, uçtan uca tünelleme yöntemleri, yetkilendirme ve kimliklendirme mekanizmaları vb.) alınacaktır. | A | D | | | | | | | | | D | |
| 17 | Milli güvenliği doğrudan etkileyen stratejik önemi haiz kurum ve kuruluşların üst yöneticileri ile kritik altyapı, tesis ve projelerde görev alacak kritik önemi haiz personel hakkında ilgili mevzuat çerçevesinde güvenlik soruşturması veya arşiv araştırması yaptırılacaktır. | | | | | A | | | | | | | |
| 18 | Kurumsal olmayan şahsi e-posta adreslerinden kurumsal iletişim yapılmayacak, kurumsal e-postalar şahsi amaçlarla (özel iletişim, kişisel sosyal medya hesapları vb.) kullanılmayacaktır. | | | | | A | | | | | | | |
| 19 | Kamu e-posta sistemlerinin ayarları güvenli olacak biçimde yapılandırılacak, e-posta sunucuları, ülkemizde ve kurumun kontrolünde bulundurulacak ve sunucular arasındaki iletişimin şifreli olarak yapılması sağlanacaktır. | A | A | | | | | | | A | A | | |
| 20 | Haberleşme hizmeti sağlamak üzere yetkilendirilmiş işletmeciler Türkiye'de internet değişim noktası kurmakla yükümlüdür. Yurtiçinde değiştirilmesi gereken yurtiçi iletişim trafiğinin yurtdışına çıkarılmamasına yönelik tedbirler alınacaktır. | | | | | | | | | | | A | |
| 21 | İşletmeciler tarafından, kritik kurumların bulunduğu bölgelerdeki veriler, radyolink ve benzeri yöntemlerle taşınmayacak, fiber optik kablolar üzerinden taşınacaktır. Kritik veri iletişiminde, radyolink haberleşmesi kullanılmayacak; ancak kullanımın zorunlu olduğu durumlarda veriler milli kripto sistemlerine sahip cihazlar kullanılarak kriptolanacaktır. | | | | | | | | | | | A | |

---

### EK-B: ULUSLARARASI STANDARTLAR VE YAYIMLI KILAVUZLAR EŞLEŞTİRME TABLOSU

| Standart / Yayımlı Doküman | Ağ ve Sistem Güvenliği | Uygulama ve Veri Güvenliği | Taşınabilir Cihaz ve Ortam Güvenliği | Nesnelerin İnterneti (IoT) Cihazlarının Güvenliği | Personel Güvenliği | Fiziksel Mekânların Güvenliği | Kişisel Verilerin Güvenliği | Anlık Mesajlaşma Güvenliği | Bulut Bilişim Güvenliği | Kripto Uygulamaları Güvenliği | Kritik Altyapılar Güvenliği | Yeni Geliştirmeler ve Tedarik | İşletim Sistemi Sıkılaştırma | Veri Tabanı Sıkılaştırma | Sunucu Sıkılaştırma |
|:---|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| Red Hat Enterprise Linux 8 Security Hardening | | | | | | | | | | | | | + | | |
| DISA STIG - Red Hat Enterprise Linux 7 Security Technical Implementation Guide | | | | | | | | | | | | | + | | |
| DISA STIG - Canonical Ubuntu 16.04 LTS Security Technical Implementation Guide | | | | | | | | | | | | | + | | |
| Oracle Linux 7 Security Guide | | | | | | | | | | | | | + | | |
| Ubuntu Server Guide - Security | | | | | | | | | | | | | + | | |
| NIST 800-125 | | | | | | | | | | | | | | | + |
| ENISA Security Aspects of Virtualization | | | | | | | | | | | | | | | + |
| CIS Benchmark | | | | | | | | | | | | | + | + | + |
| NIST 800-82 | | | | | | | | | | | + | | | | |
| OWASP IoT Security Guidance | | | | + | | | | | | | | | | | |
| Mobile Application Security Checklist 1.1 | | + | | | | | | | | | | | | | |
| TÜBİTAK BİLGEM Güvenli Yazılım Geliştirme Kılavuzu 1.1 | | + | | | | | | | | | | + | | | |
| OWASP Mobile Application Security Verification 1.1.4 | | + | | | | | | | | | | | | | |
| OWASP Application Security Verification Standard 4.0 | | + | | | | | | | | | | | | | |
| NIST 800-53 | + | + | + | + | + | + | + | + | + | + | + | + | + | + | + |
| Cloud Controls Matrix 3.0.1 | | | | | | | | | + | | | | | | |
| CIS Controls v7.1 | + | + | + | + | + | + | + | + | + | + | + | + | + | + | + |
| ISO 27001:2017 | + | + | + | + | + | + | + | + | + | + | + | + | + | + | + |
| CMMC v1.0 | + | + | + | + | + | + | + | + | + | + | + | + | + | + | + |

---

### EK-C: BİLGİ VE İLETİŞİM GÜVENLİĞİ REHBERİ UYGULAMA SÜRECİ KAPSAMINDA KULLANILACAK FORMLAR, ŞABLONLAR VE ÖRNEK DOKÜMANLAR

#### EK-C.1: VARLIK GRUBU KRİTİKLİK DERECELENDİRME ANKETİ

Bu anket, Rehber'de yer alan varlık grubu ana başlıkları altında yer alan ve Kurum tarafından belirlenen tüm varlık grupları için tek tek doldurulmalıdır.

**Varlık Grupları Tanımlanırken Dikkat Edilecek Hususlar:**
Kurum bilgi güvenliği yönetim sistemi kapsamında yer alan varlıkların, aşağıda listelenen altı varlık grubu ana başlığı altında gruplandırılması gerekmektedir.
1. Ağ ve Sistemler
2. Uygulamalar
3. Taşınabilir Cihaz ve Ortamlar
4. IoT Cihazları
5. Personel
6. Fiziksel Mekânlar

**Anket Doldurulurken Dikkat Edilecek Hususlar:**
Anket, ilgili varlık grubuyla alakalı paydaşların, Kurumun sahip olduğu en yetkin personelin ve yöneticilerin katılımı ile doldurulur. Anket doldurma çalışmasında delfi metodunun kullanılması önerilir.
Ankette her bir soru için sadece bir şık işaretlenebilir. Sorular, varlık grubu içerisinde yer alan en kritik ve en etkili varlık dikkate alınarak yanıtlanmalıdır. Soruların Kurumunuzla ilişkili birden fazla doğru cevabı varsa en yüksek puanlı olan şık seçilmelidir. Cevaplandırdığınız her seçeneğin gerekçesi de ayrıntılı olarak yazılmalıdır.

**Varlık Grubu No / Adı:** ......................................

**Varlık Grubu için Anket Soruları**

**A) Varlık Grubunun İşlediği Veri Açısından Değerlendirilmesi**

**Gizlilik Boyutu:**
1. Varlık grubunuzun işlediği en kritik bilginin açığa çıkması veya yetkisiz kişiler tarafından ele geçirilmesi durumunda;
a. Herhangi bir zarar oluşmaz, Kurum ve kişiler işlerine devam edebilir.
b. Kurumun ya da ilgili kişilerin işlerini ve çıkarlarını etkileyecek zararlar gelir.
c. Milli güvenlik ve ulusal çıkarlara saygınlık anlamında zararlar gelir. Söz konusu zararın telafisi mümkündür.
d. Milli güvenlik ve ulusal çıkarlara yaşamsal zararlar gelir. Söz konusu zararın telafisi mümkün olamaz.

**Bütünlük Boyutu:**
2. Varlık grubunuzun işlediği en kritik bilginin içeriğinin yetkisiz kişiler tarafından değiştirilmesi durumunda;
a. Herhangi bir zarar oluşmaz. Kurum ve kişiler işlerine devam edebilir.
b. Kurumun ya da ilgili kişilerin işlerini ve çıkarlarını etkileyecek zararlar gelir.
c. Milli güvenlik ve ulusal çıkarlara saygınlık anlamında zararlar gelir. Söz konusu zararın telafisi mümkündür.
d. Milli güvenlik ve ulusal çıkarlara yaşamsal zararlar gelir. Söz konusu zararın telafisi mümkün olamaz.

**Erişilebilirlik Boyutu:**
3. Varlık grubunuzdaki varlıklara bağımlılığı bulunan hizmetlerde, hizmetin en yoğun olarak kullanıldığı periyodu göz önünde bulundurduğunuzda en fazla tolere edebildiğiniz devre dışı kalma süresi nedir?
a. 24 (yirmi dört) saatten fazla
b. 8 (sekiz) - 24 (yirmi dört) saat arası
c. 1 (bir) - 8 (sekiz) saat arası
d. 1 (bir) saatten az

**B) Varlık Grubunun Etki Alanı Açısından Değerlendirilmesi**

**Etkilenen Kişi Sayısı:**
4. Varlık grubunuzda yer alan varlıklar üzerinde gizlilik, bütünlük ve erişilebilirlik boyutlarının tamamını etkileyecek, olası en kötü senaryoya sahip bir bilgi güvenliği ihlal olayı meydana geldiğinde doğrudan etkilenebilecek kişi sayısı;
a. Binden azdır.
b. Binden fazla, 10 binden azdır.
c. 10 binden fazla, 100 binden azdır.
d. 100 binden fazla, 1 milyondan azdır.
e. 1 milyondan fazladır.

**Toplumsal Sonuçlar:**
5. Varlık grubunuzda yer alan varlıklar üzerinde gizlilik, bütünlük ve erişilebilirlik boyutlarının tamamını etkileyecek, olası en kötü senaryoya sahip bir bilgi güvenliği ihlal olayı meydana geldiğinde karşılaşılan durum aşağıdaki sonuçlardan hangisine yol açar?
a. Toplumsal kargaşa olmaz, yazılı görsel basına intikal etmez.
b. Toplumsal kargaşa olmaz, fakat olay yazılı görsel basına intikal eder.
c. Toplumsal kargaşa meydana gelir.
d. Can kaybı meydana gelir.
e. Diğer (a, b, c, d seçeneklerinden daha yüksek etkili bir sonuç doğurması durumu)

**Kurumsal Sonuçlar:**
6. Varlık grubunuzda yer alan varlıklar üzerinde gizlilik, bütünlük ve erişilebilirlik boyutlarının tamamını etkileyecek, olası en kötü senaryoya sahip herhangi bir bilgi güvenliği ihlal olayı olduğunda söz konusu olayın Kuruma etkisi ne olur?
a. Kuruma etkisi olmaz, Kurum mevcut organizasyonu ve itibarını devam ettirir.
b. Kurumun itibarı olumsuz etkilenmez, fakat bilgi güvenliği organizasyon yapısını etkiler ya da personel değişikliğine gidilir.
c. Kurumun itibarı olumsuz etkilenir.

**Sektörel Etki:**
7. Varlık grubunun hizmet verdiği sektöre etkisi nedir?
a. Varlık grubu kurumun ana fonksiyonuna/sektöre doğrudan hizmet vermemektedir.
b. Kamu kurum ve kuruluşları ana fonksiyonlarını yerine getirir ve sektöre doğrudan hizmet eder.
c. Düzenleyici ve denetleyici kurum ve kuruluşlar, büyük ölçekli sanayi ve ticari kurumlar, AR-GE kurumlarının ana fonksiyonlarını yerine getirir ve sektöre doğrudan hizmet eder.
d. Enerji, su yönetimi, bankacılık ve finans, ulaştırma, elektronik haberleşme, sağlık ve milli güvenlik/savunma sektörlerindeki ana fonksiyonlardan birini yerine getirir ve sektöre doğrudan hizmet eder.

**Bağımlı Varlıklar:**
8. Diğer varlıkların (entegre olan diğer yazılımlar, sunucular vb.) yönetiminizdeki varlığa olan bağımlılığı göz önünde bulundurulduğunda, varlığınızın işlediği verinin (uygulanabilir durumlarda) gizlilik, bütünlük veya erişilebilirliğine zarar gelmesi durumunda;
a. Bağımlılığı olan varlıkların çalışması etkilenmez.
b. Bağımlı varlıkların çalışmasını etkileyecek zararlar oluşur ancak ana faaliyet devam eder.
c. Bağımlı varlıkların çalışmasını etkileyecek zararlar oluşur ve ana faaliyette aksamalar meydana gelir.
d. Bağımlı varlıkların çalışmasını etkileyecek zararlar oluşur ve ana faaliyet durur.
e. Diğer (a, b, c, d seçeneklerinden daha yüksek etkili bir sonuç doğurması durumu)

**Anket Özeti**

**Varlık Grubu No / Adı:** ......................................

**a) Anket çalışmasına katılan ve anketi dolduran kişilerle ilgili bilgiyi aşağıdaki tabloya yazınız.**
| No. | Anket Katılımcısı | Görevi / Unvanı | Birimi/Kurumu | İrtibat | Tarih |
|:---|:---|:---|:---|:---|:---|
| 1 | | | | | |
| 2 | | | | | |
| 3 | | | | | |
| 4 | | | | | |
| 5 | | | | | |
| 6 | | | | | |
| 7 | | | | | |
| 8 | | | | | |
| 9 | | | | | |

**b) Her soru için anket cevaplarını aşağıdaki tabloya işaretleyerek anket puanını hesaplayınız.**
| Boyut | Soru No. | a | b | c | d | e | Soru Puanı |
|:---|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| **İşlenen Veri Açısından** | | | | | | | |
| Gizlilik | 1 | 1 puan | 2 puan | 3 puan | 5 puan | | |
| Bütünlük | 2 | 1 puan | 2 puan | 3 puan | 5 puan | | |
| Erişilebilirlik | 3 | 1 puan | 2 puan | 3 puan | 5 puan | | |
| **Etki Alanı Açısından** | | | | | | | |
| Etkilenen Kişi Sayısı | 4 | 1 puan | 2 puan | 3 puan | 4 puan | 5 puan | |
| Toplumsal Sonuçlar | 5 | 1 puan | 2 puan | 3 puan | 5 puan | 6 puan | |
| Kurumsal Sonuçlar | 6 | 1 puan | 2 puan | 3 puan | | | |
| Sektörel Etki | 7 | 1 puan | 2 puan | 3 puan | 5 puan | | |
| Bağımlı Varlıklar | 8 | 1 puan | 2 puan | 3 puan | 5 puan | 6 puan | |
| | | | | | | **Anket Puanı (Toplam):** | |

**c) Her soru için işaretlediğiniz cevap şıkkını, olası senaryoyu da belirterek, gerekçelendiriniz.**
| Soru No. | Açıklama/Gerekçe |
|:---:|:---|
| 1 | |
| 2 | |
| 3 | |
| 4 | |
| 5 | |
| 6 | |
| 7 | |
| 8 | |

**d) Anket puanına göre varlık grubunun kritiklik derecesini aşağıdaki tablodan faydalanarak belirleyiniz.**
| Anket Puanı | Varlık Grubu Kritiklik Derecesi |
| :--- | :--- |
| Anket puanı 18'den küçük ise | Derece 1 |
| Anket puanı 18 (dâhil) ile 28 arasında ise | Derece 2 |
| Anket puanı 28 ve daha yüksek ise | Derece 3 |

**e) Varlık Grubu için Kritiklik Derecelendirme Anketi sonuçlarını aşağıdaki tabloda özetleyiniz.**
| | | | |
|:---|:---|:---|:---|
| **Varlık Grubu No/Adı** | \multicolumn{3}{l|}{} |
| **Anket Tamamlanma Tarihi** | \multicolumn{3}{l|}{} |
| **Anket Çalışması Koordinatörü** | \multicolumn{3}{l|}{} |
| **Anket Puanı (Toplam)** | \multicolumn{3}{l|}{} |
| **Varlık Grubu Kritiklik Derecesi** | Derece 1 | Derece 2 | Derece 3 |

**f) Anket sonuçlarını onaylayan yetkililerin bilgilerini yazınız.**
| | |
|:---|:---|
| **Anket Sonucu Onay Tarihi** | |
| **Anket Sonuçlarını Onaylayan Yetkili** | |
| **Anket Sonuçlarını Onaylayan Yetkilinin İmzası** | |

---

#### EK-C.2: VARLIK GRUBU VE KRİTİKLİK DERECESİ TANIMLAMA FORMU

Varlık grubunda yer alan tüm varlıklar göz önünde bulundurularak, varlık grubu ile ilişkili uygulama ve teknoloji alanlarına yönelik uygulanması gereken güvenlik tedbirleri ile ilgili sıkılaştırma tedbirleri, varlık grubu kritiklik derecesi ile birlikte aşağıdaki tabloda kayıt altına alınmalıdır. (U: Uygulanabilir, UD: Uygulanabilir Değil)

| Ana Başlığı | Varlık Grubu No | Varlık Grubu Adı | Kişisel Verilerin Güvenliği | Anlık Mesajlaşma Güvenliği | Bulut Bilişim Güvenliği | Kripto Uygulamaları Güvenliği | Kritik Altyapılar Güvenliği | Yeni Geliştirmeler ve Tedarik | İşletim Sistemi Sıkılaştırma Tedbirleri | Veri Tabanı Sıkılaştırma Tedbirleri | Sunucu Sıkılaştırma Tedbirleri | Kritiklik Derecesi (1/2/3) |
|:---|:---|:---|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| Ağ ve Sistemler | | | | | | | | | | | | |
| Uygulamalar | | | | | | | | | | | | |
| Taşınabilir Cihaz ve Ortamlar | | | | | | | | | | | | |
| Nesnelerin İnterneti (IoT) Cihazları | | | | | | | | | | | | |
| Fiziksel Mekânlar | | | | | | | | | | | | |
| Personel | | | | | | | | | | | | |

---

#### EK-C.3: MEVCUT DURUM VE BOŞLUK ANALİZ FORMU

Her bir varlık grubu için tedbir maddelerinin uygulanıp uygulanmadığı Uygulama Durumu açıklamaları dikkate alınarak belirlenmelidir. Mevcut duruma yönelik açıklamalar detaylı olarak belirtilmelidir. Ayrıca ilgili varlık grubu için hedeflenen duruma ulaşılması amacıyla yapılması gereken çalışmalar aşağıdaki tabloda kayıt altına alınmalıdır.

*   Tedbir varlık grubunda yer alan tüm varlıklara uygulanmakta ise "tamamen" **(T)**
*   Tedbir varlık grubunda yer alan varlıkların çoğuna uygulanmakta fakat bazı varlıklara kısmen uygulanmakta veya henüz uygulanmamakta ise "çoğunlukla" **(Ç)**
*   Tedbir varlık grubunda yer alan bir kısım varlığa uygulanmakta veya tedbir kısmen uygulanmakta ise "kısmen" **(K)**
*   Tedbir hiç uygulanmamakta ise "hiç" **(H)**
*   Tedbirin teknik olarak uygulanma ihtimali bulunmuyorsa "uygulanamaz" **(UD)**

**Varlık Grubu Adı / Kodu:** ......................................

| Tedbir No | Uygulanma Durumu * (T/Ç/K/H/UD) | Mevcut Duruma Yönelik Açıklama | Hedeflenen Durum (T/Ç/K/H/UD) | Telafi Edici Kontrol (Tedbirin Birebir Uygulanamadığı Durumda) ** | Hedeflenen Durum İçin Yapılması Gereken Çalışmalar |
|:---|:---:|:---|:---:|:---|:---|
| | | | | | |
| | | | | | |
| | | | | | |

*\* Varlık gruplarının mevcut durum ve boşluk analizi kapsamında belirlenen çalışmalar yazılmalıdır.*
*\*\* Tedbir için telafi edici kontrol tanımlanması gerekiyorsa EK-C.5 formu doldurulur ve kontrol formunun numarası bu bölüme girilir.*

---

#### EK-C.4: REHBER UYGULAMA YOL HARİTASI BELİRLEME FORMU

Mevcut durum ve boşluk analizi kapsamında yapılan çalışmalar göz önünde bulundurarak yapılması gereken iş paketleri ve bu kapsamda yapılacak 3-24 aylık çalışmalar aşağıdaki tabloda kayıt altına alınmalıdır.

| İş Paketi No | İş Paketi Adı | İş Paketinin Kapsadığı Faaliyetler | İş Paketi Hedefleri | 3.Ay | 6.Ay | 9.Ay | 12.Ay | 15.Ay | 18.Ay | 21.Ay | 24.Ay |
|:---:|:---|:---|:---|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| | | | | | | | | | | | |
| | | | | | | | | | | | |
| | | | | | | | | | | | |

---

#### EK-C.5: TELAFİ EDİCİ KONTROL KAYIT FORMU

Kurum, boşluk analizi sonucunda uygulanması gereken ilave tedbirler kapsamındaki herhangi bir gereksinimi; üst yönetim tarafından onaylanmış teknik kısıtlamalar ve iş gereksinimlerinden dolayı rehberde tanımlandığı şekli ile karşılayamaması durumunda telafi edici kontroller uygulamalıdır. Telafi edici kontroller, yerine uygulandıkları tedbir maddeleri ile aynı amaç ve etkiye sahip olmaları durumunda kullanılabilir olarak kabul edilecektir. Tedbir maddesi ile ilgili gereklilikleri karşılamak amacıyla kullanılan her bir telafi edici kontrolü tanımlamak için aşağıdaki form kullanılmalıdır.

| | TELAFİ EDİCİ KONTROLE YÖNELİK BİLGİ | AÇIKLAMA |
|:---|:---|:---|
| **Telafi Edici Kontrolün Numarası** | Telafi edici kontrole ait numara bilgisi | |
| **Telafi Edici Kontrolün Tanımı** | Güvenlik tedbir maddesi yerine uygulanan telafi edici kontrolün tanımının yapıldığı alan | |
| **Telafi Edici Kontrolün Niteliği (Geçici / Kalıcı)** | Telafi edici kontrolün geçici ya da kalıcı nitelikte olduğunun tanımlandığı alan | |
| **Telafi Edici Kontrolün Geçici Olması Durumunda Planlanan Uygulama Zaman Aralığı** | Telafi edici kontrolün geçici nitelikte olması durumunda, kontrolün planlanan uygulama zaman aralığı | |
| **İlişkili Güvenlik Tedbiri Madde Numarası** | Telafi edici kontrolün hangi güvenlik tedbiri yerine uygulanacağının tanımlandığı alan | |
| **İlişkili Güvenlik Tedbiri Gereklilikleri** | Telafi edici kontrolün ilişkili olduğu güvenlik tedbir maddesinin gerekliliklerinin tanımlandığı alan | |
| **İlişkili Güvenlik Tedbirinin Uygulanamamasından Kaynaklanan Riskler** | Güvenlik tedbir maddesinin uygulanmaması durumunda ortaya çıkacak risklere yönelik açıklamaların yapıldığı alan | |
| **İlişkili Güvenlik Tedbirinin Uygulanamamasının Gerekçeleri** | Güvenlik tedbir maddesinin mevcut durumda uygulanamamasının nedenlerinin, uygulama kısıtlarının ve gerekçelerinin tanımlandığı alan | |
| **Telafi Edici Kontrolün Doğrulama Yöntemi** | Telafi edici kontrolün etkinliği ve yeterliliğine yönelik yapılan doğrulama ve test faaliyetlerinin açıklandığı alan | |

---

#### EK-C.6: TAAHHÜTNAME ÖRNEĞİ

İşbu taahhütname, 06.07.2019 tarih ve 30823 sayılı Resmi Gazete'de yayımlanarak yürürlüğe giren 2019/12 sayılı Bilgi ve İletişim Güvenliği Tedbirleri konulu Cumhurbaşkanlığı Genelgesi'nin 12. maddesinde yer alan hükme dayanılarak hazırlanmıştır.

**1. Tanımlar ve Kısaltmalar**
İşbu taahhütnamede geçen;
1.1. **"Arka kapı"**, Uygulama yazılımı, donanım ve işletim sistemleri veya bu bileşenlerin bir ya da birkaçını üzerinde barındıran cihaz/sistemlerde mevcut güvenlik önlemlerini aşarak erişim sağlamak üzere özel olarak tasarlanan ve/veya kasıtlı olarak dâhil edilmiş boşluklar veya güvenlik açıklarını,
1.2. **"Dağıtıcı"**, Bir üreticiye ait olan ürünlerin belirli bölgelerde tanıtımı ve satışını sağlamakla yetkili tüzel kişiyi,
1.3. **"Kurum"**, ............................................................. adresinde faaliyet göstermekte olan ............................................................. Kurumu'nu,
1.4. **"Tedarikçi"**, tedarik zincirinde yer alan, üretici ve dağıtıcı dışındaki tüzel kişiyi,
1.5. **"Üretici"**, ürünü üreten, imal eden veya ürüne adını, ticari markasını veya ayırt edici işaretini koyan tüzel kişiyi,
1.6. **"Ürün"**, Kurum tarafından tedarik edilmesi planlanan uygulama yazılımı, donanım, işletim sistemi veya bu bileşenlerin bir ya da birkaçını üzerinde barındıran cihaz/sistemi,
1.7. **"Şirket"**, işbu taahhütnamede yer alan yükümlülüklerden sorumlu üretici, dağıtıcı veya tedarikçiyi
ifade etmektedir.

**2. Ürün Özellikleri**
| | |
|:---|:---|
| **Üretici** | |
| **Ürünün Markası** | |
| **Ürünün Adı** | |
| **Ürünün Modeli** | |
| **Ürün Üzerindeki Yazılımlara Ait Versiyon Bilgisi** | |
| **Ürünü Kapsayan Ulusal/Uluslararası Standartlar** | |

**3. Yükümlülükler**
3.1. İşbu taahhütnamenin 2. maddesinde özellikleri belirtilen ürünün, Kurum yetkililerinin bilgisi ve izni olmadan; ürünü veya ürün içerisindeki herhangi bir bileşeni devre dışı bırakmak, yetkisiz kod çalıştırmak, ürün içerisindeki verilere erişim sağlamak, verileri silmek ya da bütünlüğünü bozmak amacıyla tasarlanmış herhangi bir arka kapı bulunmadığını,
3.2. Ürüne bakım, onarım ve garanti süreci dâhil olmak üzere tüm yaşam döngüsü süresince şirket tarafından sunulan yama ve güncellemeler ile yeni versiyonların kurulum ve yönetim süreçlerinde işbu taahhütnamenin 3.1. maddesinde yer alan hükümlere herhangi bir uygunsuzluk olmayacağını,
3.3. Yukarıda beyan ve taahhüt edilen yükümlülüklere uyulmadığı ve/veya Kurum tarafından, verdiğimiz bilgilerde gerçeğe aykırı durumların saptanması halinde, Kurum tarafından bu konuda alınacak kararlara uyacağımızı ve uygulanacak yaptırımların tarafımıza doğrudan uygulanma kabiliyeti bulunduğunu kabul ve taahhüt ederiz.

**4. Muhtelif Hükümler**
4.1. İşbu taahhütnamede yer almayan hususlarda Türkiye Cumhuriyeti mevzuat hükümleri uygulanacaktır.
4.2. İşbu taahhütnameden kaynaklanan uyuşmazlıklarda yalnız ...................................... Mahkemeleri yetkili olacaktır.
4.3. İşbu taahhütnamenin hükümlerinden biri ya da birkaçının kısmen veya tamamen geçersiz addedilmesi, taahhütnamenin kalan hükümlerinin geçerliliğine etki etmeyecektir.
4.4. İşbu taahhütname kapsamında şirkete yapılacak bildirim, tebligat ve diğer haberleşme yöntemlerinde aşağıda şirket yetkilileri tarafından beyan edilen adres(ler) ve diğer iletişim bilgileri geçerlidir. Şirket adres değişikliklerini derhal noter yolu ile Kurum'a bildirmek zorundadır. Aksi halde taahhütnamede belirtilen adreslere yapılan tebligatlar geçerli olacaktır.
4.5. İşbu taahhütname şirketi temsil ve ilzama yetkili kişiler tarafından imzalanmış olup imza tarihi itibarıyla ....... (süresince) yürürlükte kalacaktır.

**Taahhütte Bulunan Şirketin**
*   **Unvanı:**
*   **Adresi:**
*   **Telefon/Faks:**
*   **Vergi Dairesi:**
*   **Vergi Numarası:**
*   **Ticaret Sicil Numarası:**
*   **Tedarik Zincirindeki Rolü:** [ ] Üretici   [ ] Dağıtıcı   [ ] Tedarikçi

**Taahhütte Bulunan Şirketi Temsil ve İlzama Yetkili Kişi (ler)**
**İmza Tarihi:** .... / .... / .......

| Yetkili Kişi Ad - Soyad | Yetkili Kişi Ad - Soyad | Yetkili Kişi Ad - Soyad |
|:---:|:---:|:---:|
| **Kaşe/İmza** | **Kaşe/İmza** | **Kaşe/İmza** |
| <br><br><br> | <br><br><br> | <br><br><br> |
