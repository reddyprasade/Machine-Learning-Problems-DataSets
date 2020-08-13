
# UCI Machine Learning Repository in CSV

The UCI Machine Learning Repository is a collection of databases, domain theories, and data generators that are used by the machine learning community for the empirical analysis of machine learning algorithms.[UCI Machine Learning](https://archive.ics.uci.edu/ml/index.php)

## Data Set Colletion For UCI

* `Step-1`: Goto this [link](https://archive.ics.uci.edu/ml/datasets.php)
* `Step-2`: Select the Data Sets![](https://lh3.googleusercontent.com/-Qprd_P1bNeE/XkkiUnProdI/AAAAAAAAm2E/YAecsJa4keUvUppwOqC0MXZYga1HJEsmgCK8BGAsYHg/s0/2020-02-16.png)

* `Step-3`: Copy the Data Url ![](https://lh3.googleusercontent.com/-_eSgbi1-jOg/XkkirtydthI/AAAAAAAAm2M/NG5Xupis8nw6-HuynC6-gE6NYfMfZKwzACK8BGAsYHg/s0/2020-02-16.png)
* `Step-4`: Copy the Attribute Information:![](https://lh3.googleusercontent.com/-w6v3O1d_Tww/XkkjJumf7sI/AAAAAAAAm2U/uZI6zSkuMo48TrMO2nbH8_f7wkIcgJFygCK8BGAsYHg/s0/2020-02-16.png)


## Usage

```Python
import numpy as np
import pandas as pd

URL = "https://archive.ics.uci.edu/ml/machine-learning-databases/adult/adult.data"
Col_Names  = ['age','workclass','fnlwgt','education','education-num','marital-status','occupation','relationship','race','sex','capital-loss','hours-per-week','native-country','Income']

Data = pd.read_csv(URL,header=None)
Data.columns = Names
Data
```

## Contributing
If any one Intrested work with Use Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.
---
# References To Learn and Develop your Self:
* [Python](https://github.com/reddyprasade/Python-Basic-For-All-3.x)
* [Data Science With Python ](https://github.com/reddyprasade/Data-Science-With-Python)
* [Machine Learning with Python](https://github.com/reddyprasade/Machine-Learning-with-Scikit-Learn-Python-3.x)
* [Deep learning With python](https://github.com/reddyprasade/Deep-Learning)
* [Data Visulization](https://github.com/reddyprasade/Data-Science-With-Python/tree/master/Data%20Visualization)
* [Life Cycle of Data Science](https://github.com/reddyprasade/Data-Science-With-Python/tree/master/Life%20Cycle%20Process%20of%20Data%20Science%20In%20Real%20World%20project)
* [Statistics](https://github.com/reddyprasade/Data-Science-With-Python/tree/master/Statistics)
---
## License
[MIT](https://choosealicense.com/licenses/mit/)[Copyright (c) 2020 REDDY PRASAD]
