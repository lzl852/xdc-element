## Breadcrumb 面包屑
显示当前页面的路径，快速返回之前的任意页面。

### 基础用法

适用广泛的基础用法。

:::demo 在`el-breadcrumb`中使用`el-breadcrumb-item`标签表示从首页开始的每一级。Xdc 提供了一个`separator`属性，在`el-breadcrumb`标签中设置它来决定分隔符，它只能是字符串，默认为斜杠`/`。

```html
<el-breadcrumb separator="/">
  <el-breadcrumb-item>首页</el-breadcrumb-item>
  <el-breadcrumb-item>活动管理</el-breadcrumb-item>
  <el-breadcrumb-item>活动列表</el-breadcrumb-item>
  <el-breadcrumb-item>活动详情</el-breadcrumb-item>
</el-breadcrumb>
```
:::

### Attributes
| 参数      | 说明          | 类型      | 可选值                           | 默认值  |
|---------- |-------------- |---------- |--------------------------------  |-------- |
| separator | 分隔符 | string | — | 斜杠'/' |
