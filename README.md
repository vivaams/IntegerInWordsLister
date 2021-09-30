# Integer In Words Lister
#### This module returns numbers to a list of words

## Dependencies
#### To use this module you need to install [humanize](https://pypi.org/project/humanize/) and [python](https://www.python.org/)

## Install

    pip install IntegerInWordsLister

## Usage
```python
inwords_lister = IntegerInWordsLister(222)
print(inwords_lister.calculate())

numbers = [120000000000, 9000870000, 245085002120, 23]
for num in numbers:
    inwords_lister = IntegerInWordsLister(num)
    print(inwords_lister.calculate())
```
## Output
```
['200', 'and', '20', 'and', '2']
['100', 'and', '20', 'milliard']
['9', 'milliard', 'and', '800', 'and', '70', 'thousand']
['200', 'and', '40', 'and', '5', 'milliard', 'and', '80', 'and', '5', 'million', 'and', '2', 'thousand', 'and', '100', 'and', '20']
['20', 'and', '3']
```

## تبدیل اعداد به حروف
##### این ماژول اعداد را به لیستی از کلمات برمی گرداند