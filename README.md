# fish_classification
# Proje Açıklaması

Bu proje, çeşitli balık türlerini içeren bir veri seti üzerinde derin öğrenme teknikleri kullanarak sınıflandırma modelinin geliştirilmesini kapsamaktadır. Projede, yapay sinir ağı (ANN) mimarisi kullanılarak bir model geliştirilmiş ve bu modelin performansı değerlendirilmiştir.

# Veri Önişleme
Veri seti, klasörlerin içinde yer alan .png formatında fotoğraflardan oluşmaktadır. Bu nedenle, pd.read_csv ile veri yüklenememektedir.

Veri önişleme aşamasında:

Görüntülerin yolları ve etiketleri bir Pandas DataFrame içine yerleştirildi.

Görüntü verileri yeniden boyutlandırıldı ve normalize edildi.

Görselleştirme işlemleri matplotlib kütüphanesi kullanılarak yapıldı.

# Kullanılan Kütüphaneler:
Pandas

Numpy

Matplotlib

TensorFlow

Scikit-learn

# Modelin Eğitilmesi

Veri seti, eğitim ve test olarak ayrıldıktan sonra ANN mimarisi kullanılarak bir model oluşturuldu. Modelde:

Katmanlar: Giriş katmanı, yoğun katmanlar ve dropout katmanları kullanıldı.

Aktivasyon fonksiyonları: relu ve softmax fonksiyonları tercih edildi.

Dropout oranı ve diğer hiperparametreler, overfitting’i önlemek ve model performansını artırmak için optimize edildi.

# Modelin Değerlendirilmesi

Modelin başarısını değerlendirmek için:

Doğruluk (accuracy) ve kayıp (loss) fonksiyonlarının iterasyonlar arası grafikleri çizildi.

Confusion matrix ve classification report kullanılarak detaylı analizler yapıldı.

# Hiperparametre Optimizasyonu
En iyi performansı elde etmek için aşağıdaki hiperparametreler üzerinde optimizasyon yapıldı:

Katman sayısı

Düğüm sayısı

Dropout oranı

Optimizer (optimizasyon algoritması)

# Kaggle’daki Notebook Linki
https://www.kaggle.com/code/defnesudekoc/fish-classification-project
