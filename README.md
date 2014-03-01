log
===


将配置文件放入conf/ 目录下

log for go project


import (
    logs "github.com/yaotian/logs"
)

logs.Logger.Critical("your critical msg")

logs.Logger.Info("your info msg")


开始使用之前，配置一下log.xml，当发critical log的时候它可以发送邮件
