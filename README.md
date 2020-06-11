# BLMS-CN
BLMS CN final version
这是BooksLendingManagementSystem（BLMS）的中文最终版本。

使用步骤：

1.将book.sql导入PHPmyadmin中

2.在Base/conf.php中修改您的数据库链接

3.管理员账号为10086，密码为admin

4.现有两个用户账号，
一个是小组成员试用，账号为10000，密码为123456
   
另一个为用户体验（现已升级为管理员账号），账号为10011，密码为123456


*本系统采用MVC框架，使用了smarty模板引擎、Bootstrap和JQuery
*用户登录ID将由管理员分发
*用户登录目前可进行的操作有：图书查询、信息修改、账户挂失、图书续借和密码修改
*借还操作只可由管理员进行
*管理员除了包含用户所有权限外，还可对图书、用户进行增删改查
