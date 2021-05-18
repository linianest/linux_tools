# linux_tools
linux 工具脚本


dt.txt 是修改日期脚本

kf.txt 是kafka自动启动停止脚本

xcall 是多台集群同时执行相同命令脚本：
如：xcall jps
里面的3台机器都会执行xcall jps 命令


xsync.txt 文件
是分发脚本,将当前目录的的文件分发到相同目录下，若其他机器已有同名文件，是否是覆盖还是过滤，目前没验证


zk.txt 
zookeeper集群启停脚本
