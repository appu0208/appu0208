import pandas as pd
import matplotlib.pyplot as plt
In [2]:
dataset = pd.read_csv("Node1.csv")
In [3]:
dataset.head(5)
Out[3]:
consume	distance(km)	speed(km/hr)	temp_inside	temp_outside	weight
0	5.0	28.0	26.0	21.5	12.0	3504.0
1	4.2	12.0	30.0	21.5	13.0	3693.0
2	5.5	11.2	38.0	21.5	15.0	3436.0
3	3.9	12.9	36.0	21.5	14.0	3433.0
4	4.5	18.5	46.0	21.5	15.0	3449.0
In [4]:
plt.scatter(dataset.iloc[0:10,0],dataset.iloc[0:10,2])
Out[4]:
<matplotlib.collections.PathCollection at 0x109f2206748>
