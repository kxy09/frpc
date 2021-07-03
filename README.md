# frpc
## 项目简介
基于 [fatedier/frp](https://github.com/fatedier/frp) 原版 frp 内网穿透客户端 frpc 的一键安装卸载脚本.
- GitHub [stilleshan/frpc](https://github.com/stilleshan/frpc)

### Linux 服务器 一键脚本安装
> *本脚本目前同时支持 Linux X86 和 ARM 架构*
> *在脚本原作者基础上添加了armv7支持*

安装
```shell
wget https://raw.githubusercontent.com/kxy09/frpc/master/frpc_linux_install.sh && chmod +x frpc_linux_install.sh && ./frpc_linux_install.sh

```

使用
```shell
vi /usr/local/frp/frpc.ini
# 修改 frpc.ini 配置
sudo systemctl restart frpc
# 重启 frpc 服务即可生效
```

卸载
```shell
wget https://raw.githubusercontent.com/stilleshan/frpc/master/frpc_linux_uninstall.sh && chmod +x frpc_linux_uninstall.sh && ./frpc_linux_uninstall.sh
# 国内 gitee 镜像
wget https://gitee.com/stilleshan/frpc/raw/master/frpc_linux_uninstall.sh && chmod +x frpc_linux_uninstall.sh && ./frpc_linux_uninstall.sh
```

