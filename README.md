# Transfotmer-Speaker-Classification

# 專案概述
此 Jupyter Notebook 是台灣大學 (NTU) 2021 年春季機器學習課程家庭作業 4 (HW4) 的實作。任務聚焦於使用基於 Transformer 的模型進行說話者分類，特別利用自注意力機制從預處理的音頻特徵 (梅爾頻譜圖) 中分類說話者。目標是學習並應用 Transformer 架構，包括基本自注意力、參數調整，以及進階變體如 Conformer。Notebook 包含資料載入、模型定義、訓練、評估及推論腳本。透過微調 Transformer 參數並整合訓練期間的資料分割技術，在驗證集上達到高準確率。

# 使用方式
在 Jupyter 或 Colab 中開啟 Notebook，設定資料路徑 (例如 data_dir = "./Dataset")。
依序執行單元：
* 載入資料及映射。
* 定義模型 (例如使用 TransformerEncoder 的 Classifier)。
* 訓練：使用 CrossEntropyLoss 及 AdamW 優化器。
* 在驗證集評估。
  
# 結果
驗證集準確率：0.9742
最佳模型於步驟 70000 儲存，準確率=0.8995。

# Project Overview
This Jupyter Notebook (hw04ab4f0f13df.ipynb) is an implementation for the Machine Learning Homework 4 (HW4) from National Taiwan University (NTU) 2021 Spring course. The task focuses on speaker classification using Transformer-based models, specifically leveraging self-attention mechanisms to classify speakers from preprocessed audio features (mel-spectrograms). The goal is to learn and apply Transformer architectures, including basic self-attention, parameter tuning, and advanced variants like Conformer.
The notebook includes data loading, model definition, training, evaluation, and inference scripts. It achieves high accuracy on the validation set by fine-tuning Transformer parameters and incorporating techniques such as data segmentation during training.

# Usage
Open the notebook in Jupyter or Colab.Set paths for data (e.g., data_dir = "./Dataset").
Run cells sequentially:
* Load data and mappings.
* Define the model (e.g., Classifier with TransformerEncoder).
* Train: Use CrossEntropyLoss and AdamW optimizer.

# Results
Validation Set Accuracy: 0.9742.
Best model saved at step 70000 with accuracy=0.8995.
* Evaluate on validation set.

#Results
