# Data-Mining-Programming

> Brain MRI edge histograms & HOG · Tweet Count/TF-IDF · PCA(→2D) · Visual separability analysis  

[![Open in Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/code/firstbuildzw/programming-assignment-1-data-preparation-and-und)  

[![Stars](https://img.shields.io/github/stars/z1zw/Data-Mining-Programming?style=flat-square)](https://github.com/z1zw/Data-Mining-Programming/stargazers)
[![Forks](https://img.shields.io/github/forks/z1zw/Data-Mining-Programming?style=flat-square)](https://github.com/z1zw/Data-Mining-Programming/network/members)
[![Issues](https://img.shields.io/github/issues/z1zw/Data-Mining-Programming?style=flat-square)](https://github.com/z1zw/Data-Mining-Programming/issues)
[![License](https://img.shields.io/badge/license-MIT-green.svg?style=flat-square)](LICENSE)

---

## 📖 Overview
- **Images**: RGB → Grayscale → Sobel edges → 36-bin histograms → PCA (36→2D) scatter plots  
- **HOG Features**: Extracted via `skimage.feature.hog`  
- **Tweets**: CountVectorizer / TF-IDF → PCA (2D) visualization  
- **Conclusion**: No perfectly separable clusters, strong overlaps between classes  

---

## 📂 Project Structure
Data-Mining-Programming/
│── data/ # Datasets
│ ├── brain-tumor-mri-dataset/
│ └── student-5/
│── programming-assignment-1-data-preparation-and-und.ipynb # Main Jupyter Notebook
│── requirements.txt
│── LICENSE
│── README.md


---

### 💻 Run Locally
1. Clone the repo:
   ```bash
   git clone https://github.com/z1zw/Data-Mining-Programming.git
   cd Data-Mining-Programming
Install dependencies:

pip install -r requirements.txt
Run the notebook:

jupyter notebook programming-assignment-1-data-preparation-and-und.ipynb
🤝 Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss.

📜 License
This project is licensed under the MIT License - see the LICENSE file for details.
