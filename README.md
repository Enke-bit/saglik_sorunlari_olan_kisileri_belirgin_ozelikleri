# Sağlık Verileri ile Model Tahmini

Bu proje, sağlık verilerini kullanarak bir makine öğrenmesi modelini eğitmek ve Tkinter ile kullanıcıdan veri alarak tahmin yapmak amacıyla geliştirilmiştir. Projede kullanılan veri seti, hastaların yaş, cinsiyet, kan grubu, tıbbi durum, ilaç kullanımı gibi bilgilerini içerir ve hedef değişken olarak test sonuçları kullanılmıştır.

## Özellikler

- **Model Eğitimi**: Veriler kullanılarak bir sinir ağı (neural network) modeli eğitilmiştir.
- **Tkinter Arayüzü**: Kullanıcıdan sağlık verilerini alarak model tahmini yapmanızı sağlar.
- **Veri Görselleştirme**: Model tahminleri ve gerçek sonuçları görselleştirir.

## Kurulum

1. **Gerekli Kütüphaneler**: Projeyi çalıştırmak için gerekli Python kütüphanelerini yükleyin.

    ```bash
    pip install numpy pandas scikit-learn tensorflow keras matplotlib joblib
    ```

2. **Model ve LabelEncoder'ları Yükleyin**: Model ve `LabelEncoder` nesnelerini yüklemek için uygun dosya yollarını belirtin.

## Kullanım

1. **Tkinter Arayüzünü Başlatma**: `main.py` dosyasını çalıştırarak Tkinter arayüzünü başlatın.

    ```bash
    python main.py
    ```

2. **Veri Girişi**: Arayüzdeki giriş kutularına yaş, cinsiyet, kan grubu, tıbbi durum ve ilaç bilgilerini girin.

3. **Tahmin Yapma**: "Tahmin Yap" butonuna tıklayarak model tahmini alın.

4. **Sonuç Görselleştirme**: Model tahminini ve gerçek sonucu grafikte görselleştirin.

## Dosya Yapısı

- `main.py`: Tkinter arayüzü ve model tahmin fonksiyonlarını içerir.
- `model.h5`: Eğitimli model dosyası.
- `label_encoder_age.pkl`, `label_encoder_gender.pkl`, `label_encoder_blood_type.pkl`, `label_encoder_medical_condition.pkl`, `label_encoder_medication.pkl`, `label_encoder_test_results.pkl`: Eğitim sırasında kullanılan `LabelEncoder` nesneleri.

## Lisans

Bu proje MIT Lisansı altında lisanslanmıştır. Daha fazla bilgi için `LICENSE` dosyasına bakabilirsiniz.

## İletişim

Herhangi bir sorunuz veya geri bildiriminiz varsa, [ibrahimpuskullu44@gmail.com] adresi üzerinden iletişime geçebilirsiniz.
