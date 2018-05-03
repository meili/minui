# MinUI

MinUI 是基于微信小程序自定义组件特性开发而成的一套简洁、易用、高效的组件库，适用场景广，覆盖小程序原生框架，各种小程序组件主流框架等，并且提供了专门的命令行工具，猛戳这里（[Min-Cli 使用文档](https://meili.github.io/min/docs/install/index.html)）详细了解如何使用吧。

![](https://img.shields.io/badge/Build-Passing-brightgreen.svg) ![](https://img.shields.io/badge/License-MIT-lightgrey.svg) ![](https://img.shields.io/badge/%E5%9F%BA%E7%A1%80%E5%BA%93-1.6.0%2B-brightgreen.svg) ![](https://img.shields.io/badge/Powered%20by-Min-28b1b0.svg)

![](http://s3.mogucdn.com/mlcdn/c45406/171101_850g622e33552bb75f74ael4k563f_3882x1734.png_1200x999.jpg)

![](http://s3.mogucdn.com/mlcdn/c45406/171025_00h0heed7c1a5iid87ch299h3l8j4_3882x1734.png_1200x999.jpg)

### ○ 体验

#### 在线体验

通过下面的小程序二维码，可以在手机中体验 MinUI（微信基础库版本 1.6.3 以上支持）：

![](http://s3.mogucdn.com/mlcdn/c45406/171103_5l89d0ih87eh9e715065310ekgdea_220x220.png)

#### 本地体验

1. 安装 Min 的环境 `$ npm install -g @mindev/min-cli`
2. Clone MinUI 仓库到本地；
3. 安装依赖 `$ npm install`
4. 在 MinUI 根目录下执行 `$ min dev`，生成 dist/ 目录；
5. 微信开发者工具 —— 新建一个小程序，目录指向生成的 dist/；
6. Done~

PS：如想尝试修改源码，终端里先执行 `$ min dev`。这样任何的修改，都会在微信开发者工具中自动刷新显示。

### ○ 文档

- [MinUI 组件库文档](https://meili.github.io/min/docs/minui/index.html)
- [MinUI 源码地址](https://github.com/meili/minui)
- [Min-Cli 工具使用文档](https://meili.github.io/min/docs/install/index.html)
- [Min-Cli 源码地址](https://github.com/meili/min-cli)

### ○ 组件列表

- 布局元素
    - [布局 flex](https://meili.github.io/min/docs/minui/index.html#flex)
    - [水平垂直居中 cc](https://meili.github.io/min/docs/minui/index.html#cc)
- 基础元件
    - [头像 avatar](https://meili.github.io/min/docs/minui/index.html#avatar)
    - [徽章 badge](https://meili.github.io/min/docs/minui/index.html#badge)
    - [文本截断 elip](https://meili.github.io/min/docs/minui/index.html#elip)
    - [图标 icon](https://meili.github.io/min/docs/minui/index.html#icon)
    - [标签 label](https://meili.github.io/min/docs/minui/index.html#label)
    - [页底提示 loadmore](https://meili.github.io/min/docs/minui/index.html#loadmore)
    - [价格price](https://meili.github.io/min/docs/minui/index.html#price)
    - [进度条 progress](https://meili.github.io/min/docs/minui/index.html#progress)
- 功能组件
    - [异常流展示 abnor](https://meili.github.io/min/docs/minui/index.html#abnor)
    - [倒计时 countdown](https://meili.github.io/min/docs/minui/index.html#countdown)
    - [数字框 couner](https://meili.github.io/min/docs/minui/index.html#counter)
    - [加载提示 loading](https://meili.github.io/min/docs/minui/index.html#loading)
    - [遮罩层 mask](https://meili.github.io/min/docs/minui/index.html#mask)
    - [ 步骤条 steps](https://meili.github.io/min/docs/minui/index.html#steps)
    - [选项卡 tab](https://meili.github.io/min/docs/minui/index.html#tab)
- 提示反馈
    - [对话框 dialog](https://meili.github.io/min/docs/minui/index.html#dialog)
    - [弹出层 popup](https://meili.github.io/min/docs/minui/index.html#popup)
    - [提示框 toast](https://meili.github.io/min/docs/minui/index.html#toast)

### ○ 反馈沟通

请添加群助手 wUf18018252882 好友或者扫码加好友，并与群助手对话发送验证码 10088 按照指引进群。

![群二维码](https://s10.mogucdn.com/mlcdn/c45406/180108_888g0d26e23h9j8fc9e3bd7j3e85h_430x430.jpg_320x999.jpg)

### ○ 开源协议

本项目基于 [MIT](http://opensource.org/licenses/MIT) License，请自由的享受、参与开源。


### ○ 更新记录

#### v2.0.0（2018.04.27）

- 新增 button 组件
- 新增 input 组件
- 新增 list 组件
- 新增 notice 组件
- 新增 panel 组件
- 新增 search 组件
- 新增 select 组件
- 新增 rate 组件
- popup 组件文档补充，增加 locked 属性的说明
- toast 组件 show() 方法增加 message 参数
- tab 组件 panel 高度自适应
- counter 组件加减操作符新增 color 属性

#### v1.0.9（2018.01.09）

- z-index 层级规范方案修改
- price 组件在 del 状态下应该可以设置颜色
- price 组件增加货币符号属性
- icon 组件 API 完善

#### v1.0.8（2018.01.04）

- tab组件修复点击定位问题
- loading更换mall的图标
- steps组件修复desc的字体
- price组件修复小数问题
- z-index层级规范
- mask,popup组件增加toggle方法
- abnor组件config补全

#### v1.0.7（2017.12.01）

- 优化 price组件价格小数点显示问题
- 优化 tab支持导出多个入口
- 优化 conter组件demo中的属性规范
- 优化 loading、toast组件透出实例内部方法
- 修复 个别组件样式错乱问题
- 重构 首页的导航部分换成 wxc-example-menu 组件

#### v1.0.6（2017.11.30）

- 新增几个小程序二维码
- 优化个别组件功能 

#### v1.0.5（2017.11.20）

- 新增 wxc-avatar 头像组件
- 新增 ChnageLog

#### v1.0.4（2017.11.15）

- 新增 wxc-cc 水平垂直居中组件

#### v1.0.3（2017.11.09）

- 新增 about 页面

#### v1.0.2（2017.11.04）

- 新增工具化页面

#### v1.0.0（2017.10.24）

- 初始版本
