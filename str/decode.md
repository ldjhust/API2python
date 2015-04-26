# str.decode([encoding[, errors]])

- 参数说明：

&emsp;&emsp;&emsp;&emsp;encoding：可选参数，表示str本身的编码类型

&emsp;&emsp;&emsp;&emsp;errors：可选参数，表示解码失败后如何处理

- 返回值类型：object

- 功能描述：将str解码成unicode（PS：若encoding没给出，则使用sys.getdefaultencoding()返回的编码类型解码；若errors没给出，则使用strict模式，即如果解码失败，则抛出UnicodeDecodeError）

- eg:

>![](http://ww4.sinaimg.cn/mw690/70cc3cccgw1eriuy2eh3uj20bw01sq2s.jpg)
