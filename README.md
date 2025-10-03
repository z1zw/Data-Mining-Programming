# Data-Mining-Programming

> Brain MRI edge histograms & HOG · Tweet Count/TF-IDF · PCA(→2D) · Visual separability analysis

[![Stars](https://img.shields.io/github/stars/z1zw/Data-Mining-Programming?style=flat-square)](https://github.com/z1zw/Data-Mining-Programming/stargazers)
[![Forks](https://img.shields.io/github/forks/z1zw/Data-Mining-Programming?style=flat-square)](https://github.com/z1zw/Data-Mining-Programming/network/members)
[![Issues](https://img.shields.io/github/issues/z1zw/Data-Mining-Programming?style=flat-square)](https://github.com/z1zw/Data-Mining-Programming/issues)
[![License](https://img.shields.io/badge/license-MIT-green.svg?style=flat-square)](LICENSE)

## 📖 Overview
- **Images**: RGB→Grayscale → Sobel edges → 36-bin histograms → PCA(36→2D)
- **HOG Features**: Extracted via `skimage.feature.hog`
- **Tweets**: CountVectorizer / TF-IDF → PCA(2D) visualization
- **Conclusion**: No perfectly separable clusters, strong overlaps between classes.

## 🚀 Usage
```bash
pip install -r requirements.txt
python src/your_script.py

