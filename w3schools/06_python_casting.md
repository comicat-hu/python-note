# Python Casting

Python是一種物件導向(object-orientated)的語言，使用class來定義資料型態，包含原始型態(primitive types)亦是。

以下建構函數可提供資料型態轉換：

## int()

可接受整數、浮點數、字串型態的整數，非上述型態的輸入會拋出ValueError，浮點數會無條件捨去至整數位。

## float()

可接受整數、浮點數、字串型態的整數、字串型態的浮點數，非上述型態的輸入會拋出ValueError，整數會自動補.0。

## str()

接受任何資料形態輸入，轉成字串。