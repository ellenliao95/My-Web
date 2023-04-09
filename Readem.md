#Still Working on it.

# Website About Me

## How to Link to a Specific Part of a Page HTML? 
- Use <a href = "get the id name to you want to jump location"> 

## How to open in new page (HTML)
- Use <a href="" target = "_blank" >

### When clicked email address create a email text area.
- <a href="mailto:...?"> 
* mailto(協議):email address?
* subject = "..." 

### Background-img 不被剪裁的放大縮小
- background-size: contain;
https://timor419.github.io/2020/04/19/CSS-img/
* 發現這個做法會讓圖片因放大而重複出現n張，所以最後還是使用：
background-size: cover;
width: 100%;
height: 600px; 

### Don't change link color when a link is clicked
- :hover{color: }

### delete <a> under line
- text-decoration: none;

### How to fix the row height? 
- position: flexed; cannot use, white area are missing 

## 自適應網頁大小
- <meta name="viewport" content="width=device-width, initial-scale=1.0"> 
* viewport 指網頁默認的高度、寬度
* content="width=device-width 指寬度 ＝ 屏幕大小
* initial-scale=1.0" 網頁初始大小，佔屏幕面積的100%

### px VS. em
- px 為絕對大小
- em 為相對大小
    em轉換成字體大小的算法為：16（默認大小） * 該值
    例如: 
    1. font-size: 1.5em => 1.5 * 16 = 24 所以1.5em = 字體24
    2. font-size: 0.875em = 0.875 * 16 = 14
    0.875em = 字體14
* 使用相對大小會更好的適應網頁縮放

### 網頁寬度佔比需使用%，這樣才能更好的適應縮放
