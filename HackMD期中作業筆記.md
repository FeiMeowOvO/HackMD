# HackMD期中作業筆記
---
**HackMD**筆記以Markdown語法為基礎，追求簡潔的線上協作筆記。創始者是由北科大資工系吳承翰於研究所作業時所啟發並開發，其中==MD指的是採用**MarkDown**語法撰寫==。

個人平常慣用的筆記、記事等的程式是**Google的*Keep***，起初我喜歡它的特點為不用儲存、可以電腦和手機使用、方便快速的簡單記錄。但在上了網際網路實務後了解到了與其性質類似，但能製作更加美觀漂亮多風格的筆記*HackMD*。

### 程式介紹 :bulb: 
<font color=FFB01C> Keep
![](https://i.imgur.com/ZGvzXXZ.png)
    一款簡單好用好上手的簡易記事程式。
<font color=0>
我簡單列出兩者之間的特點：
##### Keep
:::warning
- 可雲端儲存
- 簡易記事
    - 如便利貼般
- 電腦、手機均可使用
    - 只要有google帳號即可使用
    - 兩者之間連接轉換方便
        - 手機安裝App使用會更加方便
- 能設立標籤及根據便利貼樣式找到所需
:::
##### HackMD
:::info
1. 可雲端儲存
2. 能製作更加豐富詳細的筆記
    1. 如顏色的設置 
    2. 粗體斜體等文字的設計
    3. 能記錄程式碼
3. 同樣電腦手機均可使用
    1. 只要有網路皆可使用
    2. 且儲存速度較快
:::
---
### 課堂作業
以下為我在該課學習中製作之課堂作業。
- [我的第一個HackMD筆記](https://hackmd.io/@MeowOvO/BJ8GtkD-q)
- [網際網路實務筆記](https://hackmd.io/@MeowOvO/ryGSWXez9)
- [色塊強調](https://hackmd.io/@MeowOvO/BJM6J4lz9)
- [程式碼](https://hackmd.io/@MeowOvO/rJFhCajX5)
---
### 程式比較表格

| 兩者比較     | Keep | HaclMD |
|:------------ |:----:|:------:|
| 雲端儲存     |  V   |   V    |
| 文字設定     |      |   V    |
| 序列清單     |      |   V    |
| 核取方塊     |  V   |        |
| 背景樣式設定 |  V   |        |
| 程式碼       |      |   V    |
| 圖片         |  V   |   V    |
| 提醒功能     |  V   |        |
| 繪圖功能     |  V   |        |
| 表情符號     |  V   |   V    |
| 標籤         |  V   |   V    |

### 程式碼
    
```python=
>>> sum(i*i for i in range(10))                 # sum of squares
285

>>> xvec = [10, 20, 30]
>>> yvec = [7, 5, 3]
>>> sum(x*y for x,y in zip(xvec, yvec))         # dot product
260

>>> unique_words = set(word for line in page  for word in line.split())

>>> valedictorian = max((student.gpa, student.name) for student in graduates)

>>> data = 'golf'
>>> list(data[i] for i in range(len(data)-1, -1, -1))
['f', 'l', 'o', 'g']
```

---
最後分享近期很喜歡的歌 :heart: 
{%youtube SkQ9ipjcdYM%}
謝謝老師 :woman-bowing: 