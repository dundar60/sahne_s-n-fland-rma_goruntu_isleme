# sahne_siniflandirma_goruntu_isleme
Kelime çantası yöntemi ile sahne sınıflandırma. 

## Kullanılan yöntemler , teknolojiler , algoritmalar
SIFT öznitelik çıkarma yöntemi
Kelime çantası yöntemi
K-nn sınıflandırması

## Kullanılan kütüphaneler
import os
import cv2
from sklearn.model_selection import train_test_split
from sklearn.neighbors import KNeighborsClassifier
from sklearn.metrics import accuracy_score
import numpy as np
from sklearn.cluster import KMeans
from sklearn.metrics.pairwise import euclidean_distances
from sklearn.preprocessing import normalize
from sklearn.metrics import classification_report, confusion_matrix
import matplotlib.pyplot as plt
import seaborn as sns

## Kurulum / Kullanım
VS Code ile:
Python 3.11 kurulumu ve VS Code ile entegrasyonu
VS Code içerisinden Jupyter extensions kurulumu
Gerekli kütüphanelerin kurulumu 

Jupyter Notebook ile:
Kod Jupyter defteri formatındadır.

## Geliştirenler 
Yusuf Eren DÜNDAR 
GitHub: dundar60
E-mail: dundar6050716@gmail.com

Mustafa Yasef ŞAHİN
GitHub: myasefsahin
E-mail: mustafasahin5529@gmail.com
