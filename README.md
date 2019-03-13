# Salinity-Data

#For this project, I compared the salinity data from World Ocean Atlas 2013 and 2018. The data I used for this project was from https://www.nodc.noaa.gov/OC5/woa18/woa18data.html and https://www.nodc.noaa.gov/OC5/woa13/woa13data.html. The 



import numpy as np
%matplotlib inline
data = np.genfromtxt('woa13_decav_s13mn01v2.csv')
print(data.shape)
import pandas as pd
import matplotlib.pyplot as plt
df = pd.read_csv('woa13_decav_s13mn01v2.csv')
plt = df.plot(y=0)
plt.set_xlabel('Time')
plt.set_ylabel('Salinity')
data = np.genfromtxt('woa13_decav_s14mn01v2.csv')
print(data.shape)
import pandas as pd
import matplotlib.pyplot as plt
df = pd.read_csv('woa13_decav_s14mn01v2.csv')
plt = df.plot(y=0)
plt.set_xlabel('Time')
plt.set_ylabel('Salinity')
data = np.genfromtxt('woa13_decav_s15mn01v2.csv')
print(data.shape)
import pandas as pd
import matplotlib.pyplot as plt
df = pd.read_csv('woa13_decav_s15mn01v2.csv')
plt = df.plot(y=0)
plt.set_xlabel('Time')
plt.set_ylabel('Salinity')
data = np.genfromtxt('woa13_decav_s16mn01v2.csv')
print(data.shape)
import pandas as pd
import matplotlib.pyplot as plt
df = pd.read_csv('woa13_decav_s16mn01v2.csv')
plt = df.plot(y=0)
plt.set_xlabel('Time')
plt.set_ylabel('Salinity')
