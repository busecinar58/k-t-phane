# Kütüphane Yönetim Sistemi - Sınıf (Class) Diyagramı

Bu proje, bir Kütüphane Yönetim Sistemi için nesne yönelimli analiz ve UML sınıf modellemesini içermektedir.

## Sistem Mimarisi ve İlişkiler
- **Kullanıcı (Base Class):** `Üye` ve `Kütüphane Görevlisi` sınıfları bu sınıftan türemektedir (Kalıtım / Inheritance).
- **Kitap & Kitap Kopyası:** Kitap ile fiziksel kopyaları arasında parça-bütün ilişkisi bulunmaktadır (Composition).
- **Ödünç Alma:** Üye ve Kitap Kopyası sınıfları ile bire çok (1..*) ilişkilendirme (Association) yapılmıştır.

## UML Sınıf Diyagramı
![Kütüphane Sınıf Diyagramı](diyagram.png)
