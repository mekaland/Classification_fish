## Balık Sınıflandırma Projesi

Bu proje, derin öğrenme tekniklerini kullanarak çeşitli balık türlerini sınıflandırmayı amaçlamaktadır. Proje, Keras ve TensorFlow kullanılarak geliştirilmiş bir yapay sinir ağı (YSA) modeline dayanmaktadır.

## Proje Yapısı

- **dataset/**: Balık görüntülerini içeren veri kümesi.
- **notebooks/**: Eğitim süreci ve model değerlendirmesi için kullanılan Jupyter Notebook dosyaları.
- **src/**: Proje kodları.
- **README.md**: Projenin açıklamaları ve kullanım talimatları.

## Kullanılan Teknolojiler

- **Python**: Proje dili.
- **Keras**: Derin öğrenme kütüphanesi.
- **TensorFlow**: YSA modelinin altyapısı.
- **Pandas**: Veri analizi için.
- **NumPy**: Sayısal hesaplamalar için.

## Veri Kümesi

Proje, çeşitli balık türlerini içeren bir veri kümesine dayanmaktadır. Her balık türü için bir etiket bulunmaktadır. Veri kümesi, aşağıdaki balık türlerini içermektedir:

1. Hourse Mackerel
2. Black Sea Sprat
3. Sea Bass
4. Red Mullet
5. Trout
6. Striped Red Mullet
7. Shrimp
8. Gilt-Head Bream
9. Red Sea Bream

## Model Eğitimi

Model, görüntü verilerini kullanarak çeşitli balık türlerini sınıflandırmak için bir yapay sinir ağı ile eğitilmiştir. Eğitim süreci sırasında aşağıdaki adımlar izlenmiştir:

1. Veri ön işleme: Görüntüler boyutlandırılmış ve normalleştirilmiştir.
2. Model mimarisi: Katmanlar ve nöron sayıları belirlenmiştir.
3. Model eğitimi: Eğitim verileri kullanılarak model eğitilmiştir.
4. Model değerlendirmesi: Test verileri kullanılarak modelin doğruluğu ölçülmüştür.

## Kullanım

Projenin çalıştırılması için gerekli kütüphanelerin yüklenmesi gerekmektedir. Aşağıdaki komutu kullanarak gerekli kütüphaneleri yükleyebilirsiniz:

```bash
pip install -r requirements.txt
