# ☢ Zararlı Yazılım Kaldırma Kılavuzu

{% hint style="info" %}
Aşağıdaki talimatlar yalnızca tavsiye niteliğindedir.

* Windows Defender'ı ana Anti-Virüs programınız olarak deneyin;
  * MCafee, Avast, AVG, vb gibi daha düşük kalite ve bilgilerinizi satan veya satabilecek Anti virüslerden çok çok daha iyidir.
* **Yalnızca Windows için**
{% endhint %}

{% hint style="info" %}
### Başlamadan Önce

* Sorunsuz Açılabilen bir sistem.
* **Sisteminizde dosyalarınızı şifreleyen bir virüs türü varsa bu kılavuzu KULLANMAYIN.**
* Tüm araçlar windowsun Normal modunda çalıştırılmalıdır. Anca eğer normal mod çalışmıyor veya Normal mod da iken bir sorun yaşıyorsanız Windowsu Güvenli Mod'da açarak kullanabilirsiniz.
* Tüm araçlar Yönetici hesabı altında çalıştırılmalıdır.
* Tarayıcılarla İlgili - **Başlamadan önce**
  * Tarayıcınızın uzantılarına gidin ve varsa tüm şüpheli öğleleri kaldırın.
  * Varsa, normal gözükmeyen sayfaları ayarlardan kaldırın.
{% endhint %}

{% hint style="danger" %}
**Dosyalarınızı şifreleyen bir virüs var ise Buraya bakınız** [ransomware-sifre-coezme-ve-tanimlama-araclari.md](ransomware-sifre-coezme-ve-tanimlama-araclari.md "mention")****
{% endhint %}

### Çalıştırılacak Araçlar

1. [rkill](https://www.bleepingcomputer.com/download/rkill/dl/10/)'i indirin ve çalıştırın.
   1. Bitmesi birkaç dakika sürebilir.
   2. RKill'i çalıştırdıktan sonra bilgisayarınızı yeniden başlatmayın.
   3. Bu ne yapar;
      1. Kötü amaçlı işlemleri durdur ve kapatır.
      2. İşletim sisteminin normal çalışmasını engelleyen kayıt defterindeki ilkeleri kaldırır.
2. [Malwarebytes](https://www.malwarebytes.com/mwb-download/thankyou/)'in güncellenmiş bir kopyasını indirin ve [Rootkit](https://i.imgur.com/5lLJB3R.png)'leri Tara özelliğini açın
   1. Taramayı çalıştırın ve bitmesini bekleyin.
   2. Bu ne yapar;
      1. Removes the vast majority of infections.
      2. Kötü amaçlı yazılımın neden olduğu hasarı düzeltmek için yerleşik onarım sahiptir.
3. [Malwarebytes ADWCleaner 8](https://downloads.malwarebytes.com/file/adwcleaner)'i indirin ve çalıştırın
   1. Bu ne yapar;
      1. Reklam yazılımlarının, Araç Çubuklarının ve Tarayıcı hijacks'in çoğunu kaldırır.
      2. Bloatware ve önceden yüklenmiş yazılımları tarar ve herhangi birini veya tamamını karantinaya almanızı sağlar
      3. Kötü amaçlı yazılım tarafından değiştirilen proxy ayarlarını düzeltir
      4. Bazı varsayılan olmayan tarayıcı ayarlarını kaldırır
4. [Sophos HitmanPro](http://get.hitmanpro.com/)'yu çalıştırın

{% hint style="warning" %}
Bu satırın altında, daha ileri düzey / teknoloji okuryazarı insanlar içindir. Buraya benimle iletişime geçerek geldiyseniz ve hala sorun yaşıyorsanız, benimle tekrar iletişime geçme zamanı.
{% endhint %}

### **Yukarıdakiler sorununuzu çözmezse aşağıdakileri araçları deneyin.**

1. [Rogue Killer](https://www.adlice.com/roguekiller/#alt\_download)
2. [Trend Micro HouseCall](https://www.trendmicro.com/en\_us/forHome/products/housecall.html)
3. [Kaspersky Virus Removal Tool](https://www.kaspersky.com/downloads/thank-you/free-virus-removal-tool)
4. [ESET Online Scanner](https://www.eset.com/us/home/online-scanner/?intcmp=intrw)

**Note:** Bir virüs / kötü amaçlı yazılım, internete girmenizi veya dosya indirmenizi engelledi ise tüm seçenekler işaretlenmiş olarak, [NetAdapter Repair](https://www.bleepingcomputer.com/download/netadapter-repair-all-in-one/) aracını çalıştırmayı deneyebilirsiniz.

### Yararlı ve Özel Araçlar

* **Reklam engelleyici**
  * uBlock Origin Tarayıcı Uzantısı (Firefox, Chrome, Edge ve Opera) [GitHub Repo](https://github.com/gorhill/uBlock)
    * `ublock.org` resmi bir site değildir.
* **Adware Temizleyici**
  * Malwarebytes [AdwCleaner](https://downloads.malwarebytes.com/file/adwcleaner)
* **Anti-Rootkit Programı**
  * [GMER Anti Rootkit](http://www.gmer.net/#files)
  * Trend-Micro [Rootkitbuster](https://www.bleepingcomputer.com/download/trend-micro-rootkitbuster/)
  * From Kaspersky Lab [TDSSKiller](https://usa.kaspersky.com/downloads/tdsskiller)
  * McAfee [McAfee RootKitRemover](https://www.mcafee.com/enterprise/en-us/downloads/free-tools/rootkitremover.html)
  * Malwarebytes [Anti-Rootkit](https://www.malwarebytes.com/antirootkit/)

### Referanslar

* [r/techsupport Wiki Site](https://rtech.support/)
* [r/techsupport Wiki](https://www.reddit.com/r/techsupport/wiki/index)
* [r/antivirus Wiki](https://www.reddit.com/r/antivirus/wiki/index)
* [Cool Web Tools for analysis or testing](https://www.reddit.com/r/antivirus/wiki/index#wiki\_web\_tools)
* [Second-Opinion Scanners](https://www.reddit.com/r/antivirus/wiki/index#wiki\_second-opinion\_scanners)
* [Redirect Virus problem](https://www.2-viruses.com/how-to-fix-google-redirect-virus-browser-hijacker-problem)
* [Information on Browser Hijacker](https://www.bleepingcomputer.com/virus-removal/threat/browser-hijacker/)
