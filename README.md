# IBEEM项目技术文档

> [README.md](https://github.com/BaoYu0721/ibeem/blob/master/README.md)

IBEEM项目主要实现环境监测设备\(coclean设备和ibeem设备\)的管理, 以及设备监测数据展示. 在技术方面采用阿里[_** egg框架 **_](https://eggjs.org/zh-cn), 用mysql作为数据库, 在进程数据同步方面采用 [_**redlock锁 **_](https://github.com/mike-marcacci/node-redlock)机制

