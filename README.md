# 各种实用脚本


## 脚本索引


* [***服务器相关***](#服务器相关)
  * [status.sh](#statussh)
* [***HTTP 相关***](#http相关)
  * [caddy_install.sh](#caddy_installsh)

---

## 服务器相关

## status.sh

- 脚本说明: ServerStatus 一键安装管理脚本
- 系统支持: CentOS6+ / Debian6+ / Ubuntu14+

#### 下载安装:
``` bash
wget -N --no-check-certificate https://raw.githubusercontent.com/rzbfreebird/Script/master/status.sh && chmod +x status.sh && bash status.sh
```

---

## HTTP相关

## caddy_install.sh

- 脚本说明: Caddy 一键安装脚本
- 系统支持: CentOS6+ / Debian7+ / Ubuntu14+

#### 下载安装:
``` bash
wget -N --no-check-certificate https://raw.githubusercontent.com/rzbfreebird/Script/master/caddy_install.sh && chmod +x caddy_install.sh && bash caddy_install.sh
 # 安装插件：
 bash caddy_install.sh xxx,xxx
  # 例如同时安装 http.filemanager 和 http.webdav插件：
  bash caddy_install.sh http.filemanager,http.webdav
  # 插件和Caddy是集成在一起的(单个二进制文件)，多个插件必须同时安装。
# 卸载命令：
wget -N --no-check-certificate https://raw.githubusercontent.com/rzbfreebird/Script/master/caddy_install.sh && chmod +x caddy_install.sh && caddy_install.sh uninstall
```


---
