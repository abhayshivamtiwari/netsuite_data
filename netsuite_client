import requests
import pandas as pd

url = 'https://www.utires.com/sizes/filters/section/245/aspect/55/rim/18/'

html = requests.get(url).content
df_list =pd.read_html(html)
my_list_len = len(df_list)
for i in range(0, my_list_len):
    print(df_list[i])
