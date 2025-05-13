# manga-colorization-project

# Manga Colorization Project

A deep learning project to automatically colorize black-and-white manga using the Manga Colorization Dataset and U-Net + GAN (pix2pix) architecture.

## Team Members
- 謝嵐蓁
- 許乃懿
- 陳禹潔

## Dataset
[Manga Colorization Dataset - Hugging Face](https://huggingface.co/datasets/MichaelP84/manga-colorization-dataset)

## Features
- Convert grayscale manga to color automatically
- Trainable on Google Colab
- Easy-to-use web interface with Gradio

## Folder Structure
manga-colorization-project/
├── notebooks/
│   ├── 1_data_preprocessing.ipynb
│   ├── 2_model_training.ipynb
│   ├── 3_gradio_demo.ipynb
├── src/
│   ├── dataset.py          ← 自定義 Dataset 處理
│   ├── model.py            ← 定義 U-Net / pix2pix 架構
│   ├── train.py            ← 訓練流程
│   ├── infer.py            ← 預測函數
├── gradio_app/
│   └── interface.py        ← Gradio 主程式
├── requirements.txt
├── README.md
├── .gitignore
└── LICENSE
