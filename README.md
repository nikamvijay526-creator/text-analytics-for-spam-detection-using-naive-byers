# text-analytics-for-spam-detection-using-naive-byers
import numpy as np
import pandas as pd
import os
print(os.listdir("../content"))
message = pd.read_csv('/content/spam.csv', encoding='latin-1')
message.head()
for message_no,message in enumerate(message[:10]):
    print(message_no,message)
    print('\n')
import pandas as pd
import pandas as pd
message = pd.read_csv('/content/spam.csv', encoding='latin-1')
message = message.iloc[:, [0, 1]]
message.columns = ['labels', 'message']
message.head()
message.describe()
message.groupby('labels').describe()
message['length']=message['message'].apply(len)
message.head()
import matplotlib.pyplot as plt
import seaborn as sns
%matplotlib inline
message['length'].plot(bins=50,kind='hist')
message.length.describe()
message[message['length']==910]['message'].iloc[0]

