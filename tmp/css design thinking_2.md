#### 写css时 有的属性顺序不可以换，（因为有加载先后顺序），否则达不到预期效果！
##### 举例：
```
margin: 0 auto;和margin-top: 150px; 的先后顺序不同效果也不同。如下：

（1）margin: 0 auto;margin-top: 150px;  //表示先自适应到中间置顶，再设置顶边距150px。

（2）margin-top: 150px;margin: 0 auto;  //表示先设置顶边距150px，再自适应到中间置顶。
```
