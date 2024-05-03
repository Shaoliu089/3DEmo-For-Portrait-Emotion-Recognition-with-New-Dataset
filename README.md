# 3DEmo-For-Portrait-Emotion-Recognition-with-New-Dataset

The 3DEmo dataset is a portrait facial emotion dataset proposed by the article [3DEmo: For Portrait Emotion Recognition with New Dataset](https://dl.acm.org/doi/abs/10.1145/3631133).

You could download the dataset using [Google Drive](https://drive.google.com/file/d/18dqJO5ABaPjSWItE1CoHx5AWb1Yf8tYD/view?usp=sharing).


File structure:
```python
Total/
    xxx.jpg # the face images
    ...
    final_label.csv # the annotation file

```

All images are croped from portrait paintings collected from [WikiArt](https://www.wikiart.org/en/terms-of-use).

## Annotation

In file `final_label.csv`, the first column indicates the categorical emotion label. The meaning of the values are: 
```python
0: neutral
1: happy
2: sad
3: surprise
4: fear
5: disgust
6: anger
7: contempt
```
The column 2, 3, 4 indicates the Dominance, Valence and Arousal value of the face emotion. The values range from -1 to 1. More details about how we got the values can be found in [3DEmo: For Portrait Emotion Recognition with New Dataset](https://dl.acm.org/doi/abs/10.1145/3631133).

The last column is the file name of the face image.

## Citation
If you find the dataset useful, please consider citing

```latex
@article{10.1145/3631133,
author = {Liu, Shao and Agaian, Sos S.},
title = {3DEmo: For Portrait Emotion Recognition with New Dataset},
year = {2024},
issue_date = {June 2024},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
volume = {17},
number = {2},
issn = {1556-4673},
url = {https://doi.org/10.1145/3631133},
doi = {10.1145/3631133},
journal = {J. Comput. Cult. Herit.},
month = {feb},
articleno = {17},
numpages = {26}
}
```
