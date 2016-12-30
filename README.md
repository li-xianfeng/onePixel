# onePixel

>1px近完美解决方案(附less mixin)

```
@import './onepx.less';
body{
	// 第一个参数代表border类型包括虚线实线等(必填参数)
	// 第二个参数代表颜色(必填参数)
	// 第三个参数代表圆角(非必填参数)
	.border(solid, #222, 10);
}
li{
	// .border-top/.border-bottom/.border-left/.boder-right四个方位的边框设置
	.border-bottom(solid, #222);
}

```

![](https://github.com/coderwin/onePixel/blob/master/onePixel.png?raw=true)


