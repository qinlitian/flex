flexble-box    （灵活的-盒子）

当我们父盒子使用后flex布局后，子元素的float（浮动）clear（清除）vertical-align（垂直的-排列）属性将失效

采用flex布局的元素，称为flex容器（flex-container）简称“父-容器”，他的所有子元素自动成为容器成员，称为flex项目（flex-item）简称“子-项目”

![](C:\Users\lenovo\AppData\Local\Temp\1593959018788.png)

![1593959122363](C:\Users\lenovo\AppData\Local\Temp\1593959122363.png)

![1593959270274](C:\Users\lenovo\AppData\Local\Temp\1593959270274.png)

flex-direction     默认是让子元素能设置大小，子盒子向主轴方向排列

默认的主轴是 x 轴  行  row

我们的子元素是根着主轴排列的，（主轴方向有两个）

flex-direction：row；默认主轴    一行排列

flex-direction：column；我们可以把我们的主轴设置为 y轴，那么 x轴就成侧轴了

![1593959354665](C:\Users\lenovo\AppData\Local\Temp\1593959354665.png)

justify-content   属性设置项目在主轴的对齐方式

`注意：使用这个属性之前一定要确定好主轴是哪个`

![1593959930743](C:\Users\lenovo\AppData\Local\Temp\1593959930743.png)

flex布局中，默认子元素是不换行显示的，父元素大小装不下子元素，子元素自动缩小

flex-wrap：wrap；   换行显示

![1593960529361](C:\Users\lenovo\AppData\Local\Temp\1593960529361.png)

`设置-侧轴的子元素的对齐方式`

![1593960705887](C:\Users\lenovo\AppData\Local\Temp\1593960705887.png)

`设置-侧轴侧轴上的子元素的排列方式`

![1593961252987](C:\Users\lenovo\AppData\Local\Temp\1593961252987.png)

`align-content和align-items的区别`

1. align-items使用单行元素的情况下，只有上对齐，下对齐，居中和拉伸
2. align-content`适用于换行（多行）`的情况下（单行情况下无效），可以设置上对齐，下对齐，居中，拉伸以及平均分配剩余空等属性值
3. `总结：就是单行找align-items   多行找align-content`

掠过-等熟悉了再用这个复合属性

![1593961928920](C:\Users\lenovo\AppData\Local\Temp\1593961928920.png)







`flex布局子元素常见属性`

![1593962023667](C:\Users\lenovo\AppData\Local\Temp\1593962023667.png)

flex属性的是设置子元素在父盒子里的`剩余空间`占比

比如：左盒子固定宽高，右盒子固定宽高，中间自适应（flex：1；）自己占满剩下的空间

还有两边盒子flex；1；中间盒子flex；2；这样的话两边盒子占父盒子的四分之一

中间盒子占父盒子的四分之二（圣杯布局，双飞翼布局，两边固定中间自适应）



`了解-要看`

> 项目属性
>
> order（属性定义项目的排列顺序。数值越小，排列约靠前，默认为0
>
> flex-grow（属性定义项目的放大比例，默认为`0`，即如果存在剩余空间，也不放大 
>
> flex-shrink（属性定义了项目的缩小比例，默认为1，即如果空间不足，该项目将缩小。 
>
> flex-basis（属性定义了在分配多余空间之前，项目占据的主轴空间（main size）。浏览器根据这个属性，计算主轴是否有多余空间。它的默认值为`auto`，即项目的本来大小。 
>
> flex（属性是`flex-grow`, `flex-shrink` 和 `flex-basis`的简写，默认值为`0 1 auto`。后两个属性可选。 
>
> align-self（属性允许单个项目有与其他项目不一样的对齐方式，可覆盖`align-items`属性。默认值为`auto`，表示继承父元素的`align-items`属性，如果没有父元素，则等同于`stretch`。
>



![1593963667780](C:\Users\lenovo\AppData\Local\Temp\1593963667780.png)

![1593963681167](C:\Users\lenovo\AppData\Local\Temp\1593963681167.png)

![1593963691929](C:\Users\lenovo\AppData\Local\Temp\1593963691929.png)

![1593963702363](C:\Users\lenovo\AppData\Local\Temp\1593963702363.png)

![1593963712653](C:\Users\lenovo\AppData\Local\Temp\1593963712653.png)

![1593963721595](C:\Users\lenovo\AppData\Local\Temp\1593963721595.png)

![1593963734850](C:\Users\lenovo\AppData\Local\Temp\1593963734850.png)





