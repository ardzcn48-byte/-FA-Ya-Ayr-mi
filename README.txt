ŞİFA ZEYTİNYAĞI FABRİKASI — ANDROID UYGULAMASI

Bu proje, hesaplama ekranını Android uygulamasının içine gömer. Uygulama açıldığında internet gerekmez.

APK DOSYASINI ÜRETME — EN KOLAY YOL (Android Studio kurmadan)
1. GitHub hesabına giriş yap veya ücretsiz bir hesap oluştur.
2. Bilgisayarda ZIP'i aç; içindeki dosyaları yeni bir GitHub deposuna yükle. Depo adı örneğin: sifa-zeytinyagi.
   Önemli: ZIP'in içindeki dosyaları yükle; ZIP dosyasının kendisini değil.
3. GitHub deposunda Actions sekmesine gir.
4. "Build Şifa Zeytinyağı APK" iş akışını seçip "Run workflow" düğmesine bas. İlk push'ta da otomatik derleme başlayabilir.
5. İşlem tamamlandığında iş akışı çalışmasının altındaki Artifacts bölümünden "Sifa-Zeytinyagi-APK" dosyasını indir.
6. İndirilen ZIP'i aç. İçindeki app-debug.apk dosyasını Android telefonuna gönder ve yükle.
7. Android sorarsa Chrome/Dosyalar uygulaması için "Bilinmeyen uygulamaları yükle" iznini aç. APK'yı yalnızca kendi oluşturduğun depodan indir.

Alternatif: Android Studio'da projeyi açıp Build > Build Bundle(s) / APK(s) > Build APK(s) seçebilirsin.

TEKNİK NOT
Bu ortamda Android SDK/Gradle bulunmadığından hazır APK'yı burada doğrudan derleyemedim. Proje, GitHub Actions iş akışı eklenerek APK'yı bulutta derleyebilecek şekilde hazırlandı. İlk kez yüklenen APK debug imzalıdır; Play Store yayımlaması için ayrı bir imzalama ve paketleme süreci gerekir.
