# Dataset Setup for Image Captioning Project

### 1. Download Dataset
Download the Flickr8k dataset from [Kaggle](https://www.kaggle.com/datasets/adityajn105/flickr8k).

### 2. Extract Files
After downloading, extract the zip file in your Google Drive:

The folder should contain:
- `Images/` — all image files (JPEG)
- `captions/` — containing `Flickr8k.token.txt`

### 3. Verify
In Colab, you can verify using:
```python
!ls /content/drive/MyDrive/DeepLearningProject/archive(5)/Images | head
