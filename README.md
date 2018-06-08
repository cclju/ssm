# SSM
整合SSM框架：SpringMVC + Spring + MyBatis

注意：

1）java连接mysql数据库8.0以上版本过程中遇到的坑
mysql8.0和之前版本的区别，驱动换了，不是'com.mysql.jdbc.Driver'而是'com.mysql.cj.jdbc.Driver'

2）controller测试，测试appoint方法可不必写jsp，用curl就行，比如
curl -H "Accept: application/json; charset=utf-8" -d "studentId=1234567890" localhost:8080/book/1003/appoint
