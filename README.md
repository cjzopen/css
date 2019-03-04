# css

* 語義化
* 全小寫
* 功能化，如同 bs4 一樣
* 盡量不要對HTML tag下樣式，會造成維護困難
* bem命名規則，edge看不懂雙橫線--，如下面的class name。
```css
    .menu_list_item--active{}
    // 這段會被edge忽略
```
  所以改用單橫線-。
* font-size base on 16px; mobile 12px。
* 通常使用rem 
