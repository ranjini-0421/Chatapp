In[1]: import pandas as pd
       import numpy as np
       import matplotlib.pyplot as plt
       import seaborn as sns

In[2]: from google.colab import drive
       drive.mount('/content/drive')

       import pandas as pd

       file_path = '/content/drive/My Drive/Colab Notebooks/GooglePlayStore/apps.csv'

       apps = pd.read_csv(file_path)
       print("Successfully Imported Data!")
       apps.head(5)
