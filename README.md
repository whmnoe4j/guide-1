# guide
    电子商城导购系统

### 在线演示地址：<http://www.yuyouzheng.top:8080/guide/>
* 测试角色：测试用户用户名及密码: 管理员1/1  维护员2/2  操作员3/3

### 功能简介: 
1, 支持商品展示, 查看详情
2, 支持按名称或按品牌查询商品
3, 支持后台对用户, 商品等信息的管理
4, 支持添加商品时进行图片上传和修改
5, 支持用户权限划分, 不同用户权限不同
6, 支持其他具体功能, 此处不尽言表


数据库表: 用户表(user), 角色表(position), 商品表(goods), 品牌表(brand), 类目表(category)


开发环境: eclipse + jdk1.7 + tomcat7 + mysql5


使用框架: struts2.3.4 + jdbc + fileupload


注意事项: 
1、 运行项目前请确认db.properties配置文件中的数据库连接参数是否正确
2、 如果打开properties文件出现乱码情况, 将此文件编码设为utf-8即可
3、 请保证数据库默认编码为utf8, 否则可能会出现中文乱码或其他字符问题
