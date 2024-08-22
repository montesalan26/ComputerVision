# Computer Vision Project - Determining a Persons Age by Photo

This project was created using Computer Vision Models to determine a persons age by photos. 

Necessary Libraries to Run this Project:  

import pandas as pd  
from matplotlib import pyplot as plt  
from tensorflow.keras.preprocessing.image import ImageDataGenerator  
import seaborn as sns  
from tensorflow.keras.preprocessing.image import load_img  
import pandas as pd  
import tensorflow as tf  
from tensorflow.keras.applications.resnet import ResNet50  
from tensorflow.keras.models import Sequential  
from tensorflow.keras.layers import GlobalAveragePooling2D, Dense, Dropout, Flatten  
from tensorflow.keras.optimizers import Adam  
from sklearn.metrics import mean_absolute_error  
