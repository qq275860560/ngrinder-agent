[TOC]
ngrinder子节点

# 适用场景
适用于开发测试环境

# 功能
## ngrinder子节点


# 使用方式
## 安装

```
docker pull qq275860560/ngrinder-agent
```

## 启动
 
```
docker run -d  \
-v /tmp:/tmp \
-e NGRINDER_AGENT_HOME=/tmp/ngrinder-agent \
--name ngrinder-agent \
--hostname ngrinder-agent \
qq275860560/ngrinder-agent \
/etc/rc.d \
127.0.0.1:80 

```

# 温馨提醒

* 此项目将会长期维护，增加或改进实用的功能
* 右上角点击star，给我继续前进的动力,谢谢