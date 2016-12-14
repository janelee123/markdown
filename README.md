# markdown
learn to use markdown syntax
###标题
#h1
##h2
###h3
####h4
#####h5
######h6

###列表
无序列表
- 1
- 2
- 3
等同于
+ 1
+ 2
+ 3
等同于
* 1
* 2
* 3


有序列表
1. 1
2. 2
3. 3

###引用
>这里是引用
>再来一个
>> 二级引用
>
>通过>可以回到指定的级别
>>>三级引用
>>
>回到二级
>
>回到一级

###插入链接
[baidu](http://www.baidu.com)

###插入图片
![icon](http://cdn-qn0.jianshu.io/assets/default_avatar/12-07a584b5038a24cbb23b81dc673c18fd.jpg)

###粗体和斜体
**这是粗体**
*这是斜体*
_这也是斜体_

###表格
表头1       | 表头2
------------- | -------------
Content Cell |   Content Cell
Content Cell |   Content Cell

| 表头1 | 表头2|
| ------------- | ------------- |
| Content Cell | Content Cell |
| Content Cell | Content Cell |

| 名字 | 描述 |
| ------------- | ----------- |
| Help | ~~Display the~~ help window.|
| Close | _Closes_ a window |

| 左对齐 | 居中 | 右对齐 |
| :------------ |:---------------:| -----:|
| col 3 is | some wordy text | $1600 |
| col 2 is | centered | $12 |
| zebra stripes | are neat | $1 |

###删除线
 ~~Display the~~
###代码框
`span{
    color: @text_color;
}
a{
    float: right;
    background: url('../../img/questionnaire/see-more.png') no-repeat 0 0;
    width: 30 * @ratio;
    height: 30 * @ratio;
    background-size: cover;
}`

`<div>hello</div>`

开头加上四个空格即可出现代码块,一直到没有缩进为止

    <div>hello</div>
    <span>hi</span>
###分割线
华丽又低调的分割线
***
###下划线
这是一段文字，然后他有下划线
___

###脚注
hello[^hello]

[^hello]: hi

second[^second]
[^second]: this is the second





