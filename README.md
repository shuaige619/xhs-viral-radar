# 小红书爆款雷达

当用户要搜索小红书爆款、寻找低粉高赞笔记或对标账号、筛选某领域近期热门内容、分析已提供的笔记样本时使用。不用于自动发布、批量互动或仅凭空生成小红书文案。

`xhs-viral-radar` · 原创 Skill · 内容版本 `f0ac10a757ce`

## 适用场景

当用户要搜索小红书爆款、寻找低粉高赞笔记或对标账号、筛选某领域近期热门内容、分析已提供的笔记样本时使用。不用于自动发布、批量互动或仅凭空生成小红书文案。

## 安装与使用

```sh
git clone https://github.com/shuaige619/xhs-viral-radar.git
cd xhs-viral-radar
```

将此目录按宿主支持的方式登记为本地 Skill，或把 [SKILL.md](SKILL.md) 交给支持 Agent Skills 的助手读取。保留 `scripts/`、`references/` 等配套目录的相对位置；下载完成不代表宿主已加载。

需要能读取本地 Markdown 的 Agent 环境。其他工具与依赖以 SKILL.md 中的要求为准。

## 输入与输出

**输入：** 按 SKILL.md 提供任务材料、必要参数和明确的输出位置。

**输出：** 按 SKILL.md 的交付约定生成结果，并报告未完成或待确认的项目。

## 使用示例

```text
请使用 xhs-viral-radar 处理我提供的材料。先核对必要输入，再按 SKILL.md 执行并回读实际输出。
```

以上是调用示例，不是已完成业务运行的记录。

## 工作方式

- 1. 确定本次搜索条件
- 2. 获取可核实样本
- 3. 筛选与排序
- 4. 拆解值得学的内容
- 5. 交付与继续使用
- 来源与个性化

- [references/output-contract.md](references/output-contract.md)
- [references/personal-profile.md](references/personal-profile.md)
- [references/research-protocol.md](references/research-protocol.md)
- [references/source-notes.md](references/source-notes.md)

## 验证与限制

本发布步骤核对文件结构、README、上传前后文件摘要；未在本步骤重新执行业务效果验证。

模型输出与业务事实需要结合具体材料核对；结构和上传检查不能替代业务效果测试。

## 来源与二创说明

作者于 2026-10-13 确认本 Skill 为原创；工具文档、外部参考与模型能力仍归各自来源。

文件身份与发布标准版本记录在 [发布清单](skill-release.json) 中。问题反馈请附复现输入、期望结果及内容版本，并先移除私人数据。

## 许可证

以仓库随附的 LICENSE / NOTICE 为准；未附许可证的部分尚未授予额外使用许可，请联系作者。
