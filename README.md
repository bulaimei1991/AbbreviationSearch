# AbbreviationSearch
用于查询英文缩写词的全拼及其对应注释说明。

基础功能：
1.对缩写/全写的增删改查。
2.对查询结果的hot排序。
3.60秒内不可重复提交hot。
4.多人对提交内容审核通过，通过之后上库。
5.模糊搜索功能

部署方式：
1.所有组件基于docker部署，包括ngnix/mysql/redis。
