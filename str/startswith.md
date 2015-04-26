# str.startswith(prefix[, start[, end]])

- 参数说明：

&emsp;&emsp;&emsp;&emsp;prefix：必选参数，表示一个字符串或字符串元祖

&emsp;&emsp;&emsp;&emsp;start：可选参数，表示从str的start下表开始查找

&emsp;&emsp;&emsp;&emsp;end：可选参数，表示查找到str的end（不包含end）下标结束

- 返回值类型：bool

- 功能描述：检查str的[start, end)区间（PS：若没给定区间则检查str整个字符串）是否是以prefix为开始（PS：当prefix为元祖时，只要str的开始是其中的任何一个字符串，就返回True）

- eg:

>![](http://ww4.sinaimg.cn/mw690/70cc3cccgw1erj4eqr0ulj20el05y0sv.jpg)