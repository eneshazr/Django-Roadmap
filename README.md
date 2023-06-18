# Python Django Yol Haritası

![image](https://github.com/yazilimfuryasi/Django-Roadmap/assets/84662757/647c94da-8dba-46de-acae-bac756f1e729)


💡 `Bu yola, en azından Python'un temel seviyesine hakim olarak başlandığını baz alıyorum.`

### 👶 Temel
  * **virtualenv**: Sanal çalışma ortamı sağlayıp projeleri izole edin.
  * Proje ve uygulama oluşturun.
  * **Views, Urls** dosyalarını anlayın.
  * **Templates, Staticfiles**: Django şablon olarak **Jinja2** kullanır. Bunu araştırıp ve temel **HTML** bilgisi ile görsel içerikli bir sayfa yazın.
  * **Template Partials yapısı**: Oluşturduğunuz şablonu Partials kullanarak geliştirin.
  * **ORM yapısı ve Models**: İlişkisel veri tabanını araştırıp basit bir model oluşturun. Başlangıç için **SQLite** veritabanı idealdir.
  * **Admin**: Admin dosyasını inceleyin ve admin panelinden veritabanına veri ekle, düzenle, sil metotlarını uygulayın.
  * **Model Forms**: Model formunu kullanmayı öğrenin.
  * **Context Processors**: Bazen şablon dosyalarına ek veri göndermemiz gerekebiliyor. Kullanmanızda fayda var.
  * **Signals**: Sinyaller kullanarak kodun çalışmasını takip edin.

### ⭐ Orta 
  * **User Authentication**: Kullanıcı kimlik doğrulama (authentication) işlemlerini öğrenin. Kullanıcı kaydı, giriş ve çıkış gibi temel işlemleri yapın.
  * **Class-Based Views**: Sınıf tabanlı görüntüleri öğrenin.
  * **Querysets**: ORM'inin güçlü sorgu yapısını öğrenin. Veritabanından veri sorgulamak, filtrelemek, sıralamak ve ilişkili nesneleri almak için queryset'lerin nasıl kullanıldığını araştırıp uygulayın.
  * **Middleware**: Middleware yapısını anlayın ve nasıl özelleştirebileceğini öğrenin.
  * **File Uploads**: Dosya yükleme işlemlerini nasıl gerçekleştireceğini öğren. Dosyaları sunucuya yükle ve işleyin.  

### ⚡ İleri
 * **Testing**: Test yazma ve otomatik testleri nasıl yürüteceğini öğrenin.
  * **Serializer**: API için sık kullanılan bu yapıyı araştırın.
  * **REST Framework**: API nedir, nasıl kullanılır öğren ve öğrendiklerini uygulayın.
  * **Cache Yönetimi**: Çerezleri kullanarak performansı arttırın.


### 📦 Djangoda Kullanılan Popüler Paketler
  * **Django REST Framework**: API'ler oluşturmak için gelişmiş bir çerçeve sağlar.
  * **Django Celery**: Asenkron görev yönetimi için kullanılır.
  * **Django Channels**: Gerçek zamanlı iletişim için WebSocket desteği sağlar.
  * **django-crispy-forms**: Şık form tasarımları oluşturmanıza yardımcı olur.
  * **django-allauth**: Kullanıcı kimlik doğrulama ve sosyal medya entegrasyonu için kapsamlı bir çözüm sunar.
  * **django-cors-header**s: Django ile Cross-Origin Resource Sharing (CORS) desteği ekler.
  * **django-debug-toolbar**: Geliştirme sırasında hata ayıklama için kullanışlı bir araç çubuğu sağlar.
  * **django-guardian**: Nesne düzeyinde erişim kontrolleri için yetkilendirme sağlar.
  * **django-taggit**: Etiket (tag) sistemi entegrasyonu sağlar.
  * **django-widget-tweaks**: Django şablonlarında form widget'larını kolayca özelleştirmenizi sağlar.
  * **django-caching-app**: Django önbellek yapısını geliştirir ve önbelleğe alma işlemlerini kolaylaştırır.
  * **django-silk**: Django uygulamanızdaki performans analizi yapmanıza olanak tanır.
  * **django-ckeditor**: Zengin metin düzenleyicisi CKEditor'ün Django ile entegrasyonunu sağlar.
  * **django-payments**: Ödeme entegrasyonu için kullanılır.

### 🛡 Django Uygulamasının Güvenliği
  * **Cross-Site Scripting (XSS) Koruması**: Django şablon motoru ve form işleme mekanizmalarını doğru şekilde kullanarak XSS saldırılarına karşı önlem alınmalı.
  * **Cross-Site Request Forgery (CSRF) Koruması**: Django, CSRF saldırılarına karşı otomatik olarak koruma sağlar, ancak doğru yapılandırma ve kullanımınızı sağlamak için bu özelliği anlayın ve uygulamanızı doğrulayın.
  * **Güçlü Parola ve Kullanıcı Doğrulama Politikaları**: Kullanıcıların güçlü şifreler seçmelerine yol gösterin ve gerektiğinde şifre sıfırlama işlemleri için doğru yöntemleri kullanın.
  * **Veritabanı Güvenliği**: Django ORM'i, veritabanına güvenli bir şekilde erişmek için kullanıcı girişi, filtreleme ve sorgu parametrelerini kullanmayı öğrenin.
  * **Güvenli Oturum Yönetimi**: Django oturum yönetimi özelliklerini kullanarak oturumların güvenliğini sağlayın, oturumları zaman aşımına uğratın ve oturum kimlik bilgilerini doğru şekilde işleyin.
  * **Güvenli Dosya İşlemleri**: Kullanıcıların yüklediği dosyaları doğru bir şekilde işleyin, dosya yollarını kontrol edin, yetkilendirme kontrolleri yapın ve zararlı dosyaların sunucuya yüklenmesini önleyin.
  * **Güncel Sürümleri ve Güvenlik Yamalarını Takip Etme**: Django'nun güncel sürümlerini kullanarak güncel güvenlik düzeltmelerini takip edin ve uygulamalarınızı güncel tutun.
  * **Hata Ayıklama ve Loglama**: Django'nun hata ayıklama ve loglama mekanizmalarını etkinleştirin ve uygulamanızdaki hataları izleyin, kaydedin ve analiz edin.
  * **Doğrulama ve Yetkilendirme**: Django'nun doğrulama ve yetkilendirme mekanizmalarını doğru şekilde kullanarak kullanıcı erişimini kontrol edin ve yetkilendirme kontrollerini uygulayın.
  * **Güvenlik İncelemeleri ve Zafiyet Taramaları**: Uygulamanızı düzenli olarak güvenlik açıklarına karşı inceleyin, zafiyet taramaları yapın ve gerektiğinde güvenlik açıklarını düzeltmek için önlemler alın.

### 🚀 Dağıtım / Deployment
  * **Sunucu**: Herhangi bir server üzerinden yayına alın. Şimdilik lokal olabilir. Ancak gerçek bir uygulama yaptıysanız, hosting olarak **AWS** veya **DigitalOcean**, sistem olarak ise **Ubuntu** tavsiye edebilirim.
  * **Nginx, SSL**: **Nginx** ile URL yönlendirmelerini yap ve **SSL** sertifikasını kullanın.
  * **Gunicorn**: Gunicorn kullanarak uygulamayı ayakta tutun.
  * **Docker**: Sıradan dağıtım kullandıktan sonra Docker öğren ve docker üzerinden deploy işlemi gerçekleştirin.


### 📝 Not
  Burada yazılanların hepsini tek seferde yapmaya çalışmayın. Projeler geliştirdikçe zaten ister istemez tüm bunları yapmış olacaksınız. Sık karşılaştığım bir kaç iş/proje örneği yazmak istiyorum.
  * E-Ticaret ve Blog sitesi
  * Chat Sistemi
  * Ödeme Sistemi

Başarılar...
