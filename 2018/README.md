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

css
1  行内元素？块级元素？
    display属性  默认值 block = 块级缘故  inline = 行内元素
    a img span input select strong 行内元素
    div table h1... p ul li 等属于块级元素
2  link和@import
    页面加载时的顺序不一样，link是同时加载，而import是等页面加载完后加载
3  