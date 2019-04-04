CSS:
<style>
  li{margin:5px 4px 10px 3px;}
</style>

【记忆】
margin:5px 4px 10px 3px;  // 上边距是5px, 右边距是4px, 下边距是10px, 左边距是3px
        上  右   下  左
        
记住【上右下左】顺序！例子：
margin:5px;  //右下左默认=上。 即margin:5px 5px 5px 5px;
        上
        
margin:5px 4px;  //下默认=上 左默认=右。 即margin:5px 4px 5px 4px;
        上  右

margin:5px 4px 10px;  //左默认=右。 即margin:5px 4px 10px 4px
        上  右   下

margin:5px 4px 10px 3px;
        上  右   下   左
