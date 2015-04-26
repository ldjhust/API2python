# str.partition(sep)

- 参数说明：

&emsp;&emsp;&emsp;&emsp;sep：必选参数，表示用sep作为分隔符

- 返回值类型：(head, sep, tail)
- 功能描述：先在str中查找第一个sep子串，然后将str分割成三部分sep之前的子串、sep本山、sep之后的子串，三部分组成元组并返回（PS：如果没有在str中找到sep则返回(str, '', '')，若有多个sep，也只会从第一个sep出分割）
- eg：


>![](http://ww4.sinaimg.cn/mw690/70cc3cccgw1erj2nldv5yj20cd03cdfw.jpg)