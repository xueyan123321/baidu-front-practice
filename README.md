# baidu-front-practice
flex布局用于解决float中飘忽不定的行为，特别适用于等高问题。
传统布局依赖display+float+position属性。对于很多特殊情况很不方便。

W3C提供了一种新的方案，可以简便清晰的实现各种布局。
flex理解为弹性布局，用来为盒装模型提供最大的灵活性。
注意设置flex以后，子元素的float，clear，vertical-align都将失效。

flex容器，flex项目
如果不想让项目放大或缩小，可以调整flex-grow或者flex-shrink。
