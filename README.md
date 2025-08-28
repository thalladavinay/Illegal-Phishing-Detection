# Illegal-Phishing-Detection
## How to Run?
Create a virtual environment
```bash
python -m venv zenv
source zenv/Scripts/activate # Windows
source zenv/bin/activate # Mac
```


- Install basic requirements
```bash
pip install -r requirements.txt

# OR INITIAL INSTALLATION 
pip install --upgrade pip
pip install --upgrade setuptools

pip install pandas whois httpx
pip install pycaret # It will take sometime.
### To Run

```bash
python main.py


# OUTPUT: {'prediction_label': 0, 'prediction_score': 68.39} 

# 0 = False | 1 True
```

---

### To Run GUI

```bash
pip install flask

python app.py
```
