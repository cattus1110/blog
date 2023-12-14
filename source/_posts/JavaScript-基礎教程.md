title: JavaScript 基礎教程
author: cattus1110
author_id: defaultAuthorId
language: zh-TW
tags:
  - JavaScript
  - 基礎教程
categories:
  - JavaScript 課程
date: 2023-12-15 05:26:00
---
JavaScript 是一種用於構建互動式網頁和應用程序的腳本語言。本教程將向您介紹 JavaScript 的基礎知識，包括變數、數據類型、運算符、控制流和函數。

## 1. JavaScript 基礎

### 引入 JavaScript

在 HTML 中引入 JavaScript 的方式有兩種：

#### 內部腳本

```html
<script>
    // JavaScript 代碼
    alert("Hello, World!");
</script>
```

#### 外部腳本

將 JavaScript 代碼存儲在一個獨立的 .js 文件中，然後在 HTML 中引入：

```html
<script src="script.js"></script>
```

## 2. 變數和數據類型

### 變數

JavaScript 使用 `var`、`let` 和 `const` 声明變數：

```javascript
var name = "John";
let age = 30;
const PI = 3.14;
```

### 數據類型

JavaScript 包括多種數據類型：

- 字符串：`"Hello"`
- 數字：`42`
- 布林值：`true` 或 `false`
- 數組：`[1, 2, 3]`
- 對象：`{ name: "John", age: 30 }`
- 函數：`function sayHello() { /* 代碼 */ }`

## 3. 運算符

JavaScript 包括各種運算符，如加法、減法、乘法、除法、賦值、比較等。

```javascript
let x = 10;
let y = 5;
let sum = x + y; // 加法
let difference = x - y; // 減法
let product = x * y; // 乘法
let quotient = x / y; // 除法
let isGreaterThan = x > y; // 比較
```

## 4. 控制流

### 條件語句

JavaScript 使用 `if`、`else if` 和 `else` 來執行不同的代碼塊：

```javascript
if (condition) {
    // 代碼塊1
} else if (anotherCondition) {
    // 代碼塊2
} else {
    // 代碼塊3
}
```

### 迴圈

JavaScript 支持 `for`、`while` 和 `do...while` 迴圈：

```javascript
for (let i = 0; i < 5; i++) {
    // 迴圈體
}

while (condition) {
    // 迴圈體
}

do {
    // 迴圈體
} while (condition);
```

## 5. 函數

JavaScript 使用 `function` 声明函數：

```javascript
function greet(name) {
    return "Hello, " + name + "!";
}
```

函數可以接受參數並返回值。您可以調用函數來執行代碼。

## 6. 事件處理

JavaScript 用於處理用戶交互和事件，如點擊、滑鼠移動、表單提交等。

```javascript
document.getElementById("myButton").addEventListener("click", function() {
    // 處理點擊事件
});
```

## 7. 物件和類別

JavaScript 是基於物件的語言。您可以創建物件和類別來組織數據和功能。

```javascript
let person = {
    name: "John",
    age: 30,
    greet: function() {
        return "Hello, " + this.name + "!";
    }
};
```

## 8. 非同步編程

JavaScript 支持非同步編程，包括回調函數、Promise 和 async/await。

```javascript
setTimeout(function() {
    // 非同步代碼
}, 1000);
```

## 9. DOM 操作

JavaScript 可以操作文件物件模型（DOM），實現動態改變網頁內容和結構。

```javascript

document.getElementById("myElement").innerHTML = "New Content";
```

## 10. AJAX 請求

JavaScript 可以進行非同步 HTTP 請求，與伺服器通信並獲取數據。

```javascript
fetch("https://api.example.com/data")
    .then(response => response.json())
    .then(data => {
        // 處理數據
    });
```

## 11. 錯誤處理

JavaScript 支持錯誤處理，使用 `try`、`catch` 和 `throw` 來捕獲和處理錯誤。

```javascript
try {
    // 可能發生錯誤的代碼
} catch (error) {
    // 處理錯誤
}
```

## 12. 模組化

JavaScript 支持模組化編程，將代碼拆分成模組並匯入匯出功能。

```javascript
// 模組匯出
export function greet(name) {
    return "Hello, " + name + "!";
}

// 模組匯入
import { greet } from "./greetings.js";
```