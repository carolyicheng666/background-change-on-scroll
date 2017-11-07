mix-blend-mode
===

利用 `css` 的 `mix-blend-mode` 和 `isolation` 实现 `Photoshop` 中图层之间混合模型的效果，具体值参考如下：

``` css
mix-blend-mode: normal;          //正常
mix-blend-mode: multiply;        //正片叠底
mix-blend-mode: screen;          //滤色
mix-blend-mode: overlay;         //叠加
mix-blend-mode: darken;          //变暗
mix-blend-mode: lighten;         //变亮
mix-blend-mode: color-dodge;     //颜色减淡
mix-blend-mode: color-burn;      //颜色加深
mix-blend-mode: hard-light;      //强光
mix-blend-mode: soft-light;      //柔光
mix-blend-mode: difference;      //差值
mix-blend-mode: exclusion;       //排除
mix-blend-mode: hue;             //色相
mix-blend-mode: saturation;      //饱和度
mix-blend-mode: color;           //颜色
mix-blend-mode: luminosity;      //亮度

mix-blend-mode: initial;         //初始
mix-blend-mode: inherit;         //继承
mix-blend-mode: unset;           //复原
```

关于 `isolation` ，只需要记住在某一元素中使用

``` css
isolation:isolate;
```

那么在其之外的元素将不会发生层叠混合，也就是说其内部会形成一个混合组，与外部隔断

参考
---
1. [原项目](https://codepen.io/giana/full/PqVbRr/)
2. [张鑫旭-CSS3混合模式mix-blend-mode/background-blend-mode简介](http://www.zhangxinxu.com/wordpress/2015/05/css3-mix-blend-mode-background-blend-mode/)
3. [张鑫旭-理解CSS3 isolation: isolate的表现和作用](http://www.zhangxinxu.com/wordpress/2016/01/understand-css3-isolation-isolate/)