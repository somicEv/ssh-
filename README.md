# ssh_shopping_mall #
基于SSH的商城项目

## 项目简介 ##
  项目采用传统的MVC分层体系结构，使用Struts+Spring+Hibernate作为架构，采用前后端分离开发方式。
## 项目所选技术栈 ##
前端：HTML+CSS+jquery 

后端：Struts+Spring+Hibernate

数据库：MySql 
 
其他：
	
	- 邮件相关：JavaMail
	- 数据库连接池：c3p0
	- 图片上传：Struts2自带的图片上传功能
## 项目结构 ##
### [前台] ###

**用户模块.**

	注册:
	* 完成JS非空校验.
	* 完成Struts2数据校验
	* 使用AJAX校验用户名是否存在.
	* 发送激活邮件.
	* 生成验证码程序.
	激活:
	* 点击邮件中连接地址,对用户进行激活.
	登录:
	* 数据校验.
	* 激活后的用户才可以进行登录.
	* 验证码程序.
	退出:
	* 销毁session.
**首页分类模块:**

	查询一级分类:显示到菜单位置，并关联二级分类.
	
**首页商品模块**:
	
	查询热门商品:
	* 检索10个热门商品.
	查询最新商品:
	* 检索10个最新商品.(按时间排序)
	根据分类查询商品:
	* 根据分类的ID检索商品.
	* 对商品显示的时候,分页显示.
	根据商品ID检索商品:
	* 显示商品详情.

### [购物模块] ###

	添加到购物车:
	* 将购物项添加到购物车.
	* 如果购物项已经存在在购物车中,那么数量和小计需要增加.
	* 如果购物项没有在购物车中,添加一个新的购物项.
	清空购物车:
	* 将购物车中所有的购物项,清空.
	从购物车中移除:
	* 将某一个购物项从购物车中移除.

### [订单模块] ###
	
	保存订单:
	* 数据从购物车中获取.
	显示某个订单:
	* 根据订单ID检索订单.
	查询我的订单:
	* 根据用户ID检索订单.


### [后台] ###

**用户模块**
	
	对用户信息进行管理(增删改查)
**一级分类模块**
	
	对一级分类信息进行管理(增删改查)
**商品模块**
	
	对商品信息进行管理(增删改查)
	修改商品图片，上传新的图片

**订单模块**
	
	对订单信息进行管理(增删改查)
	




