# epub-transformation
epub傍点变换
基础功能是将em-sesame样式着重号转变成ruby样式的·.py附加了很多的功能方便自己自动化处理epub，单一转换功能做了个sigil0.9.8的插件可以直接执行

        基础功能:
        1.固定傍点转换成ruby样式,不固定会产生奇怪的代码
        2.傍点class名称需要确认
        3.图片处理可能会不正确,图片处理是在正则匹配处理之后,
        请确认处理后的epub
        4.ruby处理是删掉了多余的rb代码并且合并多个rt规格化不让其造成
        后面ruby兼容正则变换的混乱

好像ebooklib会强行把epub变成epub3.0  暂时没想到解决方法,手动修改就行了

   ![图片描述](20230824192745.png)
