# Machine-Learning-sandbox
Some machine learning notebooks.

## How to use?

* First of all, python3.6 should be installed. 

* Clone the repository:

`git clone https://github.com/yuriimchg/Machine-Learning-sandbox`
 
 
* Create virtual environment and activate it:

`virtualenv -p python3.6 ml`

`source ml/bin/activate`


* Install python3.6 dependencies:

`pip install -r ts_requirements.txt` to work with time series / statsmodels / xgboost 

or

`pip install -r tf_requirements.txt` to work with keras / tensorflow / opencv


* To use Jupyter Notebook inside virtual environment, install the new kernel:

`jupyter kernel install --user --name=ml`
