# 阅读spark源码的笔记注释

# 各个模块(目录)的说明(从上往下):
## assembly
        Spark项目的一个组装模块
        它创建一个tar.gz文件，其中包括项目所需的所有依赖项除了org.apache.hadoop。文件中应该可用的jar文件部署Hadoop集群。
        这个模块在默认情况下是关闭的。要激活它，请在命令行中指定概要文件 -Pbigtop-dist
        如果需要为不同版本的Hadoop构建程序集，则需要像本例一样设置hadoop版本的系统属性: -Dhadoop.version=2.7.4
## bin
    各种脚本
## build
    项目构建脚本
## common
    主要是spark的通讯框架
## conf
    spark的配置文件(像安装的时候,就需要改这些配置文件)
## core
    spark核心(不做过多介绍)
## data
    各种测试的数据源
## dev
    环境检查模块
## docs
    文件说明模块
## examples
    各种语言使用spark的案例模块
## external
    spark的外部模块
## graphx
    spark图计算引擎
## hadoop-cloud
    Hadoop jar和与云基础设施交互模块
## launcher
    spark代码提交的模块 
## licenses
    spark的许可证
## licenses-binary
    spark的许可证
## mllib
    spark的机器学习库
## mllib-local
    spark的机器学习库(本地)
## project
    
## python
    python接口
## R
    R接口
## repl
    spark的交互式解释器
## resource-managers
    spark的资源管理器(yarn等)
## sbin
    spark的启动停止等脚本
## sql
    不做过多介绍
## streaming
    不做过多介绍
## tools
    工具模块
