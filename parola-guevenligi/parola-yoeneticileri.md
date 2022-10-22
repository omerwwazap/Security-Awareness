# 🔏 Parola Yöneticileri

{% hint style="info" %}
Bu doküman bir tavsiye niteliğindedir. Kullanıp kullanmayacağınıza ve nasıl kullanacağınıza karar vermenize yardımcı olmak için yazılmıştır.
{% endhint %}

### Parola yöneticisi nedir?

Parola yöneticisi, telefonunuzda, tabletinizde veya bilgisayarınızda parolalarınızı güvenli bir şekilde saklayan ve böylece tüm parolaları hatırlamanızı gerektirmeyen bir uygulamadır.

Bazı şifre yöneticileri, şifrelerinizi farklı cihazlarınız arasında senkronize ederek, nerede olursanız olun oturum açmayı kolaylaştırır. Bazıları, yeni bir parola oluşturmanız (veya mevcut bir parolayı değiştirmeniz) gerektiğinde sizin için rastgele, benzersiz parolalar da oluşturabilir.&#x20;

Bir parola yöneticisi oluşturduğunuzda, kullanacağınız bir "ana parola/master password" oluşturursunuz. Tüm çevrimiçi hesap ayrıntılarınızı parola yöneticisine kaydettikten sonra, hatırlamanız gereken tek parola ana paroladır. Parola yöneticisi diğerlerini sizin için hatırlayacak. "master password" oluşturmasında yarıdım arıyorsanız [iyi-bir-sifre-nasil-olusturulur.md](iyi-bir-sifre-nasil-olusturulur.md "mention") dokümanımıza bakabilirsiniz.

### Bir parola yöneticisi kullanmalı mıyım?

Kısacası evet. Parola yöneticileri çok iyi bir şeydir. Herkesin hatırlaması gereken çok fazla parolanın olduğu bir dünyada size büyük avantajlar sağlarlar. Örneğin;

* Farklı siteler ve hizmetler arasında uzun, karmaşık, benzersiz parolaları ezberlemek zorunda kalmadan, güçlü parolalar kullanmanızı sağlar.
* Sahte web sitelerini tespit etmede insanlardan daha iyidirler, bu nedenle kimlik avı saldırılarına düşmenizi önlemeye yardımcı olabilirler.
* İhtiyaç duyduğunuzda yeni şifreler oluşturabilir ve bunları otomatik olarak doğru yerlere yapıştırabilirler.
* Parolalarınızı tüm cihazlarınızda senkronize edebilirler, böylece ister dizüstü bilgisayarınızda ister telefonunuzda veya tabletinizde olun, parolalarınız yanınızda olacaktır.(hepsi yapmamaktadır)

Bütün bunlar kullanıcılar için kolay ve efor harcamadan uyarlanabilir bir güvenlik yöntemi oluştur. Ne de olsa bizi uğraştıran ya da rahatsız eden bir şey varsa her zaman uğraştırmayan bir yöntem ararız. Parolalar da işin kolayı tüm hesaplarınız aynı parolayı koymak olduğu için parola yöneticileri çok büyük bir önlem ve kolaylıktır.

### <mark style="color:orange;">Kulağa harika geliyor. Gerçekten bu kadar iyi mi?</mark>

Peki gerçekten kusursuzlar mı? Hemen hiç düşünmeden kullanmaya başlamalı mıyım? Hayır bazı sıkıntılar var.

* Parola yöneticileri tek başına çok çekici bir saldırı hedefidir. Tüm şifrelerinizi barındıran tek bir sistem olması büyük bir risktir. Örnek vermek gerekirse çok kullanılan bir parola yöneticisi olan LastPass 2021 Aralık ayında uygulamalarına izin erişim girişimi bulunulduğunu açıkladı. Olay hakkında yazı [LastPass says no passwords were compromised following breach scare](https://www.theverge.com/2021/12/28/22857485/lastpass-compromised-breach-scare).
* Geçmişte bir şekilde saldırıya uğradılar ve gerçekçi olmak gerekirse tekrar olacaktır.
  * 2017, 2016, 2015 ve 2014 de KeePass, LatsPass, Keeper ve 1Password gibi bir çok bilinen uygulama zafiyetler bulundu.
* Onları her şey için kullanamazsınız. Bazı servisler (belirli bankalar gibi) şifre yöneticilerinin kullanımını desteklemez. Parola yöneticilerin otomatik olarak şifreleri girmesine izin vermez.
* Banka şifrelerinizi bir şifre yöneticisine koyduğunuzu (veya herhangi bir şekilde not ettiğinizi) söylerseniz, siber suç mağduru olmanız durumunda paranızı size geri vermeyebilirler. İşin iyi yanı, parolalarınızın çoğunu ezberlemek zorunda olmadığınız için sadece banka şifrenizi ezberlemek kolay olacaktır. (Bazı bankalar şifre yöneticilerini 3. şahıs olarak gördüğü için, şiflerinizi alenen başkasına vermiş gibi değerlendirebilir ve yapılan harcamalardan sizin sorumlu olduğunuzu idaa edebilir, paranızı geri vermeye bilir.)

### Tarayıcı tabanlı bir şifre yöneticisi kullanmalı mıyım?

Birçok web tarayıcısı artık yerleşik parola yöneticileriyle birlikte gelir ve bunlar çok iyi bir seçim olabilir. Web tarayıcısı ile tamamen entegre oldukları için kullanımı çok kolaydır.

Böylece, parola gerektiren bir web sitesinde olduğunuzu anlarlar ve hemen açılırlar ve verileri otomatik ya da size sorarak girerler. Bu algılamayı yaparken siteleri kontrol ettikleri için sahte (oltalama) sitelerinde doğaları gereği çalışmazlar.

Bu nedenle, aşağıdakileri sağlamak koşuluyla tarayıcıların şifre yöneticisini kullanmaktan çekinmeyin;

* Web tarayıcınızı güncel tutarsınız.
* Cihazınızda PIN/şifre/biyometrik gibi bir tür erişim kontrolünüz olması.

Tarayıcı tabanlı parola yöneticilerinin bir dezavantajı, farklı işletim sistemleri kullanıyorlarsa parolalarınızın tüm cihazlarınız arasında otomatik olarak eşitlenmeyebilmesidir. Dolayısıyla, bir Windows dizüstü bilgisayarınız, bir iPad'iniz ve bir Android akıllı telefonunuz varsa, tüm cihazlarınızda aynı web tarayıcısını kullanmadığınız ve oturum açmadığınız sürece parolalarınız sizinle beraber cihaz değiştirmez.&#x20;

### Bağımsız bir parola yöneticisi kullanmalı mıyım?

Tarayıcı tabanlı yöneticilerle karşılaştırıldığında, bağımsız şifre yöneticileri, hangi platformda olurlarsa olsunlar, şifrelerinizi farklı cihazlarınızda kullanımınız konusunda daha iyi bir iş çıkarma eğilimindedir.

Daha da önemlisi, bağımsız bir parola yöneticisiyle (tarayıcı tabanlı parolanın aksine) uzun bir ana parola oluşturmanız (Master Password) ve hatırlamanız gerekir. Bağımsız parola yöneticileri ayrıca aşağıdakiler gibi daha gelişmiş özellikler içerebilir;

* Güvenliği ihlal edilmiş web siteleri hakkında bildirimler verebilirler.
* Yeniden kullanılan veya zayıf şifreleri işaretleyebilirler. Detaylı bilgi için [iyi-bir-sifre-nasil-olusturulur.md](iyi-bir-sifre-nasil-olusturulur.md "mention")
* Eski şifreleri değiştirmenizi isteyebilirler.
* Çok faktörlü kimlik doğrulama kullanabilirler. Detaylı bilgi için [iki-faktoerlue-kimlik-dogrulama-2fa.md](iki-faktoerlue-kimlik-dogrulama-2fa.md "mention")

{% hint style="warning" %}
Bilgisayarınıza lokal olarak bir parola yöneticisi kurmayı seçebilirsiniz veya bulut tabanlı bir parola yöneticisi de seçebilirsiniz. Yerel olarak depolanmış bir parola yöneticisine karar verirseniz, bilgisayarınızı düzenli olarak yedeklediğinizden emin olun.Bu, şifre yöneticinizin silinmesi durumunda veya bir siber saldırıdan sonra bilgisayarınızın geri yüklenmesi gerektiğinde korunmasına yardımcı olacaktır.
{% endhint %}
