---
title:
date: 2019-03-05 11:17:00
categories:
- Java
tags:
- mysql,oracle
---

```

//mysql
1.
SELECT
  table_name
FROM
  information_schema.tables
WHERE table_schema = 'ry'
  AND table_type = 'base table' ;
2.
SELECT
	*
FROM
	information_schema. COLUMNS
WHERE
	table_name = 'sys_menu';

//oracle
1.select table_name from user_tables;
2.select * from user_tab_columns where Table_Name='表名';