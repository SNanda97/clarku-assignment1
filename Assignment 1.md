# TESLA STOCK HISTORY
Link: https://www.kaggle.com/ammaraahmad/tesla-stocks-history

Description:This Dataset Contain data about Opening value, Closing value, Lowest value, Highest value, Adj closing value and Volume of Tesla stocks from its inception to Aug-2021.

# CYBER CRIMES STATE WISE - INDIA
Link: https://www.kaggle.com/amritvirsinghx/cyber-crime-statewise

Description:This dataset contains information about state-wise cybercrime in India and can be used to predict future crime rates. Some interesting insights can be generated by predicting the crimes in 2020 and how pandemic has effected the increasing cybercrimes.

# COVID-19 PATIENTS SYMPTOMS DATASET
Link:https://www.kaggle.com/takbiralam/covid19-symptoms-dataset

Description:Covid-19 positive and negative cases patient's symptoms dataset collected from a nearby hospital.

# ZOMATO RESTAURANTS IN DELHI NCR - INDIA

Link : https://www.kaggle.com/aestheteaman01/zomato-restaurants-in-delhi-ncr

Description : The dataset contains information on 1965 restaurants in Delhi NCR as listed on Zomato. The list of restaurants covers the entire NCR Region, last updated on August 30th 2021.


# GOOGLE PLAY STORE

Link : https://www.kaggle.com/lava18/google-play-store-apps

Description : The Play Store apps data has enormous potential to drive app-making businesses to success. Actionable insights can be drawn for developers to work on and capture the Android market!


```python

```


```python
import pandas as pd
```


```python
df = pd.read_csv(r'TSLA.CSV')
```
print(df)

```python
df
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Date</th>
      <th>Open</th>
      <th>High</th>
      <th>Low</th>
      <th>Close</th>
      <th>Adj Close</th>
      <th>Volume</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>2010-06-29</td>
      <td>3.800000</td>
      <td>5.000000</td>
      <td>3.508000</td>
      <td>4.778000</td>
      <td>4.778000</td>
      <td>93831500</td>
    </tr>
    <tr>
      <th>1</th>
      <td>2010-06-30</td>
      <td>5.158000</td>
      <td>6.084000</td>
      <td>4.660000</td>
      <td>4.766000</td>
      <td>4.766000</td>
      <td>85935500</td>
    </tr>
    <tr>
      <th>2</th>
      <td>2010-07-01</td>
      <td>5.000000</td>
      <td>5.184000</td>
      <td>4.054000</td>
      <td>4.392000</td>
      <td>4.392000</td>
      <td>41094000</td>
    </tr>
    <tr>
      <th>3</th>
      <td>2010-07-02</td>
      <td>4.600000</td>
      <td>4.620000</td>
      <td>3.742000</td>
      <td>3.840000</td>
      <td>3.840000</td>
      <td>25699000</td>
    </tr>
    <tr>
      <th>4</th>
      <td>2010-07-06</td>
      <td>4.000000</td>
      <td>4.000000</td>
      <td>3.166000</td>
      <td>3.222000</td>
      <td>3.222000</td>
      <td>34334500</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>2808</th>
      <td>2021-08-24</td>
      <td>710.679993</td>
      <td>715.219971</td>
      <td>702.640015</td>
      <td>708.489990</td>
      <td>708.489990</td>
      <td>13083100</td>
    </tr>
    <tr>
      <th>2809</th>
      <td>2021-08-25</td>
      <td>707.030029</td>
      <td>716.969971</td>
      <td>704.000000</td>
      <td>711.200012</td>
      <td>711.200012</td>
      <td>12645600</td>
    </tr>
    <tr>
      <th>2810</th>
      <td>2021-08-26</td>
      <td>708.309998</td>
      <td>715.400024</td>
      <td>697.619995</td>
      <td>701.159973</td>
      <td>701.159973</td>
      <td>13214300</td>
    </tr>
    <tr>
      <th>2811</th>
      <td>2021-08-27</td>
      <td>705.000000</td>
      <td>715.000000</td>
      <td>702.099976</td>
      <td>711.919983</td>
      <td>711.919983</td>
      <td>13762100</td>
    </tr>
    <tr>
      <th>2812</th>
      <td>2021-08-30</td>
      <td>714.719971</td>
      <td>731.000000</td>
      <td>712.729980</td>
      <td>730.909973</td>
      <td>730.909973</td>
      <td>18502400</td>
    </tr>
  </tbody>
</table>
<p>2813 rows × 7 columns</p>
</div>




```python

```
