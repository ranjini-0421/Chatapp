In[1]:  

       import pandas as pd
       import numpy as np
       import matplotlib.pyplot as plt
       import seaborn as sns

In[2]:

       import pandas as pd

       file_path = '/content/drive/My Drive/Colab Notebooks/GooglePlayStore/apps.csv'

       apps = pd.read_csv(file_path)
       print("Successfully Imported Data!")
       apps.head(5)

Out[2]:
       #              App              Category              Rating              Reviews              Size              Installs              Type              Price              ContentRating

       0        Infinite Painter    ART_AND_DESIGN       

       1

       2
       
       3

       4






