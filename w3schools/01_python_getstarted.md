# Python Getting Started

## 確認python版本

`python --version` 或 `python -V`

```bash
Python 3.6.4
```

## 執行python腳本

python為直譯式程式語言，不須經過預編譯，直接建立檔案腳本副檔名為`.py`，輸出"Hello World!"。

```bash
echo 'print("Hello World!")' > hello.py
python hello.py
```

## command line mode(interactive mode)

指令輸入`python`進入python command line mode

```bash
Python 3.6.4 (v3.6.4:d48eceb, Dec 19 2017, 06:54:40) [MSC v.1900 64 bit (AMD64)] on win32
Type "help", "copyright", "credits" or "license" for more information.
>>>
```

在最後一行輸入的程式連按兩次Enter，不輸入任何指令，會將剛剛輸入的程式執行出結果。

`exit()`離開python command line mode

```bash
>>> if 5 > 2:
...     print("5 is greater than 2")
...
5 is greater than 2
>>> exit()
```