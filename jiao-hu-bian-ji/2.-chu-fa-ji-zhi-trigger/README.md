---
description: Trigger
---

# 2. 触发机制 Trigger

![](../../.gitbook/assets/企业微信截图\_ccb9ff0f-42c0-474a-bd32-e284ed06b12a.png)

Trigger 触发机制有多个类型，可以参考下述表格：

| Trigger                                             | 描述                                          | 备注                     |
| --------------------------------------------------- | ------------------------------------------- | ---------------------- |
| [单击 Tap](2.1-dan-ji-tap.md)                         | 最常用的Trigger，点击调整、点击切换、点击发生状态变更各种都支持         |                        |
| [双击 Double tap](2.2-shuang-ji-double-tap.md)        | 双击比单击少见，一般为了区别于单击使用                         |                        |
| [长按 Long Press](2.3-chang-an-long-press.md)         | 长按，在车机中不常见，一般进行复杂操作需要的手势                    |                        |
| [划 Pull](2.4-hua-pull.md)                           | 划动是分四个方向、同时支持多指划动，能承载更多手势交互                 |                        |
| [拖拽 Drag](2.5-tuo-zhuai-drag.md)                    | 支持多指拖拽承载多种交互                                |                        |
| [捏合 Pinch](2.6-nie-he-pinch.md)                     | 快速放大缩小当前元件图层                                | 目前需要配合Action-scale进行操作 |
| [根据某主题 On Topic](2.7-gen-ju-mou-zhu-ti-on-topic.md) | 基于项目与场景互动的特定主题；目前还包含了一些特殊的使用案例，例如音乐播放器、键盘按键 | 同时也支持自定义编辑             |
| [启动 Start](2.8-qi-dong-start.md)                    | 部分交互存在随时间发生，即开始后，进入当前页面后，或是进入当前页面再延时后等      |                        |
| [关联 Chain](2.9-guan-lian-chain.md)                  | 可以关联到组件 Component 内的 Screen进行的交互            |                        |
| [监听 Detect](2.10-jian-ting-detect.md)               | 监听一个变量，继而有因为变量的变化而发生 Action动作反馈             |                        |





