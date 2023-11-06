# Python Depth-aware Style Transfer

[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](https://github.com/Nekhocheninov/Style-Transfer/blob/main/LICENSE.md)
![GitHub last commit](https://img.shields.io/github/last-commit/Nekhocheninov/Style-Transfer)
[![Open in Colab](https://img.shields.io/badge/Open%20in%20Colab-Open-blue?logo=google-colab)](https://colab.research.google.com/drive/1ecgyZ1TxaoFOsFLXJMPd4UGqMcyq3ZXJ?usp=sharing)

Depth-aware [neural style transfer](https://en.wikipedia.org/wiki/Neural_style_transfer) algorithm in Python.

## Running the notebook

The code was written in Python across Jupyter notebooks. It was developed in Google Colab which is a free Jupyter notebook environment that allows you to run code through a browser.

Follow [this link](https://colab.research.google.com/drive/1ecgyZ1TxaoFOsFLXJMPd4UGqMcyq3ZXJ?usp=sharing) to open the notepad with this code and click on Google Colaboratory.

## Samples

Input images, depth-aware style transfer and style transfer, respectively:
<img src="https://github.com/Nekhocheninov/StyleTransfer/blob/main/img/img_1.png" width="800">

Input images, depth-aware style transfer and style transfer, respectively:
<img src="https://github.com/Nekhocheninov/StyleTransfer/blob/main/img/img_2.png" width="800">
  
### Analysis

Input images:

<img src="https://github.com/Nekhocheninov/StyleTransfer/blob/main/img/img_3.png" width="500">

Result of the algorithm with parameters α = 1000, 𝛽 = 0.01 (α, 𝛽 ∈ R - weighting coefficients for content and style reconstruction,
respectively):

for 100 and 250 iterations:

<img src="https://github.com/Nekhocheninov/StyleTransfer/blob/main/img/img_4.png" width="500">

for 500 and 1000 iterations:

<img src="https://github.com/Nekhocheninov/StyleTransfer/blob/main/img/img_5.png" width="500">

for 5000 and 10000 iterations:

<img src="https://github.com/Nekhocheninov/StyleTransfer/blob/main/img/img_6.png" width="500">

The value of the loss function at some iterations:

| i | L | i | L | i | L |
|---|:--|---|:--|---|:--|
|1| 227951260|501| 10906696|9996| 7032089,5|
|2| 180691700|502| 10896347|9997| 7031814|
|3| 148849890|503| 10886492|9998| 7032557,5|
|4| 122218376|504| 10877209|9999| 7033357|
|5| 103735630|505| 10867916|10000| 7030789,5|

<img src="https://github.com/Nekhocheninov/StyleTransfer/blob/main/img/img_11.png" width="500">

---

Input images:

<img src="https://github.com/Nekhocheninov/StyleTransfer/blob/main/img/img_7.png" width="500">

Result of the algorithm for 1000 iterations:

for 𝛼/𝛽 = 1 and 𝛼/𝛽 = 10:

<img src="https://github.com/Nekhocheninov/StyleTransfer/blob/main/img/img_8.png" width="500">

for 𝛼/𝛽 = 100 and 𝛼/𝛽 = 1000:

<img src="https://github.com/Nekhocheninov/StyleTransfer/blob/main/img/img_9.png" width="500">

for 𝛼/𝛽 = 10000 and 𝛼/𝛽 = 100000:

<img src="https://github.com/Nekhocheninov/StyleTransfer/blob/main/img/img_10.png" width="500">
