 ＃ 我的筆記

## 變數
條件：開頭不能是數字類的，且不能包含運算元

```python
a = 10
print(a)
```

## 運算元
    指派運算元: =
    算數運算元: + - * ** / %
    比較運算元: > < == >= <= !=
    邏輯運算元:and or ^ not

```python
a=10
a=a+5  #a=15
a=a/5  #a=2
```

## Input
• 功能:讓使用者輸入東⻄用的,可以給他字串作為提
```python
print("Today is a good day") #框框內輸入字串(用 ' 、 '' 包起來的就是字串)
```

## Print
• 功能:印出所輸入的字串
```python
print("Today is a good day")
```

## 資料結構
布林值 : True, False

• 數字 | 浮點數 : 20, 0x1d, 0o22, 0b33 | 20.0  #0x0a表示十六進位（簡寫為hex).

• 字串(str), Bytes : "XDD", b"XDDD"  #(用 ' 、 '' 包起來的就是字串). b"XDDD"的b代表Byte 字串

• Tuple : (1,2,3,4,)   # ()通常用來表示一個數列、或一筆相關的資料


• 列 (list) : [1,2,3,4,]  #[]通常用來儲存相關的資料列
    
    1.''.join() 插入前方字串

• 集合 (set) : {1,2,3,4,}  #{}集合內的東⻄不會重複
    
    1.a.add() 加東⻄進去 

    2.a.union({}) 取聯集 
 
    3. a.intersection({})

• 字典 (dict):{1:"貓", 8:"狗"} #能設變數給字串
     
    1.keys() 拿出所有的 key

    2.values() 拿出所有的 value

    3.items() 一組組拿出來

    4.list() []
   
## 條件判斷式
•假如a=b就印出A 等於 B
•如果不等於就判斷
•有沒有大於b
•有就印出A 大於 B
•若還是沒有
•就印出A 小於 B
```python
if a == b :
print("A 等於 B")
elif a > b:
print("A 大於 B")
else :
print("A 小於 B")
```

## 迴圈 (for)(while)
     
     for (自訂變數) in (可以遍歷的東⻄ iter):
            (要幹嘛)
  •重複動作的事
  
     while (條件) :
     
       (要幹嘛)
      
  •for迴圈常用關鍵字 :range(從, 到), enumerate(iter物),len(長度)
  •break=中斷跳出迴圈
  •continue=重新一次

## 函式 (function)

    def 名稱(參數) :
   
       (要幹嘛)
      
    •return 回傳值
      
    •from (函式庫) import (函式、類別、變數) (as (自訂名字))

    •import (函式庫) (as (自訂名字))
    
 ## pwntools
 •作用:用來和遠端程式互動的 python 套件   
      
      from pwn import 
      
      r = process(‘’)可以打開一個本地程序並進行交互

      r = remote(‘地址’,地址 )產生一个遠程的入口

      s = r.recvuntil(‘’)一直讀到什麼出現為止

      r.sendline(‘ ’)發送一行數據








