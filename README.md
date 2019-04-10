# visual-layout
可视化布局系统

## 组件

布局组件

|组件|描述|说明|
|---|---|---|
|`Container`|布局容器|`mainAxis` 主轴方向<br>`mainAxisAlignment` 主轴对齐方式<br>`crossAxisAlignment` 交叉轴对齐方式<br>`width` 宽度<br>`height` 高度|
|`Row`|横向布局容器|同上|
|`Column`|纵向布局容器|同上|
|`Expanded`|扩展布局容器|在主轴方向上自动填充剩余空间|
|`Center`|居中布局容器|水平垂直居中布局|
|`Stack`|层叠（绝对定位）布局容器|`left` 左<br>`top` 上<br>`right` 右<br>`bottom` 下<br>`zIndex` 层级|
|`ScrollView`|列表容器|可滚动容器|
|`GridView`|栅格容器|未定|

功能组件

|组件|描述|说明|
|---|---|---|
|`Text`|文本|`color` 颜色<br>`fontSize` 字号<br>`lineHeight` 行高<br>`textAlign` 文本对齐|
|`Image`|图片|`src` 链接<br>`fit` 图片自适应|
|`BoxDecoration`|修饰容器|`color` 背景色<br>`image` 背景图<br>`borderRadius` 圆角<br>`boxShadow` 阴影<br>`gradient` 渐变<br>`opacity` 透明度<br>`padding` 内边距<br>`margin` 外边距<br>`border` 边框<br>|

> 部分参考flutter布局系统