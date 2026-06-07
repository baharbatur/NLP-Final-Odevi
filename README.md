# Proje Açıklaması
## Doğal Dil İşleme - Word2Vec ile Metin Benzerliği Analizi

Bu proje, Türkçe metinler üzerinde ön işleme adımlarının uygulanması ve ardından Word2Vec (CBOW ve Skip-gram) mimarileri kullanılarak metin benzerliklerinin analiz edilmesi amacıyla hazırlanmıştır.

## Proje İçeriği
- `2302131018baharbaturd.ipynb`: Eğitim, benzerlik hesaplamaları ve görselleştirme işlemlerini içeren Jupyter Notebook dosyası.
- `stemmed.csv`: Stemming (gövdeleme) uygulanmış temizlenmiş veri seti.
- `lemmatized.csv`: Lemmatization (lemalaştırma) uygulanmış temizlenmiş veri seti.
- `models/`: Eğitilmiş 16 farklı Word2Vec modelini içeren klasör.

## Çalıştırma Talimatları
Projeyi yerel bilgisayarınızda çalıştırmak için aşağıdaki adımları izleyin:

1. Gerekli kütüphaneleri yükleyin:
   ```bash
   pip install gensim pandas scikit-learn seaborn matplotlib
   #Repoyu bilgisayarınıza klonlayın veya indirin.

Jupyter Notebook dosyasını (2302131018baharbaturd.ipynb) herhangi bir IDE (VS Code, JupyterLab vb.) ile açın.

Hücreleri sırasıyla çalıştırın. (Modeller models/ klasöründen otomatik olarak yüklenecektir.)

Proje Hakkında
Öğrenci: Bahar Batur

Ders: Doğal Dil İşleme
# model dosyası boyut nedeniyle yüklenememiştir




Yöntem: Cümle vektörlerinin ortalaması alınarak Cosine Similarity ile benzerlik hesaplanmıştır. Modeller arasındaki tutarlılık Jaccard Benzerlik Matrisi ile analiz edilmiştir




