QQ交流群340195342，点击加入：http://jq.qq.com/?_wv=1027&k=2ADNTk3
======

快速上手
======
1. 下载bftrader发布包
下载地址: https://github.com/sunwangme/bftrader/releases
下载地址: http://pan.baidu.com/s/1nvgrNst
运行ctpgateway，点击ctp/ctpConfig配置好ctp账号

2. 安装grpc for python
   2.1 安装python-2.7.11.msi (https://www.python.org/ftp/python/2.7.11/python-2.7.11.msi)
   2.2 安装grpcio库：pip install "grpcio>=0.15.0"
   2.3 装了老版本的，可以升级：pip install grpcio --upgrade

3. 写策略，调试策略，运行策略
    3.1 运行ctpgateway.exe,datafeed.exe
    3.2 点击ctpgateway的net/netStart,点击datafeed的net/netStart
    3.3 运行datarecorder.py，以连接ctpgateway datafeed
    3.4 点击ctpgateway的ctp/ctpStart
    3.5 可以看到datarecorder.py跑起来啦

    
网友策略列表
======
datarecorder.py：tick收集器，演示BfTraderClient+BfRun的用法
z++/: 1分钟方向策略
xiaoge/: 1分钟动力策略
xiaoge/multi-period: 多周期多品种的数据收集器
oneywang/：1分钟方向策略
bluesky/：1分钟方向策略
bingdian/：1分钟方向策略
sunwangme/: grpc例子
tao/: 1分钟方向策略
twelvedays/simplepower/:简单震荡策略


（完）
