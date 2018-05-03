# wxc-select

> select - 小程序组件

## Install

``` bash
$ min install @minui/wxc-select
```


## API

### Select

| 名称                  | 描述                         |
|----------------------|------------------------------|
|`items`               | [说明]：`select` 选项数据。<br>[类型]：`Array`<br>[默认值]：`[]` |
|`checked`             | [说明]：选中数据的 `value` 值。<br>[类型]：`String`<br>[默认值]：`""` |
|`color`               | [说明]：选中时 `radio` 的颜色。<br>[类型]：`String`<br>[默认值]：`#ff5777` |
|`bind:change`         | [说明]：选中项发生变化时触发 `change` 事件，event.detail = {value: 选中项radio的value}|

### items 数据格式
| 名称                  | 描述                         |
|----------------------|------------------------------|
|`value`               | [说明]：选项的值。|
|`title`               | [说明]：选项标题。|
|`desc`                | [说明]：选项描述。可选。|

## ChangeLog

#### v1.0.0（2018-4-12）

- 初始版本
