# About this repo

Project to visualize steam data
---

soruce: 
``
https://www.kaggle.com/datasets/antonkozyriev/game-recommendations-on-steam?resource=download
``

# Python version
Python 3.11.0

# Running locally and testing

```
virtualenv env
source env/bin/activate
pip3 install -r requirements.txt
```

# Test

```shell
python -m unittest
```


# Check coverage

Make sure you have "coverage" in your requirements.txt file and run pip install. 
Then run `coverage run -m unittest discover` and after that run `coverage report` to get the following table:

```shell

```

# Code beautifier
This code has been beautify using black: https://github.com/psf/black. 
The command to use is `black . -l 120`.