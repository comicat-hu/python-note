# Python String

## 單行字串

在python中，字串可以用單引號`''`或雙引號`""`括住來表示。

```py
s = 'Hello'
print('Hello')
print("Hello")
```

## 多行字串

使用三對單引號或三對雙引號括助表示。

```py
str1 = '''This is
mutiple
string'''

str2 = """This is 
mutiple string
too"""
```

## 字串處理

python的字串如同其他程式語言一樣是一個個位元組(bytes)的字元所組成的陣列，在python3.x中，字串預設是utf-8編碼。

### 取得任意位置的字元

```py
s = "Hello World!"
print(s[1]) # "e"
```

### 子字串(substring)

```py
s = "Hello World!"
print(s[2:6]) # "llo W"
```

### 頭尾去空白

```py
s = " Hello World! "
print(s.strip()) # "Hello World!"
```

### 字串長度

```py
s = "Hello!"
print(len(s)) # 6
```

### 英文轉大小寫

```py
s = "Hello World!"
print(s.upper()) # "HELLO WORLD!"
print(s.lower()) # "hello world!"
```

### 字串取代

```py
s = "Hello World!"
print(a.replace("l", "o")) # "Heooo Worod!"
```

### 字串分割

```py
s = "Hello, World!"
print(s.split(",")) # ["Hello", " World!"]
```

## 字串格式化

python無法將字串跟數字直接組合，必須使用format()函示來達成。

在字串中使用`{}`佔位符，呼叫format()會將其中的參數帶入格式化。

### one parameter

```py
age = 25
print("I am {} years old.".format(age)) # "I am 25 years old."
```

### mutiple parameters

```py
print("{} + {} = 5".format(2, 3)) # "2 + 3 = 5"
```

### assign parameters index

指定foramt的index順序，從0開始。

```py
quantity = 3
itemno = 567
price = 49.95
print("I want to pay {2} dollars for {0} pieces of item {1}.".format(quantity, itemno, price))
# "I want to pay 49.95 dollars for 3 pieces of item 567."
```
