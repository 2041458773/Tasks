# 选择器
 ```css
        /* 元素选择器 */
        h2 {
            color: blue;
        }

        /* 类选择器 */
        .highlight {
            background-color: yellow;
        }
        /* id选择器 */
        #header {
            font-size: 35px;
        }
        /* 通用选择器 */
        * {
            font-family: 'KaiTi';
        }
        /* 子代选择器 */
        .father > .son {
            color: yellow;
        }
        /* 后代选择器 */
        .father p {
            color: brown;
            font-size: large;
        }
        /* 相邻选择器 */
        h3 + p {
            background-color: red;
            font-weight: bolder;
        }
        /* 伪类选择器 */
        h3#element:hover {
            background-color: blueviolet;
        }
  ```
# 区块
 ```css
<div class="nav">
        <a href="#">链接1</a>
        <a href="#">链接2</a>
        <a href="#">链接3</a>
    </div>
    <div class="content">
        <h1>文章标题</h1>
        <p>内容</p>
        <p>内容</p>
        <p>内容</p>
    </div>
    <span>第一个span标签</span>
    <span>第二个span标签</span>
    <span>第三个span标签</span>
    <hr>
    <span><a href="#">链接</a></span>
 ```
# 导入
```css
 <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="./css样式/style.css">

    <style>
        p {
            color: blue;
            font-size: 16px;
        }
    </style>
</head>
<body>
```
# 常用属性
```css
    <h1 style="font: bolder 50px KaiTi;">font 复合属性示例</h1>
    <p style="line-height: 40px;">这是一段长文本这是一段长文本这是一段长文本这是一段长文本这是一段长文本这是一段长文本这是一段长文本这是一段长文本这是一段长文本这是一段长文本这是一段长文本这是一段长文本这是一段长文本这是一段长文本这是一段长文本这是一段长文本这是一段长文本这是一段长文本这是一段长文本这是一段长文本这是一段长文本</p>
    <div class="div-inline">块级元素转行内元素</div>
    <P>这是一个css样式文本，内部样式</P>
    <h1 style="color: red;">内联样式</h1>
    <h2>外部样式</h2>
