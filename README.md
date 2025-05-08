# MNIST_HandWritten-Recongnition
# MNIST 手寫數字辨識 | MNIST Handwritten Digit Recognition

本專案使用 TensorFlow/Keras 建立一個神經網路模型，用於辨識 MNIST 資料集中 0–9 的手寫數字。  
資料集中每張圖片為 28×28 的灰階圖，總共有 70,000 筆數據。

This project uses **TensorFlow/Keras** to build a neural network model for recognizing handwritten digits (0–9)  
from the **MNIST dataset**. Each image in the dataset is a 28×28 grayscale image, and there are a total of 70,000 samples.

---

## 專案結構 | Project Structure

| 檔案 File              | 說明 Description                                 |
|------------------------|--------------------------------------------------|
| `writting_recong.ipynb`| 主要的 Jupyter Notebook，包含完整訓練流程<br>Main notebook with full training pipeline |
| `README.md`            | 本說明文件<br>This documentation file           |
| `mnist_cnn_model.keras`| 已訓練完成的模型<br>Pre-trained model file      |

---

## 功能說明 | Features

- ✅ 匯入與前處理 MNIST 手寫數字資料集  
  Import and preprocess the MNIST handwritten digit dataset  
- ✅ 對圖片進行正規化處理（0~1）  
  Normalize image pixel values to the range [0, 1]  
- ✅ 擴展維度（28×28×1）以符合 CNN 輸入需求  
  Expand image dimensions to (28×28×1) for CNN compatibility  
- ✅ 使用 One-hot encoding 處理標籤  
  Apply one-hot encoding to the labels  
- ✅ 建立 Keras 的 CNN 模型  
  Build a Convolutional Neural Network (CNN) using Keras  
- ✅ 訓練與驗證模型準確率  
  Train the model and validate accuracy on a validation set  
- ✅ 評估測試集效能  
  Evaluate model performance on the test set  
- ✅ 視覺化訓練歷程與預測結果  
  Visualize training history and sample prediction results  
