# Medical Image Segmentation using U-Net

This project demonstrates binary image segmentation using the U-Net architecture, widely used in medical imaging tasks like tumor detection, organ localization, etc.
---------
-----------
-----
## 📦 Data

- For simplicity, synthetic grayscale images with binary masks are used.
- In real-world cases, use datasets like:
  - [Kaggle Lung Segmentation](https://www.kaggle.com/kmader/finding-lungs-in-ct-data)
  - [ISIC Skin Lesion Segmentation](https://www.isic-archive.com)

-----------------------------

##  Model: U-Net

- Encoder-decoder structure
- Skip connections for fine-grained localization
- Final activation: `sigmoid` for binary mask

--------------

## ⚙️ Requirements

```bash
pip install tensorflow numpy matplotlib scikit-learn
