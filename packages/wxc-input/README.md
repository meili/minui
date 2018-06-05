# wxc-input

> 输入框组件 - 小程序组件

## Install

``` bash
$ min install @minui/wxc-input
```


## API

### Input

| 名称                  | 描述                         |
|----------------------|------------------------------|
|`title`               | [说明]：输入框前面的标题。若 `src` 或 `icon` 同时指定，`title` 的优先级最高，`src` 次之，`icon` 最低。<br>[类型]：`String`<br>[默认值]：`""` <br>|
|`src`                 | [说明]：输入框前面的图标，自定义图片链接。<br>[类型]：`String`<br>[默认值]：`""` <br>|
|`icon`                | [说明]：输入框前面的图标，类型见 `wxc-icon` 组件。<br>[类型]：`String`<br>[默认值]：`""` <br>|
|`icon-color`          | [说明]：输入框前面的图标颜色，与 `icon` 一同使用。<br>[类型]：`String`<br>[默认值]：`""` <br>|
|`mode`                | [说明]：输入框边框模式。<br>[类型]：`String`<br>[可选值]：`wrapped`，有边框包裹；`normal`，只有下边框；`none`，无边框。<br>[默认值]：`normal` <br>|
|`right`               | [说明]：输入框文本是否向右对齐。<br>[类型]：`Boolean`<br>[默认值]：`false` <br>|
|`error`               | [说明]：是否显示为输入框错误情况下的样式。<br>[类型]：`Boolean`<br>[默认值]：`false` <br>|
|`value`               | [说明]：输入框的内容。<br>[类型]：`String`<br>[默认值]：`""` <br>|
|`type`                | [说明]：input 的类型。<br>[类型]：`String`<br>[可选值]：`text, number, idcard, digit`<br>[默认值]：`"text"` <br>|
|`password`            | [说明]：是否是密码类型。<br>[类型]：`Boolean`<br>[默认值]：`false` <br>|
|`placeholder`         | [说明]：输入框为空时占位符。<br>[类型]：`String`<br>[默认值]：`""` <br>|
|`placeholder-style`   | [说明]：指定 `placeholder` 的样式。<br>[类型]：`String`<br>[默认值]：`""` <br>|
|`disabled`            | [说明]：是否禁用。<br>[类型]：`Boolean`<br>[默认值]：`false` <br>|
|`maxlength`           | [说明]：最大输入长度，设置为 -1 的时候不限制最大长度。<br>[类型]：`Number`<br>[默认值]：`140` <br>|
|`cursor-spacing`      | [说明]：指定光标与键盘的距离，单位 px。<br>[类型]：`Number`<br>[默认值]：`0` <br>|
|`focus`               | [说明]：获取焦点。<br>[类型]：`Boolean`<br>[默认值]：`false` <br>|
|`confirm-type`        | [说明]：设置键盘右下角按钮的文字。<br>[类型]：`String`<br>[可选值]：`send, search, next, go, done`<br>[默认值]：`done` <br>|
|`confirm-hold`        | [说明]：点击键盘右下角按钮时是否保持键盘不收起。<br>[类型]：`Boolean`<br>[默认值]：`false` <br>|
|`cursor`              | [说明]：指定focus时的光标位置。<br>[类型]：`Number`<br>[默认值]：`0` <br>|
|`selection-start`     | [说明]：光标起始位置，自动聚集时有效，需与selection-end搭配使用。<br>[类型]：`Number`<br>[默认值]：`-1` <br>|
|`selection-end`       | [说明]：光标结束位置，自动聚集时有效，需与selection-start搭配使用。<br>[类型]：`Number`<br>[默认值]：`-1` <br>|
|`adjust-position`     | [说明]：键盘弹起时，是否自动上推页面。<br>[类型]：`Boolean`<br>[默认值]：`true` <br>|
|`bind:input`          | [说明]：当键盘输入时，触发input事件，event.detail = {value, cursor}，处理函数可以直接 return 一个字符串，将替换输入框的内容。|
|`bind:focus`          | [说明]：输入框聚焦时触发，event.detail = { value, height }，height 参数在基础库 1.9.90 起支持         |
|`bind:blur`           | [说明]：输入框失去焦点时触发，event.detail = {value: value}|
|`bind:confirm`        | [说明]：点击完成按钮时触发，event.detail = {value: value}|

## Note

> 小程序组件系统中组件是隔离的，所以提交表单时无法用 `form` 表单获取输入框中的值，只能单独获取。

## ChangeLog

#### v1.0.0（2018-3-29）

- 初始版本
