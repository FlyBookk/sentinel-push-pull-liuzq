#springboot接入sentinel案例
1.sentinel-jar包下有一个sentinel的dashboard包,端口已经修改为8099,避免后期跟apollo接入做持久化时,端口冲突

2.运行方式 java -jar sentinel-dashboard-1.7.1.jar

3.本案例的动态规则及监控数据均使用默认的内存缓存模式,所以数据会在项目重启或一段时间后消失(持久化操作后期再进行更新)

