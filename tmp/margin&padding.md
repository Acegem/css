```
CSS:
<style>
  li{margin:5px 4px 10px 3px;}
</style>

【记忆】
margin:5px 4px 10px 3px;  // 上边距是5px, 右边距是4px, 下边距是10px, 左边距是3px
        上  右   下  左
        
记住上面【上右下左】顺序！例子如下：

margin:5px;  //右下左默认=上。 即margin:5px 5px 5px 5px;
        上
        
margin:5px 4px;  //下默认=上 左默认=右。 即margin:5px 4px 5px 4px;
        上  右

margin:5px 4px 10px;  //左默认=右。 即margin:5px 4px 10px 4px
        上  右   下

margin:5px 4px 10px 3px;
        上  右   下   左
```


外边距margin
内边距padding：补白
margin是盒子的外边距，即盒子与盒子之间（<div>与<div>间）的距离，而padding是内边距，是盒子的边与盒子内部元素的距离。
  
用故事讲解下：-----该故事来自简书 [参考链接](https://www.jianshu.com/p/73deb2ae7992)
  如何理解margin与padding呀，我们首先可以想象一下我们手里拿了一个钻戒要向女朋友求婚，一般求婚的时候钻戒都是在盒子里放着呢，我们要有盒子的概念，钻戒一般都放在盒子的中央，没有哪家的钻戒是把盒子占的满满的，我们的钻戒就放在盒子的中央，占了很小的一块面积，其它的地方都是有填充物的，我们可以把这个填充物简单的理解为padding也就是钻戒距离盒子内边缘的距离，这时候我们想把钻戒放在桌子上，放在桌子的什么位置呢，左上角，右上角，还是中间，我们姑且把他放在中间把，那么我们这个钻戒盒子距离桌子边缘的距离就是margin，那么很简单我们那个钻戒的盒子就是我们所说的border。

[!image]()
