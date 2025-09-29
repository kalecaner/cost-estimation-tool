# 💰 CostEstimationApp  
_Cost estimation and password system sample app (for learning / eğitim amaçlı)_

Bu proje, maliyet tahmini (cost estimation) ve basit bir şifre sistemi içeren örnek bir uygulamadır.  
**Tamamen eğitim ve kişisel gelişim amacıyla** geliştirilmiştir.  
This project is a sample application with cost estimation and a simple password system.  
It is developed **purely for educational and personal development**.

---

## 🎯 Projenin Amacı / Project Purpose

**TR**  
- Maliyet tahmini süreçlerini modellemek ve uygulamak  
- Basit kullanıcı / şifre sistemiyle birlikte güvenlik konseptleri görmek  
- CRUD işlemleri, doğrulama, iş mantığı katmanlarını pratik etmek  

**EN**  
- Model and implement cost estimation processes  
- Demonstrate basic user/password system with security concept  
- Practice CRUD operations, validation, business logic layers  

---


- `WinFormsApp_MasrafOtomasyonu/` → Görsel uygulama UI (WinForms)  
- `Domain/` → `Cost`, `User`, `Password` gibi modeller  
- `Application/` → Maliyet tahmin servisleri, iş kuralları  
- `Infrastructure/` → Veri erişim, dosya / DB işlemleri  
- `Security/` → Şifreleme / parola kontrolü  
- `Tests/` → İş mantığı ve güvenlik kontrolleri için testler  

---

## 🛠 Teknolojiler / Technologies

- C# / .NET (WinForms ya da başka UI)  
- Veri erişim: Entity Framework, Dapper ya da dosya tabanlı sistem  
- Şifreleme / Hashing (örneğin SHA, AES, bcrypt vb.)  
- Validation kütüphaneleri (örneğin FluentValidation)  
- Unit test çerçevesi (xUnit, NUnit vb.)  

---

## 🚀 Kurulum & Çalıştırma / Setup & Running

### 1. Repoyu Klonla / Clone the Repository  
```bash
git clone https://github.com/kalecaner/CostEstimationApp.git
cd CostEstimationApp


