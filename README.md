# BTP
BTP Geomechaniscs
i have used colab code editor and have uploaded files in form google drive , but to run it on your on colab , u will have to upload the excel files on your drive or , change a bit of code 
from 
# OLD - only works for you
from google.colab import drive
drive.mount('/content/drive')
df_final = pd.read_excel('/content/drive/MyDrive/BTP data final.xlsx')
to import pandas as pd
df_final = pd.read_excel('BTP data final.xlsx')
display(df_final.head())
