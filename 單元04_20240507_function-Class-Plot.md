# Function? Class? plot?

> 在寫程式碼時有一個非常重要的觀念是DRY(Don’t Repeat Yourself)，意思是避免同樣的程式碼重複出現在很多個地方，除了可讀性很低外，也不易維護。所以要適當的進行封裝，來達到程式碼的重用性(Reusable)。
> 今天的重點就是要來教大家如何建構自己的 Python函式(Function)，就是能夠讓你的程式碼被重複的使用(Reusable)，並且提高維護性及可讀性!!

## 1. Function, List, For Loop

![image](https://github.com/PhuclamU1114171028/Phuclamu11114171028/assets/162246935/5fd1dd32-8a52-4130-b4a8-78649aa39e72)

## 2. Function with Default Value

![image](https://github.com/PhuclamU1114171028/Phuclamu11114171028/assets/162246935/ad9a59ea-b937-4e6c-afa5-6004cf271258)



## 5. Class? Class類別，就是像一個模組，可以產出具有相似特性的實體(物件) 也有人會說他像是一個蛋糕模子，可以一直套用 生產蛋糕

![image](https://github.com/PhuclamU1114171028/Phuclamu11114171028/assets/162246935/a5ebedbc-02ff-40c7-bede-9643fd2d1d88)


## 6. 如何作圖(plot)?

### a. 計算正弦曲線上點的 x 和 y 座標

![image](https://github.com/PhuclamU1114171028/Phuclamu11114171028/assets/162246935/305efca8-e7a0-4915-ba0e-35590cfef5aa)

### b. 只需一點額外的工作，我們就可以輕鬆地一次繪製多條線，並添加標題、圖例和軸標籤

![image](https://github.com/PhuclamU1114171028/Phuclamu11114171028/assets/162246935/df708360-7630-4564-8cea-f6d9c75dbd6f)

### c. 繪製多子圖，並添加標題、圖例和軸標籤

![image](https://github.com/PhuclamU1114171028/Phuclamu11114171028/assets/162246935/954a855b-c03d-483b-9320-d09c9e697a90)

### d. 繪製2X2子圖，並添加標題、圖例和軸標籤

![image](https://github.com/PhuclamU1114171028/Phuclamu11114171028/assets/162246935/3b15607f-0c53-4f8b-91ca-54fafcc13a06)


## Your Show Time: Challenge 1

![image](https://github.com/PhuclamU1114171028/Phuclamu11114171028/assets/162246935/ebe1c4ea-8c6e-4cde-a70b-b07dc5f61c28)

## Your Show Time: Challenge 2

```python
## ## Challenge 2:
sID = '109065804'
import random

def Sum(x,y):
  print('x+y = ', x+y) # 加法

def Delta(x,y):  
  print('x-y = ', x-y) # 減法

def MM(x,y):  
  print('x*y = ', x*y) # 乘法

def DD(x,y):  
  print('x/y = ', x/y) # 除法

def Calc(ss, xx, yy):
  print('x=%d, y=%d, ss=%d; thus, ' % (xx, yy, ss),end="")

  if ss == 1: # 加法
    Sum(xx,yy)

  elif ss == 2: # 減法
    Delta(xx,yy) 

  elif ss == 3: # 乘法
    MM(xx,yy)

  elif ss == 4: # 除法
    DD(xx,yy)  

  else:
    print('ss = %d, Do nothing!' % ss)

# Main Program
for i in range(1,10):
  xx = random.randint(1, 10) # Generate an integer number the range between 1 and 10
  yy = random.randint(1, 10)

  # Your Program with One Line!

today = datetime.now()
print('*** %s! Done by %s at ' % ('Good Job',sID),today)

```
### Output Result
![image](https://github.com/PhuclamU1114171028/Phuclamu11114171028/assets/162246935/093b1153-374c-465e-8a44-eeb48e353e1a)


## Your Show Time: Challenge 3: 如何用 matplotlib 繪製一個圓？
![image](https://github.com/PhuclamU1114171028/Phuclamu11114171028/assets/162246935/4eef4a34-02c1-4a64-a549-ae2e9661a697)

