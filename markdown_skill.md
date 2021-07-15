# Example for writing markdown document
**<div style="text-align: right">Author: Eric Tsai</div>**
<a name='top'></a> 
---
# 1. Hyperlink
Create a hyperlink to a location in the current document. It is useful to create a table of content.
* [hyperlink for title](#hyperlink-location)
* [hyperlink for html tag name](#1)

# 2. Heading
# Heading 
## heading
### heading
#### heading

# 3. Show Miltiple Tables Side By Side
<table>
<caption>
  <h1>Data Schema</h1>
</caption>
    
<tr>
  <th><h3>Table1</h3></th>
  <th><h3>Table2</h3></th></tr>
<tr>
<td>
    
| 欄位名稱 | 說明 |
|:------------------:|:--------:|
| action             | 瀏覽行為記錄
| date               | 此筆log的時間戳記
| source             | 產品名稱
| device             | app裝置系統
</td>

<td>
    
| 欄位名稱 | 說明 |
|:------------------:|:--------:|
| action          | 瀏覽行為記錄      
| date            | 此筆log的時間戳記
| joblist         | 工作列表
| querystring     | 網址參數
| source          | 產品名稱
</td>
</tr>
</table>


# 4. Some text format
_look at me_

**Look at me**

**_Look at me_**

~Don't look at me~

# 5. Show image
![wronged image](https://static02-proxy.hket.com/res/v3/image/content/1500000/1503614/0919SE01_1024.jpg "image label")

# 6. Link
[link](https://github.com/EricTsai83 "Github: EricTsai")

# 7. Lists
* Milk
* Bread
    * Wholegrain
        * 123
* Butter

# 8. Quotes
> To be or not to be, that is the question.

# 9. Separation Between Different Sections of Text
---

# 10. Code Snippets
* use \`\`

Some text with an inline `code` snippet

* use \`\`\` code write here \`\`\`
```
.my-link {
    text-decoration: underline;
}
```

* Indenting by 2 or 4 spaces
  .my-link {
      text-decoration: underline;
  }
  
  
# 11. Embedding HTML
<button class="button-save large">Big Fat Button</button>



# 12. Syntax Highlighting
>### ptyhon
```python
import pandas as pd

def fun(x):
    return x
```
>### javascript
```javascript
//js code
[...]
```


# 13. Color Text
<span style="color:red;">color text</span>

# 14. Alert Boxes
<div class="alert alert-success">
  <strong>Success!</strong> Indicates a successful or positive action.
</div>

<div class="alert alert-info">
  <strong>Info!</strong> Indicates a neutral informative change or action.
</div>

<div class="alert alert-warning">
  <strong>Warning!</strong> Indicates a warning that might need attention.
</div>

<div class="alert alert-danger">
  <strong>Danger!</strong> Indicates a dangerous or potentially negative action.
</div>


---
<a name='1'></a> 
### hyperlink location
<button class="button-save large">[Go To The Top](#top)</button>



