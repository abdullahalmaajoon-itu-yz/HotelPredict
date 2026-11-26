# HotelPredict — Otel Rezervasyon Iptal Tahmini (FET445)

Bu depo, Veri Madenciliği (FET445) dersi final projesi kapsamında **Hotel Booking Demand** veri seti üzerinde rezervasyon iptallerini (`is_canceled`) tahmin etmek amacıyla geliştirilen sınıflandırma modellerini içermektedir.

## Ekip Üyeleri ve Görev Dağılımı
* **Abdullah Almaajoon (22040301108):** Veri hazırlığı, sızıntısız ön işleme pipeline yapısı, temel model (Dummy Classifier), Lojistik Regresyon, nihai test değerlendirmesi ve alt grup adalet analizi (`_1.ipynb`).
* **Hamza Alrakad (22040301200):** Keşifsel veri analizi (EDA) ve Karar Ağacı sınıflandırıcısı (`_2.ipynb`).
* **Ragad Alhamdo (23040301131):** k-En Yakın Komşu (k-NN) modellemesi (`_3.ipynb`).

## Veri Seti ve Kurulum
1. Veri setini [Kaggle Hotel Booking Demand](https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand) adresinden indirin ve `hotel_bookings.csv` dosyasını `data/` klasörünün içine yerleştirin.
2. Gerekli Python kütüphanelerini kurun:
   ```bash
   pip install numpy pandas scikit-learn matplotlib seaborn joblib