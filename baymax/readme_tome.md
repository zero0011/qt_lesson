伪元素


线性渐变
linear-gradient()
    原始渐变轴  从上到下
环形渐变


背景大小
    background-size 属性能调整背景图片的大小，从而替代了用原始大小显示图片的默认行为。你可以随意的缩放背景图。
    用法：background-size: length|percentage|cover|contain;

    length：设置背景图片高度和宽度。第一个值设置宽度，第二个值设置的高度。如果只给出一个值，第二个是设置为 auto(自动)
    percentage：将计算相对于背景定位区域的百分比。第一个值设置宽度，第二个值设置的高度。如果只给出一个值，第二个是设置为"auto(自动)"
    cover：此时会保持图像的纵横比并将图像缩放成将完全覆盖背景定位区域的最小大小。
    contain：此时会保持图像的纵横比并将图像缩放成将适合背景定位区域的最大大小。


背景定位
    







浮动  float
    1.脱离文档流,不排队,空间被后面的人占用
    2.但不排队的那些人,也得排自己的队
    3.全部浮动,实现横向排列
    4.父元素没有了高度,导致下面的元素会出错

清除浮动  clear
    1.下面的元素简单清除浮动,会使margin-top失效
    2.在父元素添加伪元素(after)
            .container::after{
            content: '';
            display: block;
            clear: both;}
        


