## 什么是css？css是如何工作的？

+ **css**是层叠样式表，样式定义如何显示html元素，样式都放在样式表中
+ 把样式添加到html中，是为了解决**内容与表现分离的问题**

## css的基本语法是怎样的?

+ css由选择器和一条或多条声明组成组成
+ 最简单的语法 selector { property:value}

## css选择器是什么？简单选择器和属性选择器是什么？

**css选择器**规定了css规则会应用到哪些元素上。

+ 简单选择器：通过元素类型，类和id匹配一个或多个元素
+ 属性选择器：通过属性/属性值匹配一个或多个元素

## 文本样式都有哪些属性？

+ **font-family**:字体种类，五个常见值**serif**，**sans-serif**，**monospace**，**cursive**,**fantasy**。

+ **font-size**:字体大小，**px**（绝对），**em**（1em等于其父元素设置字体大小），**rem**（1rem等于其根元素上设置的字体大小）。

+ **font-style**:用来设置字体是否为斜体，通常有**normal**（普通），**italic**（斜体）。

+ **font-weight**:设置文字的粗体大小，常用**normal**（普通），**bold**（加粗）。

+ **text-transform**:允许要设置的转换字体

  + **none**: 防止任何转型。

  + **uppercase**: 将所有文本转为大写。

  + **lowercase**: 将所有文本转为小写。

  + **capitalize**: 转换所有单词让其首字母大写。

  + **full-width**: 将所有字形转换成全角，即固定宽度的正方形，类似于等宽字体，允许拉丁字符和亚洲语言字形（如中文，日文，韩文）对齐。

    

+ **text-decoration**:文本装饰，值为none（取消所有装饰），underline（文本加下划线），overline（文本加上划线），line-through（穿过文本的线）
+ **text-align**:文本布局
+ **text-shadow**:文本阴影
+ **letter-spacing**:字母间距
+ **word-spacing**:单词间距