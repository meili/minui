# wxc-toast

> MinUI 小程序组件 - 提示框

## Install

``` bash
$ min install @minui/wxc-toast
```

## API

### Toast【props】

| 名称                  | 描述                         |
|----------------------|------------------------------|
|`is-show`             | [说明]： `toast` 显示控制字段。<br>类型：`Boolean`<br>默认值：`false`|
|`text`                | [说明]：提示的文案，必填。<br>类型：`String`<br>默认值：`""` <br>     |
|`icon`                | [说明]：图标。<br>类型：`String`<br>默认值：`""` <br> 可选值详见 `wxc-icon` 组件中的 `type` 属性    |
|`icon-image`          | [说明]：【已废弃，请使用 `src` 】自定义图标图片的路径，优先级高于 icon。<br>类型：`String`<br>默认值：`""` <br>       |
|`src`                 | [说明]：自定义图标图片的路径，优先级高于 icon。<br>类型：`String`<br>默认值：`""` <br>       |
|`icon-color`          | [说明]：图标颜色。<br>类型：`String`<br>默认值：`"#fff"` <br> |
|`duration`            | [说明]：提示的延迟时间，单位毫秒。<br>类型：`Number`<br>默认值：`2000` <br>  |
|`bind:success`        | [说明]：调用成功的回调函数。|

### Toast【methods】

| 名称                  | 描述                         |
|----------------------|------------------------------|
|`show(msg)`           | [说明]：显示toast。<br>[类型]：`Function`<br>[参数]：`String`<br>[返回]：`void`|

## Link
||地址|
|--|---|
||toast 组件文档 <br> [https://meili.github.io/min/docs/minui/index.html#toast](https://meili.github.io/min/docs/minui/index.html#toast)<br>|
||toast 组件源码 <br> [https://github.com/meili/minui/tree/master/packages/wxc-toast](https://github.com/meili/minui/tree/master/packages/wxc-toast)<br>|
||MinUI 组件库 <br> [https://github.com/meili/minui](https://github.com/meili/minui) <br>|

## Preview
![toast](https://s10.mogucdn.com/mlcdn/c45406/171107_1361j09d04c4426a5gd743i7kk5hg_480x480.jpg_225x999.jpg)

##  ChangeLog
#### v1.0.8（2018.03.29)
- show() 方法增加 message 参数

#### v1.0.7（2018.01.16)
- icon-image 属性更改为 src，1.0.7 及以上版本的 min 支持本地图片路径

#### v1.0.6（2018.01.09)
- z-index 层级规范方案修改

#### v1.0.3（2018.01.04）

- 修复自定义 icon 时，icon 的颜色样式问题，规范 z-index 规范

#### v1.0.2（2017.11.02）

- update .npmignore

#### v1.0.1（2017.10.24）

- 初始版本
