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
- **CV Sitesi Kullanıcı Paneli**  


- **CV Sitesi Admin Paneli**  


---

## Proje Yapısı
/DinamikCV
│
├── Controllers
│ ├── AdminController.cs
│ └── HomeController.cs
│
├── Models
│ └── EF (DB First)
│
├── Views
│ ├── Admin
│ ├── Home
│ └── Shared (PartialViews)
│
├── Scripts
├── Content
└── Web.config

---

## Kurulum ve Çalıştırma
1. Repository’i klonlayın:
```bash
git clone https://github.com/sena-nur-ozdemir/dinamik-cv.git

2. Visual Studio ile projeyi açın.

3. SQL Server üzerinde veritabanı bağlantısını yapılandırın:
-DB First yaklaşımı kullanıldığı için, .edmx dosyası üzerinden veritabanını bağlayın.
-Gerekli connection string’i Web.config içinde güncelleyin.

4. Projeyi çalıştırın:
-Visual Studio’da IIS Express veya uygun bir sunucu ile çalıştırabilirsiniz.
-Tarayıcıda açıldığında kullanıcı panelini görüntüleyebilir, admin paneline giriş yaparak içerikleri yönetebilirsiniz.

5.Admin paneline giriş yapmak için:
Kullanıcı adı ve şifreyi veritabanından kontrol edin veya ilk kayıt için seed verileri kullanın.

---

📝 Katkılar

Bu proje, Udemy’deki Admin Panelli Dinamik CV kursu tamamlandıktan sonra geliştirilmiş olup, Murat Yücedağ hocamın yönlendirmeleri sayesinde tamamlanmıştır.
