title: CSS 基礎教程
author: cattus1110
author_id: defaultAuthorId
language: zh-TW
tags:
  - css
  - 基礎教程
categories:
  - css 課程
date: 2023-12-15 05:24:00
---
CSS（Cascading Style Sheets）是一種用於設計和排版網頁的樣式表語言。本教程將向您介紹 CSS 的基礎知識，包括選擇器、屬性和樣式規則。

## 1. CSS 基礎

### 引入 CSS

在 HTML 中引入 CSS 的方式有兩種：

#### 內部樣式表

```html
<head>
    <style>
        /* CSS 樣式規則 */
        h1 {
            color: blue;
        }
    </style>
</head>
```

#### 外部樣式表

將 CSS 規則存儲在獨立的 .css 文件中，然後在 HTML 中引入：

```html
<head>
    <link rel="stylesheet" type="text/css" href="styles.css">
</head>
```

## 2. 選擇器

### 標籤選擇器

```css
p {
    color: red;
}
```

### 類別選擇器

```css
.my-class {
    font-size: 16px;
}

<p class="my-class">這是一個段落。</p>
```

### ID 選擇器

```css
#my-id {
    background-color: yellow;
}

<div id="my-id">這是一個區塊元素。</div>
```

### 階層選擇器

```css
ul li {
    list-style-type: square;
}
```

### 後代選擇器

```css
.parent-class p {
    font-weight: bold;
}
```

## 3. CSS 屬性

### 文本樣式

- `color`：文字顏色。
- `font-size`：字體大小。
- `font-family`：字體類型。
- `font-weight`：字體粗細。
- `text-decoration`：文字裝飾（如下劃線）。

### 背景樣式

- `background-color`：背景顏色。
- `background-image`：背景圖像。
- `background-size`：背景圖像大小。

### 盒模型

- `width`：寬度。
- `height`：高度。
- `margin`：外邊距。
- `padding`：內邊距。
- `border`：邊框。
- `border-radius`：邊框圓角。

### 定位

- `position`：元素定位方式。
- `top`、`right`、`bottom`、`left`：位置屬性。
- `float`：浮動元素。

### 顯示和可見性

- `display`：元素的顯示方式。
- `visibility`：元素的可見性。

## 4. CSS 盒模型

CSS 盒模型定義了每個 HTML 元素的空間，包括內容、內邊距、邊框和外邊距。

![盒模型](https://www.csssolid.com/images/box-model/css-box-model.png)

## 5. CSS 佈局

### 定位和浮動

- `position: static`：元素的默認定位方式。
- `position: relative`：相對定位。
- `position: absolute`：絕對定位。
- `position: fixed`：固定定位。
- `float: left`：左浮動。
- `float: right`：右浮動。

### 彈性盒模型

```css
.container {
    display: flex;
    justify-content: center;
}
```

## 6. 媒體查詢

使用媒體查詢可以根據不同設備的螢幕大小和特性應用不同的 CSS 樣式。

```css
@media screen and (max-width: 768px) {
    /* 在小螢幕上應用的樣式 */
}
```

## 7. CSS 顏色

CSS 支援多種顏色表示方式，包括名稱、十六進制值和 RGB 值。

- `color: red;`
- `color: #00FF00;`
- `color: rgb(255, 0, 0);`

## 8. CSS 偽類和偽元素

偽類和偽元素用於選擇元素的特定狀態或位置。

- `:hover`：滑鼠懸停時應用的樣式。
- `:first-child`：第一個子元素。
- `::before`：在元素前插入內容。

## 9. CSS 動畫

使用 CSS 動畫可以創建元素的過渡和動畫效果。

```css
@keyframes slide {
    from {
        left: 0;
    }
    to {
        left: 100px;
    }
}

.slide {
    animation: slide 2s linear infinite;
}
```

## 10. CSS 預處理器

CSS 預處理器（如 SASS 和 LESS）可以增強 CSS 的功能，包括變數、嵌套規則和函數。

## 11. CSS 框架

CSS 框架（如 Bootstrap）提供了現成的樣式和元件，以簡化網頁設計和開發。
