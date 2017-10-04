# 定位元素

- 可见的页面板式
    * position 属性
        > 控制页面上元素间的位置关系。

    * display 属性
        > 控制元素在页面上是堆叠、并排，还是根本不在页面上出现。

    * float 属性
        > 提供控制的方式，以便把元素组成多栏布局。 

- 盒模型
    > 浏览器为页面中的每个HTML 元素生成的矩形盒子。

    * 盒子属性
        + 边框 border ( 宽度、样式、颜色 )
        + 内边距 padding
        + 外边距 margin （ 垂直方向的外边距叠加 ）
    * 显式的设定元素的width 属性，是内容区的属性。盒子宽度=width+padding+border+margin

- 浮动与清除
    > 会把元素从常规文档流中拿出来

    * 文字绕排图片
    * 实现分栏布局
    * 围住浮动元素的三种方法
        + 浮动父元素
        + 为父元素应用overflow:hidden
        + 在父元素的末尾添加非浮动元素，可以直接在标记中添加，也可以通过给父元素添加clearfix类来加
    * clearfix规则
    ```CSS
    .clearfix:after {
        content:".";
        display:block;
        height:0;
        visibility:hidden;
        clear:both;
    }
    ```

- 定位
    > position属性是CSS布局的核心。

    * 值
        + static 静态定位
        + relative 相对定位
        + absolute 绝对定位
        + fixed 固定定位

    * 定位上下文

- 显示属性

    * 值
        + block 浏览器中上下堆叠显示
        + inline 浏览器中左右并排显示
        + inline-block
        + none

- 背景
    > 支持为元素添加背景颜色和背景图片。

    * 属性
        + background-color
        + background-image
        + background-repeat 背景重复
        + background-position 背景位置
        + background-size 背景尺寸
        + background-attachment 背景粘附
        + background 简写属性
        + background-clip 背景绘制区域的范围
        + background-origin
        + background-break
    * 背景渐变
        + linear-gradient 线性渐变
        + radial-gradient 放射性渐变
    








