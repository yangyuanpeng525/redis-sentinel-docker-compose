至少三台服务器
服务器规划：一主、两从，三哨兵
注意;所有redis密码一致，网络使用host
先启动redis主从，在启动哨兵
#
主从编排文件：./docker-compose.yaml
哨兵编排文件：./sentinel/docker-compose.yaml
csdn：https://blog.csdn.net/linux_yyp/article/details/110086876
