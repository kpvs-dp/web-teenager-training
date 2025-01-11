# Day01

## 檔案介紹

- `flex.html` 介紹 `flex`
- `navbar.html` 實作導覽列

## Display
[Display 介紹](https://lucashsu95.github.io/LucasHsu.dev/css/basic/display)

### flex

#### 垂直對齊 
縮寫:aic
```css
align-items: center
```

#### 水平對齊 
縮寫:jcc
```css
justify-content: center
```

#### 垂直排列
```
flex-direction: column
```

## 如何讓`<ul>`移到右邊
### 方法一
自動分配`<ul>`左邊的距離
```css
ul {
    margin-left: auto;
}
```

### 方法二
在父元素中使用`flex`的水平散開
```css
nav {
    justify-content: space-between;
}
```

## CSS property

### margin 外距
- 一個參數:`margin: top/left/right/bottom`
- 二個參數:`margin: top/bottom left/right`
- 四個參數:`margin: top right bottom left`
```css
margin: 10px;
margin: 10px 20px;
margin: 10px 5px 20px 15px;
```

### box-shadow 陰影
`box-shadow: 水平 垂直 擴散 顏色`
```css
box-shadow: 2px 3px 5px #ccc;
```
### border 框線
`border: 框線粗度 框線樣式 顏色`
```css
border: 1px solid #333;
```
