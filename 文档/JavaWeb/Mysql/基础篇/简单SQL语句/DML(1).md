﻿DML用来对数据库中表的数据记录进行增删改操作

### 增加数据
---
```
INSERT INTO 表名 (字段1, 字段2, 字段3, ...)//给全部数据添加可省略字段名
VALUES (值1, 值2, 值3, ...),(值1, 值2, 值3, ...);
```
### 修改数据
---

```
update 表名 set 字段名1 = 值1 , 字段名2 = 值2 , .... [where 条件] ;
```

### 删除数据
---

```
delete from 表名  [where  条件] ;//DELETE 语句的条件可以有，也可以没有，如果没有条件，则会删除整张表的所有数据
```