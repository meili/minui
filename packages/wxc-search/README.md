# wxc-search

> 搜索栏 - 小程序组件

## Install

``` bash
$ min install @minui/wxc-search
```


## API

### Search

| 名称                  | 描述                         |
|----------------------|------------------------------|
|`show-icon`           | [说明]：是否显示 `search` 图标。<br>[类型]：`Boolean`<br>[默认值]：`true` <br>|
|`show-clear`          | [说明]：是否显示清除图标。<br>[类型]：`Boolean`<br>[默认值]：`true` <br>|
|`icon-color`          | [说明]：`search` 图标的颜色。<br>[类型]：`String`<br>[默认值]：`#bbb` <br>|
|`ph-color`            | [说明]：`placeholder` 的颜色。<br>[类型]：`String`<br>[默认值]：`#bbb` <br>|
|`bg-color`            | [说明]：搜索栏的背景颜色。<br>[类型]：`String`<br>[默认值]：`#f6f6f6` <br>|
|`color`               | [说明]：搜索栏输入框字体颜色。<br>[类型]：`String`<br>[默认值]：`#333` <br>|
|`radius`              | [说明]：搜索栏 `border-radius`。<br>[类型]：`Number`<br>[默认值]：`6` <br>|
|`placeholder`         | [说明]：搜索栏 `placeholder`。<br>[类型]：`String`<br>[默认值]：`搜索` <br>|
|`mode`                | [说明]：搜索栏模式。<br>[类型]：`String`<br>[可选值]：`normal`，输入模式；`static`，静态模式，无输入框。<br>[默认值]：`normal` <br>|
|`align`               | [说明]：静态模式下搜索栏内容对齐方式。<br>[类型]：`String`<br>[可选值]：`left`，向左对齐；`center`，居中。<br>[默认值]：`left` <br>|
|`button`              | [说明]：搜索按钮文案。不设置文案时不显示搜索按钮<br>[类型]：`String`<br>[默认值]：`""` <br>|
|`btn-color`           | [说明]：搜索按钮文字颜色。<br>[类型]：`String`<br>[默认值]：`#333` <br>|
|`bind:input`          | [说明]：当键盘输入时，触发 `input` 事件，`event.detail = {value, cursor}`|
|`bind:confirm`        | [说明]：点击搜索或键盘右下角按钮，触发 `confirm` 事件，`event.detail = {value: value}`|
|`bind:submit`         | [说明]：搜索栏组件中内置 `form` 表单，点击搜索按钮时触发 `submit` 事件，可用于获取 `formId` 等，`event.detail = {value, formId}`|

## ChangeLog

#### v1.0.0（2018-4-9）

- 初始版本
