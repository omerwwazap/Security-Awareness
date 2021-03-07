# Kötü Amaçlı Yazılım Kaldırma Kılavuzu

[![Maintenance](https://img.shields.io/badge/Repo_Status-Semi_Active-yellow.svg)](https://shields.io/) [![HitCount](http://hits.dwyl.com/omerwwazap/omerwwazap/Malware-Removal-Guide.svg)](http://hits.dwyl.com/omerwwazap/omerwwazap/Malware-Removal-Guide) [![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/dwyl/esta/issues)

Anlamadığım bazı nedenlerden dolayı birçok arkadaşımın Virüs / Kötü Amaçlı Yazılımın kaldırılması hakkında soru sorması nedeniyle yaptığım bir çalışma, bu onlara yardımcı olacak küçük bir kılavuzdur.

- [Kötü Amaçlı Yazılım Kaldırma Kılavuzu](#kötü-amaçlı-yazılım-kaldırma-kılavuzu)
  - [Ön Bİlgi](#ön-bi̇lgi)
  - [Başlamadan Önce](#başlamadan-önce)
  - [Çalıştırılacak Araçlar](#çalıştırılacak-araçlar)
  - [Yararlı ve Özel Araçlar (To Translate)](#yararlı-ve-özel-araçlar-to-translate)
  - [Fidye Yazılımı Şifre Çözme ve Tanımlama Araçları (To Translate)](#fidye-yazılımı-şifre-çözme-ve-tanımlama-araçları-to-translate)
  - [Referanslar (To Translate)](#referanslar-to-translate)

## Ön Bİlgi

- Aşağıdaki talimatlar yalnızca tavsiye niteliğindedir..
- Windows Defender'ı ana Anti-Virüs programınız olarak deneyin;;
  - MCafee, Avast, AVG, vb gibi daha düşük kalite ve bilgilerinizi satan veya satabilecek Anti virüslerden çok çok daha iyidir.
- **Yalnızca Windows için**

## Başlamadan Önce

- Sorunsuz Açılabilen bir sistem.
- **Sisteminizde dosyalarınızı şifreleyen bir virüs türü varsa bu kılavuzu KULLANMAYIN.**
  - Bunun için buraya [gidin](#for-ransomware-type-malware-to-do), ancak bir profesyonelle iletişime geçmeniz daha iyi olacaktır
- Tüm araçlar windowsun Normal modunda çalıştırılmalıdır. Anca eğer normal mod çalışmıyor veya Normal mod da iken bir sorun yaşıyorsanız Windowsu Güvenli Mod da açarak kullanabilirsiniz.
- Tüm araçlar bir Yönetici hesabı altında çalıştırılmalıdır.
- Tarayıcılarla İlgili - **Başlamadan önce**
  - Tarayıcınızın uzantılarına gidin ve varsa tüm şüpheli öğeleri kaldırın
  - Varsa, normal gözükmeyen sayfaları ayarlardan kaldırın.

## Çalıştırılacak Araçlar

1. [rkill](https://www.bleepingcomputer.com/download/rkill/dl/10/)'i indirin ve çalıştırın.
   1. Bitmesi bir kaç dakika sürebilir.
   2. RKill'i çalıştırdıktan sonra bilgisayarınızı yeniden başlatmayın.
   3. Bu ne yapar;
      - Kötü amaçlı işlemleri durdur ve kapatır.
      - İşletim sisteminin normal çalışmasını engelleyen kayıt defterindeki ilkeleri kaldırır.
2. [Malwarebytes](https://www.malwarebytes.com/mwb-download/thankyou/)'in güncellenmiş bir kopyasını indirin ve [Rootkit](https://i.imgur.com/5lLJB3R.png)'leri Tara özelliğini açın
   1. Taramayı çalıştırın ve bitmesini bekleyin.
   2. Bu ne yapar;
      - Removes the vast majority of infections.
      - Kötü amaçlı yazılımın neden olduğu hasarı düzeltmek için yerleşik onarım sahiptir.
3. [Malwarebytes ADWCleaner 8](https://downloads.malwarebytes.com/file/adwcleaner)'i indirin ve çalıştırın
   1. Bu ne yapar;
      - Reklam yazılımlarının, Araç Çubuklarının ve Tarayıcı hijacks'in çoğunu kaldırır.
      - Bloatware ve önceden yüklenmiş yazılımları tarar ve herhangi birini veya tamamını karantinaya almanızı sağlar
      - Kötü amaçlı yazılım tarafından değiştirilen proxy ayarlarını düzeltir
      - Bazı varsayılan olmayan tarayıcı ayarlarını kaldırır
4. [Sophos HitmanPro](http://get.hitmanpro.com/)'yu çalıştırın

---

Bu satırın altında, daha ileri düzey / teknoloji okuryazarı insanlar içindir.
Buraya benimle iletişime geçerek geldiyseniz ve hala sorun yaşıyorsanız, benimle tekrar iletişime geçme zamanı

- Çizginin Altındaki Içerik
  - [Yararlı ve Özel Araçlar](#yararlı-ve-özel-araçlar-to-translate)
  - [Fidye Yazılımı Şifre Çözme ve Tanımlama Araçları (To Translate)](#fidye-yazılımı-şifre-çözme-ve-tanımlama-araçları-to-translate)
  - [Referanslar (To Translate)](#referanslar-to-translate)

[Yukarı Çıkın](#kötü-amaçlı-yazılım-kaldırma-kılavuzu)

---

**Yukarıdakiler sorununuzu çözmezse aşağıdakileri araçları deneyin.**

1. [Rogue Killer](https://www.adlice.com/roguekiller/#alt_download)
2. [Trend Micro HouseCall](https://www.trendmicro.com/en_us/forHome/products/housecall.html)
3. [Kaspersky Virus Removal Tool](https://www.kaspersky.com/downloads/thank-you/free-virus-removal-tool)
4. [ESET Online Scanner](https://www.eset.com/us/home/online-scanner/?intcmp=intrw)

**Note:** Bir virüs / kötü amaçlı yazılım, internete girmenizi veya dosya indirmenizi engelledi ise tüm seçenekler işaretlenmiş olarak, [NetAdapter Repair](https://www.bleepingcomputer.com/download/netadapter-repair-all-in-one/) aracını çalıştırmayı deneyebilirsiniz.

## Yararlı ve Özel Araçlar (To Translate)

- **Adb Blocker**
  - uBlock Origin Browser Extension (Firefox, Chrome, Edge and Opera) [GitHub Repo](https://github.com/gorhill/uBlock)
    - <code>ublock.org</code> is not a official site.
- **Adware Cleaner**
  - Malwarebytes [AdwCleaner](https://downloads.malwarebytes.com/file/adwcleaner)
- **Anti-Rootkit Program**
  - [GMER Anti Rootkit](http://www.gmer.net/#files)
  - Trend-Micro [Rootkitbuster](https://www.bleepingcomputer.com/download/trend-micro-rootkitbuster/)
  - From Kaspersky Lab [TDSSKiller](https://usa.kaspersky.com/downloads/tdsskiller)
  - McAfee [McAfee RootKitRemover](https://www.mcafee.com/enterprise/en-us/downloads/free-tools/rootkitremover.html)
  - Malwarebytes [Anti-Rootkit](https://www.malwarebytes.com/antirootkit/)

## Fidye Yazılımı Şifre Çözme ve Tanımlama Araçları (To Translate)

| Vendor                                   | Name and Link                                        | Decryption / Identification | Notes                                  |
| ---------------------------------------- | -----------------------------------------------------| --------------------------- | --------------------------------------|
| NoMoreRansom.org and EUROPOL             | [Crypto Sheriff](https://www.nomoreransom.org/crypto-sheriff.php?lang=en)                                                  | Identification              |                                                                                                  |
| Malwarehunterteam                        | [Ransomware Identification](https://id-ransomware.malwarehunterteam.com/)                                                  | Identification              |                                                                                                  |
| Avast                                    | [Ransomware Decryption Tools](https://www.avast.com/ransomware-decryption-tools)                                           | Decryption                  |                                                                                                  |
| Emsisoft                                 | [Ransomware Decryption Tools](https://www.emsisoft.com/ransomware-decryption-tools/)                                       | Decryption                  | Has a very nice and easy to use Ransomware Identifier                                            |
| Eset                                     | [Stand-Alone Malware Removal Tools](https://support.eset.com/en/kb2372-stand-alone-malware-removal-tools)                  | Decryption                  |                                                                                                  |
| Kaspersky Lab                            | [Ransomware Decryption Tools](https://noransom.kaspersky.com/)                                                             | Decryption                  |                                                                                                  |
| NoMoreRansom.org and EUROPOL             | [Decryption Tools](https://www.nomoreransom.org/en/decryption-tools.html)                                                  | Decryption                  |                                                                                                  |
| McAfee                                   | [McAfee Ransomware Recover (Mr2)](https://www.mcafee.com/enterprise/en-us/downloads/free-tools/ransomware-decryption.html) | Decryption                  |                                                                                                  |
| AVG                                      | [Ransomware Decryption Tools](https://www.avg.com/en-ww/ransomware-decryption-tools)                                       | Decryption                  |                                                                                                  |
| QuickHeal                                | [Ransomware Decryption Tool](https://www.quickheal.com/free-ransomware-decryption-tool/)                                   | Decryption                  |                                                                                                  |
| Old Github Repo for Decryption Tools     | [All-in-One Ransomware Decryption Tools](https://github.com/jamestiotio/NoMoreRansom)                                      | Decryption                  | Long list of URLs, but the repo is 4 year old.                                                    |
| Old Github Repo for Decryption Tools - 2 | [Ransomware Decryptor List](https://github.com/alternat0r/Ransomware-Decryptor-List)                                       | Decryption                  | A similar repo to this one, but it has all the executables for decryption and it is 3 years old. |
| Cisco Talos Github Repo                  | [Decryption Tools](https://github.com/Cisco-Talos?q=decryptor&type=&language=)                                             | Decryption                  |                                                                                                  |
| Heimdal Security Blog                    | [Decryption Tools List](https://heimdalsecurity.com/blog/ransomware-decryption-tools/)                                     | Decryption                  |                                                                                                  |
| BleepingComputer                         | [Windows Ransomware Decryptor Download Exec's](https://www.bleepingcomputer.com/download/windows/ransomware-decryptors/)   | Decryption                  |

**NOTE:** Many security companies, including some of the ones listed above, have additional ransomware decryptors available, but do not list them publicly. If you have a system affected by ransomware, contact your security software provider for the latest information and assistance.

- Some Forum Lists in case you need help
  - [Major Geeks Forum](https://forums.majorgeeks.com/)
  - [Malware Removal Forum](https://www.malwareremoval.com/forum/)
  - [Bleeping Computer Virus, Spyware, Malware, & PUP Removal Guides](https://www.bleepingcomputer.com/virus-removal/)
  - [Bleeping Computer Forum](https://www.bleepingcomputer.com/forums/f/79/security/)
  - [MalwareTips](https://malwaretips.com/)
  - [**Malwarebytes** Forum](https://forums.malwarebytes.com/)
  - [Tech Spot Forum](https://www.techspot.com/community/forums/virus-and-malware-removal.28/)
  - [Malwaretips - Malware Removal Help](https://malwaretips.com/categories/malware-removal-help.9/)

## Referanslar (To Translate)

- Amazing Info by [r/techsupport Wiki Site](https://rtech.support/)
- [r/techsupport Wiki](https://www.reddit.com/r/techsupport/wiki/index)
- Very in-depth info by [r/antivirus Wiki](https://www.reddit.com/r/antivirus/wiki/index)
- [Cool Web Tools for analysis or testing](https://www.reddit.com/r/antivirus/wiki/index#wiki_web_tools)
- [Second-Opinion Scanners](https://www.reddit.com/r/antivirus/wiki/index#wiki_second-opinion_scanners)
- [Redirect Virus problem](https://www.2-viruses.com/how-to-fix-google-redirect-virus-browser-hijacker-problem)
- [Information on Browser Hijacker](https://www.bleepingcomputer.com/virus-removal/threat/browser-hijacker/)

[Yukarı Çıkın](#kötü-amaçlı-yazılım-kaldırma-kılavuzu)
