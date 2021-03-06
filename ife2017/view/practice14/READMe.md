# 雪碧图
CSS雪碧 即CSS Sprite，也有人叫它CSS精灵，是一种CSS图像合并技术，该方法是将小图标和背景图像合并到一张图片上，然后利用css的背景定位来显示需要显示的图片部分。

CSS雪碧的基本原理是把你的网站上用到的一些图片整合到一张单独的图片中，从而减少你的网站的HTTP请求数量。该图片使用CSS background和background-position属性渲染，这也就意味着你的标签变得更加复杂了，图片是在CSS中定义，而非<img>标签。

## 优点
减少加载网页图片时对服务器的请求次数

可以合并多数背景图片和小图标，方便在任何位置使用，这样不同位置的请求只需要调用一个图片，从而减少对服务器的请求次数，降低服务器压力，同时提高了页面的加载速度，节约服务器的流量。
提高页面的加载速度

sprite 技术的其中一个好处是图片的加载时间(在有许多 sprite 时，单张图片的加载时间)。由所需图片拼成的一张 GIF 图片的尺寸会明显小于所有图片拼合前的大小。单张的 GIF 只有相关的一个色表，而单独分割的每一张 GIF 都有自己的一个色表，这就增加了总体的大小。因此，单独的一张 JPEG 或者 PNG sprite 在大小上非常可能比把一张图分成多张得来的图片总尺寸小。

# 伪元素
伪元素是创造关于文档语言能够指定的文档树之外的抽象。例如文档语言不能提供访问元素内容第一字或者第一行的机制。伪元素允许设计师引用它们，否则这是难以办到的。伪元素还提供样式设计师给在源文档中不存在的内容分配样式（例如：:before和:after能够访问产生的内容）

伪元素有： :first-line，:first-letter，:before，:after

伪元素的语法：

selector:pseudo-element {property:value;}

CSS 类也可以与伪元素配合使用：

selector.class:pseudo-element {property:value;}