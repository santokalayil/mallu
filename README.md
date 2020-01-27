# MALLU
---

[![N|Solid](https://www.python.org/static/community_logos/python-powered-w-70x28.png)](https://www.python.org/)
[![License](https://img.shields.io/badge/license-MIT-green.svg?style=flat)](https://github.com/longboardcat/Flask-Portfolio/blob/master/LICENSE)
---
This project is a python module for making machine learning workflow easier than ever before. 

### How to install:
```
$ pip install mallu
```
### Importing Mallu Modules:
```python
 import mallu as ml
 from mallu import santa as san
 from mallu import model as mlm
```
Use the following to run All Machine Learning Classificatin alogorithms at once and see the results
```python
data = mlm.Split(df,target='target_col_name',test_size=0.3,random_state=8)
models = mlm.ClassificationModelDictionary()
mlm.RunAll(models,data)
```
Please follow the following information for using the module for the first time.
- *models* can be a customized dictionary. 
- Try running  - *mlm.ClassificationModelDictionary()* to see the structure of the dictionary
- *data* should be in the form of *X_train, X_train, y_train, y_test*
  - see function docs for more info.


## Coming Features in the next version!

  - New module called 'stats' will be added with Hypothesis Testing Support
  - RunAll function will provide support for regression algorithms as well


You will be able to:
  - Import and save files pickle files directly without running more complicated code
  - run a help function which will guide you through the modules to get more grip on the workflow of Mallu.



### Imports

Mallu internally import uses other machine learning related libraries.

| Libraries | README |
| ------ | ------ |
| sklearn | machine learning |
| lightgbm | LIght Gradient Boosting ML Algorithm |
| xgboost | Xtreme Gradient Boosting ML Alogirthm |
| numpy | Numerical Python for faster execution of the code in multi-dimentional arrays |
| pandas | Library for viewing data in tables and doing Data Analysis |
| scipy.stats | Library often used for Statistics |


### Development

Want to contribute? Great!

Mallu Library is the initial stage. Help us to improve the libary in whatever way you can


### Todos

 - Bug fixes
 - Add documentation

License
----

MIT

---
| Author: Santo K Thomas | santokalayil@gmail.com | +91 8891960880
