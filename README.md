# AttributeSql
联系方式：QQ 648808699；  
c#开发，基于.net core 依赖注入的方式添加服务,方便快捷；  
特性sql,基于model上添加特性的方式，通过特定的扩展方式将特性的配置转换成sql语句，便于查询的扩展以及查询条件的动态绑定；  
目前支持Mysql和Sqlserver两种数据库,简单一句调用即可完成数据库初始化:  
services.AddAttributeSqlService(option =>  
{  
    option.UseMysql(connStr);  
});  
具体的查询方式以及版本的修改情况在demo的文档有说明；  
