# Image Retrieval
> Image Retrieval is a task in the field of Information Retrieval, in which our task is to build a program to return images that are related to query image. Some applications of this task is Google Search Image, searching products with images like Shopee, Lazada,... In this project, we will build a image retrieval system by using pre-trained Deep Learning model (CLIP) to extract images' feature and feature vectors. Then, we will use vector database to index, store and retrieve images based on similarity measurements.

## Table of Contents
- [Installation](#installation)
- [Usage](#Usage)

## Installation
1. Clone the repositiory:
```bash
git clone https://github.com/khenm/basic_image_retrieval.git
cd basic_image_retrieval # or folder name storing the git
```
2. Install dependenicies:
If you run this file in Google Colab or Jupiter Notebook, please follow the instructions in the file.
Otherwise, you need to download the library in powershell or integrated terminal (like VSCode).
```bash
pip install chromadb
pip install open_clip_torch
```
> Please remember you have to download Microsoft Visual Tools to build wheels for Chroma Database.

 ## Usage
If you want to briefly grasp the program, run `.ipynb` file in the folder. 
After that, for other test samples, you can change the path to the image to achieve different results.
