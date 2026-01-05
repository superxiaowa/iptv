
### 直播源开源站点地址

- [https://live.zbds.top/](https://live.zbds.top/)



### 🔄 Fork 仓库自动同步

如果您 Fork 了本项目，可以通过以下方式保持与上游仓库的同步：

#### 开启 GitHub Actions 工作流
**重要**：Fork 后需要手动开启 Actions 功能才能使用自动同步：

1. 进入您 Fork 的仓库页面
2. 点击仓库顶部的 **"Actions"** 标签页
3. 如果看到 "Workflows aren't being run on this forked repository" 的提示，点击 **"I understand my workflows, go ahead and enable them"** 按钮
4. 在左侧工作流列表中找到 **"Sync with Upstream Repository"** 工作流
5. 点击该工作流，然后点击 **"Enable workflow"** 按钮
6. 确认启用工作流

> **说明**：由于 GitHub 安全策略，包含定时任务（schedule）和手动触发（workflow_dispatch）的工作流在 Fork 后默认是关闭的，需要手动启用。

#### 自动同步（推荐）
开启 Actions 后，本项目已配置 GitHub Actions 工作流，每6小时自动同步上游仓库的更新：
- ✅ 每6小时自动检测上游仓库更新
- ✅ 自动合并最新更改，每次同步都会生成详细的执行报告
- ✅ 自动解决合并冲突（以远程仓库为准）
- ✅ 保护工作流文件，避免权限问题




  

<h2>📊 Star History</h2>

[![Star History Chart](https://api.star-history.com/svg?repos=vbskycn/iptv&type=Date)](https://star-history.com/#vbskycn/iptv&Date)

