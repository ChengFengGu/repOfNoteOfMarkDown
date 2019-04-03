# 1、标题设置
    几个标题几个#
    一级标题：===
    二级标题：---
## 试一试

标题1
===
标题2
---

---
# 2、段落改行
    + 如果是全部一段话换行并不能换段
    + 如果需要换段，换行后再加两个空格

## 试一试
天长地久有时尽  
此恨绵绵无绝期

---
# 3、添加分割线
+ ：---
+ ：***
+ ：- - - 
+ ：___

---
# 4、引用表现
    语法：> (空格不能忘)
## 试一试
> 我在引用一些东西
> 我在引用另外一些东西

---
# 5、强调表现
+ 斜体
  *两端各加一个星号*
  _或者两端各加一个下划线_
+ 粗体
  **前后各加两个星号**
  __或者前后各加两个下划线__
---

# 6、列表表示
    + - * 无序
    数字  有序
## 试一试
- 1
- 2
- 3
- 4
- 5
- 6
  
1. 1
2. 2
3. 3
4. 4
5. 5
6. 6

---
# 7、超文本连接
    直接写
    或者前后加上<>

## 试一试
http://www.runoob.com/
<http://www.runoob.com/>

---

# 8、代码高亮

- 代码高亮显示符号: `
- 代码高亮显示符号：~

## 试一试
```java
    package com.example.demo;

    import org.springframework.boot.SpringApplication;
    import org.springframework.boot.autoconfigure.SpringBootApplication;

    @SpringBootApplication
    public class DemoApplication {

        public static void main(String[] args) {
            SpringApplication.run(DemoApplication.class, args);
        }

    }
```

在一段文字中的效果：`add { document.write("hello world");}`

---

# 9、图片显示
    1、图片的引用与显示：![用于图片的显示](图片url 图片title)
    2、制作图片链接
## 试一试

[![加载中。。。](https://p2.ssl.qhimgs1.com/bdr/594__/t015aae573913ea4772.jpg "图片")](http://www.runoob.com/)


---

# 10、表格显示

| TH1 | TH2 | TH3 |
----|----|----
|td1|td2|td3|
|td4|td5|td6|