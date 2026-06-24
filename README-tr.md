# 🔐 Nova Locker v1.0.0

Nova Locker; dijital dünyada veri gizliliğini ve güvenliğini en üst düzeye çıkarmak amacıyla, askeri düzeyde şifreleme standartlarını son kullanıcının rahatça erişebileceği, tamamen **ücretsiz** ve bağımsız bir yapıda sunan yeni nesil bir dosya koruma yazılımıdır.

Bu proje, **Netbyteware** çatısı altında kullanıcıların gizlilik haklarını korumak amacıyla geliştirilmiştir.

---

## 🚀 Öne Çıkan Özellikler

*   **Askeri Düzeyde Koruma (AES 256-Bit):** Dünyanın en güvenilir şifreleme protokolü olan AES 256-Bit mimarisini kullanır. Verileriniz, süper bilgisayarların bile kıramayacağı bir algoritmik duvarla örülür.
*   **Çift Yönlü Güvenlik Mekanizması:** Tek bir arayüz veya komut üzerinden hem dosyalarınızı saniyeler içinde şifreleyebilir hem de oluşturduğunuz benzersiz anahtarla şifrelenmiş dosyalarınızın kilidini güvenle açabilirsiniz.
*   **Sıfır Bilgi (Zero-Knowledge) Altyapısı:** Belirlediğiniz şifreleme anahtarları (parolalar) hiçbir uzak sunucuya gönderilmez veya kaydedilmez. Güvenliğiniz tamamen sizin kontrolünüzdedir. Şifrenizi kaybetmeniz durumunda veriye erişim imkansız hale gelir.
*   **Son Kullanıcı Odaklı Tasarım:** Karmaşık kriptografik komutlar ve kafa karıştırıcı ayarlar yerine, her seviyeden bilgisayar kullanıcısının en hızlı şekilde sonuç alabileceği bir deneyim sunar.
*   **%100 Ücretsiz Yazılım:** Güvenliğin bir lüks değil, hak olduğuna inanıyoruz. Nova Locker tüm özellikleriyle tamamen ücretsiz olarak sunulmuştur.

---

## 🛠️ Teknik Özellikler ve Çalışma Mantığı

Nova Locker, çalışma esnasında girdiğiniz parolayı özel bir hashing işleminden geçirerek AES 256-Bit algoritması için bir şifreleme anahtarına (Key) dönüştürür. 

1. **Şifreleme Modu:** Dosya bayt seviyesinde okunur, AES-256 algoritmasıyla karıştırılır ve orijinal dosya tamamen okunamaz bir formata dönüştürülür.
2. **Şifre Çözme Modu:** Şifrelenmiş dosya seçilir, doğru anahtar (parola) girildiğinde algoritma tersine çalışarak dosyayı orijinal, temiz haline geri getirir.

---

## ⚠️ Antivirüs Uyarıları Hakkında (False Positive / Yanlış Pozitif)

**Önemli Açıklama:** Nova Locker, Python mimarisi kullanılarak geliştirilmiş ve son kullanıcının ek bir kütüphane kurmasına gerek kalmadan doğrudan çalıştırabilmesi için `.exe` (çalıştırılabilir dosya) formatında paketlenmiştir.

Python paketleyicilerinin (PyInstaller, cx_Freeze vb.) çalışma prensibi, tüm kaynak kodları ve Python yorumlayıcısını tek bir sıkıştırılmış dosya içinde toplamaktır. Bu sıkıştırma yöntemi, bazı antivirüs yazılımlarının sezgisel (Heuristic) tarama motorları tarafından **"şüpheli/zararlı yazılım"** olarak algılanabilmektedir. Bu durum yazılım dünyasında tamamen **False Positive (Yanlış Alarm)** olarak bilinir.

### 🛡️ Şeffaflık ve Güven Raporu
Yazılımımız içerisinde hiçbir zararlı kod, reklam aracı veya veri izleyici bulunmamaktadır. Kullanıcılarımızın içine sinebilmesi adına projenin güncel tarama sonuçlarını aşağıdaki linkten şeffaf bir şekilde inceleyebilirsiniz:

🔗 **[Güncel VirusTotal Tarama Sonuçlarını Görmek İçin Tıklayın](BURAYA_VIRUSTOTAL_LINKINI_YAPISTIR)**

---

## 💻 Sistem Gereksinimleri

*   **İşletim Sistemi:** Windows 10 / Windows 11 (64-bit sürümleri önerilir)
*   **Ek Kurulum:** Herhangi bir Python kurulumu veya ek kütüphane gerektirmez; `.exe` dosyasını çalıştırmanız yeterlidir.

---

## 📣 Yasal Uyarı
Nova Locker, güçlü bir şifreleme algoritması kullanır. Şifrelediğiniz dosyalara ait belirlediğiniz parolaları unutmamanız/kaybetmemeniz tamamen sizin sorumluluğunuzdadır. Kaybolan şifrelerin kırılması veya geri getirilmesi teknik olarak mümkün değildir.

---
*Geleceğin teknolojilerini inşa etmek adına...*  
**Netbyteware © 2026**
