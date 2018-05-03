# wxc-popup

> MinUI 小程序组件 - 弹出层

## Install

``` bash
$ min install @minui/wxc-popup
```

## API

### Popup【props】

| 名称                  | 描述                         |
|----------------------|------------------------------|
|`animation-mode`           | 【说明】动画样式<br>【类型】`String`<br>【默认值】`""`<br>【可选值】`none, center, top, bottom, left, right`         |
|`align`           | 【说明】占位位置<br>【类型】`String`<br>【默认值】`""`<br>【可选值】`center, top, bottom, left, right`         |
|`status`           | 【说明】默认状态<br>【类型】`String`<br>【默认值】`""`<br>[可选值】`hide, show  `       |
|`locked`           | 【说明】遮罩层是否设置锁定态。<br>【类型】`String`<br>【默认值】`"hide"` <br>[可选值]：<br>`"true"`，点击遮罩层背景部分不会关闭遮罩（点击子节点部分关闭遮罩）。<br>`"hide"`，点击遮罩层背景部分关闭遮罩（点击子节点部分不会关闭遮罩）。<br>      |

### Popup【methods】

| 名称                  | 描述                         |
|----------------------|------------------------------|
|`show`         | 【说明】显示 `popup` <br>【params】void<br>【return】void        |
|`hide`			| 【说明】隐藏 `popup` <br>【params】void<br>【return】void		|
|`toggle`       | 【说明】切换 `popup` 的可见状态。<br>【params】`switch`: `Boolean`。可选。<br>【return】void|

## Link
||地址|
|--|---|
||popup 组件文档 <br> [https://meili.github.io/min/docs/minui/index.html#popup](https://meili.github.io/min/docs/minui/index.html#popup)<br>|
||popup 组件源码 <br> [https://github.com/meili/minui/tree/master/packages/wxc-popup](https://github.com/meili/minui/tree/master/packages/wxc-popup)<br>|
||MinUI 组件库 <br> [https://github.com/meili/minui](https://github.com/meili/minui) <br>|

## Preview
![popup](https://s10.mogucdn.com/mlcdn/c45406/171107_68e8eb623kc5gk73j8f6f99clfc4f_480x480.jpg_225x999.jpg)

##  ChangeLog
#### v1.0.7（2018.03.29)
- 补充文档，增加 locked 属性的说明

#### v1.0.6（2018.01.09)
- z-index 层级规范方案修改

#### v1.0.3（2018.01.04）

- 增加toggle方法，规范z-index层级

#### v1.0.2（2017.11.02）

- update .npmignore

#### v1.0.1（2017.10.24）

- 初始版本

