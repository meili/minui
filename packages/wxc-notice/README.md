# wxc-notice

> 通告栏 - 小程序组件

## Install

``` bash
$ min install @minui/wxc-notice
```


## API

### Notice

| 名称                  | 描述                         |
|----------------------|------------------------------|
|`scroll`              | [说明]：通告栏文案是否滚动。<br>[类型]：`Boolean`<br>[默认值]：`false` <br>|
|`isShow`              | [说明]：是否显示通告栏。<br>[类型]：`Boolean`<br>[默认值]：`true` <br>|
|`notice`              | [说明]：通告栏文案。<br>[类型]：`String`<br>[默认值]：`""` <br>|
|`color`               | [说明]：通告栏文案颜色。<br>[类型]：`String`<br>[默认值]：`#fff` <br>|
|`bg-color`            | [说明]：通告栏背景色。<br>[类型]：`String`<br>[默认值]：`#ff5777` <br>|
|`show-icon`           | [说明]：是否显示通告栏前面的 `icon`。<br>[类型]：`Boolean`<br>[默认值]：`false` <br>|
|`icon-color`          | [说明]：通告栏前面的 `icon` 的颜色，配合 `show-icon` 使用。<br>[类型]：`String`<br>[默认值]：`#fff` <br>|
|`close`               | [说明]：是否显示关闭按钮。<br>[类型]：`Boolean`<br>[默认值]：`false` <br>|
|`bg-rgba`             | [说明]：通告栏关闭按钮前的遮罩层颜色，取背景颜色的 `rgba` 形式，`a` 的值为 `0`，配合关闭按钮一起使用。<br>[类型]：`String`<br>[默认值]：`rgba(255, 87, 119, 0)` <br>|
|`bind:close`          | [说明]：关闭按钮点击事件的回掉函数。         |

## ChangeLog

#### v1.0.0（2018-4-3）

- 初始版本
