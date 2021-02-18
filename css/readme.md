1.vh/vw
vh: 相对于视窗的高度, 视窗被均分为100单位的vh; 
vw: 相对于视窗的宽度, 视窗被均分为100单位的vw;
即window.innerWidth/window.innerHeight大小，不包含任务栏标题栏以及底部工具栏的浏览器区域大小.

2.calc是css3的一个新增的功能，用来指定元素的长度。
比如说，你可以使用calc()给元素的border、margin、pading、font-size和width等属性设置动态值。
为何说是动态值呢?因为我们使用的表达式来得到的值。不过calc()最大的好处就是用在流体布局上，可以通过calc()计算得到元素的宽度。

3.注意，运算符前后都需要保留一个空格，例如：width: calc(100% - 10px)