# Marks Validation (Tasks 9–14)

Тапсырма: `marks.csv` файлының `points` бағанын тексеру (0–100, NaN жоқ).

## Технологиялар
- Python 3
- NumPy, Pandas, Matplotlib, Flask

## Орнату
pip install -r requirements.txt

## Іске қосу
python task_09_10.py
python task_11.py
python task_12.py
python task_13.py
python task_14_flask.py

## API тест
curl -X POST -F "file=@marks.csv" http://localhost:5000/validate
