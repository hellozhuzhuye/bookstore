# bookstore——基于JavaWeb的网上书城系统

## 技术栈

### 1.	JavaSE
### 2.	Linux、Mysql
### 3.	HTML、CSS、JavaScript
### 4.	XML、MVC架构模式、Servlet、Filter、JSP、EL、JSTL、AJAX、代理模式、工厂模式、数据库连接池


## 项目前台功能介绍
  * User模块
    > 注册
    > 激活
    > 登录
    > 修改密码
    > 退出
  * Category模块
    > 显示所有分类
  * Book模块
    > 按分类查询(分页)
    > 按图名查询（模糊）（分页）
    > 按作者查询（分页）
    > 按出版社查询（分页）
    > 按id查询
    > 多条件组合查询（分页）
  * 购物车模块（使用的不是session,也不是cookie，而是表）\
    > 添加购物条目
    > 修改购物条目的数量
    > 删除条目
    > 批量删除条目
    > 我的购物车，即按用户查询条目
    > 查询勾选的条目
  * 订单Order模块
    > 生成订单
    > 我的订单，按用户查询订单
    > 查看订单详细信息
    > 订单支付(发送请求)
    > 订单支付(银行回馈)修改订单状态为“支付成功”
    > 取消订单
    > 确认收货

## 项目后台功能介绍
  * 管理员管理
  * 分类管理
    > 显示所有分类
    > 添加一级分类
    > 修改一级分类
    > 删除一级分类
    > 添加二级分类
    > 修改二级分类
    > 删除二级分类
  * 图书管理
    > 多条件组合查询
    > 添加图书
    > 按分类查询
    > 编辑图书
    > 删除图书
    > 很多与前台相同的查询功能
  * 订单管理
    > 按状态查询
    > 查询订单详细
    > 发货
    > 取消订单
