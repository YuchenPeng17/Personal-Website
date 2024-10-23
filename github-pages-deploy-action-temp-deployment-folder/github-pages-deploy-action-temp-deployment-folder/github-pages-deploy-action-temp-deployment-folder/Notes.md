**Responsive Design - viewport**

viewport（视口）可以理解为设备或文档对象的逻辑尺寸。

```html
<meta name="viewport" content="width=device-width,initial-scale=1.0,minimum-
scale=1.0,maximum-scale=1.0,user-scalable=no">
```

| 属性名        | 取值                    | 描述                                                |
| ------------- | ----------------------- | --------------------------------------------------- |
| width         | 正整数 or device-width  | 定义视口的宽度，单位为像素                          |
| height        | 正整数 or device-height | 定义视口的高度，单位为像素，一般不用                |
| initial-scale | [0.0 - 10.0]            | 定义初始缩放值                                      |
| minimum-scale | [0.0 - 10.0]            | 定义缩小最小比例，它必须小于或等于maximum-scale设置 |
| maximum-scale | [0.0 - 10.0]            | 定义放大最大比例，它必须大于或等于minimum-scale设置 |
| user-scalable | yes / no                | 定义是否允许用户手动缩放页面，默认值yes             |

