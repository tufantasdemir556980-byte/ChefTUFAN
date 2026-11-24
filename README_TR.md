# Chef TUFAN Android projesi

Tarif defteri, Android WebView içinde çalışan çevrimdışı bir uygulamadır. Tarifler ve fotoğraflar cihazın yerel tarayıcı depolamasında saklanır.

## Telefon üzerinden APK üretmek (GitHub Actions)
1. ZIP dosyasını telefona indirip çıkart.
2. github.com üzerinde hesap aç/giriş yap.
3. New repository ile `ChefTUFAN` adında repository oluştur (Public seçmek Actions kullanımını kolaylaştırabilir; istersen Private da olabilir).
4. Proje klasöründeki tüm dosyaları ve `.github/workflows/build-apk.yml` dosyasını repository'ye yükle. `.github` klasörü dahil olmalı.
5. Repository sayfasında **Actions** sekmesine git. `Chef TUFAN APK` workflow'u görünür.
6. `Run workflow` düğmesine bas (workflow henüz otomatik çalışmadıysa), çalışmasını bekle.
7. Tamamlanınca çalışmanın sayfasında **Artifacts** bölümünden `Chef-TUFAN-APK` dosyasını indir.
8. Artifact ZIP'ini aç; içindeki `app-debug.apk` dosyasını Android telefonuna yükle.

## Bilgisayarla
Android Studio'da projeyi açıp Build > Build APK(s) seçebilirsin.

İlk derleme için internet gerekir. Uygulamanın tarif özellikleri, kurulduktan sonra internet bağlantısı olmadan kullanılmak üzere tasarlanmıştır.
