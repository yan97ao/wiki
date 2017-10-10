# Neutron

* [深入理解 Neutron -- OpenStack 网络实现](https://yeasy.gitbooks.io/openstack_understand_neutron/)  
兼顾快速入门和深入分析的neutron网络数据面介绍

# Kolla

* [OpenStack Kolla deployment from RDO packages](http://egonzalez.org/page/9/)  
kolla多节点部署

# Rally

* [Rally OpenStack benchmarking from Docker containers](http://egonzalez.org/rally-openstack-benchmarking-from-docker-containers/)  
其实docker尤其适合用作这种随时启动，运行完之后立即抛弃的应用场景，并且可以很好集成在CI/CD的流程中。这篇文章就给出了这么一个在docker容器中使用rally的最佳实践：  
```
创建容器 ==> 挂载外部存储（用于持久化数据） ==> 运行rally任务 ==> 导出结果 ==> 关停容器
```

* [如何使用Rally+Docker测试OpenStack](http://geek.csdn.net/news/detail/67842)  
从头开始（干净的centos 7）构建自己的rally docker image
