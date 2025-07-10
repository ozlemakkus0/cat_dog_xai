# cat_dog_xai
Grad-CAM ile kedi/köpek görsellerinde sınıflandırma ve görselleştirme
# 🐶 Grad-CAM ile Görsel Sınıflandırma (Kedi/Köpek)

Bu proje, VGG16 modeli kullanılarak eğitilmiş bir görüntü sınıflandırma modelinin kararlarını **Grad-CAM (Gradient-weighted Class Activation Mapping)** yöntemiyle açıklamayı hedefler.

## 📂 İçerik

- `cat_dog_xai.ipynb`: Jupyter Notebook dosyası. Modelin tahminleri ve Grad-CAM görselleştirmesi burada yapılır.
- `dog.jpeg`: Örnek görsel. Kedi veya köpek resmi kullanabilirsin.

## 🔧 Kullanılan Teknolojiler

- Python
- TensorFlow / Keras
- OpenCV
- Matplotlib
- VGG16 (ImageNet ile eğitilmiş)

## 🚀 Çalıştırmak için

Google Colab'da çalıştırabilirsiniz:

1. `cat_dog_xai.ipynb` dosyasını açın
2. `dog.jpeg` dosyasını aynı dizine yükleyin
3. Tüm hücreleri sırasıyla çalıştırın

## 🔍 Grad-CAM Nedir?

Grad-CAM, bir sinir ağının karar verirken görselin hangi bölgelerine odaklandığını gösteren ısı haritası üretir. Bu sayede modelin karar süreci daha anlaşılır hale gelir.

---


