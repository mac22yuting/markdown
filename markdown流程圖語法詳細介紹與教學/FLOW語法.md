# FLOW語法

## 使用方法：

首先在 Typora 中，输入 **```flow**  然後按enter，即可初始化一张空白图。

底下為示範:

<video src="C:\Users\a0979\OneDrive\桌面\markdown流程圖語法詳細介紹與教學\圖片\建立FLOW_ 使用 Clipchamp 製作.mp4"></video>

## 範例代碼



```flow

st=>start: 开始框
 
op=>operation: 处理框
 
cond=>condition: 判断框(是或否?)
 
sub1=>subroutine: 子流程
 
io=>inputoutput: 输入输出框
 
e=>end: 结束框
 
st->op->cond
 
cond(yes)->io->e
 
cond(no)->sub1(right)->op

```



## 使用細節



![你的段落文字](.\圖片\你的段落文字.png)

![新增標題](.\圖片\新增標題.png)



- **紅色塗鴉的地方記得要按*空白建***

- **寫的時候直得先寫 邊看邊連 當流程圖有判斷寫在下一行**

