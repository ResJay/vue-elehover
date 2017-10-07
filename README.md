# vue-elehover
vue点击特效插件

![](https://github.com/ResJay/vue-elehover/blob/master/GIF1.gif?raw=true)

#### 笔记
```
以后写特效时请记得先想好再写
var requestAnimFrame = function () {
        return (
          window.requestAnimationFrame ||
          window.mozRequestAnimationFrame ||
          window.oRequestAnimationFrame ||
          window.msRequestAnimationFrame ||
          function (callback) {
            window.setTimeout(callback, 1000 / 60);
          }
        );
      }()   //判断requestAnimFrame
```

## 安装

#### npm下载
`````
● cnpm install vue-elehover 
`````
### vue-cli内main文件

``````
● import Vue from 'vue'

● import ele from "vue-elehover"

● Vue.use(ele)
````````````````

## 使用

* this.$elehover(e)  ||  Vue.$elehover(e)

* 参数e为字符串格式  可以是所有标签名 如 "a"  
  可以是所有class或者ID  "classname" ; "idName"
