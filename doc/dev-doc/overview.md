# Overview
## 一、 特性  
    1. 一个调度节点(dispatch node)，多个计算节点(calculate node).  
    2. 通信协议包含两个方面:节点之间的通信，服务与客户端之间的通信.  
    3. 提供客户端命令行方式的操作.   
    4. 一个服务可以接受多个客户端的连接与计算.  
    5. 支持多账户权限和优先级配置,默认提供root账号.  
    
## 二、 拓扑结构  
    
    
## 三、 服务端命令
yd  [-command]

command list  
    -start      启动yuandao服务器  
    -restart    重启yuandao服务器  
    -reload     重新加载yuandao配置文件  
    -stop       安全停止yuandao服务器  
    
## 四、 客户端命令
yd [-command] [-options]  

command list  