# Çoklu Nesne Takibi (Multi-Object Tracking)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/halukcansarioz/coklu-nesne-takibi/blob/main/main.ipynb)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python](https://img.shields.io/badge/python-3.8%2B-blue)](https://www.python.org/)

Bu proje, video akışları üzerindeki birden fazla nesneyi gerçek zamanlı olarak algılamak, kimlik atamak ve takip etmek için geliştirilmiş bir Bilgisayarla Görme (Computer Vision) uygulamasıdır. 

## 🎯 Proje Hakkında

Bu çalışma, nesne takibi (Object Tracking) problemlerine çözüm üretmek amacıyla hazırlanmıştır. Proje temel olarak şu adımları içerir:
1.  **Nesne Tespiti (Detection):** Her karedeki nesnelerin (insan, araç vb.) konumlarının belirlenmesi.
2.  **Nesne Takibi (Tracking):** Tespit edilen nesnelerin kareler arasında ilişkilendirilmesi ve benzersiz ID atanması.

## 🛠️ Kullanılan Teknolojiler

* **Dil:** Python
* **Görüntü İşleme:** OpenCV
* **Derin Öğrenme:** PyTorch / TensorFlow
* **Model:** YOLO (You Only Look Once)
* **Takip Algoritması:** DeepSORT / SORT

## 🚀 Kurulum

Projeyi yerel makinenizde çalıştırmak için terminalde şu komutları çalıştırın:

```bash
# 1. Repoyu klonlayın
git clone [https://github.com/halukcansarioz/coklu-nesne-takibi.git](https://github.com/halukcansarioz/coklu-nesne-takibi.git)
cd coklu-nesne-takibi

