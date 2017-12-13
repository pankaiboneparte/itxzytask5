# itxzytask5
background属性的缩写顺序color，image，repeat，attachment，position 。http://blog.csdn.net/yunying_si/article/details/22381657
滚动条要在除去固定元素（header\footer）之外的元素使用 overflow-y: auto;overflow-x: hidden;使用-webkit-overflow-scrolling: touch;可以在滚动时自动隐藏滚动条，并用z-index:1;去除ios中的bug。https://www.w3cways.com/1988.html
使用border-radius: 50%;制作圆形头像框，使用overflow: hidden;将超出头像框的图片隐藏，将其中的头像设为width:100%可以将其完整显示。
使用position定位时top: 50%;transform: translate(0,-50%);。可以实现居中 https://segmentfault.com/a/1190000002436755
li元素可以用padding撑起高度。http://www.imooc.com/wenda/detail/324046 使用list-style: none;去掉表格前面的圆点。
<strong>默认加粗字体（font-weight: bold;也可以），也可以设置颜色。
display: flex;可以用作占满一整行（平分）的布局，对于平分的布局内部元素使用flex:1就可以实现。