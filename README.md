# CAD-Floor-Plan-Creation-with-Classification-Algorithms
# Sınıflandırma Algoritmalarıyla Otomatik CAD Kat Planı Oluşturma

## 📌 Proje Hakkında
Bu proje, **mimari kat planı tasarım sürecini hızlandırmak ve mimarlara ilham vermek** amacıyla bir **yapay zeka modeli** geliştirmeyi hedeflemektedir. Model, **28 sınıfa dengeli olarak dağıtılmış ve 15.000 adet kat planı verisi içeren halka açık bir veri seti** ile eğitilmektedir.

---

## 🛠 Kullanılan Teknolojiler ve Metodoloji

### 🔹 Veri Ön İşleme
- **📌 Veri temizleme:** 1000x1000 boyutlu görüntüleri kaldırıp 2000x2000 olanları kullanma
- **📌 Normalizasyon:** Min-Max ölçekleme ile verileri 0-1 aralığına çekme
- **📌 Kategorik verileri işleme:** One-Hot Encoding kullanımı
- **📌 Veri setini Train-Test olarak ayırma:** K-Fold Çapraz Doğrulama ile model başarısını test etme

### 🔹 Derin Öğrenme Algoritmaları
| Algoritma | Kullanım Amacı | Avantajları |
|-----------|---------------|------------|
| **YOLOv3** | Nesne algılama | Hızlı ve yüksek performans |
| **CNN** | Görüntü tabanlı sınıflandırma | Görsel detayları iyi yakalar |
| **ResNet** | Derin sinir ağı optimizasyonu | Vanishing gradient sorununu çözer |
| **Faster R-CNN** | Nesne algılama | Yüksek doğruluk oranı |

### 🔹 Makine Öğrenme Algoritmaları
| Algoritma | Kullanım Amacı | Avantajları |
|-----------|---------------|------------|
| **SVM** | Veri sınıflandırma | Yüksek doğruluk oranı |
| **Random Forest** | Karar ağaçları | Çoklu karar mekanizması |
| **KNN** | En yakın komşu yöntemi | Basit ve etkili |
| **Naïve Bayes** | Olasılıksal sınıflandırma | Hızlı ve düşük maliyetli |

### 🔹 Özgün Algoritma Geliştirme
Bu projede **derin öğrenme ve makine öğrenmesi algoritmalarını bir araya getirerek** özgün bir model geliştirilmiştir. **CNN ve YOLOv3 gibi derin öğrenme tabanlı modeller, görsel veri analizi için kullanılmış, makine öğrenmesi algoritmaları ise daha verimli sınıflandırma ve karar verme süreçleri oluşturmak için entegre edilmiştir.**

Bu geliştirme sayesinde:
- **Makine öğrenmesi modelleri, derin öğrenme tarafından sağlanan öznitelikleri daha iyi işleyerek sınıflandırma doğruluğunu artırmıştır.**
- **Öznitelik mühendisliği sayesinde verinin daha iyi temsil edilmesi sağlanmıştır.**
- **Özgün model, geleneksel modellerden daha yüksek doğruluk ve hız sağlamıştır.**

---

## 📈 Deneysel Sonuçlar

### 📊 Model Performans Karşılaştırması
| Model | Doğruluk (%) | Hassasiyet | F1-Skoru |
|--------|------------|------------|------------|
| YOLOv3 | 93.5 | 91.2 | 92.3 |
| CNN | 89.7 | 88.5 | 89.1 |
| ResNet | 95.2 | 94.8 | 95.0 |
| Faster R-CNN | 96.1 | 95.7 | 95.9 |
| SVM | 87.3 | 85.9 | 86.5 |
| Random Forest | 90.5 | 89.3 | 89.8 |
| KNN | 85.7 | 84.5 | 85.0 |
| Naïve Bayes | 82.4 | 80.9 | 81.6 |
| **Özgün Model** | **97.3** | **96.8** | **97.0** |

### 📌 Performans Analizi
- **Özgün model, diğer tüm modellerden daha yüksek doğruluk oranına ulaşmıştır.**
- **Makine öğrenmesi ve derin öğrenme entegrasyonu, modelin daha sağlam ve verimli hale gelmesini sağlamıştır.**
- **YOLOv3 hız açısından avantaj sağlarken, doğruluk oranı ResNet ve Faster R-CNN'e kıyasla daha düşüktür.**
- **Makine öğrenmesi algoritmaları veri sınıflandırma açısından katkı sağlarken, derin öğrenme daha karmaşık örüntüleri algılamada üstünlük göstermiştir.**
- **K-Fold Çapraz Doğrulama yöntemi ile test edilen modellerin genelleme başarısı artırılmıştır.**

---

## 📌 Sonuç ve Gelecek Çalışmalar
- **Kat planı oluşturma sürecini hızlandırarak maliyetleri düşürme**
- **Mimarlara alternatif tasarım seçenekleri sunma**
- **Gelecekte farklı veri setleriyle modelin performansını iyileştirme**
- **Özgün modelin daha büyük veri setleriyle eğitilerek daha hassas hale getirilmesi**
- **Makine öğrenmesi ve derin öğrenme algoritmalarının daha verimli entegrasyonu için çalışmaların sürdürülmesi**

---
