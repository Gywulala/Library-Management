# 基本情况

前端：BootCamp+JQuery 
后端：Spring

#技术栈
（后）
1、采用java的Spring MVC框架，利用其分层特性减少代码耦合性，并行开发；
2、加入象关系映射框架Hibernate,与mySQL数据库建立映射关系，同时利用对数据库兼容性较高的HQL语句对数据库进行增、删、改、查；
3、shior作为安全框架，对请求进行认证，授权，加密，会话管理，达到分权登录及过滤游客目的；
4、采用前后端不分离方式，引入thymeleaf模板，对.html格式的View层服务；

（前）
1、bootstrap作为css样式框架，搭建pc端自适应网页（暂不考虑移动端与浏览器兼容性）；
2、echarts进行数据可视化，丰富页面视觉效果；
3、主要采用ajax与后台进行数据交互，实现局部刷新效果（无需跨域请求）；
