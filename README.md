# AI-PDF-DİLCEVİRİCİ
# 🌍 Yapay Zeka Destekli Bağlam Duyarlı PDF Çeviri Aracı

![Python](https://img.shields.io/badge/Python-3.9%2B-blue?style=for-the-badge&logo=python&logoColor=white)
![Google Gemini](https://img.shields.io/badge/AI-Gemini%202.5%20Flash-orange?style=for-the-badge&logo=google&logoColor=white)
![PDF Processing](https://img.shields.io/badge/Format-PDF%20to%20PDF-red?style=for-the-badge&logo=adobeacrobatreader&logoColor=white)

## 📖 Proje Hakkında
Bu proje, dil bariyerlerini aşarken orijinal belgenin yapısını ve özünü koruyan akıllı bir doküman çeviri aracıdır. **Google Gemini 2.5 Flash** modelinin gücünü kullanarak, doğrudan **PDF'den PDF'e çeviri** işlemi gerçekleştirir.

Formatı bozan veya basit kelime değişimleri yapan standart araçların aksine, bu sistem **Yapay Zeka Görüşü (AI-Vision)** teknolojisini kullanır. Kaynak PDF'i görsel olarak okur, analiz eder ve profesyonel akışı koruyarak yeniden oluşturur.

## 🚀 Temel Özellikler

### 1. Doğrudan PDF'den PDF'e Çeviri
Araç, kaynak PDF dosyasını alır, içeriğini yapay zeka ile işler ve çevrilmiş çıktıyı doğrudan yeni bir **PDF dosyası** olarak oluşturur. Aracı formatlarla (Word vb.) uğraşmanıza gerek kalmaz.

### 2. Yapay Zeka Destekli Görsel OCR
Hata payı yüksek metin kazıma (text scraping) yöntemleri yerine, bu sistem PDF sayfalarını yüksek çözünürlüklü görsellere dönüştürür. **Gemini Vision**, bu görselleri analiz ederek taranmış belgelerden veya karmaşık tablolardan bile %99 doğrulukla metin çıkarır.

### 3. Bağlam Duyarlı (Context-Aware) Çeviri
Gelişmiş "Prompt Engineering" teknikleri kullanılarak, yapay zekaya "Profesyonel Çevirmen" rolü atanmıştır. Bu sayede:
* Teknik terminoloji korunur.
* Orijinal metnin tonu (resmi/samimi) hedef dile yansıtılır.
* Gramer akışı hedef dilde (örn: Türkçe) doğal ve akıcıdır.

### 4. Asenkron Performans
Python'un `asyncio` kütüphanesi ile geliştirilen altyapı, sayfa işleme ve API çağrılarını eşzamanlı yürüterek çok sayfalı belgelerin çeviri süresini minimuma indirir.

---

## 🛠️ Teknoloji Yığını

| Bileşen | Teknoloji | Açıklama |
|-----------|------------|-------------|
| **Çekirdek Mantık** | Python 3.x | Ana otomasyon scripti. |
| **Yapay Zeka Motoru** | Google Gemini 2.5 Flash | Hem Görsel OCR hem de Çeviri işlemlerini yönetir. |
| **Girdi İşleme** | PyMuPDF (fitz) | Yüksek performanslı PDF render ve ayrıştırma motoru. |
| **Çıktı Oluşturma** | PDF Generator | Çevrilmiş metni PDF formatında yeniden inşa eder. |

---

## ⚙️ Kurulum ve Kullanım

### 1. Projeyi Klonlayın
```bash
git clone [https://github.com/kutayaydeniz/ai-pdf-translator.git](https://github.com/kutayaydeniz/ai-pdf-translator.git)
cd ai-pdf-translator
