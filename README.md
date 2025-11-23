# WolGoWeb on Lazycat

## 项目简介

WolGoWeb 是一款基于 Go 的 Wake-on-LAN 远程唤醒管理面板,支持多终端设备集中管理。Lazycat 团队将社区版本移植到 Lazycat 平台,并提供一键部署、自动化运维和权限托管,让用户无需关注底层容器命令即可获得稳定可控的局域网唤醒体验。

## 主要功能

- **可视化终端管理**: 通过 Web 控制台集中维护多台设备、批量修改描述信息以及查看状态。
- **多网络唤醒策略**: 支持同一设备配置多个网口/MAC,并兼容自定义端口与广播地址策略。
- **安全访问与审计**: 可启用用户名/密码与 API Key 双重保护,搭配 Lazycat 平台提供的访问审计日志。
- **自动化任务**: 结合 Lazycat 定时器实现定期唤醒、巡检与关机编排,满足远程办公或实验室场景。
- **开放 API**: 暴露 REST 接口,可与 Lazycat 生态内的自动化流程或第三方工具进行集成。
- **监控告警**: 支持通过 Lazycat 指标和通知渠道获取服务运行状态与失败重试结果。

## Lazycat 平台体验

- 一键安装: 在 Lazycat 市场中直接启用 WolGoWeb 即可完成部署与升级。
- 配置托管: 平台自动维护环境变量、密钥与证书,避免手动编辑 Docker/Compose。
- 资源可视: 与 Lazycat 资源管理体系联动,可按需扩展 CPU、内存和网络能力。
- 快速恢复: 借助 Lazycat 备份机制,可以回滚任意一个版本,保障服务连续性。

## 致谢

特别感谢 WolGoWeb 原始作者与社区贡献者打造出高质量的开源项目。Lazycat 团队尊重并遵循其 GPLv3 授权,持续回馈修复与文档以帮助更多用户受益。

## 版权说明

本项目遵循 GNU General Public License v3.0。版权所属: Copyright (c) 2025 Lazycat Apps。

有关许可条款请查阅仓库根目录的 `LICENSE` 文件。如需在 Lazycat 平台外进行二次分发或商业使用,请确保遵守 GPLv3 要求。

## 相关链接

- WolGoWeb 官方仓库: https://github.com/xiaoxinpro/WolGoWeb
- Lazycat WolGoWeb 应用页: https://lazycat.app
- Lazycat 平台文档: https://docs.lazycat.app
- Lazycat 支持与反馈: https://support.lazycat.app
