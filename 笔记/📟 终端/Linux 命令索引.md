# Linux 命令索引

#unix #linux #终端

## 文件管理

| 文档状态 | 命令 | 简介 |
| --------- | ----| ----- |
| 正常 | [cd 变更目录](cd%20%E5%8F%98%E6%9B%B4%E7%9B%AE%E5%BD%95.md) | 变更当前 **工作目录** 的位置 |
| 正常 | [cp 复制](cp%20%E5%A4%8D%E5%88%B6.md) | 把文件复制到别的地方 |
| 正常 | [file 获取文件信息](file%20%E8%8E%B7%E5%8F%96%E6%96%87%E4%BB%B6%E4%BF%A1%E6%81%AF.md) | 获取文件的信息、编码、格式、大小等等信息 |
| 正常 | [find 查找](find%20%E6%9F%A5%E6%89%BE.md) | 查找文件和目录 |
| 正常 | [ls 列出文件](ls%20%E5%88%97%E5%87%BA%E6%96%87%E4%BB%B6.md) | 看到当前 **工作目录** 下的目录和文件 |
| 正常 | [mkdir 创建目录](mkdir%20%E5%88%9B%E5%BB%BA%E7%9B%AE%E5%BD%95.md) | 创建目录 |
| 正常 | [mv 剪贴、移动](mv%20%E5%89%AA%E8%B4%B4%E3%80%81%E7%A7%BB%E5%8A%A8.md) | 把文件移动到别的地方（重命名） |
| 正常 | [rm 移除文件](rm%20%E7%A7%BB%E9%99%A4%E6%96%87%E4%BB%B6.md) | 删除文件或者目录 |
| 正常 | [touch 创建文件](touch%20%E5%88%9B%E5%BB%BA%E6%96%87%E4%BB%B6.md) | 修改文件或者目录的时间属性，若文件不存在，系统会建立一个新的文件 |
| 正常 | [tree 树状图列出文件](tree%20%E6%A0%91%E7%8A%B6%E5%9B%BE%E5%88%97%E5%87%BA%E6%96%87%E4%BB%B6.md) | 以树状图列出目录的内容 |
| 正常 | [which where 获取命令对应的可执行文件](which%20where%20%E8%8E%B7%E5%8F%96%E5%91%BD%E4%BB%A4%E5%AF%B9%E5%BA%94%E7%9A%84%E5%8F%AF%E6%89%A7%E8%A1%8C%E6%96%87%E4%BB%B6.md) | 获取可执行命令的具体位置 |

## 文档读写

| 文档状态 | 命令 | 简介 |
| --------- | ----| ----- |
| 正常 | [cat 输出文件](cat%20%E8%BE%93%E5%87%BA%E6%96%87%E4%BB%B6.md) | 把任何文件的内容以文本形式输出到命令行上 |
| 施工中 | [🚧  grep 查找文件](%F0%9F%9A%A7%20%20grep%20%E6%9F%A5%E6%89%BE%E6%96%87%E4%BB%B6.md) | |
| 施工中 | [🚧  head 文件首部](%F0%9F%9A%A7%20%20head%20%E6%96%87%E4%BB%B6%E9%A6%96%E9%83%A8.md) | |
| 施工中 | [🚧  tail 文件追踪](%F0%9F%9A%A7%20%20tail%20%E6%96%87%E4%BB%B6%E8%BF%BD%E8%B8%AA.md) | |

## 权限管理

| 文档状态 | 命令 | 简介 |
| --------- | ----| ----- |
| 正常 | [chown 变更所属权](chown%20%E5%8F%98%E6%9B%B4%E6%89%80%E5%B1%9E%E6%9D%83.md) | 设置文件所有者和文件关联组 |
| 正常 | [chmod 变更权限](chmod%20%E5%8F%98%E6%9B%B4%E6%9D%83%E9%99%90.md) | 控制用户对文件的权限 |
| 施工中 | [🚧  chgrp 变更所属群组](%F0%9F%9A%A7%20%20chgrp%20%E5%8F%98%E6%9B%B4%E6%89%80%E5%B1%9E%E7%BE%A4%E7%BB%84.md) | |
| 施工中 | [🚧  groupadd 创建用户组](%F0%9F%9A%A7%20%20groupadd%20%E5%88%9B%E5%BB%BA%E7%94%A8%E6%88%B7%E7%BB%84.md) | |
| 施工中 | [🚧  setsebool 配置 SELinux 参数](%F0%9F%9A%A7%20%20setsebool%20%E9%85%8D%E7%BD%AE%20SELinux%20%E5%8F%82%E6%95%B0.md) | |
| 施工中 | [🚧  useradd 创建用户](%F0%9F%9A%A7%20%20useradd%20%E5%88%9B%E5%BB%BA%E7%94%A8%E6%88%B7.md) | |
| 施工中 | [🚧  usermod 变更用户](%F0%9F%9A%A7%20%20usermod%20%E5%8F%98%E6%9B%B4%E7%94%A8%E6%88%B7.md) | |

## 网络通讯

| 文档状态 | 命令 | 简介 |
| --------- | ----| ----- |
| 施工中 | [🚧  dig DNS 查询](%F0%9F%9A%A7%20%20dig%20DNS%20%E6%9F%A5%E8%AF%A2.md) | |
| 施工中 | [🚧  firewalld 防火墙配置](%F0%9F%9A%A7%20%20firewalld%20%E9%98%B2%E7%81%AB%E5%A2%99%E9%85%8D%E7%BD%AE.md) | |
| 施工中 | [🚧  iptables 防火墙配置](%F0%9F%9A%A7%20%20iptables%20%E9%98%B2%E7%81%AB%E5%A2%99%E9%85%8D%E7%BD%AE.md) | |
| 施工中 | [🚧  ifconfig 网络配置](%F0%9F%9A%A7%20%20ifconfig%20%E7%BD%91%E7%BB%9C%E9%85%8D%E7%BD%AE.md) | |
| 施工中 | [🚧  ip 网络配置](%F0%9F%9A%A7%20%20ip%20%E7%BD%91%E7%BB%9C%E9%85%8D%E7%BD%AE.md) | |
| 施工中 | [🚧  nc 网络读写](%F0%9F%9A%A7%20%20nc%20%E7%BD%91%E7%BB%9C%E8%AF%BB%E5%86%99.md) | |
| 施工中 | [🚧  netstat 网络状态](%F0%9F%9A%A7%20%20netstat%20%E7%BD%91%E7%BB%9C%E7%8A%B6%E6%80%81.md)| |
| 施工中 | [🚧  nslookup DNS 查询](%F0%9F%9A%A7%20%20nslookup%20DNS%20%E6%9F%A5%E8%AF%A2.md) | |
| 施工中 | [🚧  ping 检测连通性](%F0%9F%9A%A7%20%20ping%20%E6%A3%80%E6%B5%8B%E8%BF%9E%E9%80%9A%E6%80%A7.md) | |
| 施工中 | [🚧  telnet 远端访问](%F0%9F%9A%A7%20%20telnet%20%E8%BF%9C%E7%AB%AF%E8%AE%BF%E9%97%AE.md) | |
| 施工中 | [🚧  traceroute 数据包追踪](%F0%9F%9A%A7%20%20traceroute%20%E6%95%B0%E6%8D%AE%E5%8C%85%E8%BF%BD%E8%B8%AA.md) | |

## 系统设置

| 文档状态 | 命令 | 简介 |
| --------- | ----| ----- |
| 施工中 | [🚧  export 设置环境变量](%F0%9F%9A%A7%20%20export%20%E8%AE%BE%E7%BD%AE%E7%8E%AF%E5%A2%83%E5%8F%98%E9%87%8F.md) | |
| 施工中 | [🚧  set 设置 shell](%F0%9F%9A%A7%20%20set%20%E8%AE%BE%E7%BD%AE%20shell.md) | |
| 施工中 | [🚧  unset 删除变量或函数](%F0%9F%9A%A7%20%20unset%20%E5%88%A0%E9%99%A4%E5%8F%98%E9%87%8F%E6%88%96%E5%87%BD%E6%95%B0.md) | |

## 系统管理

| 文档状态 | 命令 | 简介 |
| --------- | ----| ----- |
| 正常 | [ps 进程状态](ps%20%E8%BF%9B%E7%A8%8B%E7%8A%B6%E6%80%81.md) | 显示当前进程的状态，类似于 windows 的任务管理器中「程序」列表 |
| 施工中 | [🚧  systemctl 服务管理](%F0%9F%9A%A7%20%20systemctl%20%E6%9C%8D%E5%8A%A1%E7%AE%A1%E7%90%86.md) | |
| 施工中 | [🚧  kill 进程终止（基于 PID）](%F0%9F%9A%A7%20%20kill%20%E8%BF%9B%E7%A8%8B%E7%BB%88%E6%AD%A2%EF%BC%88%E5%9F%BA%E4%BA%8E%20PID%EF%BC%89.md) | |
| 施工中 | [🚧  killall 进程终止（基于进程名）](%F0%9F%9A%A7%20%20killall%20%E8%BF%9B%E7%A8%8B%E7%BB%88%E6%AD%A2%EF%BC%88%E5%9F%BA%E4%BA%8E%E8%BF%9B%E7%A8%8B%E5%90%8D%EF%BC%89.md) | |
| 施工中 | [🚧  top htop bpytop 任务管理器](%F0%9F%9A%A7%20%20top%20htop%20bpytop%20%E4%BB%BB%E5%8A%A1%E7%AE%A1%E7%90%86%E5%99%A8.md) | |

## 磁盘管理

| 文档状态 | 命令 | 简介 |
| --------- | ----| ----- |
| 施工中 | [🚧  dd 转换与输出（镜像）](%F0%9F%9A%A7%20%20dd%20%E8%BD%AC%E6%8D%A2%E4%B8%8E%E8%BE%93%E5%87%BA%EF%BC%88%E9%95%9C%E5%83%8F%EF%BC%89.md) | |
| 施工中 | [🚧  fdisk 分区管理](%F0%9F%9A%A7%20%20fdisk%20%E5%88%86%E5%8C%BA%E7%AE%A1%E7%90%86.md) | |
| 施工中 | [🚧  mkswap 创建虚拟内存](%F0%9F%9A%A7%20%20mkswap%20%E5%88%9B%E5%BB%BA%E8%99%9A%E6%8B%9F%E5%86%85%E5%AD%98.md) | |
| 施工中 | [🚧  swapoff 关闭虚拟内存](%F0%9F%9A%A7%20%20swapoff%20%E5%85%B3%E9%97%AD%E8%99%9A%E6%8B%9F%E5%86%85%E5%AD%98.md) | |
| 施工中 | [🚧  swapon 激活虚拟内存](%F0%9F%9A%A7%20%20swapon%20%E6%BF%80%E6%B4%BB%E8%99%9A%E6%8B%9F%E5%86%85%E5%AD%98.md) | |