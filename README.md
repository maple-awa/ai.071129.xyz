# ai.071129.xyz

`ai.071129.xyz` 主站的公开反馈 / 交流区。

这个仓库只做一件事：通过 GitHub Issues 收集主站相关的反馈、建议和使用问题，并把讨论留在可追踪、可检索的位置。

## 这个仓库适合提交什么

- 主站功能异常
- 页面显示问题
- 接口调用失败
- 使用流程卡住
- 产品建议与体验反馈
- 文档或反馈流程相关改进建议

## 不适合提交什么

- 与本项目无关的第三方服务问题
- 缺少基本信息、无法判断的问题描述
- 已存在且内容重复的 Issue
- 未经讨论的大范围站点实现改动

## 提交前先选对类型

请在 `Issues` 页面选择最接近的一类模板：

- `Bug 反馈`：站点报错、异常行为、逻辑错误、显示问题
- `功能建议`：新需求、体验优化、流程改进、产品想法
- `使用咨询`：不会用、看不懂、暂时无法判断是否为 Bug

如果你不确定该选哪一个，直接使用 `使用咨询`。

## 怎样反馈更容易被处理

信息越完整，越容易排查。建议至少提供这些内容：

- 问题出现的页面或功能入口
- 复现步骤
- 期望结果
- 实际结果
- 截图、报错、日志片段
- 使用环境：设备、浏览器、系统版本、网络情况

## Issue 标题建议

建议用统一前缀，方便后续检索和归类：

- `[Bug] 登录后跳转空白页`
- `[Feature] 希望增加历史记录搜索`
- `[Question] API Key 应该在哪里配置`

## 标签说明

仓库内建议使用以下几类标签：

- 类型：`bug`、`enhancement`、`question`、`documentation`
- 状态：`needs-info`、`confirmed`、`in-progress`、`blocked`
- 结果：`duplicate`、`invalid`、`wontfix`
- 优先级：`priority:low`、`priority:medium`、`priority:high`
- 模块：`area:login`、`area:settings`、`area:key`、`area:model`、`area:proxy`、`area:routing`、`area:upstream`、`area:dashboard`、`area:usage`、`area:docs`、`area:automation`

标签配置文件见 [.github/labels.yml](E:\Project\AI\ai.071129.xyz\.github\labels.yml)。

## 自动化说明

仓库已启用一组基础自动化，用来减少手工分拣成本：

- `labels`：同步 [.github/labels.yml](E:\Project\AI\ai.071129.xyz\.github\labels.yml) 到 GitHub Labels
- `welcome`：首次提交 Issue 或 PR 时自动欢迎
- `auto-label`：按标题、模板字段、正文关键词和 PR 文件路径自动打标签
- `issue-activity`：用户补充信息后自动移除 `needs-info`，维护者介入后自动标记 `in-progress`
- `stale`：长期无更新的 Issue / PR 自动提醒并关闭
- `close-guidance`：Issue 关闭时自动补结果标签，或提醒补 `duplicate / invalid / wontfix / confirmed`

这些流程默认只做辅助分类和状态收敛，不会替代人工判断。

## 处理约定

- 优先处理信息完整、可复现的问题
- 重复问题可能会被合并
- 信息不足的反馈会先要求补充
- 长时间无更新的问题可能会被自动标记 `stale`
- 关闭 Issue 时会尽量补齐结果标签，方便后续检索
- 较大改动建议先开 Issue 再提 PR

## 协作入口

- 提交反馈：`Issues`
- 查看历史反馈：`Issues` / `Closed Issues`
- 参与仓库协作：[CONTRIBUTING.md](E:\Project\AI\ai.071129.xyz\CONTRIBUTING.md)

如果你是来反馈主站问题，这个仓库就是正确入口。
