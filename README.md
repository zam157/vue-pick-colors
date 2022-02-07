### vue-pick-colors：颜色拾取器

<img src="data:image/png;base64,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"  style="zoom:50%;" />

安装：

```
npm i vue-pick-colors -S
```



API：

| 属性           | 说明               | 类型            | 默认值    |
| -------------- | ------------------ | --------------- | --------- |
| value(v-model) | 值                 | String          | #FF0000FF |
| format         | 格式               | hex / rgb / hsl | hex       |
| show-alpha     | 是否支持透明度选择 | boolean         | true      |

事件：

| 事件名称 | 说明               | 回调参数               |
| -------- | ------------------ | ---------------------- |
| change   | 颜色变化时回调函数 | Function(color:string) |



TODO:

- 颜色校验
- 多颜色拾取
- 预备颜色列表
- 暗黑主题