# 第13章 数据库支持


Python Database API Specification v2.0


* apilevel: 版本
* threadsafety: 线程安全
* paramstyle: 参数风格

### 函数

* connect: 连接数据库
* close: 关闭连接
* commit: 提交事务
* rollback: 回滚事务
* cursor: 返回连接的游标对象


游标对象: 通过游标执行SQL查询并检查结果

### pysqlite

	import sqlite3
	conn = sqlite3.connect('xxx.db')