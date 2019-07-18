# Python Numbers

Python的數字型態有三種

* int(整數)
* float(浮點數)
* complex(複數)

在python中檢查任意物件的型態可用type()

## int

包含所有無小數點的正數負數，無長度限制

```py
x = 1
y = 35656222554887711
z = -3255522
```

## float

包含所有含小數點、科學記號(e或E)的正數負數

```py
x = 1.10
y = 1.0
z = -35.59
a = 35e3
b = 12E4
c = -87.7e100
```

## complex

python中可以使用j來表示複數的虛部

```py
x = 3+5j
y = 5j
z = -5j
```

## 轉型

```py
x = 1 # int
y = 2.8 # float
z = 1j # complex

#convert from int to float:
a = float(x)

#convert from float to int:
b = int(y)

#convert from int to complex:
c = complex(x)
```

## 亂數

```py
import random

print(random.randrange(1,10)) # 產生1~9亂數
```