1. 查询表user的所有内容
SELECT *FROM user

2.查询大于某值
SELECT *FROM user WHERE score >80

3.查询等于某值
SELECT *FROM user WHERE score = 80

4.查询表中字段中以。。。开头
SELECT *FROM user WHERE score LIKE  "小%"
