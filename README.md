# Çoklu Nesne Takibi (Multi-Object Tracking)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/halukcansarioz/coklu-nesne-takibi/blob/main/main.ipynb)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python](https://img.shields.io/badge/python-3.8%2B-blue)](https://www.python.org/)

Bu proje, video akışları üzerindeki birden fazla nesneyi gerçek zamanlı olarak algılamak, kimlik atamak ve takip etmek için geliştirilmiş bir Bilgisayarla Görme (Computer Vision) uygulamasıdır. 

## 🎯 Proje Hakkında

Bu çalışma, nesne takibi (Object Tracking) problemlerine çözüm üretmek amacıyla hazırlanmıştır. Proje temel olarak şu adımları içerir:
1.  **Nesne Tespiti (Detection):** Her karedeki nesnelerin (insan, araç vb.) konumlarının belirlenmesi.
2.  **Nesne Takibi (Tracking):** Tespit edilen nesnelerin kareler arasında ilişkilendirilmesi ve benzersiz ID atanması.

Bu proje özellikle güvenlik sistemleri, otonom sürüş ve trafik analizi gibi alanlarda temel oluşturabilecek bir yapıdadır.

## 🛠️ Kullanılan Teknolojiler ve Yöntemler

Projede aşağıdaki kütüphaneler ve algoritmalar kullanılmıştır:

* **Dil:** Python
* **Görüntü İşleme:** OpenCV
* **Derin Öğrenme:** [Örn: PyTorch / TensorFlow]
* **Tespit Algoritması:** [Örn: YOLOv8 / YOLOv5 / SSD]
* **Takip Algoritması:** [Örn: DeepSORT / ByteTrack / SORT]

## 🚀 Kurulum

Projeyi yerel makinenizde çalıştırmak için aşağıdaki adımları izleyin:

1.  **Repoyu klonlayın:**
    ```bash
    git clone [https://github.com/halukcansarioz/coklu-nesne-takibi.git](https://github.com/halukcansarioz/coklu-nesne-takibi.git)
    cd coklu-nesne-takibi
    ```

2.  **Gerekli kütüphaneleri yükleyin:**
    ```bash
    pip install -r requirements.txt
    ```
    *(Not: Eğer GPU desteği kullanacaksanız, PyTorch/TensorFlow'un CUDA versiyonlarını yüklediğinizden emin olun.)*

## 💻 Kullanım

Projeyi bir video dosyası veya web kamerası üzerinde çalıştırmak için:

```bash
# Web kamerası için
python main.py --source 0

# Video dosyası için
python main.py --source data/ornek_video.mp4
