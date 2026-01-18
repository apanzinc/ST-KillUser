<img width="3000" height="1277" alt="公众号封面 2 35_1 - 1@1x" src="https://github.com/user-attachments/assets/d8afe061-f8c1-4ca3-84ea-54c9e7fab104" />
# 𝐊𝐢𝐥𝐥𝐔𝐬𝐞𝐫-𝐒𝐦𝐚𝐫𝐭𝐓𝐞𝐚𝐜𝐡

一个用于屏蔽智教联盟论坛上不想看到的用户的油猴脚本。

## 功能特性

- ✅ 支持屏蔽多种内容类型：
  - 帖子
  - 月活榜单
  - 在线榜单
  - 管理员列表
  - 通知
  - 评论
  - @提及
  - 回复提示

- ✅ 动态内容检测：使用MutationObserver实时监控页面变化，自动屏蔽新加载的内容
- ✅ 持久化存储：使用localStorage保存屏蔽列表和设置
- ✅ 直观的设置界面：在论坛设置页面中嵌入管理界面
- ✅ 日志开关：可控制是否显示控制台日志
- ✅ 完整的URL变化检测：支持单页应用导航
- ✅ 页面可见性监控：切换标签页时自动执行屏蔽检查

## 安装方法

1. 安装油猴扩展（Tampermonkey）：
   - Chrome/Firefox/Edge: [Tampermonkey](https://www.tampermonkey.net/)

2. 点击以下链接安装脚本：
   - [安装 𝐊𝐢𝐥𝐥𝐔𝐬𝐞𝐫-𝐒𝐦𝐚𝐫𝐭𝐓𝐞𝐚𝐜𝐡](https://github.com/apanzinc/ST-KillUser/raw/main/forum_user_blocker.user.js)

## 使用说明

1. **管理屏蔽列表**：
   - 进入论坛设置页面（`https://forum.smart-teach.cn/settings`）
   - 在页面底部找到「𝐊𝐢𝐥𝐥𝐔𝐬𝐞𝐫-𝐒𝐦𝐚𝐫𝐭𝐓𝐞𝐚𝐜𝐡 设置」部分
   - 可以添加、删除屏蔽用户
2. **日志开关**：
   - 在设置页面中可以切换控制台日志输出
   - 默认关闭日志输出

## 版本信息

- **当前版本**：v1.0
- **作者**：apanzinc

## 技术实现

- 使用原生JavaScript开发
- 支持现代浏览器
- 兼容单页应用（SPA）导航
- 模块化设计，易于扩展

## 项目链接

- GitHub: [github.com/apanzinc/ST-KillUser](https://github.com/apanzinc/ST-KillUser)

## 支持的论坛页面

- `https://forum.smart-teach.cn/` - 主页
- `https://forum.smart-teach.cn/notifications` - 通知页
- `https://forum.smart-teach.cn/d/*` - 帖子详情页
- `https://forum.smart-teach.cn/settings` - 设置页

## 常见问题

### Q: 为什么屏蔽的用户又出现了？
A: 脚本会自动检测页面内容变化，但如果遇到特殊情况，可以刷新页面或在设置中重新保存屏蔽列表。

### Q: 如何恢复被屏蔽的用户？
A: 进入设置页面，在屏蔽列表中删除该用户，然后刷新页面。

### Q: 脚本会影响论坛性能吗？
A: 脚本采用了高效的DOM操作和事件监听机制，对性能影响极小。

## 许可证

本项目基于GPL V3.0协议开源。您可以在遵守协议的前提下自由使用、修改和分发本项目的代码。


## 贡献

欢迎提交Issue和Pull Request！

## 联系方式

- 作者：apanzinc
- 如有问题欢迎反馈（小杨柳科技除外）
