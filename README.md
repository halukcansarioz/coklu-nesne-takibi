# 🎯 Multi-Object Tracking (Çoklu Nesne Takibi)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/halukcansarioz/coklu-nesne-takibi/blob/main/Derin_%C3%96%C4%9Frenme_ve_Yapay_Sinir_A%C4%9Flar%C4%B1.ipynb)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python](https://img.shields.io/badge/python-3.8%2B-blue)](https://www.python.org/)
[![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat&logo=opencv&logoColor=white)](#)
[![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)](#)

This project is a Computer Vision application developed to detect, assign identities to, and track multiple objects in video streams in real time.

## 📚 Table of Contents
- [About the Project](#about-the-project)
- [Features](#features)
- [Technologies & Methods Used](#technologies--methods-used)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [Contact](#contact)
- [License](#license)

---

## About the Project
This work was created to provide solutions to object tracking problems. The project basically includes the following steps:

1. **Object Detection:** Determining the locations of objects (people, vehicles, etc.) in each frame.
2. **Object Tracking:** Associating the detected objects between frames and assigning them unique IDs.

This project can serve as a foundation particularly in areas such as security systems, autonomous driving, and traffic analysis.

- **Developer:** Haluk Can SARIÖZ
- **Type:** Computer Vision / Deep Learning Application
- **Platform:** Google Colab / Jupyter Notebook

---

## Features
- **Multi-Object Tracking:** Simultaneously track multiple objects in a video stream.
- **Unique ID Assignment:** Assign a persistent identity to each object for consistency across frames.
- **Real-Time Processing:** Low latency thanks to optimized algorithms.
- **Google Colab Support:** Runnable notebook directly in the browser.
- **GPU Acceleration:** Fast model inference with CUDA-enabled PyTorch.

---

## Technologies & Methods Used
The following libraries and algorithms are used in the project:

| Category | Technology |
|----------|------------|
| **Language** | Python |
| **Image Processing** | OpenCV |
| **Deep Learning** | PyTorch, TorchVision |
| **Detection Algorithm** | YOLO (You Only Look Once) |
| **Tracking Algorithm** | SORT / DeepSORT |
| **Helper Libraries** | NumPy, Matplotlib, FilterPy, Scikit-learn |
| **Environment** | Jupyter Notebook / Google Colab |

---

## Installation
Follow the steps below to run the project on your local machine:

### 1. Clone the repository:
```bash
git clone https://github.com/halukcansarioz/coklu-nesne-takibi.git
cd coklu-nesne-takibi
```

### 2. Install the required libraries:
```bash
pip install -r requirements
```
*(Note: If you want to use GPU support, make sure you install the CUDA versions of PyTorch.)*

### 3. Launch the notebook:
```bash
jupyter notebook "Derin_Öğrenme_ve_Yapay_Sinir_Ağları.ipynb"
```
or click the **"Open In Colab"** badge above to open directly in Google Colab.

---

## Usage
You can see the object detection and tracking processes step by step by running the notebook cells in order. To change the video source, update the file path in the relevant cell:

```python
# For webcam
source = 0

# For a video file
source = "data/sample_video.mp4"
```

---

## Project Structure
```text
coklu-nesne-takibi/
├── Derin_Öğrenme_ve_Yapay_Sinir_Ağları.ipynb   # Main notebook (Colab compatible)
├── requirements                                  # Python dependencies
└── README.md                                     # Project documentation
```

---

## Contributing
Contributions, bug reports, and feature requests are welcome!

1. **Fork** this repository.
2. Create a **Branch** (`git checkout -b feature/NewFeature`).
3. Make your changes and **Commit** (`git commit -m 'Add: New feature'`).
4. **Push** your code (`git push origin feature/NewFeature`).
5. Open a **Pull Request**.

---

<a name="contact"></a>
## Contact
**Haluk Can Sarıöz**

- GitHub: [@halukcansarioz](https://github.com/halukcansarioz)
- Email: [halukcansarioz19@gmail.com](mailto:halukcansarioz19@gmail.com)
- LinkedIn: [Haluk Can Sarıöz](https://www.linkedin.com/in/halukcansarioz)

---

*If you found this project helpful, don't forget to ⭐ it!*

---

## License
This project is licensed under the [MIT License](LICENSE).
