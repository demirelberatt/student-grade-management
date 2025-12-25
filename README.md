# student-grade-management
Input edilen öğrenci notlarını dosya haline getirir ve aynı dosyadan veri çekebilir.
İlk projemdir!

**🎓 Öğrenci Not Yönetim Sistemi**

Bu proje, öğrencilerin sınav notlarını kaydeden, ortalamalarını hesaplayan ve bu ortalamaları harf notuna dönüştürerek raporlayan basit bir Python uygulamasıdır. Veriler metin dosyaları (.txt) üzerinde saklanır ve yönetilir.
**🚀 Özellikler**

    Notları Görüntüle: Mevcut kayıtlı öğrencilerin ortalamalarını ve harf notlarını ekrana yazdırır.

    Not Gir: Yeni öğrenci adı, soyadı ve 3 farklı sınav notunu sisteme ekler.

    Notları Kaydet: Tüm öğrencilerin harf notu sonuçlarını letterGrades.txt dosyasına kalıcı olarak raporlar.

    Hata Yönetimi: Geçersiz not girişlerini (sayı olmayan değerler) ve menü seçim hatalarını kontrol eder.

**🛠️ Kullanılan Teknolojiler**

    Dil: Python 3

    Veri Saklama: Dosya İşlemleri (File I/O - .txt)

**📋 Harf Notu Skalası**

Sistem şu aralıklara göre harf notu hesaplar:

    90 - 100: AA

    85 - 89: BA

    80 - 84: BB

    ... (ve devamı)

    0 - 54: FF

**💻 Kullanım**

    Bilgisayarınızda Python yüklü olduğundan emin olun.

    Depoyu klonlayın veya dosyayı indirin.

    Terminal/Komut istemcisinde dosyanın bulunduğu dizine gidin.

    Aşağıdaki komutu çalıştırın:
    Bash

    python gradeApplication.py

    Ekrandaki menüden yapmak istediğiniz işlemi seçin (1-4).

**📂 Dosya Yapısı**

    gradeApplication.py: Uygulamanın ana kaynak kodu.

    sinavNotlari.txt: Ham verilerin (isim ve notlar) tutulduğu dosya.

    letterGrades.txt: Hesaplanan harf notlarının kaydedildiği çıktı dosyası.
