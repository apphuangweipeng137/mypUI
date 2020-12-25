# myp-popup

## Props

| Prop name    | Description                  | Type    | Values | Default                                                                                                                       |
| ------------ | ---------------------------- | ------- | ------ | ----------------------------------------------------------------------------------------------------------------------------- |
| show         | 是否显示/打开                | boolean | -      | false                                                                                                                         |
| pos          | 定位位置                     | string  | -      | 'bottom'                                                                                                                      |
| bgType       | 背景主题                     | string  | -      | 'none'                                                                                                                        |
| duration     | 动画周期                     | number  | -      | 300                                                                                                                           |
| hasOverlay   | 是否有 overlay               | boolean | -      | true                                                                                                                          |
| overlay      | 遮罩层设置                   | object  | -      | {<br> hasAnimation: true,<br> timingFunction: ['ease-in', 'ease-out'],<br> duration: 300,<br> bg: '',<br> bgType: 'mask'<br>} |
| height       | 自定义高度                   | string  | -      | '0'                                                                                                                           |
| extra        | 需要从屏幕高度额外减去的高度 | string  | -      | '0'                                                                                                                           |
| leftOffset   | 内容与屏幕左侧的偏移量       | string  | -      | '-1'                                                                                                                          |
| rightOffset  | 内容与屏幕右侧的偏移量       | string  | -      | '-1'                                                                                                                          |
| bottomOffset | 内容与屏幕底部的偏移量       | string  | -      | '-1'                                                                                                                          |
| topOffset    | 内容与屏幕顶部的偏移量       | string  | -      | '-1'                                                                                                                          |
| width        | 自定义宽度                   | string  | -      | '750rpx'                                                                                                                      |
| animation    | 动画函数                     | object  | -      | {<br> timingFunction: 'ease-in-out'<br>}                                                                                      |
| left         | 遮罩与屏幕左侧的偏移量       | string  | -      | '0'                                                                                                                           |
| top          | 遮罩与屏幕顶部的偏移量       | string  | -      | '0'                                                                                                                           |
| right        | 遮罩与屏幕右侧的偏移量       | string  | -      | '0'                                                                                                                           |
| bottom       | 遮罩与屏幕底部的偏移量       | string  | -      | '0'                                                                                                                           |
| boxStyle     | 内容外层样式                 | string  | -      | ''                                                                                                                            |
| overlayStyle | overlay 的外层样式           | string  | -      | ''                                                                                                                            |

## Events

| Event name     | Type      | Description |
| -------------- | --------- | ----------- |
| overlayClicked | undefined |

## Slots

| Name    | Description | Bindings |
| ------- | ----------- | -------- |
| default |             |          |

---
