
# Sakarya'da Emlak Fiyat Tahmini ve Konut Kompleksi Sınıflandırması

Bu proje, veri madenciliği ve makine öğrenimi teknikleri kullanarak Sakarya, Türkiye'deki emlak ilanlarından elde edilen veriler ile hem fiyat tahmini (regresyon) hem de konut kompleksine ait olup olmadığını tespit etme (ikili sınıflandırma) amaçlamaktadır.

## Proje Özeti

- **Amaç:**  
  - Sakarya’daki emlak fiyatlarını tahmin etmek (regresyon).
  - Mülkün konut kompleksi içinde olup olmadığını belirlemek (ikili sınıflandırma).
- **Veri Kaynağı:**  
  - HepsiEmlak platformundan toplanan ve 1000’den fazla ilan içeren veri seti (alan, yaş, konum gibi özelliklerle).

## Kullanılan Yöntemler ve Modeller

- **Veri Ön İşleme:**  
  - Eksik değerlerin doldurulması  
  - Kategorik değişkenlerin kodlanması  
  - Sayısal özelliklerin ölçeklendirilmesi
- **Algoritmalar:**  
  - SVM  
  - Lineer Regresyon  
  - KNN  
  - Lojistik Regresyon  
  - Random Forest  
  - XGBoost  
  - LightGBM
- **Model Optimizasyonu:**  
  - Recursive Feature Elimination (RFE) ile öznitelik seçimi  
  - Optuna ile hiperparametre optimizasyonu

## Temel Bulgular

- **Fiyat Tahmini:** LightGBM algoritması en iyi performansı göstermiştir.  
- **Konut Kompleksi Sınıflandırması:** XGBoost modeli en yüksek başarıyı sağlamıştır.
- **Not:** Veri setinin yalnızca Sakarya bölgesine ait olması ve dış veri eksikliği, modelin genellenebilirliğini sınırlamıştır.

## Kullanılan Teknolojiler

- Python
- scikit-learn
- XGBoost
- LightGBM
- Optuna
- pandas
- NumPy
- Matplotlib
- Seaborn

## Proje Klasör Yapısı

```
├── data/         # Veri seti (boyut nedeniyle yüklenmedi; veri edinme talimatları içerir)
├── Notebooks/    # Jupyter notebook'ları (analiz ve modelleme)
├── scripts/      # Veri işleme ve modelleme betikleri
├── reports/      # Proje raporu ve sunumlar
└── README.md     # Proje tanıtımı, kurulum ve kullanım kılavuzu
```

## Kurulum ve Kullanım

1. **Gereksinimler:**  
   Gerekli Python paketlerini yüklemek için aşağıdaki komutu çalıştırın:
   ```bash
   pip install -r requirements.txt
   ```
2. **Veri Seti:**  
   `data/` klasöründeki talimatlara göre veri setini temin edin.
3. **Analiz ve Modelleme:**  
   `Notebooks/` klasöründe bulunan Jupyter notebook'larını kullanarak analiz ve modelleme adımlarını inceleyebilirsiniz.

## Katkı Sağlama

Katkıda bulunmak isterseniz, lütfen bir fork oluşturup pull request gönderin veya issue açın.

## Lisans

Bu proje MIT lisansı ile lisanslanmıştır.

---

İsterseniz bu metni doğrudan README.md dosyanıza ekleyebilirsiniz. Eklemek veya çıkarmak istediğiniz özel bir bölüm varsa bana iletebilirsiniz!
