## Setup Environment

1) Create python virtual environment
	python -m venv env_shap

2) Activate your virtual environment
	env_shap\Scripts\activate -- Windows
	
	source env_shap/bin/activate -- Ubuntu

3) Install all the packages in your virtual environment
	pip install -r requirements.txt

4) Create kernel
	python -m ipykernel install --user --name shap --display-name shap-kernel

5) Launch Jupyter notebook
	jupyter lab

6) Connect jupyter to kernel shap-kernel


## Videos
You can find out more details in the below youtube videos

1) **Partial dependency plot**: How feature impact model prediction?
https://youtu.be/BgUMI8_oSRI

2) **SHAP Dependency Plot** : How feature interaction impact model prediction?
https://youtu.be/eDoKwho03vk

3) **How does SHAP model interpretation work?**
https://youtu.be/mp4xYRUq9-U

4) **How SHAP global feature importance is different from XGBOOST Feature importance?**
https://youtu.be/kFEOQlepXPo

5) **Why does the model think that a given customer will churn? What explanation SHAP can provide to the end-user?**
https://youtu.be/UAFEVtIw4h4
