# Kead


原项目[NoMoreWalls](https://github.com/peasoft/NoMoreWalls) 请优先为该项目 点亮☆


自动抓取合并互联网上的公开节点。

## 公告

**我们拒绝为任何“女权组织”提供任何服务！我们绝不允许任何企图破坏中国国家和社会稳定的组织或个人使用本服务！**

本项目拒绝为**流氓资本家**提供任何服务！特别的，项目的许可证**严格禁止**实行 996 工作制的公司使用本项目！

此项目包含“反 996 许可证”，请各位使用者**不要违法违规要求别人加班，自觉遵守《中华人民共和国劳动法》及其它法律法规**！

**本项目提供的 Clash 订阅包含我们精心设计的分流规则，Google Play 软件秒下 (限国行机)，自动识别被墙域名，只需将 `🐟 漏网之鱼` 维持在 `DIRECT` 即可！**

由于 [BootCDN/Staticfile 已被病毒公司收购](https://www.52pojie.cn/thread-1944970-1-1.html)，我们拦截了这些网站。

如果您访问部分网站时遇到问题，可以将 `🚨 病毒网站` 分类切换为 `DIRECT`，但是您需要**自行承担一切安全风险，包括但不限于广告骚扰，账号被盗，设备中毒**等，请三思而后行！！！

为防止失联，我们建立了镜像：<https://peasoft.github.io/NWalls.html>

另有**理论上永不被墙的** jsDelivr 镜像，**强烈建议**收藏：<https://www.jsdelivr.com/package/gh/peasoft/NoMoreWalls>

我们新增了 [`snippets` 目录](./snippets/) 来存放从 `list.meta.yml` 中拆分出的配置片段，用于将本项目提供的一些配置整合到你自己的配置中。此目录中还有本项目的独立规则集覆写文件。

免费节点的安全无法保障，不建议通过节点访问明文网站，也 [不要用免费节点挖矿](https://www.youtube.com/watch?v=5Uq8uNVy0DE)！（挖矿协议是明文的，恶意节点可以修改目标钱包）

### 为什么 *不要* 使用付费节点？

1. 付费节点存在付完费厂商立即跑路的**诈骗风险**，且一旦被骗钱款**无法追回**！
2. 付费节点需要注册账号并付费，厂商可以借此收集你的**个人信息**然后倒卖！付费节点管理程序可能**存在漏洞**，由 ZF 支持的黑客也可能把你的个人信息提交给 ZF。

推荐阅读 [DiningFactory/panda-vpn-pro](https://github.com/DiningFactory/panda-vpn-pro)。

## 使用方法

注意：下列 JsDelivr 链接有长时间缓存，得到的订阅可能存在 1 小时 ～ 7 天 不等的延迟。更新订阅时优先使用非 JsDelivr 订阅；如无法更新再使用 JsDelivr 订阅，然后在开启代理的情况下从“原始链接”更新。

添加 Base64 订阅：
- [原始链接](https://raw.githubusercontent.com/Yux28/Kead/refs/heads/main/list.txt)
- [GhProxy.net](https://ghproxy.net/https://raw.githubusercontent.com/Yux28/Kead/refs/heads/main/list.txt)


或添加 Clash Meta 订阅：（如果使用的是原版 Clash，请将链接最后的 `.meta.yml` 替换成 `.yml`。我们始终建议您使用 Clash Meta 而不是已被废弃的 Clash。**提醒：Clash Meta (mihomo) 是有手机版的！还在用 Clash For Android 的用户请尽快迁移至 [Clash Meta For Android](https://github.com/MetaCubeX/ClashMetaForAndroid)！**）
- [原始链接](https://raw.githubusercontent.com/Yux28/Kead/refs/heads/main/list.meta.yml)
- [GhProxy.net](https://ghproxy.net/https://raw.githubusercontent.com/Yux28/Kead/refs/heads/main/list.meta.yml)


或添加自更新的 Clash Meta 订阅：（适用于不支持自动更新订阅的客户端，或是直接使用内核。尽管该文件很少变更，我们仍然建议您定期手动更新本地配置。更多详情请见 [配置片段说明](./snippets/README.md)）

- [原始链接](https://raw.githubusercontent.com/Yux28/Kead/refs/heads/main/snippets/example.yml)
- [GhProxy.net](https://ghproxy.net/https://raw.githubusercontent.com/Yux28/Kead/refs/heads/main/snippets/example.yml)


或添加 Sing-Box 订阅：（第三方提供转换，不支持本项目的节点选择和分流规则。建议在本地搭建转换服务。）
- [转换链接（第三方）](https://subwork.top/singbox?config=https%3A%2F%2Fraw.githubusercontent.com%2Fpeasoft%2FNoMoreWalls%2Fmaster%2Fsnippets%2Fnodes.meta.yml&ua=&selectedRules=%5B%22Location%3ACN%22%2C%22Private%22%2C%22Non-China%22%2C%22Github%22%2C%22Google%22%2C%22Youtube%22%2C%22AI+Services%22%2C%22Telegram%22%5D&customRules=%5B%5D&enable_clash_ui=true)

## 免责声明

订阅节点仅作学习交流使用，用于查找资料，学习知识，不做任何违法行为。所有资源均来自互联网，仅供大家交流学习使用，出现违法问题概不负责。**做出违法行为需要承担法律责任，侥幸逃脱是不可能的**！~~为阻止违法行为，本项目随时可以停止运行~~ 本项目可以采取各种技术手段来尽力阻止违法行为。

## 关于 Fork 和在线部署

不是说不能 Fork，但是请记得定时点击仓库中的 Sync fork 来同步更新主程序。这个项目是有时效性的，老版本基本都不能用了。

## 本地部署

请确保你安装了 Python 且版本大于等于 3.8。

1. 使用 Git 克隆本仓库，由于本仓库的完整 Commit 历史极大，请务必指定 `--depth=1`：
    ```bash
    git clone https://github.com/Yux28/Kead.git --depth=1
    ```
2. 安装依赖库
    ```bash
    pip install -r requirements.txt
    ```
3. 如果你所在地区没有墙或你在使用 Tun 模式或透明代理：创建空白文件 `local_proxy.conf`，填入 `NONE`，然后跳到第 9 步
4. 如果你已有代理，请跳到第 8 步。
5. 创建空白文件 `local_proxy.conf`
6. 运行 `fetch.py`
7. 将生成的订阅导入代理工具并正确配置好代理
8. 在 `local_proxy.conf` 中按如下格式填入你的代理工具的 http(s) 地址，如：
    ```plain
    http://127.0.0.1:7890/
    ```
9. 运行 `fetch.py`
10. 你已获得完整订阅

如果本地仓库长期未更新，也请使用 `--depth=1` 更新仓库：

```bash
git pull --depth=1
git reset --hard origin/main
```
