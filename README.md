# Machine-Learning-Bootcamp

# Şarap Kalitesi Sınıflandırma Projesi

Bu proje, bir şarap veri setini kullanarak şarapların kalitesini sınıflandırmak için makine öğrenimi modeli oluşturmayı amaçlamaktadır. Veri seti, şarapların kimyasal özelliklerini ve kalite puanlarını içerir.

## Kullanılan Modeller

Projede, şu sınıflandırma modelleri kullanılmıştır:

- Support Vector Classifier (SVC)
- Decision Tree Classifier
- Random Forest Classifier
- Gradient Boosting Classifier
- K-Nearest Neighbors (KNN) Classifier

## Model Seçimi ve Eğitimi

İlk olarak, veri seti yüklendi ve ön işleme adımları uygulandı. Daha sonra, farklı modeller çapraz doğrulama ile değerlendirildi ve en iyi performansı gösteren model seçildi. Seçilen en iyi model eğitildi ve test edildi.

## Hiperparametre Optimizasyonu

En iyi model için hiperparametre optimizasyonu yapıldı. Randomized Search yöntemi kullanılarak en uygun hiperparametreler bulundu.

## Model Değerlendirme

Optimize edilmiş model, test verisi üzerinde değerlendirildi. Doğruluk, kesinlik, duyarlılık, F1-skoru ve karışıklık matrisi gibi metrikler kullanılarak modelin performansı ölçüldü.

## Dosya Yapısı

- `winequality-red.csv`: Kullanılan şarap veri seti.
- `app.ipynb`: Proje için Python kodlarının bulunduğu Jupyter Notebook dosyası.
- `README.md`: Proje hakkında bilgi veren bu dosya.

