# html ch01 Introduction

## A Simple HTML Document
 - ```<!DOCTYPE html>```宣告這整個html檔為HTML5的檔案
 - ```<html>```元素是以HTML為主語言的網頁最主要的根元素
 - ```<head>```元素是指包含在HTML網頁裡面的元訊息
 - ```<title>```元素指定HTML網頁的標題
 - ```<body>```元素是用來宣告這檔案的身體，並擔任所有可見內容的容器，像是標題、段落、圖片、超連結、標籤、清單等
 - ```<h1>```元素是宣告一段字體大的標題
 - ```<p>```元素是宣告一個段落

## HTML Element
html的元素會有開始與結束，稱為start tag跟end tag，只有少數的元素只有start tag

```html
<tagname>Content goes here...</tagname>
```

example:
```htnl
<h1>My First Heading</h1>
<p>My first paragraph
```

# HTML Document
整個HTML的文件，最開始都必須要有宣告```<!DOCTYPE html>```
HTML文件都是由```<html>```開始，```</html>```結束
而整個文件的可視部分是```<body>```與```</body>```之間的內容

## <!DOCTYPE html>
```<!DOCTYPE>```是宣告整個文件的架構，他幫助瀏覽器正確的顯示訊息
他只能在在整個文件的第一行(在所有HTML的標籤之前)宣告，並且只能有一行
```<!DOCTYPE>```不區分大小寫
```<!DOCTYPE>```的HTML5的宣告方法如下
```HTML
<!DOCTYPE html>
```

## HTML Heading
HTML的標題是在```<h1>```與```</h1>```之間的文字
```<h1>```宣告最重要的標題，```<h6>```宣告最不重要的標題
```html
<h1>This is heading 1</h1>
<h2>This is heading 2</h2>
<h3>This is heading 3</h3>
```

## HTML Paragraphs
HTML的段落是宣告在```<p>```元素中
```html
<p>This is a paragraph.</p>
<p>This is another paragraph.</p>
```

## HTML Links
HTML的超連結是宣告在```<a>```的元素之中
```html
<a href="https://www.w3schools.com">This is a link</a>
```
超連結的網址是在```href```屬性裡面定義
「屬性」是用來提供給html元素的附加訊息
之後會學到更多關於屬性的相關內容

## HTML Image
HTML的圖片是顯示在```<img>的元素裡面
```<img>```之中會有文件地址```src```、當圖片無法顯示時，代替用來顯示的文字```alt```、寬度```width```與高度```height```等元素來修改圖片的附加內容
```html
<img src="w3schools.jpg" alt="W2Schools.com" width="104 height="142>
```
