# İzin Takip Sistemi

## Genel Bakış

İzin Takip Sistemi, şirketlerdeki personellerin yıllık izin, mazeret izni, hastalık izni gibi tüm izin süreçlerini yönetmek için tasarlanmış bir uygulamadır. Sistem, Flask web çerçevesi üzerine inşa edilmiş olup, SQLite veritabanı kullanmaktadır.

## Özellikler

- Personel bilgilerinin kayıt ve takibi
- Farklı izin türlerinin (yıllık, mazeret, hastalık, ücretsiz) yönetimi
- Personele göre izin geçmişi görüntüleme
- Kalan izin sürelerinin otomatik hesaplanması
- Resmi tatiller ve özel günlerin tanımlanması
- Departman ve görev tanımlamaları
- Kullanıcı yönetimi (admin, normal kullanıcı)
- Excel'e veri aktarımı

## Kurulum

### Windows Kurulum Programı ile Kurulum

1. `İzin Takip Sistemi Kurulum.exe` dosyasını çalıştırın
2. Kurulum sihirbazını takip edin
3. Kurulum tamamlandığında, masaüstünde oluşturulan kısayolu kullanarak uygulamayı başlatabilirsiniz

### Manuel Kurulum

1. `İzin Takip Sistemi.exe` dosyasını istediğiniz bir konuma kopyalayın
2. Exe dosyasını çalıştırarak uygulamayı başlatın
3. Web tarayıcınızı açın ve `http://127.0.0.1:5001` adresine gidin

## İlk Kullanım

- Uygulama ilk kullanımda otomatik olarak veritabanını oluşturur
- Varsayılan admin kullanıcısı bilgileri:
  - Kullanıcı adı: `admin`
  - Şifre: `admin123`
- Güvenlik için ilk girişte şifrenizi değiştirmeniz önerilir

## Kullanım

### Personel Yönetimi

- Personel eklemek için "Personel" menüsünden "Yeni Personel Ekle" seçeneğini kullanın
- Personelleri listelemek için "Personel" menüsüne tıklayın
- Personel detaylarını görüntülemek için listedeki personel adına tıklayın
- Personel bilgilerini düzenlemek için detay sayfasındaki "Düzenle" butonunu kullanın

### İzin Yönetimi

- İzin eklemek için personel detay sayfasından "İzin Ekle" butonuna tıklayın
- İzin geçmişini görüntülemek için personel detay sayfasındaki "İzin Geçmişi" sekmesini kullanın
- Tüm izinleri listelemek için "İzinler" menüsüne tıklayın

### Tanımlamalar

- Resmi tatil eklemek için "Tanımlamalar" > "Resmi Tatiller" menüsünü kullanın
- Departman tanımlamaları için "Tanımlamalar" > "Departman Tanımlamaları" menüsünü kullanın
- Görev/Statü tanımlamaları için "Tanımlamalar" > "Görev/Statü Tanımlamaları" menüsünü kullanın

## Teknik Detaylar

- Uygulama, Flask web çerçevesi kullanılarak geliştirilmiştir
- Veritabanı olarak SQLite kullanılmaktadır
- Kullanıcı arayüzü, Bootstrap 5 ile tasarlanmıştır
- Kullanıcı kimlik doğrulama için Flask-Login kullanılmaktadır

## Sorun Giderme

- Uygulama başlatılamıyorsa, bilgisayarınızı yeniden başlatmayı deneyin
- Veritabanı hataları için uygulamayı yeniden başlatmayı deneyin
- 5001 portunu kullanan başka bir uygulama varsa çakışma olabilir

## İletişim

Sorularınız veya geri bildirimleriniz için: [alisoglu@yahoo.com] 