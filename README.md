# ✈️ Airline Passenger Satisfaction Analysis

Bu proje, [Kaggle](https://www.kaggle.com/datasets/teejmahal20/airline-passenger-satisfaction) platformundan alınan **Airline Passenger Satisfaction Dataset** veri seti kullanılarak gerçekleştirilmiş kapsamlı bir veri analizi çalışmasıdır.

---

## 📌 Proje Amacı

Uçak yolculuğu yapan yolcuların demografik bilgileri, hizmet kalitesi değerlendirmeleri ve memnuniyet düzeyleri üzerinden çeşitli analizler yapılarak:

- Müşteri memnuniyetini etkileyen faktörlerin belirlenmesi,
- Aykırı ve eksik verilerin yönetimi,
- Görsel ve istatistiksel yöntemlerle verilerin yorumlanması,
- Veriye dayalı çıkarımlarla karar destek sistemlerine zemin hazırlanması amaçlanmıştır.

---

## 🗂️ Kullanılan Veri Seti

- **Veri Seti Kaynağı:** [Kaggle - Airline Passenger Satisfaction](https://www.kaggle.com/datasets/teejmahal20/airline-passenger-satisfaction)
- **Veri Türü:** Gerçek dünya, sınıflandırma problemi (memnun/memnun değil)
- **Özellik Sayısı:** 25+
- **Veri Boyutu:** Yaklaşık 100.000 satır
- **Veri Dosyaları:** `train.csv` ve `test.csv` birleştirilerek analiz edilmiştir.

---

## 🔍 Uygulanan Analizler

### ✔️ İstatistiksel Özet
- Ortalama, medyan, min, max, standart sapma
- Dağılım şekilleri (çarpıklık yorumları dahil)

### ✔️ Eksik Değer Analizi
- `Arrival Delay in Minutes` kolonunda 393 eksik değer tespit edildi.
- Medyan değeri ile doldurularak analiz devam ettirildi.

### ✔️ Aykırı Değer Analizi
- Sayısal değişkenlerde IQR yöntemi kullanıldı.
- Toplam 16.834 aykırı gözlem filtrelenerek temiz veri elde edildi.

### ✔️ Görselleştirme
- Histogram (Flight Distance)
- Boxplot (Age, Inflight Service)
- Countplot (Gender, Customer Type, Class vs. Satisfaction)
- KDE (Flight Distance)
- Segmentasyon ve memnuniyet karşılaştırmaları

---

## 📊 Kullanılan Kütüphaneler

- `pandas`
- `matplotlib`
- `seaborn`
- `numpy`

---

## 📝 Notlar

Bu çalışma bireysel olarak veri analizi yetkinliklerini göstermek ve müşteri deneyimi ile hizmet kalitesini ölçümleyerek içgörü üretmek amacıyla yapılmıştır.  
Tüm analizler Python dilinde Jupyter Notebook ortamında gerçekleştirilmiştir.

---

## 📁 Çıktılar

- [Analiz Raporu (PDF)](./airline_satisfaction_report_clean.pdf)
- Jupyter Notebook: `final_task.ipynb`

---

## 📬 İletişim

📧İlayda Çelikkaya -ilaydacelikkaya2@gmail.com
🎓 Süleyman Demirel Üniversitesi – Bilgisayar Mühendisliği  
