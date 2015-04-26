# str.index(sub[, start[, end]])

- 参数说明：

&emsp;&emsp;&emsp;&emsp;sub：必选参数，表示你希望在str中查找的子串

&emsp;&emsp;&emsp;&emsp;start：可选参数，表示你希望从str中下标为start的位置开始查找

&emsp;&emsp;&emsp;&emsp;end：可选参数，表示你希望找到str中下标为end（PS：不包括end）的位置为止

- 返回值类型：int

- 功能描述：返回str中找到的首个sub子串的下标，与find方法功能相似，与find不同的是，如果index方法没有在str中找到sub，那么他会抛出ValueError异常

- eg:

>![](http://ww4.sinaimg.cn/mw690/70cc3cccgw1eriz1h4epdj20e00820tb.jpg)