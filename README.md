# Dinamik CV Yönetim Sistemi (ASP.NET MVC)

> Profesyonel CV içeriklerinin dinamik olarak yönetilebildiği web uygulaması. Admin paneli sayesinde CV’nin tüm bölümleri kolayca güncellenebilir ve yönetilebilir.

---

## Proje Hakkında
Bu proje, **ASP.NET MVC 5** kullanılarak geliştirilmiş bir **dinamik CV yönetim sistemi**dir.  
Kullanıcılar CV’yi görüntüleyebilirken, admin paneli sayesinde tüm içerikler kolayca güncellenebilir ve yönetilebilir.  

Öğrenilen ve uygulanan temel konular:
- MVC mimarisi ve katmanlı yapı
- Database First yaklaşımı ile **Entity Framework** kullanımı
- Admin yetkilendirme ve güvenlik (ASP.NET Authorize)
- Repository Pattern ile modüler ve tekrar kullanılabilir veri yönetimi
- PartialView kullanımı ile esnek sayfa tasarımı
- Form doğrulama ve veri güvenliği (Required Validation)
- Dinamik içerik yönetimi ve veritabanı işlemleri optimizasyonu

---

## Teknolojiler
| Katman | Teknoloji |
|--------|-----------|
| Backend | C#, ASP.NET MVC 5 |
| Frontend | HTML5, CSS3, JavaScript, Bootstrap |
| Database | Microsoft SQL Server |
| ORM | Entity Framework (DB First) |
| Tasarım | Responsive ve kullanıcı dostu arayüz |

---

## Öne Çıkan Özellikler
- Güvenli admin girişi (ASP.NET Authorize)  
- Repository Pattern ile modüler ve tekrar kullanılabilir kod yapısı  
- PartialView kullanımı ile esnek ve modüler sayfalar  
- Dinamik içerik yönetimi: eğitim, deneyim, beceriler, sertifikalar, projeler  
- Form doğrulama ve veri güvenliği  
- Veritabanı işlemleri optimize edilmiş (Entity Framework DB First)  
- Admin paneli ile tüm CV bölümleri kolayca yönetilebilir  

---

## Kazanımlar
- MVC mimarisi ile proje geliştirme deneyimi  
- Modüler ve sürdürülebilir kod yapısı  
- Dinamik içerik yönetimi ve admin paneli uygulamaları  
- Repository Pattern ve Entity Framework kullanımı  
- Veri doğrulama ve güvenlik uygulamaları  

---

## Kullanıcı Arayüzü

🏠 CV Sitesi Kullanıcı Paneli

<img width="1902" height="912" alt="mvc_cv5" src="https://github.com/user-attachments/assets/a725ca1d-6bf6-459a-8f5b-68bfa115919b" />

<img width="1901" height="915" alt="mvc_cv6" src="https://github.com/user-attachments/assets/e0374102-4d1f-4b3d-8144-baaf88afc6f3" />

<img width="1902" height="907" alt="mvc_cv7" src="https://github.com/user-attachments/assets/a9947b98-f740-4575-98e3-95486a5db75e" />

<img width="1902" height="907" alt="mvc_cv8" src="https://github.com/user-attachments/assets/81054b34-30cf-4b13-93a7-1cf0aff6d191" />

<img width="1898" height="907" alt="mvc_cv9" src="https://github.com/user-attachments/assets/371de785-63dd-43e4-9303-fa141b7a2cc5" />



🛠️ CV Sitesi Admin Paneli

<img width="1917" height="910" alt="mvc_cv1" src="https://github.com/user-attachments/assets/98a0af86-55e8-4b92-aca2-dfbf680ad220" />

<img width="1917" height="911" alt="mvc_cv3" src="https://github.com/user-attachments/assets/57f54261-7f3f-432e-a1a3-2f5ff4a548c7" />

<img width="1915" height="910" alt="mvc_cv2" src="https://github.com/user-attachments/assets/764bf395-1d73-4a86-acbb-093635c83ad9" />

<img width="1916" height="912" alt="mvc_cv4" src="https://github.com/user-attachments/assets/38233baf-3b72-48b2-8f9c-f7bdbb7e210b" />

---

## Proje Yapısı

- **Controllers**
  - AdminController.cs
  - HomeController.cs
- **Models**
  - EF (DB First)
- **Views**
  - Admin
  - Home
  - Shared (PartialViews)
- **Scripts**
- **Content**
- Web.config

---

## Kurulum ve Çalıştırma

1. Repository’i klonlayın:

```bash
git clone https://github.com/sena-nur-ozdemir/dinamik-cv.git
```

2. Visual Studio ile projeyi açın.

3. SQL Server üzerinde veritabanı bağlantısını yapılandırın:
-DB First yaklaşımı kullanıldığı için, .edmx dosyası üzerinden veritabanını bağlayın.
-Gerekli connection string’i Web.config içinde güncelleyin.

4.Projeyi çalıştırın:
-Visual Studio’da IIS Express veya uygun bir sunucu ile çalıştırabilirsiniz.
-Tarayıcıda açıldığında kullanıcı panelini görüntüleyebilir, admin paneline giriş yaparak içerikleri yönetebilirsiniz.

5.Admin paneline giriş yapmak için:
-Kullanıcı adı ve şifreyi veritabanından kontrol edin veya ilk kayıt için seed verilerini kullanın.

---

📝 Katkılar
Bu proje, Udemy’deki Admin Panelli Dinamik CV kursu tamamlandıktan sonra geliştirilmiş olup, Murat Yücedağ hocamın yönlendirmeleri sayesinde tamamlanmıştır.
GitHub profili: [muratyucedag](https://github.com/muratyucedag)
