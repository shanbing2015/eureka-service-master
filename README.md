
###see服务注册中心

---    
* 版本依赖
    >springCloud:Dalston.SR1     
    springBoot:1.5.2.RELEASE
    
* 环境说明
    >application-*-dev.yml 分别对应不同的服务环境。         
    master和slave 为一对主从服务。分别启动来达到集群，用来支撑生产环境。（需要配置peer1、peer2 对应host地址）           
    single为单机服务，主要用来支撑开发环境。

* 待完善点
   > 服务注册自定义统计监控    
        项目不同环境配置                
        