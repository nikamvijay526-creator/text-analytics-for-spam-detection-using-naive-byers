# text-analytics-for-spam-detection-using-naive-byers
import numpy as np
import pandas as pd
import os
print(os.listdir("../content"))
message = pd.read_csv('/content/spam.csv', encoding='latin-1')
message.head()
