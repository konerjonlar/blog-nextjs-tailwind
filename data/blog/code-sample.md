---
title: Örnek .md dosyası
date: '2021-12-26'
tags: ['markdown', 'kod', 'özellik']
draft: false
summary: Kod blokları ve sözdizimi vurgulamalı bir markdown dosyası örneği
---

Markdown içeren örnek bir gönderi.

## Satır İçi Vurgulama

Satır içi vurgulama örneği `sum = parseInt(num1) + parseInt(num2)`

## Kod bloğu

Örnek javascript kodu

```javascript
var num1, num2, sum
num1 = prompt('Enter first number')
num2 = prompt('Enter second number')
sum = parseInt(num1) + parseInt(num2) // "+" means "add"
alert('Sum = ' + sum) // "+" means combine into a string
```

Örnek Python kodu 🐍

```python
def fib():
    a, b = 0, 1
    while True:            # Döngü başlancı
        yield a            # 0'dan başlayarak a'nın değerini döndürür
        a, b = b, a + b    # a = b ve  b = a +b ile aynı 

for index, fibonacci_number in zip(range(10), fib()):
     print('{i:3}: {f:3}'.format(i=index, f=fibonacci_number))
```
