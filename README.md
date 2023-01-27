# Домашнее задание:

Logistic Regression
Задание
: реализовать свой логистический регрессор, который будет классифицировать отзывы из Amazon. Большая часть работы уже проделана и описана в homework.ipynb, в основном нужно дописать dmia/classifiers/logistic_regression.py.
Цель задания
: на практике познакомиться с numpy и побывать "в шкуре"аналитика, получить навык чтения/понимания number-crunching кода и обращения с численными массивами.
Критерии успеха
: задание
обязательно
, критерием успеха является работающий классификатор, эффективность которого на данном датасете не сильно отличаетсяот того, что есть scikit-learn. Далее успешность определяется code review.

# requirements.txt
## create
pip freeze > requirements.txt
## use
pip install -r requirements.txt

# code style
## isort
python -m pip install isort
### run 
isort .
## mypy
python -m pip install mypy
### run 
mypy .
## flake8
python -m pip install flake8
### run
flake8 --exclude venv,docs --ignore=F401
## code coverage
pip install coverage
### run
coverage run C:\Users\agrusha\AppData\Local\Packages\PythonSoftwareFoundation.Python.3.10_qbz5n2kfra8p0\LocalCache\local-packages\Python310\site-packages\behave\__main__.py
в файле .coveragerc нужно указать исходники
