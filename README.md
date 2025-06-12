# 🧠 Derin Öğrenme ile El Yazısı Rakam Tanıma

Bu proje, derin öğrenme (deep learning) teknikleri kullanılarak el yazısı ile yazılmış rakamların sınıflandırılmasını amaçlamaktadır. Projede Convolutional Neural Network (CNN) mimarisi kullanılmış ve TensorFlow/Keras kütüphanesi ile MNIST veri kümesi üzerinde eğitim gerçekleştirilmiştir.

---

## 📁 Proje İçeriği

- `deerinmakale.ipynb` – CNN modeli ile eğitme, test etme ve görselleştirme işlemleri.
- `makaleCalıSması.ipynb` – Alternatif testler ve hiperparametre denemeleri.
- `.docx` dosyaları – Proje raporları ve bilimsel dökümantasyon.

---

## 🧪 Kullanılan Teknolojiler

- Python 3.x  
- TensorFlow & Keras  
- NumPy, Matplotlib  
- Jupyter Notebook  
- Pillow (PIL)

---

## 🗃️ Veri Kümesi

Bu projede **MNIST** (Modified National Institute of Standards and Technology) veri kümesi kullanılmıştır. MNIST, 0 ile 9 arasındaki el yazısı rakamlarını içeren 70.000 adet 28x28 piksellik gri tonlamalı görüntüden oluşur.

- 60.000 eğitim örneği  
- 10.000 test örneği

Veri seti TensorFlow üzerinden doğrudan `tf.keras.datasets.mnist.load_data()` fonksiyonu ile yüklenmektedir.

---

## 🚀 Kurulum ve Çalıştırma

### Gerekli Kütüphaneler
Aşağıdaki komutla tüm bağımlılıkları yükleyebilirsiniz:

```bash
pip install tensorflow matplotlib numpy pillow
Notebook'u çalıştırmak için:
bash
