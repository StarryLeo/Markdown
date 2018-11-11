# Markdown
Markdown基本语法

标题

# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题

区块引用

> 区块引用
>> 套嵌引用
> 区块引用

> ## 这是一个标题。
> 
> 1.   这是第一行列表项。
> 2.   这是第二行列表项。
> 
> 给出一些例子代码：
> 
>     return shell_exec("echo $input | $markdown_script");

代码区块

void main()
{
    printf("Hello, Markdown.");
}

列表

* Red
* Green
* Blue

1. Red
2. Green
3. Blue

分割线

***
---
___

链接

行内式
欢迎访问[喵喵的灿烂星空](https://starrycat.me "一个窝")

参考式
谷歌搜索：[Google][00]
欢迎访问我的博客：[喵喵的灿烂星空]，我的GitHub主页：[StarryLeo's GitHub]。
[00]: https://www.google.com
[喵喵的灿烂星空]: https://starrycat.me "一个窝"
[StarryLeo's GitHub]: https://github.com/StarryLeo

自动链接

<http://example.com/>
<address@example.com>

强调

*斜体*
**粗体**
***加粗斜体***
~~删除线~~

反引号"`"

Use the `printf()` function.
``` c
    #include <stdio.h>
    int main()
    {
    printf("Hello, world!\n");
    return 0;
    }
```

