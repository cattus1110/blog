title: Markdown 語法
author: cattus1110
author_id: defaultAuthorId
language: zh-TW
tags:
  - Markdown
  - 語法
categories:
  - Markdown 語法
date: 2023-12-15 05:42:00
---
---

### 程式區塊

---

- 行內程式碼：`
- 程式區塊碼：``` + 程式語言

```python
for i in range(10):
    print(i)
```

### 文字字體樣式

---

- **粗體**
```
**粗體**
```
- *斜體*
```
*斜體*
```
- ***粗斜體***
```
***粗斜體***
```
- ==高亮==
```
==高亮==
```
- ~~刪除線~~
```
~~刪除線~~
```
- <u>底線</u>
```
<u>底線</u>
```
- 文字<sup>上標</sup>
```
文字<sup>上標</sup>
```
- 文字<sub>下標</sub>
```
文字<sub>下標</sub>
```
- 文字<mark>高亮</mark>
```
文字<mark>高亮</mark>
```

### 標題

---

- # 一級標題	`#`
- ## 二級標題	`##`
- ### 三級標題	`###`
- #### 四級標題	`####`
- ##### 五級標題	`#####`
- ###### 六級標題	`######`
- 一級、二級標題自動加分隔線

### 引用

---

- >內容	`>內容`
- >>內容	`>>內容`

### 分隔線

---
`---`

`- - - - 或 ***`

### 圖片

---

- ![upload successful](..\images\pasted-0.png)
`![upload successful](..\images\pasted-0.png)`

### 超鏈結

---

- [ 文字 ] ( 鏈結 )
- 自動鏈結：<[https://www.google.com.tw/](https://www.google.com.tw/)>

`自動鏈結：<[https://www.google.com.tw/](https://www.google.com.tw/)>`

### 列表

---

- 無序：- 文字
- 有序：數字. 文字

### 表格

---

- Markdown 表格的基本組成是 標題列 和 分隔列，可以沒有資料列。
- 表格的欄位數以標題列的欄位數為基準
    - 欄位以 | 劃分，外側的垂直分隔符號可以不寫。
    - 分隔列每欄至少要有三個 - 號，左邊右邊插入 : 號指定對齊方式。

```
Age           | Time  | Food | Gold | Requirement
|---|---|---|---|---|
Feudal Age    | 02:10 |  500 |    0 | Dark Age building x 2
Castle Age    | 02:40 |  800 |  200 | Feudal Age building x 2
Imperial Age  | 03:30 | 1000 |  800 | Castle Age building x 2
```

### 目錄

---

- 產生目錄：[TOC]

### 公式

---

$$ f(x,y,z) = 3y^2z \left( 3+\frac{7x+5}{1+y^2} \right) $$