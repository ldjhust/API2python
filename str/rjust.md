# str.rjust(width[, fillchar])

- 参数说明：

&emsp;&emsp;&emsp;&emsp;width：必选参数，表示所希望的方法调用返回字符串的宽度

&emsp;&emsp;&emsp;&emsp;fillchar：可选参数，表示用于填充空白位置的字符（PS：只能是**字符**，不能是**字符串**），默认用空白符填充

- 返回值类型：string
- 功能描述：将str置于width宽度字符串的右边（PS：如果width的值比str本身的长度小，则此方法调用不会产品任何效果，只会返回与str相同的字符串），左边的空白用fillchar填充，默认用空白符填充
- eg：


>![](http://ww2.sinaimg.cn/mw690/70cc3cccgw1erj1qz8d1gj20d606qjrz.jpg)