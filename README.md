## 级联选择插件
一个基础的级联选择插件，可适配大多数场景使用。



## 目录
- [配置项说明](#user-content-配置项说明)
- [使用方法](#Usage)
- [模板 DOM 结构](#dom)



## 配置项说明

``` javascript
var defaults = {
  data: [], // 列表项数组，每个数组元素代表了一个列表项的数据集
  domTag: ['ul', 'li'],
  dataKeys: ['id', 'name'],
  responseField: 'data',  // 异步请求数据源返回数据字段
  defaultActiveData: [], // 默认选中激活项 [...id]，依次对应每个层级
  wrapperClass: 'cascade-list-wrapper',
  wrapperActiveClass: 'cascade-list-wrapper-active',
  listClass: 'cascade-list',
  listActiveClass: 'cascade-list-active',
  itemClass: 'cascade-list-item',
  itemActiveClass: 'cascade-list-item-active',
  onChange: undefined,
  afterRender: undefined,
  referenceKey: '', // 默认取 dataKeys 的第一项
  queryKey: '',     // 接口查询字段
  isRendered: false
};
```

### data 数据源配置项

### domTag

### dataKeys

### responseField

### defaultActiveData

### wrapperClass

### wrapperActiveClass

 ### listClass

### listActiveClass

### queryKey

### onChange

### afterRender



