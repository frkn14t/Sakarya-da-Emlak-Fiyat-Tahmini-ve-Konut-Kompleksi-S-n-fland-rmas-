# Sakarya-da-Emlak-Fiyat-Tahmini-ve-Konut-Kompleksi-Siniflandirmasi

Bu proje, veri madenciliği teknikleri kullanılarak Sakarya, Türkiye'deki emlak verilerini analiz etmeyi amaçlar. Hedef, emlak fiyatlarını tahmin etmek ve bir mülkün konut kompleksi içinde olup olmadığını sınıflandırmaktır.

Proje Özeti

Amaç: Sakarya'daki emlak fiyatlarını tahmin etmek (regresyon) ve mülklerin konut kompleksi içinde olup olmadığını belirlemek (ikili sınıflandırma).
Veri Kaynağı: HepsiEmlak platformundan toplanan, 1000'den fazla emlak ilanını içeren veri seti (alan, yaş, konum gibi özelliklerle).

Yöntemler:
Eksik değerlerin doldurulması, kategorik kodlama ve sayısal ölçeklendirme gibi kapsamlı veri ön işleme adımları.
Kullanılan algoritmalar: SVM, Lineer Regresyon, KNN, Lojistik Regresyon, XGBoost, Random Forest.
Recursive Feature Elimination (RFE) ve Optuna ile hiperparametre optimizasyonu.

Temel Bulgular:
Fiyat tahmini için LightGBM en iyi performansı gösterdi.
Konut kompleksi sınıflandırmasında XGBoost üstün sonuçlar verdi.
Veri setinin tek bölgeye odaklanması ve dış veri eksikliği sınırlılıklar yarattı.

Kullanılan Teknolojiler: Python, scikit-learn, XGBoost, LightGBM, Optuna, pandas, NumPy, Matplotlib, Seaborn.

Depo Yapısı
data/: Veri seti (boyut nedeniyle yüklenmedi; talimatlar mevcut).
Notebooks/: Veri analizi ve modelleme için Jupyter notebook'ları.
scripts/: Veri işleme ve modelleme betikleri.
reports/: Proje raporu ve sunumlar.
README.md: Kurulum ve kullanım kılavuzu.
Kodları ve bulguları keşfederek emlak verilerinden nasıl içgörüler elde edildiğini görün!
