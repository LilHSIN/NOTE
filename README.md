## 1. 標題（Headings）  
使用 `#` 來建立標題，`#` 的數量代表標題層級。  
```markdown
# 這是 H1 標題
## 這是 H2 標題
### 這是 H3 標題
#### 這是 H4 標題
##### 這是 H5 標題
###### 這是 H6 標題
```

## 2. 粗體、斜體與刪除線  
```markdown
**這是粗體**
*這是斜體*
~~這是刪除線~~
```

## 3. 清單（Lists）  
### 無序清單（Unordered List）
```markdown
- 項目 1
- 項目 2
  - 子項目 2.1
  - 子項目 2.2
- 項目 3
```
### 有序清單（Ordered List）
```markdown
1. 第一項
2. 第二項
   1. 子項目 2.1
   2. 子項目 2.2
3. 第三項
```

## 4. 連結（Links）  
```markdown
[Google](https://www.google.com)
[GitHub](https://github.com "GitHub 官方網站")
```

## 5. 圖片（Images）  
```markdown
![替代文字](https://example.com/image.jpg)
```

## 6. 程式碼（Code）  
### 行內程式碼（Inline Code）
```markdown
這是一個 `code` 片段。
```

### 區塊程式碼（Code Block）
```markdown
```python
def hello():
    print("Hello, World!")
```
```

## 7. 引用（Blockquotes）  
```markdown
> 這是一個引用區塊
>> 這是巢狀引用
```

## 8. 分隔線（Horizontal Rule）  
```markdown
---
```

## 9. 表格（Tables）  

| 標題1 | 標題2 | 標題3 |
|-------|-------|-------|
| 資料1 | 資料2 | 資料3 |
| 資料4 | 資料5 | 資料6 |


| Name | Phone | Address |
|:-|-:|:-:|
|左對齊|右對齊|中對齊|
|Sam|0913630230|New Taipei|
|Eva|0953|Taipei|    


## 10. 待辦事項清單（Task List）  
```markdown
- [x] 已完成項目
- [ ] 未完成項目
