# wxc-flex

> MinUI 小程序组件 - flex

## Install

``` bash
$ min install @minui/wxc-flex
```

## API

### Flex【props】

| 名称                  | 描述                         |
|----------------------|------------------------------|
|`dir`           | 主轴方向。取值范围: <br><br>  - left：水平正序(默认) <br>  - right：水平倒序 <br>  - top：垂直正序 <br>  - bottom：垂直倒序       |
|`main`         | 主轴对齐方式。取值范围: <br><br>  - start：启点排列(默认) <br>  - end：终点排列 <br>  - between：两端对齐 <br>  - center：居中对齐 <br>  - around：等间分布         |
|`cross`         | 交叉轴对齐方式。取值范围：<br><br>  - stretch：拉伸铺满(默认) <br> - start：启点排列 <br>  - end：终点排列 <br>  - center：居中对齐 <br>  - baseline：基线对齐       |
|`wrap`         | 换行设置。取值范围：<br><br> - nowrap：不换行(默认)  <br> - wrap：正序换行 <br> - reverse：倒序换行       |
|`bind:click`   | 点击事件。组件带 `slot` 时，在组件中使用事件点击到 `slot` 会报错，绑定事件请用该自定义事件。|

## Link
||地址|
|--|---|
||flex 组件文档 <br> [https://meili.github.io/min/docs/minui/index.html#flex](https://meili.github.io/min/docs/minui/index.html#flex)<br>|
||flex 组件源码 <br> [https://github.com/meili/minui/tree/master/packages/wxc-flex](https://github.com/meili/minui/tree/master/packages/wxc-flex)<br>|
||MinUI 组件库 <br> [https://github.com/meili/minui](https://github.com/meili/minui) <br>|

## Preview
![flex](https://s10.mogucdn.com/mlcdn/c45406/171107_644d29k85d23lgafie50h51ci8gg1_480x480.jpg_225x999.jpg)

##  ChangeLog
#### v1.0.3（2018.6.5）

- 增加点击事件。

#### v1.0.2（2017.11.02）

- update .npmignore

#### v1.0.1（2017.10.24）

- 初始版本
