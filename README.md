# go语言学习笔记

> create by afterloe <lm6289511@gmail.com>  
> version is 0.0.1  
> apache 2.0  

golang 教程 学习笔记&开发日记

golang day08中的项目已经单独立项了，可以关注 https://github.com/afterloe/AwPaas 下的 https://github.com/afterloe/awpaas-manager 项目

* [目录](README.md)
* [第一天](day01/index.md)
    * 变量
    * map & slice
    * make & new 以及默认值
* [第二天](day02/index.md)
    * 函数、流程、goto、循环
    * [结构体 struct](day02/struct.md)
* [第三天](day03/index.md)
    * channel、多线程
    * 反射、匿名函数、interface继承
* [第四天](day04/index.md)
    * 反射的使用
    * 读取、写入文件与json处理
    * 分包分模块使用
* [第五天](day05/index.md)
    * 数据库连接
    * 字符串模板使用，输出流字符串转换
    * interface进阶使用
* [第六天](day06/index.md)
    * http服务之默认路由
    * 自定义路由
    * 文件上传
* [第七天](day07/index.md)
    * 单元测试
    * 压力、性能测试
    * mock 测试
* [第八天](https://github.com/afterloe/awpaas-manager)
    * [构建通用go打包镜像](https://github.com/afterloe/AwPaas/tree/master/awpaas-builder)
    * [构建打包工具打包成docker镜像](https://github.com/afterloe/awpaas-route/blob/master/Makefile)
    * [实战 - 使用gin构建web基础框架](day08_framework.md)
    * 调用docker api 构建一个SOA服务管理平台
    * docker 封装go的服务实现ci
* [第九天（实战） 前置数据网关](https://github.com/afterloe/awpaas-route)
    * SOA前置数据网关
    * 自定义黑白名单
    * 链接docker service 获取服务列表
    * 使用docker swarm 网络实现服务负载均衡
* [第十天（实战） Docker 增量维护](https://github.com/afterloe/awpaas-repository)
    * 链接CouchDB
