# wxc-rate

> 评分 - 小程序组件

## Install

``` bash
$ min install @minui/wxc-rate
```


## API

### Rate

| 名称                  | 描述                         |
|----------------------|------------------------------|
|`value`               | [说明]：评分值。<br>[类型]：`Number`<br>[默认值]：`0` <br>|
|`count`               | [说明]：星星个数。<br>[类型]：`Number`<br>[默认值]：`5` <br>|
|`size`                | [说明]：图标大小。<br>[类型]：`Number`<br>[默认值]：`44` <br>|
|`color`               | [说明]：初始颜色值。<br>[类型]：`String`<br>[默认值]：`#e5e5e5` <br>|
|`active-color`        | [说明]：选中颜色值。<br>[类型]：`String`<br>[默认值]：`#fdb757` <br>|
|`padding`             | [说明]：两颗星星间的距离。<br>[类型]：`Number`<br>[默认值]：`20` <br>|
|`readonly`            | [说明]：是否只读。<br>[类型]：`Boolean`<br>[默认值]：`false` <br>|
|`bind:rate`           | [说明]：评分点击事件，event.detail = {value: value}。|

## ChangeLog

#### v1.0.1（2018-6-5）
- 补充文档，增加 `rate` 点击事件说明

#### v1.0.0（2018-4-23）

- 初始版本
