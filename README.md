#route
resetful 网站的本质就是提供资源访问
url => 资源 一一对应关系
?queryString1=a&queryString2=b

backend 来做 路由规则 route
mvc 解析url，映射一个route 跟后端脚本对应的controller
/book/123456
现在后台已经是 /api

fontend 接管一切？
跟服务器相关性
url => 资源 缺点，http
href 刷新页面 用户体验不ok PC时代
https://m.taobao.com/#index 前端url
https://m.taobao.com/#home  
html5 historyAPI
前端url 切换一张小卡片
整个页面都没有动，单页应用 SPA
SinglePageApplication
(要构建现代前端的用户体验，即单页应用，来代替需要重新访问的前端页面)
动态更新界面？ 前端url规则 启动，交给ajax
vue？ url => page => 组件
/book/123123