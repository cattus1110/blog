title: HTML 基礎教程
author: cattus1110
author_id: defaultAuthorId
language: zh-TW
tags:
  - html
  - 基礎教程
categories:
  - html 課程
date: 2023-12-15 05:05:00
---
HTML（Hypertext Markup Language）是一個用於創建網頁內容的標記語言。本教程將向您介紹 HTML 的基礎知識，包括常用的 HTML 標籤和屬性。

## 1. HTML 文件結構

一個基本的 HTML 文件由以下幾個部分組成：
```html
<!DOCTYPE html> <!-- 声明文档类型 -->
<html> <!-- 根元素 -->
<head> <!-- 頁面頭部資訊，包括標題、引用的樣式和腳本檔案 -->
    <meta charset="UTF-8"> <!-- 設置字符編碼 -->
    <title>頁面標題</title> <!-- 設置頁面標題 -->
</head>
<body> <!-- 頁面內容 -->
    <h1>這是一個標題</h1> <!-- 標題 -->
    <p>這是一個段落。</p> <!-- 段落 -->
    <a href="https://www.example.com">這是一個連結</a> <!-- 連結 -->
    <img src="image.jpg" alt="圖片描述"> <!-- 圖像 -->
    <ul> <!-- 無序列表 -->
        <li>項目 1</li>
        <li>項目 2</li>
    </ul>
    <ol> <!-- 有序列表 -->
        <li>項目 1</li>
        <li>項目 2</li>
    </ol>
</body>
</html>
```

## 2. 基本標籤

### 標題標籤

- `<h1>` 到 `<h6>`：定義標題的級別，`<h1>` 是最高級別。

### 段落標籤

- `<p>`：定義段落。

### 超連結標籤

- `<a href="URL">連結文字</a>`：創建連結。

### 圖像標籤

- `<img src="image.jpg" alt="圖片描述">`：插入圖像。

### 列表標籤

- `<ul>`：無序列表。
- `<ol>`：有序列表。
- `<li>`：列表項目。

## 3. 文本格式化

### 粗體和斜體

- `<b>`：粗體文字。
- `<i>`：斜體文字。

### 底線和刪除線

- `<u>`：底線文字。
- `<del>`：刪除線文字。

### 換行和水平線

- `<br>`：換行。
- `<hr>`：水平線。

## 4. 表格

- `<table>`：創建表格。
- `<tr>`：定義表格行。
- `<th>`：定義表頭單元格。
- `<td>`：定義數據單元格。

## 5. 表單

- `<form>`：創建表單。
- `<input type="text">`：文本輸入字段。
- `<input type="password">`：密碼輸入字段。
- `<input type="checkbox">`：複選框。
- `<input type="radio">`：單選按鈕。
- `<input type="submit">`：提交按鈕。

## 6. 嵌入多媒體

- `<audio src="audio.mp3">`：嵌入音頻。
- `<video src="video.mp4">`：嵌入視頻。
- `<iframe src="https://www.example.com">`：嵌入外部網頁。

## 7. 註釋

- `<!-- 這是註釋 -->`：在 HTML 中添加註釋。

## 8. HTML 屬性

- 屬性通常包含在標籤內，用於提供有關元素的附加信息，如 `href`、`src`、`alt` 等。