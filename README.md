## 使用方法

在VPS上安装好node以及npm。

首先安装npm包

``` bash
npm install
```

进入代码根路径:

``` bash
#启动程序，默认端口3000
nohup npm start &
```

结束进程

```bash
ps -ef | grep "node"
kill [pid]
```
