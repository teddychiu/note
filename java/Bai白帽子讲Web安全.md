
### 风险分析

除了造成损失的大小,还需要考虑到发生的可能性

#### 设计安全方案
生产环境设置允许安装的软件列表
设置"白名单"要比"黑名单",更能保障系统的安全性

最低权限原则:需要梳理系统中所存在的权限,设置账户的权限集合


## 浏览器安全
### 同源策略

<script/>,<img/>,<iframe/>,<link/> 这些带有 src属性的标签是可以跨域加载资源的,而不受同源策略的影响
不同于 XMLHttpRequest,通过src加载的资源,浏览器限制了JavaScript的权限,使其不能读/写返回的内容

除了DOM/Cookie/XMLHttpRequest会受到同源策略的限制,浏览器的插件,Flash,Jave Applet,Silverlight,Google Gears等都有自己的控制策略

### 风险
当前的浏览器各种插件中可能存在,自身的增强

## 跨站脚本攻击想 XSS
