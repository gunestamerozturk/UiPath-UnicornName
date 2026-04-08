# 🦄 UiPath Studio Web: Unicorn Name Generator

Bu proje, **UiPath Academy - Agentic Automation Training** kapsamında geliştirilmiş, bulut tabanlı bir RPA (Robotic Process Automation) uygulamasıdır. Projenin temel amacı, UiPath Studio Web arayüzüne aşinalık kazanmak, Google Workspace entegrasyonlarını deneyimlemek ve temel UI otomasyon süreçlerini uçtan uca kurgulamaktır.

---

## 🚀 Projenin Amacı
UiPath Studio Web ortamında; tarayıcı tabanlı işlemler, Google Drive/Sheets entegrasyonu ve e-posta otomasyonu gibi temel bileşenleri bir araya getirerek manuel bir süreci tam otonom hale getirmek.

## 🛠️ Uygulama Ne Yapıyor?
Otomasyon süreci aşağıdaki adımları sırasıyla gerçekleştirir:

1.  **Veri Okuma:** Google Drive üzerinde bulunan bir Google Sheets dosyasındaki isim ve doğum ayı verilerini okur.
2.  **UI Otomasyonu:** Her bir satır için [rpasamples.com/unicornname](https://rpasamples.com/unicornname) web sitesine gider.
3.  **Veri Girişi:** Tablodaki ismi ve ayı ilgili alanlara yazar, "Get Name" butonuna tıklar ve oluşturulan "Unicorn Name" sonucunu kopyalar.
4.  **Veri Yazma:** Alınan sonucu tekrar Google Sheets dosyasındaki ilgili sütuna dinamik olarak yazar.
5.  **Dosya Yönetimi:** Güncellenen dosyayı yerel dizine indirir.
6.  **Bildirim:** İşlem tamamlandığında, indirilen dosyayı ekleyerek belirlenen adrese bir bilgilendirme e-postası gönderir.

## 🧰 Kullanılan Teknolojiler
* **UiPath Studio Web:** Bulut tabanlı geliştirme ortamı.
* **Google Workspace Activity Set:** Google Drive ve Google Sheets işlemleri için.
* **UI Automation:** Web tarayıcı etkileşimleri için.
* **Gmail/Outlook Integration:** E-posta gönderimi ve dosya paylaşımı için.

## ⚙️ Kurulum ve Çalıştırma
Bu projeyi kendi ortamınızda çalıştırmak için:
1. Projeyi `.zip` olarak indirin ve UiPath Studio Web arayüzünden içeri aktarın (Import).
2. Google Sheets ve E-posta servisleri için kendi bağlantılarınızı (**Connections**) oluşturun veya mevcut olanları yetkilendirin.
3. Kullanılan Google Sheets dosyasının başlıklarının `Name`, `BirthdayMonth` ve `UnicornName` olduğunu doğrulayın.

---
*Bu proje eğitim amaçlı geliştirilmiştir.*
