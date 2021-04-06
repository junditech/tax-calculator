# 房地产税费计算器

JDTax是一款应用于房地产行业的税费计算器小程序，适用于中介、有税费计算需求的人员。

* 计算器客户端使用小程序开发、
* 后台管理采用采用Vue、Element UI、Spring Boot、MyBatis & MyBatisPlus。
* 安全框架采用Spring Security & Jwt。
* 权限认证使用Jwt，支持多终端认证系统。
* 缓存采用Redis
* 数据库采用MySQL
* 支持加载动态权限菜单，多方式轻松权限控制。
* 支持微信小程序会员功能。
* 支持动态计算规则，采用表达式实现自定义计算公式。
* 基于[RuoYi-Vue-Plus](https://gitee.com/JavaLionLi/RuoYi-Vue-Plus)开发

## 特色功能
1.  计算字段：配置需要参与计算的字段信息
2.  计算项目：配置税费计算项目树，以及设置计算项目提供的字段信息，以便小程序端输入。
3.  计算公式：根据计算项目配置的字段信息，配置计算公式以达到动态配置计算规则的目的。
4.  会员信息：支持微信小程序登录
5.  问题反馈：收录小程序端用户提交的反馈信息，支持图片上传
6.  会员计算历史：用户可以保存计算历史

## 基础功能
1.  用户管理：用户是系统操作者，该功能主要完成系统用户配置。
2.  部门管理：配置系统组织机构（公司、部门、小组），树结构展现支持数据权限。
3.  岗位管理：配置系统用户所属担任职务。
4.  菜单管理：配置系统菜单，操作权限，按钮权限标识等。
5.  角色管理：角色菜单权限分配、设置角色按机构进行数据范围权限划分。
6.  字典管理：对系统中经常使用的一些较为固定的数据进行维护。
7.  参数管理：对系统动态配置常用参数。
8.  通知公告：系统通知公告信息发布维护。
9.  操作日志：系统正常操作日志记录和查询；系统异常信息日志记录和查询。
10. 登录日志：系统登录日志记录查询包含登录异常。
