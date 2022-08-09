---
description: >-
  Çoklu kimlik doğrulama metotları hakkında bilinmesi gerek ve neden kullanmamız
  gerektiğini anlatan bir tavsiye dokümanıdır.
---

# 🔐 İki Faktörlü Kimlik Doğrulama (2FA)

<details>

<summary>Olası Riskler</summary>

**Phishing and Smishing,** güvenilir bir kaynaktan geliyormuş gibi davranarak sizi kandırmak için tasarlanmış e-postalar ve metin mesajlarıdır. Kimlik avcıları, ana parolanızı almak için kendilerini saygın bir şirket (bu durumda, parola yöneticinizin sağlayıcısı) olarak gizler ve sizden oturum açma bilgilerinizi ister veya sahte bir oturum açma sitesine bir bağlantı gönderir.

</details>

### İki Faktörlü Kimlik Doğrulama Nedir?

İki faktörlü kimlik doğrulama, çoklu kimlik doğrulama (kısaca 2FA) bir sisteme girişiniz sırasında, sistemin şifreniz dışında girenin doğru kişi olduğunu anlamasına yardım eden ikini kontroldür. İlk kontrol ise şifrenizdir. Aklınıza gelecek büyük şirketlerin tamamında kullanabilirsiniz.

2FA açarken bahsedilen ikinci doğrulama metodu sadece sizin erişebileceğiniz sistemler ile yapılır. Bu metot size SMS, e-mail veya özel bir uygulama ile bir kod ulaştırılması ile yapılır.

### Neden 2FA Kullanmalıyım?

Şifrenizin çalınması ya da sızdırılması durumunda hesabınızı koruyabilecek bir sistemdir. Saldırganlar 2FA olmayan hesaplara direk giriş yapabilecek, 2FA'sı olan sistemlere özel kodlara erişimi olmadığı için giriş yapamayacaktır.

Önemli gördüğünüz tüm hesaplarınıza 2FA açmanızı şiddetle tavsiye ederiz. E-Mail'iniz, Finansal Hesaplarınız, E-Devlet gibi önemli olabilecek hesaplarda olmasını tavsiye ederiz.

### 2FA Nasıl Açılır?

2FA'sı olan çoğu ürün servise üye olurken, açıp açmamayı sormaktadır. Sormayanlar için ya da kullandığınız bir ürün açmak istiyorsanız, genellikle Hesap Ayarlarınızın, Güvenlik sekmesinde bu ayarı bulabilirsiniz. 2FA, çoklu-doğrulama ya da iki adımlı doğrulama olarak adlandırılabilir.

### 2FA Tipleri

2FA'yı açtığını taktirde genelde iki farklı seçenek ile karşı karşıya gelirsiniz. Bunlar SMS veya Authenticator uygulamalarıdır.

* SMS Şirketler tarafından en çok kullanılan 2FA yöntemidir. Kullanmak için şirket telefon numaranızı talep edecektir. SMS 2FA çok güvenli olmasa da. Hiç olamamasından daha iyidir.
* Authenticator uygulamaları telefon, tablet veya bilgisayarınıza kurduğunuz bir uygulamadır. Google Authenticator, Authy ve Microsoft Authenticator en çok kullanılanlar arasındadır. Kod üretimi cihazınızın üzerinde yapıldığı için SMS gibi teflonunuzun bağlantıya ihtiyacı yoktur ve SMS'in gelmesini beklemenize gerek yoktur.
* E-Mail SMS'den sonra en çok kullanılan yöntemdir ancak mailinize izinsiz erişim olması sonrası 2FA kodunuza erişim sağlanabileceği için çok tercih edilmez. Çoğunlukla telefon numaranızı vermediğiniz zaman otomatik olarak kullanılır.

Ek olarak 2FA açılırken kullandığınız ürün, yedek kodlar verir. Bu kodların her birisi sadece bir defa kullanılabilir ve 2FA koduna erişim sorunu olduğu zaman ya da telefonunuzu kaybettiğiniz ya da ulaşamadığınız gibi acil durumlarda kullanılmak için verilir.

Çok nadiren şirketler 2FA yerine kişisel sorular sorarlar, **"İlk evcil hayvanızın adı nedir?"** gibi bunlar 2FA gibi düşünülmemelidir ve aynı güvenliği kesinlikle vermez.

### Her seferinde 2FA mi girişi istenecek

Ürüne göre değişiklik gösterse de genellikle hayır. Her seferinde girmek zorunda değilsiniz. Kullandığınız sistem, giriş sırında olağan dışı bir durum tespit ederse karşınıza çıkar ya da uzun süre giriş yapmadıysanız 2FA girmeniz gerekecektir. Bazı sistemler ise her seferinde 2FA talep etmektedir. Eğer her seferinde soruyor "beni hatırlama" gibi opsiyonu giriş sırasında seçebilirsiniz, sizin o anda bilgilerini kayıt eder başka cihazlarda sormasına neden olur.

{% hint style="info" %}
**Not**: Birden fazla kişinin kullandığı veya şifresi olmayan bir cihazda **"beni hatırla"** özelliğinin kullanılması çok doğru değildir.
{% endhint %}

### 2FA yok ise ne yapmalıyım?

Son zamanlarda 2FA ürünlerin çok büyük çoğunluğunda kullanılabilir hale gelmiştir ancak 2FA kullandığınız ve kullanmak isteğiniz üründe yok ise yapılabilecek şeyler şunlardır,

* Kullandığınız ya da kullanmak istediğiniz servisi 2FA olan alternatif bir ürün ile değiştirmeyi düşünmelisiniz.
* Ürünü yapan firmaya bu talebinizi iletebilirsiniz ve geliştirilmesini isteyebilirsiniz.
* Kuvvetli bir Parola kullanmak isteyeceksiniz, daha fazla bilgi için Cihazlarınızı ve verilerinizi korumak için şifreleri kullanımı adlı dokümanımıza bakabilirsiniz.
