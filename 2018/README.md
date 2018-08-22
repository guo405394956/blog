面试集锦

html
1  doctype ？
    html说明，告诉浏览器的解析器用什么标准进行解析，h5中只有一个就是“html”
2  html5新特性
    canvas画布  动画效果  frame 本地存储localStorage  语义化（比如header，footer，nav等）
3  低版本的IE支持html5
    引入成熟的js html5.js
4  localStorage 和 cookie 
    传输区别   cookie在服务器和浏览器种来回传递，localStorage只保存在本地，并不会乡服务器主动发送。
    存储大小   cookie存储空间为4k，localStorage为5M
    存储时效   cookie有设定的有效期，localStorage始终有效
    ps localStorage不能跨浏览器
5  遇到的浏览器兼容性问题和解决方法
    css：
    问题：浏览器的默认的margin和padding不同
    解决：统一设置*{margin:0;padding:0;}
    其他：
    解决：hack \9标记 ie6-10都生效



css
1  行内元素？块级元素？
    display属性  默认值 block = 块级缘故  inline = 行内元素
    a img span input select strong 行内元素
    div table h1... p ul li 等属于块级元素
2  link和@import
    页面加载时的顺序不一样，link是同时加载，而import是等页面加载完后加载
3  盒子模型
    border padding margin content  
    ie盒子模型和W3C盒子模型，具体参考demo：https://github.com/guo405394956/demos.git /cssBoxMode/index.html
4  CSS选择器
    id选择器  (#J_elementId)
    类选择器  （.class）
    标签选择器  （div a p span input table tr td th...）
    子选择器   （ul>li）
    后代选择器   （.class span）
    通配符选择    （*）
    属性选择器   （input[type = 'button']）
    伪类选择器   （a:hover, li:nth-child）
5  css样式应用的优先级
    内联样式（标签内部） > 嵌入样式（页面中定义的） > 外部引用样式（import导入）
6  css3新增伪类
    ::after  清除浮动 clear:both
    ::before
    ::checked
    ::disabled
7  div水平居中
    width: 100px; margin: auto;
    left和margin left设置为50%；margin设置为div容器的一半宽度 
    transform css3的新特性
8  div垂直居中
    transform css3新特性
    flex布局 align-items: center; 		/* 垂直居中 */      justify-content: center;	/* 水平居中 */
9  css3的新特性
   圆角 border-radius
   阴影 shadow
   旋转 transform
   移动 translate
   平滑过度 transtion
   动画 animation
   缩放 scale

