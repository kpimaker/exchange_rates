# Учебная библиотека для обновления курсов валют
Используется в образовательных целях, но курс валют возвращает исправно. Данные курсов берутся с сайта cbr-xml-daily.ru.

### Быстрый старт

```python
from exchange_lib import Rate

Rate().usd()
```

Результат
```
66.8497
```

Или в полном варианте:
```python
from exchange_lib import Rate

r = Rate('full')
r.eur()
```

Результат
```
{'CharCode': 'EUR',
 'ID': 'R01239',
 'Name': 'Евро',
 'Nominal': 1,
 'NumCode': '978',
 'Previous': 75.6711,
 'Value': 75.8076}
```