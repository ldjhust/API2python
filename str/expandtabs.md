# str.expandtabs([tabsize])

- 参数说明：

&emsp;&emsp;&emsp;&emsp;tabsize：可选参数，表示一个tab长度等于多少个空格（PS：没有限制，你说多少就是多少）

- 返回值类型：string

- 功能描述：用tabsize个空格（PS：若不给tabsize，则默认tabsize为8）替换str中的tab符（PS：如果str中没有tab，则此方法调用不会产生任何效果）

- eg:

>![](http://ww1.sinaimg.cn/mw690/70cc3cccgw1erix8ogyfgj20gc09twez.jpg)

**PS：这个方法不怎么准确，特别是当tab符不在str的开始位置或str中有多个tab符时，因此不建议使用**