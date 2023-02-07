# css字体属性

### font-size

设置字体大小

### font-family（重要）

设置文字的字体

### font-weight

设置文字的粗细

默认：400

bold：700



### font-style

设置文字的常规、斜体显示

- normal：常规显示

- italic(斜体)：有字体的斜体显示（通常会有专门的字体）

- oblique(倾斜)：文本倾斜显示（仅仅是让文字倾斜）

  

### font-variant

可以影响小写字母的显示形式

- normal：常规显示
- small-caps：将小写字母替换为缩小过的大写字母

### line-height（常用）

设置行高：元素中每一行文字所占据的高度

 行高的严格定义是：两行文字基线（baseline）之间的间距。

基线（baseline）：与小写字母x最低部对齐的线

![image-20220920090634017](C:\Users\87608\AppData\Roaming\Typora\typora-user-images\image-20220920090634017.png)



### font缩写属性

- font是一个缩写属性
  - font属性可以用来作为font-style,font-variant,font-weight,font-size,line-height和font-family属性的简写
  - font-style font-variant font-weight font-size line-height font-family
- 规则
  - font-style、font-variant、font-weight可以随意调换顺序，也可以省略
  - /line-height可以省略、如果补省略，必须跟在font-size后面
  - font-size、font-family不可以调换顺序，不可以省略