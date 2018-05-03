# wxc-list

> 列表组件 - 小程序组件

## Install

``` bash
$ min install @minui/wxc-list
```


## API

### List

| 名称                  | 描述                         |
|----------------------|------------------------------|
|`title`               | [说明]：列表项左侧的标题。<br>[类型]：`String`<br>[默认值]：`""` <br>|
|`detail`              | [说明]：标题下方的的详细描述。<br>[类型]：`String`<br>[默认值]：`""` <br>|
|`desc`                | [说明]：列表项右侧的描述。<br>[类型]：`String`<br>[默认值]：`""` <br>|
|`src`                 | [说明]：标题前面的图标，自定义图片链接。优先级高于 `icon`。<br>[类型]：`String`<br>[默认值]：`""` <br>|
|`icon`                | [说明]：标题前面的图标，类型见 `wxc-icon` 组件。<br>[类型]：`String`<br>[默认值]：`""` <br>|
|`icon-color`          | [说明]：标题前面的icon图标颜色，同 `icon` 一同使用。<br>[类型]：`String`<br>[默认值]：`#ff5077` <br>|
|`dot`                 | [说明]：右侧描述部分前面的提醒红点。<br>[类型]：`Boolean`<br>[默认值]：`false` <br>|
|`dot-color`           | [说明]：右侧描述部分前面的提醒红点颜色，与 `dot` 一同使用。<br>[类型]：`String`<br>[默认值]：`#f5123e` <br>|
|`arrow`               | [说明]：是否显示箭头。<br>[类型]：`Boolean`<br>[默认值]：`true` <br>|
|`mode`                | [说明]：列表项边框模式。<br>[类型]：`String`<br>[可选值]：`normal`，有下边框；`none`，无边框。<br>[默认值]：`normal` <br>|
|`bind:click`          | [说明]：点击列表项时触发的事件。组件带 `slot` 时给组件添加原生事件后点击到 `slot` 时会报错，故增加自定义事件避免此错误。 |

## ChangeLog

#### v1.0.0（2018-3-29）

- 初始版本
