# pullToRefresh

## 说明
* 完整的功能：同时支持"下拉刷新"，"上拉加载"
* 简单的接口：用户仅需提供数据回调函数，框架负责剩余任务
* 参数化配置：用户可自定义"下拉/上拉"的触发位置、图片等，但是默认值通常可以满足需求
* 灵活的设定："下拉/上拉"特性可独立"开启/关闭","上拉加载"特效交由用户订制
 
## 依赖
* iscroll5：兼容各移动平台的滚动条方案
* jquery：高效跨平台的DOM操作

## 实现
* 基于transition实现bounce回弹动画
* 基于anamation实现自旋loading加载动画
* 基于iscroll5滚动事件实现"上拉加载"
* 基于jquery静态函数实现为插件

## 测试
* 微信浏览器
* chrome移动浏览器
* safari浏览器
