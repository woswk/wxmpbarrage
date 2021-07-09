# 小程序弹幕组件

### 介绍
小程序弹幕组件，可用于商品购买信息飘窗展示，开箱即用，只支持小程序。




### 使用说明

| 属性名 | 是否必填 | 值类型 | 默认值 | 说明 |
| --------- | -------- | -----: | --: | --: |
| top| 否  | String| 10vh |   距离屏幕顶部距离 |
| rowSpacing| 否  | String| 40rpx |   弹幕行间距 |
| list| 否  | Array| [] |   数据源示例：[{avatar:"",words:""}] |
| zIndex| 否  | Number| 999 |   层级 |
| speed| 否  | Number| 5000 |   滚动100vw所需时间 |
| shakeSpeed| 否  | Number| 500 |   速度波动范围-500~500ms之间选取随机值 |
| shakeDelay| 否  | Number| 500 |   动画延时执行时间波动范围上限值 0~500ms之间选取随机值, 用于控制弹幕出厂顺序 |
| rows| 否  | Number| 3 |  弹幕行数 |
| marRight| 否  | String| 40rpx |  每项弹幕右外边距 |
| loop| 否  | Boolean| true |  是否循环 |
| @done| 否  | Function|  |  单次滚动完成的回调 |

### 演示图片

![Image text](https://z3.ax1x.com/2021/07/09/RxVKMj.gif)

