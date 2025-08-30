
# MDA-Bot v6.0.0 - Gizlilik Politikası

**Son Güncelleme:** 20 Ocak 2025   
**Versiyon:** 6.0.0  
**Bot ID:** 791595852728762368

## 📋 Genel Bilgiler

MDA-Bot, Discord sunucularında güvenlik ve moderasyon hizmetleri sunan bir bottur. Bu gizlilik politikası, botumuzun hangi verileri topladığını, nasıl kullandığını ve nasıl koruduğunu açıklar.

## 🛡️ KVKK ve GDPR Uyumluluk

Bu bot **Kişisel Verilerin Korunması Kanunu (KVKK)** ve **Genel Veri Koruma Tüzüğü (GDPR)** ile tam uyumludur:

- ✅ Veri minimizasyonu prensibi uygulanır
- ✅ Otomatik anonimleştirme sistemi aktif
- ✅ Şifreleme ve güvenlik protokolleri aktif
- ✅ Kullanıcı haklarına tam saygı
- ✅ Saklama süresi sınırlaması (30 gün)

## 📊 Toplanan Veriler

### 🔹 Otomatik Toplanan Veriler

**Discord Kullanıcı Verileri:**
- Kullanıcı ID'si (Discord tarafından sağlanan benzersiz numara)
- Kullanıcı adı ve tag bilgisi
- Sunucu üyelik durumu
- Mesaj gönderme zamanları (spam koruması için)

**Sunucu Verileri:**
- Sunucu ID'si
- Sunucu adı
- Üye sayısı
- Sunucu sahibi bilgisi
- Bot ayar tercihleri

**Aktivite Verileri:**
- Komut kullanım istatistikleri
- Mesaj aktivite zamanları (sadece zaman damgası)
- Moderasyon işlem kayıtları

### 🔹 Manuel Girilen Veriler

**Yapılandırma Verileri:**
- Log kanal tercihleri
- Koruma sistemi ayarları
- Özel kara liste kelimeleri
- Oto rol ayarları

**İletişim Verileri:**
- Sorun bildirimi mesajları
- Bot davet talepleri

## 🎯 Verilerin Kullanım Amaçları

### ✅ Kullanım Amaçları

1. **Güvenlik ve Koruma:**
   - Spam tespiti ve engelleme
   - Küfür ve uygunsuz içerik filtreleme
   - Link koruması

2. **Moderasyon Hizmetleri:**
   - Ban, kick ve timeout işlemleri
   - Log sistemi ve kayıt tutma
   - Üye aktivite takibi

3. **Bot Fonksiyonelliği:**
   - Komut işleme ve yanıtlama
   - Ayar saklama ve yapılandırma
   - İstatistik hesaplama

4. **Teknik Operasyonlar:**
   - Hata tespiti ve düzeltme
   - Performans optimizasyonu
   - Sistem güvenliği

### ❌ Kullanılmayan Amaçlar

- Ticari pazarlama
- Kişisel profil oluşturma
- Üçüncü taraf paylaşım
- Reklam hedefleme

## 🔐 Veri Güvenliği

### 🛡️ Teknik Güvenlik Önlemleri

**Şifreleme:**
- Hassas veriler AES-256 ile şifrelenir
- İletim sırasında TLS 1.3 kullanılır
- Veritabanı şifreleme aktif

**Anonimleştirme:**
- Kişisel veriler otomatik anonimleştirilir
- Hassas bilgiler hash ile korunur
- Log kayıtlarında kişisel veri gizlenir

**Erişim Kontrolü:**
- Sadece gerekli personel erişimi
- İki faktörlü kimlik doğrulama
- API güvenlik token'ları

### 🔒 Veri Saklama

**Saklama Süreleri:**
- Temel kayıtlar: 30 gün
- Güvenlik logları: 30 gün
- Ayar verileri: Sunucu silene kadar
- Geçici veriler: 24 saat

**Otomatik Temizleme:**
- Günlük otomatik veri temizleme
- Süresi dolmuş kayıt silme
- Cache temizleme sistemi

## 👤 Kullanıcı Hakları

### ✅ Sahip Olduğunuz Haklar

**1. Bilgi Alma Hakkı:**
- Hangi verilerinizin toplandığını öğrenme
- Veri işleme amaçlarını öğrenme
- İletişim: `/sorun_bildir` komutu

**2. Düzeltme Hakkı:**
- Yanlış bilgilerin düzeltilmesini isteme
- Güncel bilgi sağlama

**3. Silme Hakkı:**
- Verilerinizin silinmesini talep etme
- "Unutulma hakkı" kullanma

**4. İşleme İtiraz Hakkı:**
- Veri işlemeye itiraz etme
- Bot kullanımını durdurma

**5. Taşınabilirlik Hakkı:**
- Verilerinizin kopyasını alma
- Başka platforma taşıma

### 📞 Hak Kullanımı

Bu haklarınızı kullanmak için:
1. `/sorun_bildir` komutunu kullanın
2. Destek sunucumuza katılın: [(https://discord.gg/ZFDzgWynct)]

## 🔄 Veri Paylaşımı

### ❌ Üçüncü Taraflarla Paylaşım Yok

- Hiçbir kişisel veri satılmaz
- Pazarlama amacıyla paylaşım yapılmaz
- Analiz şirketleriyle veri paylaşılmaz

### ✅ Sınırlı Teknik Paylaşım

**Discord API:**
- Sadece bot fonksiyonları için gerekli veriler
- Discord'un gizlilik politikası geçerli

**Sistem Logları:**
- Anonimleştirilmiş teknik veriler
- Sadece güvenlik amaçlı

## 📋 Özel Durumlar

### 🚨 Yasal Yükümlülükler

Aşağıdaki durumlarda veri paylaşımı zorunlu olabilir:
- Yasal mahkeme kararları
- Resmi makam talepleri
- Acil güvenlik durumları

### ⚖️ Hukuki Süreçler

Bu durumlarda:
- Kullanıcılar mümkün olduğunca bilgilendirilir
- Sadece gerekli minimum veri paylaşılır
- Yasal süreç belgeleri saklanır

## 🔧 Teknik Detaylar

### 💾 Veritabanı Yapısı

**Saklanan Ana Veriler:**
```
- guild_settings: Sunucu ayarları
- spam_tracking: Spam koruması (geçici)
- votes: Oy sistemi (anonim)
- active_tracking: Aktivite (geçici)
- logs: İşlem kayıtları (30 gün)
- blacklist_words: Filtre listeleri
- temp_bans: Geçici yasaklar (otomatik silinir)
```

**Veri Şifreleme:**
- AES-256 algoritması
- Benzersiz şifreleme anahtarları
- Düzenli anahtar rotasyonu

### 🛠️ API ve Entegrasyonlar

**Discord API:**
- Discord Developer Terms of Service uyumlu
- Minimal veri çekme prensibi
- Cache optimizasyonu

**Top.gg API:**
- Sadece oy doğrulaması için
- Kullanıcı ID'si ve oy durumu
- Kişisel bilgi paylaşılmaz

## 📱 Bot Özellikleri ve Veri İlişkisi

### 🛡️ Güvenlik Sistemleri

**Spam Koruması:**
- Mesaj sayısı ve zaman aralıkları saklanır
- 5 dakika sonra otomatik silinir
- Kişisel mesaj içeriği saklanmaz

**Küfür Koruması:**
- Sadece tespit bilgisi loglanır
- Mesaj içeriği şifrelenerek saklanır
- 24 saat sonra otomatik silinir

**Link Koruması:**
- Link tespit bilgisi saklanır
- URL içeriği işlenmez
- Geçici kayıt sistemi

### ⚔️ Moderasyon Sistemi

**Ban/Kick İşlemleri:**
- İşlem nedeni ve yapan kişi kaydı
- Etkilenen kullanıcı bilgisi
- 30 gün saklama süresi

**Log Sistemi:**
- Sunucu aktivite kayıtları
- Anonimleştirilmiş kullanıcı bilgileri
- Yapılandırılabilir saklama

### 🎭 Oto Rol Sistemi

**Rol Atama:**
- Sadece rol ID'si saklanır
- Kişisel tercih bilgisi yok
- Sunucu bazlı yapılandırma

## 🌐 Web Panel ve Yönetim

### 👨‍💻 Admin Panel

**Erişim:**
- Sunucu sahipleri ve yöneticiler
- Şifresiz erişim sistemi
- Sadece bot ayarları yönetimi

**Saklanan Veriler:**
- Komut kullanım istatistikleri
- Sunucu yapılandırma geçmişi
- İşlem kayıtları (anonimleştirilmiş)

**Güvenlik:**
- Rate limiting sistemi
- IP tabanlı koruma
- Güvenlik logları

## 📞 İletişim ve Destek

### 🆘 Sorun Bildirimi

**`/sorun_bildir` Komutu:**
- Bildirilen sorun metni saklanır
- Kullanıcı ve sunucu bilgisi eklenir
- Çözüm sonrası otomatik silinir

**Veri İşleme:**
- Sadece teknik destek amaçlı
- Kişisel bilgi filtreleme
- 7 gün saklama süresi

### 💬 Destek Kanalları

**Discord Destek:**
- Destek sunucusu: [(https://discord.gg/ZFDzgWynct)]
- Ticket sistemi
- Canlı yardım

**Teknik İletişim:**
- GitHub Issues
- Email desteği
- Acil durum hattı

## 🔄 Veri Güncelleme ve Değişiklik

### 📝 Politika Güncellemeleri

**Bildirimi:**
- Tüm sunucu sahiplerine bildirim
- Bot güncellemesi ile birlikte
- Web panelinde duyuru

**Yürürlük:**
- 30 gün önceden duyuru
- Aşamalı uygulama
- Geri bildirim süreci

### 🔧 Sistem Güncellemeleri

**Veri Migrasyonu:**
- Güvenli veri aktarımı
- Anonimlik korunması
- Yedekleme protokolü

## 🚨 Acil Durum Protokolleri

### 🆘 Veri İhlali Durumu

**Anında Eylemler:**
1. Sistem derhal durdurulur
2. Güvenlik analizi başlatılır
3. Etkilenen kullanıcılar bilgilendirilir
4. Yasal makamlar bilgilendirilir (gerekirse)

### 🧹 Acil Veri Silme

**Tam Veri Temizleme:**
- `/api/emergency-wipe` endpoint'i
- Tüm cache ve buffer temizleme
- Geri döndürülemez silme
- KVKK/GDPR Madde 17 uyumlu

## 📈 Veri Analitikleri

### 📊 İstatistiksel Veriler

**Toplanan İstatistikler:**
- Sunucu sayısı ve büyüme
- Komut kullanım oranları
- Sistem performans metrikleri
- Güvenlik olay sayıları

**Anonimleştirme:**
- Kişisel kimlik bilgileri kaldırılır
- Gruplandırılmış veriler kullanılır
- Bireysel takip yapılmaz

### 📈 Kullanım Analitiği

**Amaç:**
- Bot performansı optimizasyonu
- Özellik geliştirme kararları
- Güvenlik iyileştirmeleri

**Sınırlamalar:**
- Bireysel profil oluşturulmaz
- Davranış tahmini yapılmaz
- Demografik analiz yapılmaz

## 🤖 Bot Özel Özellikleri

### 🔐 Elite Güvenlik Sistemi

**Gelişmiş Küfür Koruması:**
- AI destekli içerik analizi
- Karakter değiştirme tespiti
- Güvenlik skoru hesaplama
- Anlık işlem, uzun süre saklama yok

**Spam Koruması:**
- Geçici bellek kullanımı
- Kullanıcı bazlı sayaç sistemi
- 5 dakika otomatik temizleme

### 📋 Log Sistemi

**Detaylı Loglar:**
- Moderasyon işlemleri
- Üye aktiviteleri
- Bot komut kullanımları
- Sistem olayları

**Veri Korunması:**
- Hassas bilgiler spoiler ile gizlenir
- Anonimleştirme filtreleri aktif
- Erişim kontrolü sistemi

## ⚖️ Yasal Çerçeve

### 📜 Geçerli Mevzuat

**Türkiye:**
- KVKK (Kişisel Verilerin Korunması Kanunu)
- 5651 Sayılı İnternet Kanunu
- 6698 Sayılı KVKK

**Avrupa Birliği:**
- GDPR (General Data Protection Regulation)
- ePrivacy Directive
- Digital Services Act

**Uluslararası:**
- Discord Developer Terms of Service
- Google Privacy Policy (hosting)
- Cloud Act Compliance

### ⚖️ Uyuşmazlık Çözümü

**Şikayet Süreci:**
1. İlk başvuru: `/sorun_bildir` komutu
2. Destek ekibi değerlendirmesi (7 gün)
3. Yanıt ve çözüm önerisi
4. Gerekirse yasal yolları bilgilendirme

## 🔄 Veri Taşınabilirlik

### 📦 Veri Dışa Aktarma

**Talep Edebileceğiniz Veriler:**
- Sunucu ayar yapılandırmaları
- Komut kullanım geçmişi (anonimleştirilmiş)
- Log kayıtları (kişisel olanlar)
- Bot etkileşim geçmişi

**Dışa Aktarma Formatları:**
- JSON (yapılandırılmış data)
- CSV (tablo formatı)  
- TXT (basit metin)

**Süreç:**
1. `/sorun_bildir` ile talep edin
2. Kimlik doğrulama (Discord ID)
3. 7 iş günü içinde hazırlık
4. Güvenli İletişim kanalıyla teslimat

## 🌍 Uluslararası Veri Aktarımı

### 🌐 Sunucu Konumları

**Ana Sunucular:**
- Avrupa (GDPR uyumlu)
- Türkiye (KVKK uyumlu)

**Discord API:**
- Amerika Birleşik Devletleri
- Discord'un gizlilik politikası geçerli
- Adequate protection düzeyi

**Güvenlik Önlemleri:**
- Standard Contractual Clauses (SCC)
- Data Transfer Impact Assessment
- Sürekli uyumluluk izleme

## 📱 Platform Entegrasyonları

### 🔗 Top.gg Entegrasyonu

**Veri Paylaşımı:**
- Sadece bot ID'si ve oy durumu
- Kişisel mesaj paylaşılmaz
- Anonim istatistik veriler

**Kullanım:**
- Vote verification sistemi
- Bot keşfedilebilirlik
- Community features

### 🌐 Web Panel

**Çerez Kullanımı:**
- Teknik çerezler (gerekli)
- Oturum yönetimi
- Güvenlik çerezleri

**Analitik:**
- Kişisel veri toplamayan analitik
- Sadece teknik metrikler
- IP anonimleştirme aktif

## 🚀 Gelecek Güncellemeler

### 🔮 Planlanan Özellikler

**Veri Minimizasyonu:**
- Daha az veri toplama
- Gelişmiş anonimleştirme
- Otomatik veri aging

**Kullanıcı Kontrolü:**
- Self-service veri yönetimi
- Anlık izin kontrolleri
- Detaylı transparans raporu

## 📋 Sık Sorulan Sorular

### ❓ Genel Sorular

**S: Botum hangi verilerimi topluyor?**
C: Sadece Discord'da herkese açık olan veriler ve bot işlevselliği için gerekli olan minimal veriler. Kişisel mesajlarınızın içeriği okunmaz veya saklanmaz.

**S: Verilerim ne kadar süre saklanır?**
C: Çoğu veri maksimum 30 gün saklanır. Sunucu ayarları sunucuda bot kaldırılana kadar saklanır.

**S: Verilerimi silebilir miyim?**
C: Evet, `/sorun_bildir` komutu ile veri silme talebinde bulunabilirsiniz.

**S: Bot ne tür kişisel veriler görebilir?**
C: Sadece Discord'un bot API'si üzerinden sağladığı verileri: kullanıcı ID, username, mesaj zamanları (içeriği değil), sunucu rolleri.

### 🔐 Güvenlik Soruları

**S: Verilerim güvenli mi?**
C: Evet, tüm veriler şifrelenir ve düzenli olarak güvenlik denetiminden geçer. KVKK ve GDPR standartlarına tam uyum sağlanır.

**S: Bot mesajlarımı okuyabiliyor mu?**
C: Bot sadece spam, küfür ve link tespiti için mesaj içeriğini analiz eder, ancak bu analiz sonucu mesaj içeriği saklanmaz.

**S: Admin panel kimler erişebilir?**
C: Sadece bot geliştiricileri ve yetkili teknik personel. Erişimler loglanır ve izlenir.

## 📞 İletişim Bilgileri

### 📧 Resmi İletişim

**Discord Destek:**
- Sunucu: [(https://discord.gg/ZFDzgWynct)]
- Kanal: #support
- Yanıt Süresi: 24 saat

**Web Panel:**
- Admin Panel: Bot sunucusunda çalışan panel
- Destek: `/sorun_bildir` komutu

### 🏢 Organizasyon Bilgileri

**Geliştirici:**
- MDA Development Team
- Türkiye menşeili geliştirici ekibi
- Discord Bot geliştirme uzmanı

**Yasal Temsilci:**
- KVKK uyum sorumlusu mevcut
- Veri Koruma Memuru atanmış
- Yasal danışman desteği

## 🎯 Bot Misyonu

### 💡 Temel İlkeler

1. **Şeffaflık:** Hangi veriyi neden topladığımızı açık şekilde belirtiyoruz
2. **Minimizm:** Sadece gerekli olan minimum veriyi topluyoruz
3. **Güvenlik:** Tüm veriler en yüksek güvenlik standartlarıyla korunur
4. **Kontrol:** Kullanıcılar verilerini kontrol edebilir

### 🎯 Hedeflerimiz

- Discord sunucularında güvenli ortam sağlama
- Kullanıcı gizliliğini korurken etkili moderasyon
- Sürekli güvenlik ve gizlilik iyileştirmesi
- Topluluk tabanlı bot geliştirme

## ⚠️ Önemli Notlar

### 🚨 Dikkat Edilmesi Gerekenler

1. **Bot Kaldırma:** Sunucudan bot kaldırıldığında tüm veriler 7 gün içinde silinir
2. **Ayar Değişiklikleri:** Bot ayarları değiştirildiğinde eski ayarlar silinir
3. **Backup Politikası:** Veriler sadece teknik arıza kurtarma için yedeklenir
4. **Cache Sistemi:** Geçici veriler maksimum 24 saat saklanır

### ✅ Güvence Altındaki Haklar

- Veri işleme şeffaflığı
- Kişisel veri güvenliği
- Unutulma hakkı
- Veri taşınabilirlik
- İşleme itiraz hakkı
- Otomatik karar verme koruması

---

## 📜 Sözleşme Bilgileri

Bu gizlilik politikası, MDA-Bot v6.0.0'ı kullanarak aşağıdaki sözleşmeleri kabul etmiş sayılırsınız:

1. **Discord Developer Terms of Service**
2. **MDA-Bot Kullanım Şartları**  
3. **KVKK Aydınlatma Metni**
4. **GDPR Compliance Agreement**

Bu dokümanda belirtilen tüm hak ve yükümlülükler **Discord Terms of Service** ile uyumludur ve onun tamamlayıcısıdır.

---

**🔐 Bu dokümandaki tüm bilgiler yasal olarak bağlayıcıdır ve düzenli olarak güncellenmektedir.**

**📅 En son güncelleme:** 20 Ocak 2025  
**🔄 Sonraki İnceleme:** 20 Nisan 2025  
**📜 Doküman Sürümü:** v6.0.0_FULL_COMPLIANCE

*MDA-Bot Development Team - 2025*
