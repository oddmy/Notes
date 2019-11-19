| 命令 | 说明 | 备注 |
| ---- | ----|----|
|top | 查看机器负载情况|
|top -H| 查看机器线程情况|
|iotop | 查看机器io使用情况|
|crontab -l | 定时任务列表|
|crontab -e | 编辑定时任务列表|
|crontab -e -u `userName` | 编辑指定用户定时任务列表|
|tail -fn100 `fileName` | 查看文件最后100行，持续更新|
|grep '`content`' `fileName` | 搜索所有content在文件行中内容|
|chown `userName` `fileName`| 更改文件所属用户|
|chgrp `groupName` `fileName`| 更改文件所属组|
