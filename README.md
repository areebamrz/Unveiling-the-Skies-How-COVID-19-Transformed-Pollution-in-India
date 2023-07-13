# Unveiling-the-Skies-How-COVID-19-Transformed-Pollution-in-India
An analysis of the COVID-19's Lockdown effect on the Pollution level in India

# Import the necessary libraries
import numpy as np
import pandas as pd
import os

# Visualisation libraries
import matplotlib.pyplot as plt
%matplotlib inline
import seaborn as sns
sns.set()

# Hide the output of pip install for pycountry
!pip install pycountry > /dev/null

import pycountry
import plotly.express as px
from plotly.offline import init_notebook_mode, iplot
import plotly.graph_objs as go
import plotly.offline as py
from plotly.offline import download_plotlyjs, init_notebook_mode, plot, iplot

# Hide the output of pip install for plotly and chart_studio
!pip install plotly > /dev/null
!pip install chart_studio > /dev/null


import chart_studio.plotly as py
import cufflinks
cufflinks.go_offline()
cufflinks.set_config_file(world_readable=True, theme='pearl')

# Geographical Plotting
import folium
from folium import Choropleth, Circle, Marker
from folium import plugins
from folium.plugins import HeatMap, MarkerCluster

# Racing Bar Chart
!pip install bar_chart_race > /dev/null
import bar_chart_race as bcr

# Increase the default plot size and set the color scheme
plt.rcParams['figure.figsize'] = 8, 5
plt.style.use("fivethirtyeight")  # for pretty graphs

# Disable warnings
import warnings
warnings.filterwarnings('ignore')

