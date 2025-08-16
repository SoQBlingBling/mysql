
### 1.介绍
 *SQL（结构化查询语言的简称）是一种编程语言，旨在管理和检索数据库中存储的数据*
 
 ### 2.查询
使用一个名为 `shows` 的表格，其中包含有关热门电视节目的数据。📺
![[base.png]]


共有七列：`id`、`name`、`genre`、`stream`、`year`、`seasons`和`tomatometer`
SQL 语句或查询是数据库可以理解的指令。换句话说，查询允许我们从数据库中检索信息。
``` sql
SElECT  * FROM  shows
```

#### 2.1 选择