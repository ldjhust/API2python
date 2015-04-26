# str.encode([encoding[, errors]])

- 参数说明：

&emsp;&emsp;&emsp;&emsp;encoding：可选参数，表示你希望将str编码成什么类型的编码

&emsp;&emsp;&emsp;&emsp;errors：可选参数，表示编码失败后如何处理

- 返回值类型：object

- 功能描述：将unicode类型的str编码成你所给的encoding类型的编码（PS：若encoding没给出，则使用sys.getdefaultencoding()返回的编码类型编码；若errors没给出，则使用strict模式，即如果编码失败，则抛出UnicodeDecodeError）

- eg:

>![](http://ww2.sinaimg.cn/mw690/70cc3cccgw1eriv3ci52zj20bs0350so.jpg)