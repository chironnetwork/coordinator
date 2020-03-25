# coordinator
Blockchain based decentralized coordinator for The Chiron Network

## 1. Installation
1. Python Dependencies ```pip3 install -r requirements.txt```
2. Gunicorn ```apt install gunicorn3```

## 2. Running the code
```
sudo gunicorn3 app:app --workers 3 --bind 0.0.0.0:80 --log-file app.log --access-logfile access.log --log-level DEBUG &
```

## 3. Code Linting
```
pylint --rcfile=pylintrc app.py
```
