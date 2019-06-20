# UnblockNetEaseMusic 海外网易云音乐代理

目前本服务运行于日本 Cloudcore 服务器

#### 服务器信息
`158.199.142.239 music.163.com`

#### 使用方法

* Windows:(未测试)
  打开命令提示符（管理员权限），执行该命令

  `echo 158.199.142.239 music.163.com >> C:\WINDOWS\System32\drivers\etc\hosts`

* Mac
  打开`终端`

  `sudo bash -c 'echo "158.199.142.239 music.163.com" >> /etc/hosts'`

* iPhone

  * Shadowrocket (无需使用中国大陆境内代理节点)

    `配置` - `添加` - 添加以下 URL 配置文件，并切换至该配置文件

    `https://raw.githubusercontent.com/sarkrui/unblock-NetEaseMusic/master/CloudMusic.conf`
