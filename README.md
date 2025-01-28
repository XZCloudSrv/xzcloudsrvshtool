# 小战云Linux工具箱
[![GitHub license](https://img.shields.io/badge/license-MPL%202.0-blue.svg)](https://github.com/yourusername/yourrepository/blob/main/LICENSE)![Shell](https://img.shields.io/badge/shell-bash%205.0-green)

小战云Linux工具箱是一款专为Linux服务器管理设计的高效工具，提供简单易用的菜单式操作界面，帮助用户快速完成复杂的系统管理和优化任务。**完全免费，纯净无后门**，是服务器管理者的得力助手[^8^][^10^]！

## 🚀 小战云Linux工具箱——服务器管理的利器！

小战云Linux工具箱集成了系统操作、网络管理、硬盘管理、服务器优化等多种功能，适合从新手到资深运维人员的各类用户。无论您是需要快速配置服务器，还是进行日常维护和优化，小战云Linux工具箱都能满足您的需求[^8^][^10^]！

![演示图片](https://doc.78san.top/Screenshot_2025-01-21-10-38-38-71_61c78dc80ee02b53007c815fefe993e3.jpg)

## 功能菜单

### 1. 系统操作菜单（最后更新：2024/7/7）
- **一键重启服务器**：快速重启服务器以应用更改或解决故障[^8^]。
- **一键修改密码**：修改当前用户的密码[^8^]。
- **一键同步上海时间**：将服务器时间同步至上海时区[^8^]。
- **一键修改SSH端口**：更改SSH服务的默认端口以增强安全性[^8^]。
- **一键修改DNS**：自定义DNS服务器设置[^8^]。
- **一键开启/关闭SSH登录**：控制SSH服务的启动和停止[^8^]。
- **一键更新系统**：支持CentOS、Ubuntu和Debian系统的更新[^8^]。
- **一键更换系统源**：快速切换为阿里云等镜像源[^8^]。
- **一键创建子用户或管理员**：添加新用户并可设置为管理员[^8^]。
- **一键查看当前与服务器连接的IP**：显示当前连接到服务器的IP地址[^8^]。
- **一键修改服务器主机名**：更改服务器的主机名[^8^]。

### 2. 网络操作菜单（最后更新：2024/7/7）
- **一键重启网卡**：重启网络接口以解决网络问题[^8^]。
- **一键开启/关闭Ping**：控制是否允许Ping请求[^8^]。
- **一键绑定附加IP**：为服务器绑定额外的IP地址[^8^]。
- **一键查看服务器地理位置**：显示服务器的地理位置信息[^8^]。
- **一键查看服务器IP原生地址**：显示服务器的真实IP地址[^8^]。
- **一键查看服务器配置信息**：显示CPU、内存、硬盘等信息[^8^]。
- **一键检测服务器是否屏蔽UDP**：检测UDP端口是否被屏蔽[^8^]。
- **一键VPS的IP映射至独立服务器**：设置端口转发[^8^]。
- **一键关闭VPS的IP映射**：关闭端口转发[^8^]。
- **一键开启/关闭四层端口转发**：管理端口转发规则[^8^]。
- **一键查看服务器在使用的端口**：显示当前监听的端口[^8^]。
- **一键查看什么IP在跑带宽**：显示占用带宽的IP地址[^8^]。

### 3. 硬盘大全菜单（最后更新：2024/7/7）
- **一键上传文件到远程服务器**：将本地文件上传到远程服务器[^8^]。
- **一键从远程服务器下载文件**：从远程服务器下载文件[^8^]。
- **一键查看所有硬盘分区信息**：显示硬盘分区信息[^8^]。
- **一键自定义挂载数据盘**：挂载数据盘到指定目录[^8^]。
- **一键自定义卸载数据盘**：卸载已挂载的数据盘[^8^]。
- **一键自定义格式化数据盘**：格式化硬盘分区[^8^]。
- **一键修复硬盘分区超级坏块**：修复硬盘分区的坏块[^8^]。
- **一键设置开机启动脚本**：设置自定义的开机脚本[^8^]。
- **一键查询关键词文件内容**：搜索包含特定关键词的文件[^8^]。
- **一键查看SSH历史输入命令**：查看SSH历史命令[^8^]。
- **一键清空SSH历史输入命令**：清空SSH历史记录[^8^]。

### 4. 其他操作菜单（最后更新：2024/6/7）
- **一键测试带宽网速**：测试服务器的网络带宽[^8^]。
- **一键测试回程路由**：测试回程路由信息[^8^]。
- **一键安装宝塔面板**：支持CentOS、Ubuntu和Debian系统[^8^]。
- **一键安装彩虹Kangle**：安装彩虹Kangle服务器软件[^8^]。
- **一键安装魔方云CentOS版**：安装魔方云管理工具[^8^]。
- **一键安装宝塔WAF**：安装宝塔Web应用防火墙[^8^]。

### 5. 服务器压榨菜单（最后更新：2024/6/7）
- **一键开启云服务器虚拟化**：启用嵌套虚拟化功能[^8^]。
- **一键自定义设置SWAP虚拟内存**：自定义SWAP空间大小[^8^]。
- **一键关闭SWAP虚拟内存**：关闭SWAP空间[^8^]。
- **一键开启/关闭KSM内存回收**：管理KSM内存优化功能[^8^]。
- **一键关闭SELinux**：禁用SELinux以减少限制[^8^]。

## 安装方法

推荐使用以下命令下载并安装小战云Linux工具箱：

```bash
if [ -f /usr/bin/curl ]; then curl -sSL https://file.78san.top/shell/sanlinux.sh -o sanlinux.sh; else wget -O sanlinux.sh https://file.78san.top/shell/sanlinux.sh; fi && chmod +x sanlinux.sh && bash sanlinux.sh
```
```python
print("Hello, World!")
```
## 赞助

如果你愿意赞助我元子 我将感激涕零

![VX](https://doc.78san.top/mm_reward_qrcode_1737686767408.png)
![ZFB](https://doc.78san.top/1737460003694.jpg )

## 联系开源作者

感谢您对开源项目的关注！如果您有任何问题、建议或想参与项目开发，可以通过以下方式联系我们：

## QQ群
- **加入QQ群**：扫描下方二维码加入项目QQ群，与其他开发者交流。
  - ![QQ群二维码](https://doc.78san.top/qrcode_1737686273167.jpg)  
    （QQ群号：1029151728）

## Telegram
- **Telegram**：通过以下链接可以跟作者联系以及反馈bug。
  - [Telegram](https://t.me/Sanxiaozhan886)

## Telegram频道
- **关注Telegram频道**：通过以下链接关注我们的Telegram频道，获取项目最新动态。
  - [Telegram频道](https://t.me/SAN869CN)
