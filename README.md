
# 🎯 Çoklu Nesne Takibi (Multi-Object Tracking)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/halukcansarioz/coklu-nesne-takibi/blob/main/Derin_%C3%96%C4%9Frenme_ve_Yapay_Sinir_A%C4%9Flar%C4%B1.ipynb)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python](https://img.shields.io/badge/python-3.8%2B-blue)](https://www.python.org/)
[![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat&logo=opencv&logoColor=white)](#)
[![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)](#)

Bu proje, video akışları üzerindeki birden fazla nesneyi gerçek zamanlı olarak algılamak, kimlik atamak ve takip etmek için geliştirilmiş bir Bilgisayarla Görme (Computer Vision) uygulamasıdır.

## 📚 İçindekiler
- [Proje Hakkında](#proje-hakkında)
- [Özellikler](#özellikler)
- [Kullanılan Teknolojiler ve Yöntemler](#kullanılan-teknolojiler-ve-yöntemler)
- [Kurulum](#kurulum)
- [Kullanım](#kullanım)
- [Proje Yapısı](#proje-yapısı)
- [Katkıda Bulunma](#katkıda-bulunma)
- [İletişim](#iletisim)
- [Lisans](#lisans)

---

## Proje Hakkında
Bu çalışma, nesne takibi (Object Tracking) problemlerine çözüm üretmek amacıyla hazırlanmıştır. Proje temel olarak şu adımları içerir:

1. **Nesne Tespiti (Detection):** Her karedeki nesnelerin (insan, araç vb.) konumlarının belirlenmesi.
2. **Nesne Takibi (Tracking):** Tespit edilen nesnelerin kareler arasında ilişkilendirilmesi ve benzersiz ID atanması.

Bu proje özellikle güvenlik sistemleri, otonom sürüş ve trafik analizi gibi alanlarda temel oluşturabilecek bir yapıdadır.

* **Geliştirici:** Haluk Can SARIÖZ
* **Tür:** Bilgisayarla Görme / Derin Öğrenme Uygulaması
* **Platform:** Google Colab / Jupyter Notebook

---

## Özellikler
* **Çoklu Nesne Takibi:** Video akışında birden fazla nesneyi eş zamanlı izleme.
* **Benzersiz ID Atama:** Her nesneye kalıcı kimlik atayarak kareler arası tutarlılık.
* **Gerçek Zamanlı İşleme:** Optimize edilmiş algoritmalar ile düşük gecikme.
* **Google Colab Desteği:** Doğrudan tarayıcı üzerinden çalıştırılabilir notebook.
* **GPU Hızlandırma:** CUDA destekli PyTorch ile hızlı model çıkarımı.

---

## Kullanılan Teknolojiler ve Yöntemler
Projede aşağıdaki kütüphaneler ve algoritmalar kullanılmıştır:

| Kategori | Teknoloji |
|----------|-----------|
| **Dil** | Python |
| **Görüntü İşleme** | OpenCV |
| **Derin Öğrenme** | PyTorch, TorchVision |
| **Tespit Algoritması** | YOLO (You Only Look Once) |
| **Takip Algoritması** | SORT / DeepSORT |
| **Yardımcı Kütüphaneler** | NumPy, Matplotlib, FilterPy, Scikit-learn |
| **Ortam** | Jupyter Notebook / Google Colab |

---

## Kurulum
Projeyi yerel makinenizde çalıştırmak için aşağıdaki adımları izleyin:

### 1. Repoyu klonlayın:
```bash
git clone https://github.com/halukcansarioz/coklu-nesne-takibi.git
cd coklu-nesne-takibi
```

### 2. Gerekli kütüphaneleri yükleyin:
```bash
pip install -r requirements
```

*(Not: Eğer GPU desteği kullanacaksanız, PyTorch'un CUDA versiyonlarını yüklediğinizden emin olun.)*

### 3. Notebook'u başlatın:
```bash
jupyter notebook "Derin_Öğrenme_ve_Yapay_Sinir_Ağları.ipynb"
```

veya doğrudan **Google Colab** üzerinde açmak için yukarıdaki "Open In Colab" rozetine tıklayın.

---

## Kullanım
Notebook hücrelerini sırasıyla çalıştırarak nesne tespiti ve takibi işlemlerini adım adım görebilirsiniz. Video kaynağını değiştirmek için ilgili hücredeki dosya yolunu güncelleyin:

```python
# Web kamerası için
source = 0

# Video dosyası için
source = "data/ornek_video.mp4"
```

---

## Proje Yapısı
```text
coklu-nesne-takibi/
├── Derin_Öğrenme_ve_Yapay_Sinir_Ağları.ipynb   # Ana notebook (Colab uyumlu)
├── requirements                                  # Python bağımlılıkları
└── README.md                                     # Proje dökümantasyonu
```

---

## Katkıda Bulunma
Katkılarınız, hata bildirimleriniz ve özellik istekleriniz memnuniyetle karşılanır!

1. Bu depoyu **Fork**'layın.
2. Bir **Branch** oluşturun (`git checkout -b feature/YeniOzellik`).
3. Değişikliklerinizi **Commit** edin (`git commit -m 'Ekleme: Yeni özellik'`).
4. Kodlarınızı **Push**'layın (`git push origin feature/YeniOzellik`).
5. Bir **Pull Request** açın.

---

<a name="iletisim"></a>
## İletişim
**Haluk Can Sarıöz**

- GitHub: [@halukcansarioz](https://github.com/halukcansarioz)
- E-posta: [halukcansarioz19@gmail.com](mailto:halukcansarioz19@gmail.com)
- LinkedIn: [Haluk Can Sarıöz](https://www.linkedin.com/in/halukcansarioz)

---

*Bu projeyi faydalı bulduysanız ⭐ vermeyi unutmayın!*

---

## Lisans
Bu proje [MIT Lisansı](LICENSE) ile lisanslanmıştır.
